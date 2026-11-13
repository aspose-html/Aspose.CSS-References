---
title: "Aspose.Css"
second_title: "Aspose.CSS for .NET API Reference"
description: "Converting HTML and CSS documents to PDF and images: the Converter entry points, results and settings."
type: "docs"
weight: 10
url: "/net/aspose.css/"
---
## Classes

| Class | Description |
| --- | --- |
| [Configuration](configuration/) | The environment of one conversion: fonts, resource policy, scripting, limits and cancellation. A conversion copies the data it holds at entry; callback objects stay borrowed. |
| [ConversionCanceledException](conversioncanceledexception/) | The conversion was cancelled through [Configuration.Cancellation](configuration/cancellation/#cancellation) or a language adapter. |
| [ConversionException](conversionexception/) | A fatal conversion failure. Match on [ConversionException.Code](conversionexception/code/#code): InvalidInput, RootLoadFailed, NoFonts, UnsupportedCapability, LimitExceeded, ReadinessNotReached, PaintRefused, LayoutAborted, EvaluationLimit, OutputFailed, InternalError (an engine fault, the original exception as the inner one). |
| [ConversionLimits](conversionlimits/) | Work and size limits. Exhausting a global one fails the conversion with a [ConversionException](conversionexception/) naming it; a per-resource one fails that resource only. |
| [ConversionResult](conversionresult/) | What one conversion produced: a detached value that owns all its data. |
| [ConversionTimings](conversiontimings/) | Wall-clock phase timings, milliseconds. |
| [Converter](converter/) | One-shot HTML to PDF or PNG conversion. A lone string input is a file path; markup goes through the overloads that also take a base URI. Caller streams are read from their current position and never closed. A file output is written beside the target and moved over it when complete. |
| [ConverterAsync](converterasync/) | The .NET task adapter over [Converter](converter/), outside the portable surface. Arguments and options are refused and the configuration copied before the task is scheduled; the conversion runs on a pool thread. Token cancellation ends the task as canceled, at the next checkpoint; [Configuration.Cancellation](configuration/cancellation/#cancellation) faults it with [ConversionCanceledException](conversioncanceledexception/), and a limit faults it with [ConversionException](conversionexception/). |
| [EvaluationLimitException](evaluationlimitexception/) | Thrown in evaluation mode when the process passes the document cap or a document passes a size ceiling. The first line of the message is the sentence the README gives for the cap. |
| [FontData](fontdata/) | Font bytes supplied by [IFontProvider](ifontprovider/). |
| [FontSettings](fontsettings/) | Where faces come from. Configured faces come before the bundled fallback, and the machine's installed fonts, when [FontSettings.UseSystemFonts](fontsettings/usesystemfonts/#usesystemfonts), come last. |
| [HtmlSource](htmlsource/) | Where the HTML comes from. A path's directory becomes an allowed file root; string and stream bases are absolute http(s) or file URIs, or about:blank. |
| [License](license/) | Applies a licence in the Aspose licence file format to this process. Without one the library runs in evaluation mode: full output, a per-process document cap, size ceilings and a metadata mark (see [EvaluationLimitException](evaluationlimitexception/)). A licence can also be given by the ASPOSE\_CSS\_LICENSE environment variable, a path or the base64 of the file. |
| [PageInfo](pageinfo/) | One page written. |
| [RenderDocument](renderdocument/) | A document loaded once and saved any number of times, each save with its own media and page options. Saves use the configuration captured at [RenderDocument.Load](renderdocument/load/#load_htmlsource_configuration); a save whose options carry a configuration is rejected. Saves are serialised per document. |
| [ResourceFailure](resourcefailure/) | One failed or denied resource. |
| [ResourceSettings](resourcesettings/) | Resource policy: network, a caller loader, allowed origins and file roots, headers. |
| [ResourceSummary](resourcesummary/) | Resource outcomes. Missing (Failed) and blocked (Denied) stay distinct. |
| [ScriptingSettings](scriptingsettings/) | Script settings. Scripts run only when [ScriptingSettings.Enabled](scriptingsettings/enabled/#enabled) is set; the default runs none. |

## Interfaces

| Interface | Description |
| --- | --- |
| [ICancellationSignal](icancellationsignal/) | A cooperative cancellation request, polled by the conversion. |
| [IFontProvider](ifontprovider/) | Supplies font bytes, not host metrics. |

## Enumerations

| Enumeration | Description |
| --- | --- |
| [ConversionCompletion](conversioncompletion/) | How a returned conversion completed. |
| [LicenseState](licensestate/) | Whether this process runs under a verified licence or in evaluation mode. |
