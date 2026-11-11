---
title: "ResourceResponse Class"
second_title: "Aspose.CSS for .NET API Reference"
description: "One hop's answer: a body with a status and media type, or a redirect."
type: "docs"
weight: 50
url: "/net/aspose.css.net/resourceresponse/"
---
## ResourceResponse class

One hop's answer: a body with a status and media type, or a redirect.

```csharp
public sealed class ResourceResponse
```

## Constructors

| Name | Description |
| --- | --- |
| [ResourceResponse](resourceresponse/#resourceresponse_int_string_byte)(int, string, byte[]) | A body; the bytes are copied. |

## Properties

| Name | Description |
| --- | --- |
| [Body](body/#body) { get; } | A copy of the body. |
| [MediaType](mediatype/#mediatype) { get; } | The media type; empty for a redirect. |
| [RedirectLocation](redirectlocation/#redirectlocation) { get; } | The redirect target, or null. |
| [StatusCode](statuscode/#statuscode) { get; } | The status. |

## Methods

| Name | Description |
| --- | --- |
| static [Redirect](redirect/#redirect_int_string)(int, string) | A redirect to *location*, resolved against the request URL. |

### See Also

* namespace [Aspose.Css.Net](../)
* assembly [Aspose.CSS](../../)
