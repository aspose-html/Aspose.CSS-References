---
title: "ConversionException Class"
second_title: "Aspose.CSS for .NET API Reference"
description: "A fatal conversion failure. Match on ConversionException.Code: InvalidInput, RootLoadFailed, NoFonts, UnsupportedCapability, LimitExceeded, ReadinessNotReached, PaintRefused, LayoutAborted, EvaluationLimit, OutputFailed, InternalError (an engine fault, the original exception as the inner one)."
type: "docs"
weight: 40
url: "/net/aspose.css/conversionexception/"
---
## ConversionException class

A fatal conversion failure. Match on [ConversionException.Code](code/#code): InvalidInput, RootLoadFailed, NoFonts, UnsupportedCapability, LimitExceeded, ReadinessNotReached, PaintRefused, LayoutAborted, EvaluationLimit, OutputFailed, InternalError (an engine fault, the original exception as the inner one).

```csharp
public class ConversionException : Exception
```

## Properties

| Name | Description |
| --- | --- |
| [Code](code/#code) { get; } | The stable failure code. |
| [ConfiguredLimit](configuredlimit/#configuredlimit) { get; } | The configured limit, for LimitExceeded. |
| [Diagnostics](diagnostics/#diagnostics) { get; } | The diagnostics gathered before the failure. |
| [LimitName](limitname/#limitname) { get; } | The limit's property name, for LimitExceeded. |
| [ObservedValue](observedvalue/#observedvalue) { get; } | The value observed, for LimitExceeded. |
| [Resources](resources/#resources) { get; } | The resource outcomes up to the failure; null when it came before saving began. |

### See Also

* namespace [Aspose.Css](../)
* assembly [Aspose.CSS](../../)
