---
title: "OptLBR class"
description: "The C++ Build Insights SDK OptLBR class reference."
ms.date: "02/12/2020"
helpviewer_keywords: ["C++ Build Insights", "C++ Build Insights SDK", "OptLBR", "throughput analysis", "build time analysis", "vcperf.exe"]
---
# OptLBR class

::: moniker range="<=vs-2015"

The C++ Build Insights SDK is compatible with Visual Studio 2017 and above. To see the documentation for these versions, set the Visual Studio version selector control for this article to Visual Studio 2017 or Visual Studio 2019.

::: moniker-end
::: moniker range=">=vs-2017"

The `OptLBR` class is used with the [MatchEvent](../functions/match-event.md), [MatchEventInMemberFunction](../functions/match-event-in-member-function.md), [MatchEventStack](../functions/match-event-stack.md), and [MatchEventStackInMemberFunction](../functions/match-event-stack-in-member-function.md) functions. Use it to match an [OPT_LBR](../event-table.md#opt-lbr) event.

## Syntax

```cpp
class OptLBR : public Activity
{
public:
    OptLBR(const RawEvent& event);
};
```

## Members

Along with the inherited members from its [Activity](activity.md) base class, the `OptLBR` class contains the following members:

### Constructors

[OptLBR](#opt-lbr)

## <a name="opt-lbr"></a> OptLBR

```cpp
OptLBR(const RawEvent& event);
```

### Parameters

*event*\
An [OPT_LBR](../event-table.md#opt-lbr) event.

::: moniker-end
