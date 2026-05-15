---
title: "FeatureAttributeCollection.Item"
second_title: "Aspose.GIS for .NET API 参考"
description: "FeatureAttributeCollection 属性。获取或设置指定索引处的 FeatureAttribute"
type: docs
weight: 30
url: /zh/net/aspose.gis/featureattributecollection/item/
---
## FeatureAttributeCollection indexer (1 of 2)

获取或设置指定索引处的 [`FeatureAttribute`](../../featureattribute/)。

```csharp
public FeatureAttribute this[int index] { get; set; }
```

| 参数 | 描述 |
| --- | --- |
| 索引 | 要获取或设置的属性的零基索引。 |

### 返回值

指定索引处的属性。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 索引超出范围。 |
| InvalidOperationException | 尝试修改已锁定的集合。 |

### 另见

* class [FeatureAttribute](../../featureattribute/)
* class [FeatureAttributeCollection](../)
* namespace [Aspose.Gis](../../featureattributecollection/)
* assembly [Aspose.GIS](../../../)

---

## FeatureAttributeCollection indexer (2 of 2)

获取或设置具有指定名称的 [`FeatureAttribute`](../../featureattribute/)。

```csharp
public FeatureAttribute this[string name] { get; }
```

| 参数 | 描述 |
| --- | --- |
| 名称 | 属性的名称。 |

### 返回值

具有指定名称的属性，如果未找到则为 `null`。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 属性名称为 `null`。 |

### 另见

* class [FeatureAttribute](../../featureattribute/)
* class [FeatureAttributeCollection](../)
* namespace [Aspose.Gis](../../featureattributecollection/)
* assembly [Aspose.GIS](../../../)


