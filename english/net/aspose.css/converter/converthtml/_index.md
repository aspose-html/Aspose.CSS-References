---
title: "Converter.ConvertHTML"
second_title: "Aspose.CSS for .NET API Reference"
description: "Converts source to the streams output creates, one per part."
type: "docs"
weight: 10
url: "/net/aspose.css/converter/converthtml/"
---
## Converter.ConvertHTML method

## ConvertHTML(HtmlSource, SaveOptions, ICreateStreamProvider) {#converthtml_htmlsource_saveoptions_icreatestreamprovider}

Converts *source* to the streams *output* creates, one per part.

```csharp
public static ConversionResult ConvertHTML(HtmlSource source, SaveOptions options, ICreateStreamProvider output)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | [HtmlSource](../../htmlsource/) | The HTML source. |
| options | [SaveOptions](../../../aspose.css.saving/saveoptions/) | PDF or image options. |
| output | [ICreateStreamProvider](../../../aspose.css.io/icreatestreamprovider/) | The stream provider. |

### Return Value

[ConversionResult](../../conversionresult/): The conversion result.

### See Also

* class [Converter](../)
* namespace [Aspose.Css](../../)
* assembly [Aspose.CSS](../../../)

---

## ConvertHTML(HtmlSource, SaveOptions, Stream) {#converthtml_htmlsource_saveoptions_stream}

Converts *source* to *output*, left open.

```csharp
public static ConversionResult ConvertHTML(HtmlSource source, SaveOptions options, Stream output)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | [HtmlSource](../../htmlsource/) | The HTML source. |
| options | [SaveOptions](../../../aspose.css.saving/saveoptions/) | PDF or image options. |
| output | Stream | A writable stream. |

### Return Value

[ConversionResult](../../conversionresult/): The conversion result.

### See Also

* class [Converter](../)
* namespace [Aspose.Css](../../)
* assembly [Aspose.CSS](../../../)

---

## ConvertHTML(HtmlSource, SaveOptions, string) {#converthtml_htmlsource_saveoptions_string}

Converts *source* to the file *outputPath*.

```csharp
public static ConversionResult ConvertHTML(HtmlSource source, SaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | [HtmlSource](../../htmlsource/) | The HTML source. |
| options | [SaveOptions](../../../aspose.css.saving/saveoptions/) | PDF or image options. |
| outputPath | string | The output file; replaced only when the conversion succeeds. |

### Return Value

[ConversionResult](../../conversionresult/): The conversion result.

### See Also

* class [Converter](../)
* namespace [Aspose.Css](../../)
* assembly [Aspose.CSS](../../../)

---

## ConvertHTML(string, SaveOptions, string) {#converthtml_string_saveoptions_string}

Converts the HTML file *inputPath* to the file *outputPath*.

```csharp
public static ConversionResult ConvertHTML(string inputPath, SaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputPath | string | The input file; its directory is an allowed file root. |
| options | [SaveOptions](../../../aspose.css.saving/saveoptions/) | PDF or image options. |
| outputPath | string | The output file. |

### Return Value

[ConversionResult](../../conversionresult/): The conversion result.

### See Also

* class [Converter](../)
* namespace [Aspose.Css](../../)
* assembly [Aspose.CSS](../../../)

---

## ConvertHTML(Stream, string, SaveOptions, Stream) {#converthtml_stream_string_saveoptions_stream}

Converts the HTML bytes of *input* to *output*; both stay open.

```csharp
public static ConversionResult ConvertHTML(Stream input, string baseUri, SaveOptions options, Stream output)
```

| Parameter | Type | Description |
| --- | --- | --- |
| input | Stream | The input, read from its current position. |
| baseUri | string | An absolute http(s) or file URI, or about:blank. |
| options | [SaveOptions](../../../aspose.css.saving/saveoptions/) | PDF or image options. |
| output | Stream | A writable stream. |

### Return Value

[ConversionResult](../../conversionresult/): The conversion result.

### See Also

* class [Converter](../)
* namespace [Aspose.Css](../../)
* assembly [Aspose.CSS](../../../)

---

## ConvertHTML(Stream, string, SaveOptions, string) {#converthtml_stream_string_saveoptions_string}

Converts the HTML bytes of *input* to the file *outputPath*.

```csharp
public static ConversionResult ConvertHTML(Stream input, string baseUri, SaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| input | Stream | The input, read from its current position and left open. |
| baseUri | string | An absolute http(s) or file URI, or about:blank. |
| options | [SaveOptions](../../../aspose.css.saving/saveoptions/) | PDF or image options. |
| outputPath | string | The output file. |

### Return Value

[ConversionResult](../../conversionresult/): The conversion result.

### See Also

* class [Converter](../)
* namespace [Aspose.Css](../../)
* assembly [Aspose.CSS](../../../)

---

## ConvertHTML(string, string, SaveOptions, Stream) {#converthtml_string_string_saveoptions_stream}

Converts the markup *html* to *output*, left open.

```csharp
public static ConversionResult ConvertHTML(string html, string baseUri, SaveOptions options, Stream output)
```

| Parameter | Type | Description |
| --- | --- | --- |
| html | string | The markup. |
| baseUri | string | An absolute http(s) or file URI, or about:blank. |
| options | [SaveOptions](../../../aspose.css.saving/saveoptions/) | PDF or image options. |
| output | Stream | A writable stream. |

### Return Value

[ConversionResult](../../conversionresult/): The conversion result.

### See Also

* class [Converter](../)
* namespace [Aspose.Css](../../)
* assembly [Aspose.CSS](../../../)

---

## ConvertHTML(string, string, SaveOptions, string) {#converthtml_string_string_saveoptions_string}

Converts the markup *html* to the file *outputPath*.

```csharp
public static ConversionResult ConvertHTML(string html, string baseUri, SaveOptions options, string outputPath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| html | string | The markup. |
| baseUri | string | An absolute http(s) or file URI, or about:blank. |
| options | [SaveOptions](../../../aspose.css.saving/saveoptions/) | PDF or image options. |
| outputPath | string | The output file. |

### Return Value

[ConversionResult](../../conversionresult/): The conversion result.

### See Also

* class [Converter](../)
* namespace [Aspose.Css](../../)
* assembly [Aspose.CSS](../../../)

---

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
