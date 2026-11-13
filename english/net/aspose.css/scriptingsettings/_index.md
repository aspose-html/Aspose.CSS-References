---
title: "ScriptingSettings Class"
second_title: "Aspose.CSS for .NET API Reference"
description: "Script settings. Scripts run only when ScriptingSettings.Enabled is set; the default runs none."
type: "docs"
weight: 230
url: "/net/aspose.css/scriptingsettings/"
---
## ScriptingSettings class

Script settings. Scripts run only when [ScriptingSettings.Enabled](enabled/#enabled) is set; the default runs none.

```csharp
public sealed class ScriptingSettings
```

## Constructors

| Name | Description |
| --- | --- |
| [ScriptingSettings](scriptingsettings/#scriptingsettings)() | Initializes a new instance of the ScriptingSettings class. |

## Properties

| Name | Description |
| --- | --- |
| [ClockUnixMilliseconds](clockunixmilliseconds/#clockunixmilliseconds) { get; set; } | The document clock's start, Unix ms. Default 0. |
| [Enabled](enabled/#enabled) { get; set; } | Whether document and user scripts run. Default false: scripts are not run and their count is reported as an Information diagnostic ScriptsDisabled. When set, the document's scripts run in document order, then [Configuration.UserScripts](../configuration/userscripts/#userscripts), and the mutated document is laid out. Scripts reach no .NET type, make no network or file request except through [ResourceSettings](../resourcesettings/), and stop at the budgets below. A script's error is reported as ScriptError and a budget reached as ScriptLimitExceeded; neither stops the conversion. |
| [MaxMemoryBytes](maxmemorybytes/#maxmemorybytes) { get; set; } | Script memory budget, bytes. Default 64 MiB. |
| [MaxStatements](maxstatements/#maxstatements) { get; set; } | Script statement budget. Default 1,000,000. |
| [MaxTimerCallbacks](maxtimercallbacks/#maxtimercallbacks) { get; set; } | Timer callbacks run at most. Default 1000. |
| [RandomSeed](randomseed/#randomseed) { get; set; } | The random seed. Default 0. |
| [ReadyFunction](readyfunction/#readyfunction) { get; set; } | A document function that must return true before rendering. Default null. A value that is not reached within the budget fails with ReadinessNotReached. |
| [TimeoutMilliseconds](timeoutmilliseconds/#timeoutmilliseconds) { get; set; } | Script wall-clock budget, ms. Default 2000. |
| [TimerHorizonMilliseconds](timerhorizonmilliseconds/#timerhorizonmilliseconds) { get; set; } | Virtual time horizon for timers, ms. Default 1000. |

### See Also

* namespace [Aspose.Css](../)
* assembly [Aspose.CSS](../../)
