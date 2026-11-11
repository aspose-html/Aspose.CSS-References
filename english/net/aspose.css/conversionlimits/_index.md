---
title: "ConversionLimits Class"
second_title: "Aspose.CSS for .NET API Reference"
description: "Work and size limits. Exhausting a global one fails the conversion with a ConversionException naming it; a per-resource one fails that resource only."
type: "docs"
weight: 50
url: "/net/aspose.css/conversionlimits/"
---
## ConversionLimits class

Work and size limits. Exhausting a global one fails the conversion with a [ConversionException](../conversionexception/) naming it; a per-resource one fails that resource only.

```csharp
public sealed class ConversionLimits
```

## Constructors

| Name | Description |
| --- | --- |
| [ConversionLimits](conversionlimits/#conversionlimits)() | Initializes a new instance of the ConversionLimits class. |

## Properties

| Name | Description |
| --- | --- |
| [ConnectMilliseconds](connectmilliseconds/#connectmilliseconds) { get; set; } | Connecting, ms. Default 10,000. |
| [FontLoadMilliseconds](fontloadmilliseconds/#fontloadmilliseconds) { get; set; } | One font load, ms. Default 10,000. |
| [HopMilliseconds](hopmilliseconds/#hopmilliseconds) { get; set; } | One request hop, ms. Default 10,000. |
| [MaxAggregateResourceBytes](maxaggregateresourcebytes/#maxaggregateresourcebytes) { get; set; } | All resource bytes together. Default 256 MiB. |
| [MaxConcurrentRequests](maxconcurrentrequests/#maxconcurrentrequests) { get; set; } | Network image requests sent at once when the network is on and no loader is set. Default 6. |
| [MaxDecodedResourceBytes](maxdecodedresourcebytes/#maxdecodedresourcebytes) { get; set; } | Decoded bytes of one resource. Default 32 MiB. |
| [MaxDiagnostics](maxdiagnostics/#maxdiagnostics) { get; set; } | Diagnostics kept; more are counted as truncated. Default 10,000. |
| [MaxEncodedResourceBytes](maxencodedresourcebytes/#maxencodedresourcebytes) { get; set; } | Encoded bytes of one resource. Default 16 MiB. |
| [MaxFonts](maxfonts/#maxfonts) { get; set; } | Distinct faces loaded. Default 256. |
| [MaxImagePixels](maximagepixels/#maximagepixels) { get; set; } | Pixels of one image or one output raster. Default 64,000,000. |
| [MaxImportDepth](maximportdepth/#maximportdepth) { get; set; } | Nested @import depth. Default 32. |
| [MaxInputBytes](maxinputbytes/#maxinputbytes) { get; set; } | Input bytes (string input counted as UTF-8). Default 16 MiB. |
| [MaxLayoutDepth](maxlayoutdepth/#maxlayoutdepth) { get; set; } | Layout nesting depth. Default 480. |
| [MaxLayoutVisits](maxlayoutvisits/#maxlayoutvisits) { get; set; } | Layout visits per pass. Default 2,000,000. |
| [MaxNodes](maxnodes/#maxnodes) { get; set; } | Document nodes. Default 1,000,000. |
| [MaxOutputBytes](maxoutputbytes/#maxoutputbytes) { get; set; } | All output bytes. Default 256 MiB. |
| [MaxPages](maxpages/#maxpages) { get; set; } | Pages. Default 10,000. |
| [MaxPreparationPasses](maxpreparationpasses/#maxpreparationpasses) { get; set; } | Preparation passes. Default 16. |
| [MaxRedirects](maxredirects/#maxredirects) { get; set; } | Redirects followed per resource. Default 20. |
| [MaxResourceTasks](maxresourcetasks/#maxresourcetasks) { get; set; } | Resource requests per conversion. Default 1000. |
| [PreparationMilliseconds](preparationmilliseconds/#preparationmilliseconds) { get; set; } | Time spent fetching resources, ms. Default 30,000. Styling and layout count only toward [ConversionLimits.TotalMilliseconds](totalmilliseconds/#totalmilliseconds). |
| [ReadIdleMilliseconds](readidlemilliseconds/#readidlemilliseconds) { get; set; } | Idle read, ms. Default 10,000. |
| [TotalMilliseconds](totalmilliseconds/#totalmilliseconds) { get; set; } | Whole conversion, ms. Default 60,000. |

### See Also

* namespace [Aspose.Css](../)
* assembly [Aspose.CSS](../../)
