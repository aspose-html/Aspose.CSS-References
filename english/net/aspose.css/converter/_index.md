---
title: "Converter Class"
second_title: "Aspose.CSS for .NET API Reference"
description: "One-shot HTML to PDF or PNG conversion. A lone string input is a file path; markup goes through the overloads that also take a base URI. Caller streams are read from their current position and never closed. A file output is written beside the target and moved over it when complete."
type: "docs"
weight: 80
url: "/net/aspose.css/converter/"
---
## Converter class

One-shot HTML to PDF or PNG conversion. A lone string input is a file path; markup goes through the overloads that also take a base URI. Caller streams are read from their current position and never closed. A file output is written beside the target and moved over it when complete.

```csharp
public static class Converter
```

## Methods

| Name | Description |
| --- | --- |
| static [ConvertHTML](converthtml/#converthtml_htmlsource_saveoptions_icreatestreamprovider)(HtmlSource, SaveOptions, ICreateStreamProvider) | Converts *source* to the streams *output* creates, one per part. |
| static [ConvertHTML](converthtml/#converthtml_htmlsource_saveoptions_stream)(HtmlSource, SaveOptions, Stream) | Converts *source* to *output*, left open. |
| static [ConvertHTML](converthtml/#converthtml_htmlsource_saveoptions_string)(HtmlSource, SaveOptions, string) | Converts *source* to the file *outputPath*. |
| static [ConvertHTML](converthtml/#converthtml_string_saveoptions_string)(string, SaveOptions, string) | Converts the HTML file *inputPath* to the file *outputPath*. |
| static [ConvertHTML](converthtml/#converthtml_stream_string_saveoptions_stream)(Stream, string, SaveOptions, Stream) | Converts the HTML bytes of *input* to *output*; both stay open. |
| static [ConvertHTML](converthtml/#converthtml_stream_string_saveoptions_string)(Stream, string, SaveOptions, string) | Converts the HTML bytes of *input* to the file *outputPath*. |
| static [ConvertHTML](converthtml/#converthtml_string_string_saveoptions_stream)(string, string, SaveOptions, Stream) | Converts the markup *html* to *output*, left open. |
| static [ConvertHTML](converthtml/#converthtml_string_string_saveoptions_string)(string, string, SaveOptions, string) | Converts the markup *html* to the file *outputPath*. |
| static [IsSupported](issupported/#issupported_pdfconformance)(PdfConformance) | True when this version writes *conformance*; only Standard in this version. |

## Examples

### Convert a local invoice with the familiar Aspose call.

```csharp
var result = Converter.ConvertHTML("invoice.html", new PdfSaveOptions(), "invoice.pdf");
Console.WriteLine(result.PageCount);
```

### Convert stream-to-stream without accidental ownership transfer.

```csharp
using var input = File.OpenRead("report.html");
using var output = File.Create("report.pdf");
Converter.ConvertHTML(input, "https://assets.example/", new PdfSaveOptions(), output);
```

### Produce one print-resolution PNG per page with explicit stream completion.

```csharp
var images = new ImageSaveOptions {
    Mode = ImageMode.PrintPages, HorizontalResolution = 300, VerticalResolution = 300,
};
images.Css.MediaType = MediaType.Print;
Converter.ConvertHTML(HtmlSource.FromFile("report.html"), images, new PageFiles());

private sealed class PageFiles : ICreateStreamProvider
{
    public Stream GetStream(OutputPart part) => File.Create($"page-{part.Index + 1}.png");

    public void Complete(OutputPart part, Stream stream, OutputOutcome outcome)
    {
        stream.Dispose();
        if (outcome != OutputOutcome.Completed) File.Delete($"page-{part.Index + 1}.png");
    }
}
```

### See Also

* namespace [Aspose.Css](../)
* assembly [Aspose.CSS](../../)
