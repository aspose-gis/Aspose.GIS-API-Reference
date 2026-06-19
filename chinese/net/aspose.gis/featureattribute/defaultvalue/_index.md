---
title: "FeatureAttribute.DefaultValue"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "FeatureAttribute 属性。获取或设置指示缺失数据的属性值"
type: docs
weight: 50
url: /zh/net/aspose.gis/featureattribute/defaultvalue/
---
## FeatureAttribute.DefaultValue property

获取或设置属性的值，以指示缺失的数据。

```csharp
public object DefaultValue { get; set; }
```

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 属性已锁定。 |
| InvalidOperationException | 该属性不允许 `null` 值。 |

## 备注

这是表示缺失信息的值，当属性不允许 `null` 值时。对于允许 `null` 值的属性（[`CanBeNull`](../canbenull/) == `true`），除非显式更改，否则 `DefaultValue` 为 `null`。

### 另见

* class [FeatureAttribute](../)
* namespace [Aspose.Gis](../../featureattribute/)
* assembly [Aspose.GIS](../../../)


