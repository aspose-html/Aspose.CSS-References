---
title: "ResourceSettings Class"
second_title: "Aspose.CSS for .NET API Reference"
description: "Resource policy: network, a caller loader, allowed origins and file roots, headers."
type: "docs"
weight: 210
url: "/net/aspose.css/resourcesettings/"
---
## ResourceSettings class

Resource policy: network, a caller loader, allowed origins and file roots, headers.

```csharp
public sealed class ResourceSettings
```

## Constructors

| Name | Description |
| --- | --- |
| [ResourceSettings](resourcesettings/#resourcesettings)() | Initializes a new instance of the ResourceSettings class. |

## Properties

| Name | Description |
| --- | --- |
| [AllowedFileRoots](allowedfileroots/#allowedfileroots) { get; set; } | Directories file resources may come from. A file source grants its own directory; string and stream sources grant none. Default empty. |
| [AllowedOrigins](allowedorigins/#allowedorigins) { get; set; } | HTTP(S) origins resources may come from; empty means any. Default empty. |
| [Headers](headers/#headers) { get; set; } | Request headers, each sent only to its exact origin. Default empty. |
| [Loader](loader/#loader) { get; set; } | A caller loader asked first for every resource. Default null. |
| [NetworkEnabled](networkenabled/#networkenabled) { get; set; } | Whether the built-in HTTP(S) loader may be used. Default true. |

### See Also

* namespace [Aspose.Css](../)
* assembly [Aspose.CSS](../../)
