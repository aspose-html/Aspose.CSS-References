---
title: "Configuration Class"
second_title: "Aspose.CSS for .NET API Reference"
description: "The environment of one conversion: fonts, resource policy, scripting, limits and cancellation. A conversion copies the data it holds at entry; callback objects stay borrowed."
type: "docs"
weight: 10
url: "/net/aspose.css/configuration/"
---
## Configuration class

The environment of one conversion: fonts, resource policy, scripting, limits and cancellation. A conversion copies the data it holds at entry; callback objects stay borrowed.

```csharp
public sealed class Configuration
```

## Constructors

| Name | Description |
| --- | --- |
| [Configuration](configuration/#configuration)() | Initializes a new instance of the Configuration class. |

## Properties

| Name | Description |
| --- | --- |
| [Cancellation](cancellation/#cancellation) { get; set; } | Polled between resource operations, layout passes, pages and writes. Default null. |
| [Fonts](fonts/#fonts) { get; } | Font sources. Getter-only; created with the configuration. |
| [Limits](limits/#limits) { get; } | Work and size limits. Getter-only; created with the configuration. |
| [Resources](resources/#resources) { get; } | Resource loading policy. Getter-only; created with the configuration. |
| [Scripting](scripting/#scripting) { get; } | Script settings. Getter-only; created with the configuration. |
| [UserScripts](userscripts/#userscripts) { get; set; } | Script texts to run once after the document's own scripts. Default empty. |
| [UserStyleSheets](userstylesheets/#userstylesheets) { get; set; } | Style sheet texts with CSS user origin, resolved against the document base. Default empty. |

### See Also

* namespace [Aspose.Css](../)
* assembly [Aspose.CSS](../../)
