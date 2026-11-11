---
title: "ScriptingSettings Class"
second_title: "Aspose.CSS for .NET API Reference"
description: "Script settings. This beta runs no scripts; see ScriptingSettings.Enabled."
type: "docs"
weight: 200
url: "/net/aspose.css/scriptingsettings/"
---
## ScriptingSettings class

Script settings. This beta runs no scripts; see [ScriptingSettings.Enabled](enabled/#enabled).

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
| [Enabled](enabled/#enabled) { get; set; } | Whether scripts are wanted. Default true. This beta has no script host: each document or user script is reported as a ScriptNotRun warning. |
| [MaxMemoryBytes](maxmemorybytes/#maxmemorybytes) { get; set; } | Script memory budget, bytes. Default 64 MiB. |
| [MaxStatements](maxstatements/#maxstatements) { get; set; } | Script statement budget. Default 1,000,000. |
| [MaxTimerCallbacks](maxtimercallbacks/#maxtimercallbacks) { get; set; } | Timer callbacks run at most. Default 1000. |
| [RandomSeed](randomseed/#randomseed) { get; set; } | The random seed. Default 0. |
| [ReadyFunction](readyfunction/#readyfunction) { get; set; } | A document function that must return true before rendering. Default null. Without a script host it is never reached: a non-null value fails with ReadinessNotReached. |
| [TimeoutMilliseconds](timeoutmilliseconds/#timeoutmilliseconds) { get; set; } | Script wall-clock budget, ms. Default 2000. |
| [TimerHorizonMilliseconds](timerhorizonmilliseconds/#timerhorizonmilliseconds) { get; set; } | Virtual time horizon for timers, ms. Default 1000. |

### See Also

* namespace [Aspose.Css](../)
* assembly [Aspose.CSS](../../)
