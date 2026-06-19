---
title: "LabelingRule.CreateFilterRule"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "LabelingRule 方法。创建一个新规则，当要素通过过滤器时对其应用标注"
type: docs
weight: 20
url: /zh/net/aspose.gis.rendering.labelings/labelingrule/createfilterrule/
---
## LabelingRule.CreateFilterRule method

创建新规则，当要素通过过滤时对其应用标注。

```csharp
public static LabelingRule CreateFilterRule(Func<Feature, bool> filter, Labeling labeling)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 过滤器 | Func`2 | 确定何时应使用标注。 |
| 标注 | 标注 | 要应用的标注。 |

### 返回值

新的 LabelingRule 对象。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 过滤器为 `null`。 |

### 另见

* class [Feature](../../../aspose.gis/feature/)
* class [Labeling](../../labeling/)
* class [LabelingRule](../)
* namespace [Aspose.Gis.Rendering.Labelings](../../labelingrule/)
* assembly [Aspose.GIS](../../../)


