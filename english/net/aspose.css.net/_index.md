---
title: "Aspose.Css.Net"
second_title: "Aspose.CSS for .NET API Reference"
description: "Loading external resources such as stylesheets, images and fonts."
type: "docs"
weight: 60
url: "/net/aspose.css.net/"
---
## Classes

| Class | Description |
| --- | --- |
| [ResourceHeader](resourceheader/) | A request header sent only to its exact origin. |
| [ResourceRequest](resourcerequest/) | One resource request handed to [IResourceLoader](iresourceloader/). |
| [ResourceResponse](resourceresponse/) | One hop's answer: a body with a status and media type, or a redirect. |

## Interfaces

| Interface | Description |
| --- | --- |
| [IResourceLoader](iresourceloader/) | A caller loader. When set it answers every http(s) request that passes policy, in place of the built-in loaders. It returns one hop: a body or a redirect, which re-enters the policy checks. Calls are serial and must honour cancellation. |

## Enumerations

| Enumeration | Description |
| --- | --- |
| [ResourceKind](resourcekind/) | What a resource is for. |
