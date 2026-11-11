---
title: "RenderDocument Class"
second_title: "Aspose.CSS for .NET API Reference"
description: "A document loaded once and saved any number of times, each save with its own media and page options. Saves use the configuration captured at RenderDocument.Load; a save whose options carry a configuration is rejected. Saves are serialised per document."
type: "docs"
weight: 160
url: "/net/aspose.css/renderdocument/"
---
## RenderDocument class

A document loaded once and saved any number of times, each save with its own media and page options. Saves use the configuration captured at [RenderDocument.Load](load/#load_htmlsource_configuration); a save whose options carry a configuration is rejected. Saves are serialised per document.

```csharp
public sealed class RenderDocument : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [Diagnostics](diagnostics/#diagnostics) { get; } | The preparation diagnostics; each save's result includes them. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](dispose/#dispose)() | Releases the loaded document; later calls throw ObjectDisposedException. |
| static [Load](load/#load_htmlsource_configuration)(HtmlSource, Configuration) | Reads and parses *source* under *configuration*, copied now. |
| [Save](save/#save_saveoptions_icreatestreamprovider)(SaveOptions, ICreateStreamProvider) | Saves to the streams *output* creates, one per part. |
| [Save](save/#save_saveoptions_stream)(SaveOptions, Stream) | Saves to *output*, left open. |

### See Also

* namespace [Aspose.Css](../)
* assembly [Aspose.CSS](../../)
