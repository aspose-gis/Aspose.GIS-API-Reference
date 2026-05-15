---
title: "Feature.GetValues"
second_title: "Aspose.GIS for .NET API 参考"
description: "Feature 方法。返回所有属性的值，以数组形式"
type: docs
weight: 50
url: /zh/net/aspose.gis/feature/getvalues/
---
## Feature.GetValues method

返回所有属性的值，以数组形式。

```csharp
public int GetValues(object[] values, object defaultValue = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | Object[] | 用于复制属性值的数组。 |
| defaultValue | Object | 如果属性值缺失（未设置），返回的值。默认值为 `null`。考虑使用 'DBNull.Value' 来区分 'unset' 和 '`null`' 值。 |

### 返回值

已复制若干属性。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| InvalidOperationException | 属性未被锁定。 |

## 备注

特征的值属性被复制到作为参数传入的 values 数组中。对于未设置值的属性，返回指定的 'unsetValue' 参数。values 数组的长度不必与特征中的属性数量匹配。如果数组长度大于属性数量，所有属性值都将复制到数组中；如果数组长度较小，则仅复制数组长度数量的属性值，起始于序号为 0 的属性值。

### 另见

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)


