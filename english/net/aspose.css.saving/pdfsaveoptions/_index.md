---
title: "PdfSaveOptions Class"
second_title: "Aspose.CSS for .NET API Reference"
description: "PDF output. Media type defaults to Print."
type: "docs"
weight: 90
url: "/net/aspose.css.saving/pdfsaveoptions/"
---
## PdfSaveOptions class

PDF output. Media type defaults to Print.

```csharp
public sealed class PdfSaveOptions : SaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/#pdfsaveoptions)() | PDF options with the defaults. |

## Properties

| Name | Description |
| --- | --- |
| [Conformance](conformance/#conformance) { get; set; } | The PDF profile asked for. Default Standard, the only one supported: PdfA2b and PdfUa1 fail with UnsupportedCapability before any output. |
| [Configuration](../saveoptions/configuration/#configuration) { get; set; } | The environment; null means defaults for a one-shot conversion. Must be null on [RenderDocument.Save](../../aspose.css/renderdocument/save/#save_saveoptions_stream), which uses the loaded one. (Inherited from [SaveOptions](../saveoptions/).) |
| [Css](../saveoptions/css/#css) { get; } | Media type and viewport. Getter-only. (Inherited from [SaveOptions](../saveoptions/).) |
| [PageSetup](../saveoptions/pagesetup/#pagesetup) { get; } | Page geometry and pagination. Getter-only. (Inherited from [SaveOptions](../saveoptions/).) |

### See Also

* namespace [Aspose.Css.Saving](../)
* assembly [Aspose.CSS](../../)
