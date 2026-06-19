---
title: "类 FeatureAttributeCollection"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.FeatureAttributeCollection 类。FeatureAttributeCollection 定义了 Feature 可用的属性。"
type: docs
weight: 1640
url: /zh/net/aspose.gis/featureattributecollection/
---
## FeatureAttributeCollection class

`FeatureAttributeCollection` 定义了可用于 [`Feature`](../feature/) 的属性。

```csharp
public sealed class FeatureAttributeCollection : IEnumerable<FeatureAttribute>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.gis/featureattributecollection/count/) { get; } | 获取 [`Feature`](../feature/) 中属性的数量。 |
| [IsLocked](../../aspose.gis/featureattributecollection/islocked/) { get; } | 获取一个值，指示此属性集合是否已锁定。 |
| [Item](../../aspose.gis/featureattributecollection/item/) { get; set; } | 获取或设置指定索引处的 [`FeatureAttribute`](../featureattribute/)。 |
| [Item](../../aspose.gis/featureattributecollection/item/) { get; } | 获取或设置具有指定名称的 [`FeatureAttribute`](../featureattribute/)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.gis/featureattributecollection/add/)(FeatureAttribute) | 向集合中添加属性。 |
| [Contains](../../aspose.gis/featureattributecollection/contains/)(string) | 确定属性集合是否包含具有指定名称的属性。 |
| [GetEnumerator](../../aspose.gis/featureattributecollection/getenumerator/)() | 返回一个遍历集合的枚举器。 |
| [IndexOf](../../aspose.gis/featureattributecollection/indexof/)(string) | 搜索属性并返回其基于零的索引。 |
| [Lock](../../aspose.gis/featureattributecollection/lock/)() | 锁定此属性集合以防止进一步修改。 |
| [Remove](../../aspose.gis/featureattributecollection/remove/#remove)(int) | 从集合中移除属性。 |
| [Remove](../../aspose.gis/featureattributecollection/remove/#remove_1)(string) | 从集合中移除属性。 |

### 另见

* class [FeatureAttribute](../featureattribute/)
* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


