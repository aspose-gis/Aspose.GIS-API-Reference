---
title: "FeaturesSequence.WhereLinq"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "FeaturesSequence 方法。使用 linq 将选择条件合并为单个查询"
type: docs
weight: 110
url: /zh/net/aspose.gis/featuressequence/wherelinq/
---
## FeaturesSequence.WhereLinq method

使用 linq 将选择条件组合成单个查询。

```csharp
public virtual FeaturesSequence WhereLinq(Func<Feature, bool> filteringPredicate)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filteringPredicate | Func`2 | 用于过滤的 Lambda 函数。 |

### 返回值

属性值满足选择条件的特征。

### 异常

| 异常 | 条件 |
| --- | --- |
| NullReferenceException | 如果基序列为 null 或谓词为 null。 |

### 另见

* class [Feature](../../feature/)
* class [FeaturesSequence](../)
* namespace [Aspose.Gis](../../featuressequence/)
* assembly [Aspose.GIS](../../../)


