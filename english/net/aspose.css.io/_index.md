---
title: "Aspose.Css.IO"
second_title: "Aspose.CSS for .NET API Reference"
description: "Writing conversion output to streams."
type: "docs"
weight: 40
url: "/net/aspose.css.io/"
---
## Classes

| Class | Description |
| --- | --- |
| [OutputPart](outputpart/) | One output part: the whole PDF, the one image, or one page image. |

## Interfaces

| Interface | Description |
| --- | --- |
| [ICreateStreamProvider](icreatestreamprovider/) | Creates one stream per output part. Each stream returned gets exactly one [ICreateStreamProvider.Complete](icreatestreamprovider/complete/#complete_outputpart_stream_outputoutcome), failure included; the provider owns closing it. Calls are serial. |

## Enumerations

| Enumeration | Description |
| --- | --- |
| [OutputOutcome](outputoutcome/) | How a part's output ended. |
