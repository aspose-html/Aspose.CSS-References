---
title: "RenderDocument.Save"
second_title: "Aspose.CSS for .NET API Reference"
description: "Saves to the streams output creates, one per part."
type: "docs"
weight: 40
url: "/net/aspose.css/renderdocument/save/"
---
## RenderDocument.Save method

## Save(SaveOptions, ICreateStreamProvider) {#save_saveoptions_icreatestreamprovider}

Saves to the streams *output* creates, one per part.

```csharp
public ConversionResult Save(SaveOptions options, ICreateStreamProvider output)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | [SaveOptions](../../../aspose.css.saving/saveoptions/) | PDF or image options with a null configuration. |
| output | [ICreateStreamProvider](../../../aspose.css.io/icreatestreamprovider/) | The stream provider. |

### Return Value

[ConversionResult](../../conversionresult/): The conversion result.

### See Also

* class [RenderDocument](../)
* namespace [Aspose.Css](../../)
* assembly [Aspose.CSS](../../../)

---

## Save(SaveOptions, Stream) {#save_saveoptions_stream}

Saves to *output*, left open.

```csharp
public ConversionResult Save(SaveOptions options, Stream output)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | [SaveOptions](../../../aspose.css.saving/saveoptions/) | PDF or image options with a null configuration. |
| output | Stream | A writable stream. |

### Return Value

[ConversionResult](../../conversionresult/): The conversion result.

### See Also

* class [RenderDocument](../)
* namespace [Aspose.Css](../../)
* assembly [Aspose.CSS](../../../)
