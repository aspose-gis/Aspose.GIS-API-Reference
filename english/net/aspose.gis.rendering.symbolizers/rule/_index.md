---
title: Rule
second_title: Aspose.GIS for .NET API Reference
description: 
type: docs
weight: 1780
url: /net/aspose.gis.rendering.symbolizers/rule/
---
## Rule class

A user-defined rule for [`RuleBasedSymbolizer`](../rulebasedsymbolizer).

```csharp
public class Rule
```

## Properties

| Name | Description |
| --- | --- |
| [Filter](filter) { get; } | Determines if "filter-rule" should apply symbolizer to the feature. If returns `true` symbolizer is used; otherwise, feature is skipped. |
| [IsElseRule](iselserule) { get; } | Gets a value indicating whether this rule is "else-rule". |
| [IsFilterRule](isfilterrule) { get; } | Gets a value indicating whether this rule is "filter-rule". |
| [Symbolizer](symbolizer) { get; } | Symbolizer to apply to the feature. |

## Methods

| Name | Description |
| --- | --- |
| static [CreateElseRule](createelserule)(VectorSymbolizer) | Creates new rule that applies a symbolizer to feature whenever it doesn't match any filter rule. |
| static [CreateFilterRule](createfilterrule)(Func&lt;Feature, bool&gt;, VectorSymbolizer) | Creates new rule that applies a symbolizer to feature whenever it passes filter. |

### See Also

* namespace [Aspose.Gis.Rendering.Symbolizers](../../aspose.gis.rendering.symbolizers)
* assembly [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->