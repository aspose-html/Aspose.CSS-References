---
title: "FontSettings Class"
second_title: "Aspose.CSS for .NET API Reference"
description: "Where faces come from. Configured faces come before any bundled fallback; there is no implicit system font discovery."
type: "docs"
weight: 110
url: "/net/aspose.css/fontsettings/"
---
## FontSettings class

Where faces come from. Configured faces come before any bundled fallback; there is no implicit system font discovery.

```csharp
public sealed class FontSettings
```

## Constructors

| Name | Description |
| --- | --- |
| [FontSettings](fontsettings/#fontsettings)() | Initializes a new instance of the FontSettings class. |

## Properties

| Name | Description |
| --- | --- |
| [FallbackFamilies](fallbackfamilies/#fallbackfamilies) { get; set; } | Family names tried, in order, for the initial face. Default empty. |
| [FontsLookupFolder](fontslookupfolder/#fontslookupfolder) { get; } | The configured folder, or null. |
| [Provider](provider/#provider) { get; set; } | Supplies font bytes at conversion start. Default null. |
| [UseBundledFonts](usebundledfonts/#usebundledfonts) { get; set; } | Whether the bundled fallback corpus is used. Default true. |

## Methods

| Name | Description |
| --- | --- |
| [AddFont](addfont/#addfont_byte)(byte[]) | Adds one font from bytes; the bytes are copied. |
| [AddFontFile](addfontfile/#addfontfile_string)(string) | Adds one font file (TrueType, OpenType or a collection). |
| [SetFontsLookupFolder](setfontslookupfolder/#setfontslookupfolder_string)(string) | Replaces the configured folder; every font file in it is a face source. |

### See Also

* namespace [Aspose.Css](../)
* assembly [Aspose.CSS](../../)
