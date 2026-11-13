---
title: "ImageMode Enum"
second_title: "Aspose.CSS for .NET API Reference"
description: "What an image shows."
type: "docs"
weight: 30
url: "/net/aspose.css.saving/imagemode/"
---
## ImageMode enum

What an image shows.

```csharp
public enum ImageMode
```

## Values

| Name | Value | Description |
| --- | --- | --- |
| Viewport {#viewport} | `0` | The viewport, clipped. |
| FullContent {#fullcontent} | `1` | The whole content extent, as one raster capped by ConversionLimits.MaxImagePixels (default 64,000,000, about 50,000 px tall at 1280 px wide). A longer page fails with LimitExceeded: raise Configuration.Limits.MaxImagePixels, or use [ImageMode.PrintPages](./#printpages) for one image per page. |
| PrintPages {#printpages} | `2` | One image per printed page. |

### See Also

* namespace [Aspose.Css.Saving](../)
* assembly [Aspose.CSS](../../)
