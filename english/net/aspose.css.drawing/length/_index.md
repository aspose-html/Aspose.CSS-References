---
title: "Length Structure"
second_title: "Aspose.CSS for .NET API Reference"
description: "An immutable absolute length. 96 CSS px = 72 pt = 25.4 mm."
type: "docs"
weight: 10
url: "/net/aspose.css.drawing/length/"
---
## Length structure

An immutable absolute length. 96 CSS px = 72 pt = 25.4 mm.

```csharp
public readonly struct Length : IEquatable<Length>
```

## Properties

| Name | Description |
| --- | --- |
| [CssPixels](csspixels/#csspixels) { get; } | The length in CSS px. |
| [Unit](unit/#unit) { get; } | The unit: px, pt or mm. |
| [Value](value/#value) { get; } | The number in [Length.Unit](unit/#unit). |

## Methods

| Name | Description |
| --- | --- |
| [Equals](equals/#equals_length)(Length) | Equality of value and unit. |
| [Equals](equals/#equals_object)(object?) | Tells whether this instance and the given object are equal. |
| [GetHashCode](gethashcode/#gethashcode)() | Returns the hash code of this instance. |
| static [Mm](mm/#mm_double)(double) | A length in millimetres. |
| static [Pt](pt/#pt_double)(double) | A length in points. |
| static [Px](px/#px_double)(double) | A length in CSS px. |
| [ToString](tostring/#tostring)() | The CSS text, e.g. 12mm. |

## Operators

| Name | Description |
| --- | --- |
| [op\_Equality](op_equality/#op_equality_length_length)(Length, Length) | Equality. |
| [op\_Inequality](op_inequality/#op_inequality_length_length)(Length, Length) | Inequality. |

### See Also

* namespace [Aspose.Css.Drawing](../)
* assembly [Aspose.CSS](../../)
