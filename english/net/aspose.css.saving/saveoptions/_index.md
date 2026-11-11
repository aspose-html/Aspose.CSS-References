---
title: "SaveOptions Class"
second_title: "Aspose.CSS for .NET API Reference"
description: "The options every output takes. Closed: use PdfSaveOptions or ImageSaveOptions."
type: "docs"
weight: 100
url: "/net/aspose.css.saving/saveoptions/"
---
## SaveOptions class

The options every output takes. Closed: use [PdfSaveOptions](../pdfsaveoptions/) or [ImageSaveOptions](../imagesaveoptions/).

```csharp
public abstract class SaveOptions
```

## Properties

| Name | Description |
| --- | --- |
| [Configuration](configuration/#configuration) { get; set; } | The environment; null means defaults for a one-shot conversion. Must be null on [RenderDocument.Save](../../aspose.css/renderdocument/save/#save_saveoptions_stream), which uses the loaded one. |
| [Css](css/#css) { get; } | Media type and viewport. Getter-only. |
| [PageSetup](pagesetup/#pagesetup) { get; } | Page geometry and pagination. Getter-only. |

### See Also

* namespace [Aspose.Css.Saving](../)
* assembly [Aspose.CSS](../../)
