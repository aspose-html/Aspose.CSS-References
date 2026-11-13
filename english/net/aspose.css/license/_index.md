---
title: "License Class"
second_title: "Aspose.CSS for .NET API Reference"
description: "Applies a licence in the Aspose licence file format to this process. Without one the library runs in evaluation mode: full output, a per-process document cap, size ceilings and a metadata mark (see EvaluationLimitException). A licence can also be given by the ASPOSE_CSS_LICENSE environment variable, a path or the base64 of the file."
type: "docs"
weight: 160
url: "/net/aspose.css/license/"
---
## License class

Applies a licence in the Aspose licence file format to this process. Without one the library runs in evaluation mode: full output, a per-process document cap, size ceilings and a metadata mark (see [EvaluationLimitException](../evaluationlimitexception/)). A licence can also be given by the ASPOSE\_CSS\_LICENSE environment variable, a path or the base64 of the file.

```csharp
public sealed class License
```

## Constructors

| Name | Description |
| --- | --- |
| [License](license/#license)() | Creates a licence object; call [License.SetLicense](setlicense/#setlicense_string) or [License.SetLicense](setlicense/#setlicense_stream) on it. |

## Properties

| Name | Description |
| --- | --- |
| static [State](state/#state) { get; } | The state of this process; reads ASPOSE\_CSS\_LICENSE first when no licence was set. |

## Methods

| Name | Description |
| --- | --- |
| [SetLicense](setlicense/#setlicense_stream)(Stream) | Applies the licence read from *stream*; throws when it is not accepted. |
| [SetLicense](setlicense/#setlicense_string)(string) | Applies the licence named *licenseName*; throws when it is not accepted. The first of these that holds it is used: the name as a path; the folder of the Aspose.CSS assembly; the folder of the calling assembly; the folder of the entry assembly; an embedded resource of the calling assembly whose name equals *licenseName* or ends with "." and *licenseName*. |

### See Also

* namespace [Aspose.Css](../)
* assembly [Aspose.CSS](../../)
