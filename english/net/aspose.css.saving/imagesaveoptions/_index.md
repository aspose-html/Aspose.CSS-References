---
title: "ImageSaveOptions Class"
second_title: "Aspose.CSS for .NET API Reference"
description: "Raster output. Media type defaults to Screen."
type: "docs"
weight: 40
url: "/net/aspose.css.saving/imagesaveoptions/"
---
## ImageSaveOptions class

Raster output. Media type defaults to Screen.

```csharp
public sealed class ImageSaveOptions : SaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageSaveOptions](imagesaveoptions/#imagesaveoptions)() | Image options with the defaults. |

## Properties

| Name | Description |
| --- | --- |
| [Format](format/#format) { get; set; } | The codec. Default Png. Jpeg has no alpha: transparent pixels are composited onto white; Png and Webp keep alpha. Page files are named .png, .jpg or .webp. |
| [HorizontalResolution](horizontalresolution/#horizontalresolution) { get; set; } | Horizontal pixel density, dots per inch. Default 96 (one pixel per CSS px). |
| [Mode](mode/#mode) { get; set; } | Viewport (default) clips to the viewport; FullContent grows to the content; PrintPages writes one image per page, needs Print media and a stream provider. |
| [Quality](quality/#quality) { get; set; } | Lossy codec quality, 1 (smallest) to 100 (best). Default 100. Jpeg encodes at this quality; Webp is lossless at 100 and lossy below it; Png ignores it. |
| [VerticalResolution](verticalresolution/#verticalresolution) { get; set; } | Vertical pixel density, dots per inch. Default 96. |
| [Configuration](../saveoptions/configuration/#configuration) { get; set; } | The environment; null means defaults for a one-shot conversion. Must be null on [RenderDocument.Save](../../aspose.css/renderdocument/save/#save_saveoptions_stream), which uses the loaded one. (Inherited from [SaveOptions](../saveoptions/).) |
| [Css](../saveoptions/css/#css) { get; } | Media type and viewport. Getter-only. (Inherited from [SaveOptions](../saveoptions/).) |
| [PageSetup](../saveoptions/pagesetup/#pagesetup) { get; } | Page geometry and pagination. Getter-only. (Inherited from [SaveOptions](../saveoptions/).) |

### See Also

* namespace [Aspose.Css.Saving](../)
* assembly [Aspose.CSS](../../)
