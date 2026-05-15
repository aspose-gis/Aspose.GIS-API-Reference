---
title: "Feature.SetValue"
second_title: "Aspose.GIS for .NET API 参考"
description: "Feature 方法。设置属性的新值。"
type: docs
weight: 100
url: /zh/net/aspose.gis/feature/setvalue/
---
## Feature.SetValue&lt;T&gt; method

设置属性的新值。

```csharp
public void SetValue<T>(string attributeName, T value)
```

| 参数 | 描述 |
| --- | --- |
| T | 值的类型。 |
| attributeName | 属性的名称。 |
| 值 | 属性的值。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 属性名称为 `null`。 |
| ArgumentException | 此图层中不存在具有此名称的属性。 |
| InvalidOperationException | 属性未被锁定。 |
| InvalidCastException | 值的类型未实现 IConvertible。 |
| FormatException | 转换失败，因为值的格式不正确。 |
| OverflowException | 转换失败，因溢出。 |

## 备注

此方法会自动将值转换为属性的类型。

### 另见

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)


