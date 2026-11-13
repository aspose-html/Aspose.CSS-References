---
title: "ConverterAsync Class"
second_title: "Aspose.CSS for .NET API Reference"
description: "The .NET task adapter over Converter, outside the portable surface. Arguments and options are refused and the configuration copied before the task is scheduled; the conversion runs on a pool thread. Token cancellation ends the task as canceled, at the next checkpoint; Configuration.Cancellation faults it with ConversionCanceledException, and a limit faults it with ConversionException."
type: "docs"
weight: 90
url: "/net/aspose.css/converterasync/"
---
## ConverterAsync class

The .NET task adapter over [Converter](../converter/), outside the portable surface. Arguments and options are refused and the configuration copied before the task is scheduled; the conversion runs on a pool thread. Token cancellation ends the task as canceled, at the next checkpoint; [Configuration.Cancellation](../configuration/cancellation/#cancellation) faults it with [ConversionCanceledException](../conversioncanceledexception/), and a limit faults it with [ConversionException](../conversionexception/).

```csharp
public static class ConverterAsync
```

## Methods

| Name | Description |
| --- | --- |
| static [ConvertHTMLAsync](converthtmlasync/#converthtmlasync_htmlsource_saveoptions_icreatestreamprovider_cancellationtoken)(HtmlSource, SaveOptions, ICreateStreamProvider, CancellationToken) | Converts *source* to the streams *output* creates, one per part. |
| static [ConvertHTMLAsync](converthtmlasync/#converthtmlasync_htmlsource_saveoptions_stream_cancellationtoken)(HtmlSource, SaveOptions, Stream, CancellationToken) | Converts *source* to *output*, left open. |
| static [ConvertHTMLAsync](converthtmlasync/#converthtmlasync_htmlsource_saveoptions_string_cancellationtoken)(HtmlSource, SaveOptions, string, CancellationToken) | Converts *source* to the file *outputPath*. |
| static [ConvertHTMLAsync](converthtmlasync/#converthtmlasync_string_saveoptions_string_cancellationtoken)(string, SaveOptions, string, CancellationToken) | Converts the HTML file *inputPath* to the file *outputPath*. |
| static [ConvertHTMLAsync](converthtmlasync/#converthtmlasync_stream_string_saveoptions_stream_cancellationtoken)(Stream, string, SaveOptions, Stream, CancellationToken) | Converts the HTML bytes of *input* to *output*; both stay open. |
| static [ConvertHTMLAsync](converthtmlasync/#converthtmlasync_stream_string_saveoptions_string_cancellationtoken)(Stream, string, SaveOptions, string, CancellationToken) | Converts the HTML bytes of *input* to the file *outputPath*. |
| static [ConvertHTMLAsync](converthtmlasync/#converthtmlasync_string_string_saveoptions_stream_cancellationtoken)(string, string, SaveOptions, Stream, CancellationToken) | Converts the markup *html* to *output*, left open. |
| static [ConvertHTMLAsync](converthtmlasync/#converthtmlasync_string_string_saveoptions_string_cancellationtoken)(string, string, SaveOptions, string, CancellationToken) | Converts the markup *html* to the file *outputPath*. |

### See Also

* namespace [Aspose.Css](../)
* assembly [Aspose.CSS](../../)
