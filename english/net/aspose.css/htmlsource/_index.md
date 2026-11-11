---
title: "HtmlSource Class"
second_title: "Aspose.CSS for .NET API Reference"
description: "Where the HTML comes from. A path's directory becomes an allowed file root; string and stream bases are absolute http(s) or file URIs, or about:blank."
type: "docs"
weight: 120
url: "/net/aspose.css/htmlsource/"
---
## HtmlSource class

Where the HTML comes from. A path's directory becomes an allowed file root; string and stream bases are absolute http(s) or file URIs, or about:blank.

```csharp
public sealed class HtmlSource
```

## Methods

| Name | Description |
| --- | --- |
| static [FromFile](fromfile/#fromfile_string)(string) | A local file, resolved to a full path now. |
| static [FromStream](fromstream/#fromstream_stream_string)(Stream, string) | Bytes read now from the current position; the stream is left open. |
| static [FromString](fromstring/#fromstring_string_string)(string, string) | Decoded markup with its base URI. |
| static [FromUrl](fromurl/#fromurl_string)(string) | An absolute http(s) URL without credentials, fetched through the resource policy. |

### See Also

* namespace [Aspose.Css](../)
* assembly [Aspose.CSS](../../)
