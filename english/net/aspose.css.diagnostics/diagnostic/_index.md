---
title: "Diagnostic Class"
second_title: "Aspose.CSS for .NET API Reference"
description: "One diagnostic. Diagnostic.Code, Diagnostic.Phase and Diagnostic.Severity are stable vocabularies to match on; Diagnostic.Message is prose for people."
type: "docs"
weight: 10
url: "/net/aspose.css.diagnostics/diagnostic/"
---
## Diagnostic class

One diagnostic. [Diagnostic.Code](code/#code), [Diagnostic.Phase](phase/#phase) and [Diagnostic.Severity](severity/#severity) are stable vocabularies to match on; [Diagnostic.Message](message/#message) is prose for people.

```csharp
public sealed class Diagnostic
```

## Properties

| Name | Description |
| --- | --- |
| [Code](code/#code) { get; } | The stable code, e.g. Drop, ResourceMissing, ResourceDenied, ScriptNotRun, PageClipped, PageScaled, PageOversize, FontFallback, TempCleanupFailed. |
| [Column](column/#column) { get; } | The column, when known. Not filled in this version. |
| [ElementId](elementid/#elementid) { get; } | The element id, when known. Not filled in this version. |
| [Line](line/#line) { get; } | The line, when known. Not filled in this version. |
| [Message](message/#message) { get; } | A human-readable message. |
| [Name](name/#name) { get; } | The thing it names: a property, feature, resource kind or limit. |
| [PageIndex](pageindex/#pageindex) { get; } | The zero-based page, when one applies. |
| [Phase](phase/#phase) { get; } | Where it arose: Load, Preparation, Layout, Paint or Output. |
| [Severity](severity/#severity) { get; } | Information, Warning or Error. |
| [SourceUrl](sourceurl/#sourceurl) { get; } | The source URL, query removed, when one applies. |

### See Also

* namespace [Aspose.Css.Diagnostics](../)
* assembly [Aspose.CSS](../../)
