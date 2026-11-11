---
title: "ConverterAsync.ConvertHTMLAsync"
second_title: "Aspose.CSS for .NET API Reference"
description: "Converts source to the streams output creates, one per part."
type: "docs"
weight: 10
url: "/net/aspose.css/converterasync/converthtmlasync/"
---
## ConverterAsync.ConvertHTMLAsync method

## ConvertHTMLAsync(HtmlSource, SaveOptions, ICreateStreamProvider, CancellationToken) {#converthtmlasync_htmlsource_saveoptions_icreatestreamprovider_cancellationtoken}

Converts *source* to the streams *output* creates, one per part.

```csharp
public static Task<ConversionResult> ConvertHTMLAsync(HtmlSource source, SaveOptions options, ICreateStreamProvider output, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | [HtmlSource](../../htmlsource/) | The HTML source. |
| options | [SaveOptions](../../../aspose.css.saving/saveoptions/) | PDF or image options. |
| output | [ICreateStreamProvider](../../../aspose.css.io/icreatestreamprovider/) | The stream provider. |
| cancellationToken | CancellationToken | Cancels the conversion at its next checkpoint. |

### Return Value

Task&lt;[ConversionResult](../../conversionresult/)&gt;: The conversion result.

### See Also

* class [ConverterAsync](../)
* namespace [Aspose.Css](../../)
* assembly [Aspose.CSS](../../../)

---

## ConvertHTMLAsync(HtmlSource, SaveOptions, Stream, CancellationToken) {#converthtmlasync_htmlsource_saveoptions_stream_cancellationtoken}

Converts *source* to *output*, left open.

```csharp
public static Task<ConversionResult> ConvertHTMLAsync(HtmlSource source, SaveOptions options, Stream output, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | [HtmlSource](../../htmlsource/) | The HTML source. |
| options | [SaveOptions](../../../aspose.css.saving/saveoptions/) | PDF or image options. |
| output | Stream | A writable stream. |
| cancellationToken | CancellationToken | Cancels the conversion at its next checkpoint. |

### Return Value

Task&lt;[ConversionResult](../../conversionresult/)&gt;: The conversion result.

### See Also

* class [ConverterAsync](../)
* namespace [Aspose.Css](../../)
* assembly [Aspose.CSS](../../../)

---

## ConvertHTMLAsync(HtmlSource, SaveOptions, string, CancellationToken) {#converthtmlasync_htmlsource_saveoptions_string_cancellationtoken}

Converts *source* to the file *outputPath*.

```csharp
public static Task<ConversionResult> ConvertHTMLAsync(HtmlSource source, SaveOptions options, string outputPath, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| source | [HtmlSource](../../htmlsource/) | The HTML source. |
| options | [SaveOptions](../../../aspose.css.saving/saveoptions/) | PDF or image options. |
| outputPath | string | The output file; replaced only when the conversion succeeds. |
| cancellationToken | CancellationToken | Cancels the conversion at its next checkpoint. |

### Return Value

Task&lt;[ConversionResult](../../conversionresult/)&gt;: The conversion result.

### See Also

* class [ConverterAsync](../)
* namespace [Aspose.Css](../../)
* assembly [Aspose.CSS](../../../)

---

## ConvertHTMLAsync(string, SaveOptions, string, CancellationToken) {#converthtmlasync_string_saveoptions_string_cancellationtoken}

Converts the HTML file *inputPath* to the file *outputPath*.

```csharp
public static Task<ConversionResult> ConvertHTMLAsync(string inputPath, SaveOptions options, string outputPath, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputPath | string | The input file; its directory is an allowed file root. |
| options | [SaveOptions](../../../aspose.css.saving/saveoptions/) | PDF or image options. |
| outputPath | string | The output file. |
| cancellationToken | CancellationToken | Cancels the conversion at its next checkpoint. |

### Return Value

Task&lt;[ConversionResult](../../conversionresult/)&gt;: The conversion result.

### See Also

* class [ConverterAsync](../)
* namespace [Aspose.Css](../../)
* assembly [Aspose.CSS](../../../)

---

## ConvertHTMLAsync(Stream, string, SaveOptions, Stream, CancellationToken) {#converthtmlasync_stream_string_saveoptions_stream_cancellationtoken}

Converts the HTML bytes of *input* to *output*; both stay open.

```csharp
public static Task<ConversionResult> ConvertHTMLAsync(Stream input, string baseUri, SaveOptions options, Stream output, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| input | Stream | The input, read on the pool thread from its current position. |
| baseUri | string | An absolute http(s) or file URI, or about:blank. |
| options | [SaveOptions](../../../aspose.css.saving/saveoptions/) | PDF or image options. |
| output | Stream | A writable stream. |
| cancellationToken | CancellationToken | Cancels the conversion at its next checkpoint. |

### Return Value

Task&lt;[ConversionResult](../../conversionresult/)&gt;: The conversion result.

### See Also

* class [ConverterAsync](../)
* namespace [Aspose.Css](../../)
* assembly [Aspose.CSS](../../../)

---

## ConvertHTMLAsync(Stream, string, SaveOptions, string, CancellationToken) {#converthtmlasync_stream_string_saveoptions_string_cancellationtoken}

Converts the HTML bytes of *input* to the file *outputPath*.

```csharp
public static Task<ConversionResult> ConvertHTMLAsync(Stream input, string baseUri, SaveOptions options, string outputPath, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| input | Stream | The input, read on the pool thread from its current position and left open. |
| baseUri | string | An absolute http(s) or file URI, or about:blank. |
| options | [SaveOptions](../../../aspose.css.saving/saveoptions/) | PDF or image options. |
| outputPath | string | The output file. |
| cancellationToken | CancellationToken | Cancels the conversion at its next checkpoint. |

### Return Value

Task&lt;[ConversionResult](../../conversionresult/)&gt;: The conversion result.

### See Also

* class [ConverterAsync](../)
* namespace [Aspose.Css](../../)
* assembly [Aspose.CSS](../../../)

---

## ConvertHTMLAsync(string, string, SaveOptions, Stream, CancellationToken) {#converthtmlasync_string_string_saveoptions_stream_cancellationtoken}

Converts the markup *html* to *output*, left open.

```csharp
public static Task<ConversionResult> ConvertHTMLAsync(string html, string baseUri, SaveOptions options, Stream output, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| html | string | The markup. |
| baseUri | string | An absolute http(s) or file URI, or about:blank. |
| options | [SaveOptions](../../../aspose.css.saving/saveoptions/) | PDF or image options. |
| output | Stream | A writable stream. |
| cancellationToken | CancellationToken | Cancels the conversion at its next checkpoint. |

### Return Value

Task&lt;[ConversionResult](../../conversionresult/)&gt;: The conversion result.

### See Also

* class [ConverterAsync](../)
* namespace [Aspose.Css](../../)
* assembly [Aspose.CSS](../../../)

---

## ConvertHTMLAsync(string, string, SaveOptions, string, CancellationToken) {#converthtmlasync_string_string_saveoptions_string_cancellationtoken}

Converts the markup *html* to the file *outputPath*.

```csharp
public static Task<ConversionResult> ConvertHTMLAsync(string html, string baseUri, SaveOptions options, string outputPath, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| html | string | The markup. |
| baseUri | string | An absolute http(s) or file URI, or about:blank. |
| options | [SaveOptions](../../../aspose.css.saving/saveoptions/) | PDF or image options. |
| outputPath | string | The output file. |
| cancellationToken | CancellationToken | Cancels the conversion at its next checkpoint. |

### Return Value

Task&lt;[ConversionResult](../../conversionresult/)&gt;: The conversion result.

### See Also

* class [ConverterAsync](../)
* namespace [Aspose.Css](../../)
* assembly [Aspose.CSS](../../../)
