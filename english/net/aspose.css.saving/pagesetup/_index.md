---
title: "PageSetup Class"
second_title: "Aspose.CSS for .NET API Reference"
description: "API page geometry. Fallback paper is A4 portrait with zero margins. Side-specific pages override PageSetup.AnyPage; PageSetup.FirstPage wins on page one; the first page is a right page."
type: "docs"
weight: 60
url: "/net/aspose.css.saving/pagesetup/"
---
## PageSetup class

API page geometry. Fallback paper is A4 portrait with zero margins. Side-specific pages override [PageSetup.AnyPage](anypage/#anypage); [PageSetup.FirstPage](firstpage/#firstpage) wins on page one; the first page is a right page.

```csharp
public sealed class PageSetup
```

## Constructors

| Name | Description |
| --- | --- |
| [PageSetup](pagesetup/#pagesetup)() | Initializes a new instance of the PageSetup class. |

## Properties

| Name | Description |
| --- | --- |
| [AnyPage](anypage/#anypage) { get; set; } | Every page. Default null. |
| [AtPagePriority](atpagepriority/#atpagepriority) { get; set; } | True (default): the document's @page values win over these; false: these win. Values left null never erase the document's. |
| [FirstPage](firstpage/#firstpage) { get; set; } | Page one. Default null. |
| [LeftPage](leftpage/#leftpage) { get; set; } | Left pages. Default null. |
| [PaginationMode](paginationmode/#paginationmode) { get; set; } | Cut (default) slices one layout into pages; Fragmentation lays the document out in pages. |
| [RightPage](rightpage/#rightpage) { get; set; } | Right pages. Default null. |

### See Also

* namespace [Aspose.Css.Saving](../)
* assembly [Aspose.CSS](../../)
