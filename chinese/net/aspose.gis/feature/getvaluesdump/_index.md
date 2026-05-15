---
title: "Feature.GetValuesDump"
second_title: "Aspose.GIS for .NET API 参考"
description: "Feature 方法。返回所有属性的值，以数组形式。考虑使用 GetValues 方法以避免额外的内存分配"
type: docs
weight: 60
url: /zh/net/aspose.gis/feature/getvaluesdump/
---
## Feature.GetValuesDump method

返回所有属性的值，以数组形式。考虑使用 [`GetValues`](../getvalues/) 方法以避免额外的内存分配。

```csharp
public object[] GetValuesDump(object defaultValue = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| defaultValue | Object | 如果属性值缺失（未设置），返回的值。默认值为 `null`。考虑使用 'DBNull.Value' 来区分 'unset' 和 '`null`' 值。 |

### 返回值

用于复制属性值的新数组。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| InvalidOperationException | 属性未被锁定。 |

## 备注

特征的值属性被复制到作为参数传入的 values 数组中。对于未设置值的属性，返回指定的 'unsetValue' 参数。

### 另见

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)


