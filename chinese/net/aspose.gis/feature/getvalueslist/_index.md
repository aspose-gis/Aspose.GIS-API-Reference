---
title: "Feature.GetValuesList"
second_title: "Aspose.GIS for .NET API 参考"
description: "Feature 方法。获取属性序列的值，作为列表返回"
type: docs
weight: 70
url: /zh/net/aspose.gis/feature/getvalueslist/
---
## Feature.GetValuesList&lt;T&gt; method

获取属性序列的值，作为列表。

```csharp
public List<T> GetValuesList<T>(string attributeName, string separator, int count = 0)
```

| 参数 | 描述 |
| --- | --- |
| T | 值的期望类型。 |
| attributeName | 属性的名称。 |
| 分隔符 | 用于分隔属性名称和序列索引值的字符串。 |
| 计数 | 要返回的值的计数（缺失的值填充为 null） |

### 返回值

属性值列表，属性名称随序列索引值而不同。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 属性名称为 `null`。 |
| ArgumentException | 此图层中不存在具有此名称的属性。 |
| InvalidOperationException | 属性未被锁定。 |
| InvalidOperationException | 此要素未设置该属性的值。 |
| InvalidCastException | 请求的类型未实现 IConvertible。 |
| InvalidCastException | 属性的值为 `null`，但请求的类型是值类型。 |
| FormatException | 转换失败，因为值的格式不正确。 |
| OverflowException | 转换失败，因溢出。 |

## 备注

此方法使用 [`GetValue`](../getvalue/) 获取单个值。因此，该方法会自动将值转换为泛型类型参数中请求的类型。如果未找到索引为 0 的属性，则会生成 ArgumentException。

### 另见

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)


