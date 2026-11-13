---
title: "License.SetLicense"
second_title: "Aspose.CSS for .NET API Reference"
description: "Applies the licence read from stream; throws when it is not accepted."
type: "docs"
weight: 20
url: "/net/aspose.css/license/setlicense/"
---
## License.SetLicense method

## SetLicense(Stream) {#setlicense_stream}

Applies the licence read from *stream*; throws when it is not accepted.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A readable stream holding a licence file in the Aspose licence file format. |

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | The licence is not accepted (bad signature, wrong product, expired). |

### See Also

* class [License](../)
* namespace [Aspose.Css](../../)
* assembly [Aspose.CSS](../../../)

---

## SetLicense(string) {#setlicense_string}

Applies the licence named *licenseName*; throws when it is not accepted. The first of these that holds it is used: the name as a path; the folder of the Aspose.CSS assembly; the folder of the calling assembly; the folder of the entry assembly; an embedded resource of the calling assembly whose name equals *licenseName* or ends with "." and *licenseName*.

```csharp
public void SetLicense(string licenseName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| licenseName | string | A full or short file name or the name of an embedded resource; an empty string returns this process to evaluation mode. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *licenseName* is null. |
| FileNotFoundException | No place holds the licence; the message names the places tried. |
| InvalidOperationException | The licence is not accepted (bad signature, wrong product, expired). |
| IOException | The file cannot be read. |

### See Also

* class [License](../)
* namespace [Aspose.Css](../../)
* assembly [Aspose.CSS](../../../)
