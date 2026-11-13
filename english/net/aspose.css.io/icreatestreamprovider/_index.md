---
title: "ICreateStreamProvider Interface"
second_title: "Aspose.CSS for .NET API Reference"
description: "Creates one stream per output part. Each stream returned gets exactly one ICreateStreamProvider.Complete, failure included; the provider owns closing it. Calls are serial."
type: "docs"
weight: 10
url: "/net/aspose.css.io/icreatestreamprovider/"
---
## ICreateStreamProvider interface

Creates one stream per output part. Each stream returned gets exactly one [ICreateStreamProvider.Complete](complete/#complete_outputpart_stream_outputoutcome), failure included; the provider owns closing it. Calls are serial.

```csharp
public interface ICreateStreamProvider
```

## Methods

| Name | Description |
| --- | --- |
| [Complete](complete/#complete_outputpart_stream_outputoutcome)(OutputPart, Stream, OutputOutcome) | The part's stream is finished with *outcome*. |
| [GetStream](getstream/#getstream_outputpart)(OutputPart) | The stream for *part*. |

### See Also

* namespace [Aspose.Css.IO](../)
* assembly [Aspose.CSS](../../)
