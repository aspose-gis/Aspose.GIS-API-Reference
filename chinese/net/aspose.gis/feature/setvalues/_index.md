---
title: "Feature.SetValues"
second_title: "Aspose.GIS for .NET API 参考"
description: "Feature 方法。为所有属性设置新值。还可以考虑使用 CopyValues 方法以在一次调用中简化设置值的过程"
type: docs
weight: 120
url: /zh/net/aspose.gis/feature/setvalues/
---
## Feature.SetValues method

为所有属性设置新值。还可以考虑使用 [`CopyValues`](../copyvalues/) 方法以在一次调用中简化设置值的过程。

```csharp
public int SetValues(object[] values)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | Object[] | 新值的数组。 |

### 返回值

已设置的属性值数量。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数不能为 `null`。 |
| ArgumentException | 此图层中不存在具有此名称的属性。 |
| InvalidOperationException | 属性未被锁定。 |
| InvalidCastException | 值的类型未实现 IConvertible。 |
| FormatException | 转换失败，因为值的格式不正确。 |
| OverflowException | 转换失败，因溢出。 |

## 备注

此方法会自动将每个值转换为属性的类型。值数组的长度不必与要素中的属性数量匹配。如果数组长度大于属性数量，所有数组值都会复制到属性中；如果数组长度较短，则仅将数组长度对应数量的值复制到属性中，从序号为 0 的属性值开始。

### 另见

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)


