---
title: "License.SetLicense"
second_title: "Aspose.CSS for .NET API Reference"
description: "Applies the licence read from stream; throws when it is not accepted."
type: "docs"
weight: 20
url: "/net/aspose.css.licensing/license/setlicense/"
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
* namespace [Aspose.Css.Licensing](../../)
* assembly [Aspose.CSS](../../../)

---

## SetLicense(string) {#setlicense_string}

Applies the licence file at *path*; throws when it is not accepted.

```csharp
public void SetLicense(string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | string | The path of a licence file in the Aspose licence file format. |

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | The licence is not accepted (bad signature, wrong product, expired). |
| IOException | The file cannot be read. |

### See Also

* class [License](../)
* namespace [Aspose.Css.Licensing](../../)
* assembly [Aspose.CSS](../../../)
