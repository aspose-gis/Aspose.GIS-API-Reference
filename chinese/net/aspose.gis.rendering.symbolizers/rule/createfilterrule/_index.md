---
title: "Rule.CreateFilterRule"
second_title: "Aspose.GIS for .NET API 参考"
description: "Rule 方法。创建新规则，在要素通过过滤器时将符号化器应用于该要素"
type: docs
weight: 20
url: /zh/net/aspose.gis.rendering.symbolizers/rule/createfilterrule/
---
## Rule.CreateFilterRule method

创建新规则，当要素通过过滤时，将符号器应用于要素。

```csharp
public static Rule CreateFilterRule(Func<Feature, bool> filter, VectorSymbolizer symbolizer)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 过滤器 | Func`2 | 确定何时应使用符号化器。 |
| 符号化器 | VectorSymbolizer | 要应用的符号化器。 |

### 返回值

新的 Rule 对象。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 过滤器为 `null`。 |

### 另见

* class [Feature](../../../aspose.gis/feature/)
* class [VectorSymbolizer](../../vectorsymbolizer/)
* class [Rule](../)
* namespace [Aspose.Gis.Rendering.Symbolizers](../../rule/)
* assembly [Aspose.GIS](../../../)


