---
title: DefaultValue
second_title: Aspose.GIS for .NET API 参考
description: 获取或设置属性的值表示缺少数据
type: docs
weight: 50
url: /zh/net/aspose.gis/featureattribute/defaultvalue/
---
## FeatureAttribute.DefaultValue property

获取或设置属性的值，表示缺少数据。

```csharp
public object DefaultValue { get; set; }
```

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| InvalidOperationException | 属性被锁定。 |
| InvalidOperationException | 该属性不允许` null` 值。 |

### 评论

当属性不允许` null` 值。 对于允许` null` 值的属性（[`CanBeNull`](../canbenull)==` true` ),`DefaultValue`is` null` 除非明确更改。

### 也可以看看

* class [FeatureAttribute](../../featureattribute)
* 命名空间 [Aspose.Gis](../../featureattribute)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->