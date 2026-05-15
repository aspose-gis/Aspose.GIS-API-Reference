---
title: "Feature.GetValue"
second_title: "Aspose.GIS for .NET API 参考"
description: "Feature 方法。获取属性的值"
type: docs
weight: 30
url: /zh/net/aspose.gis/feature/getvalue/
---
## GetValue(string) {#getvalue}

获取属性的值。

```csharp
public object GetValue(string attributeName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| attributeName | String | 属性的名称。 |

### 返回值

属性的值。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 属性名称为 `null`。 |
| ArgumentException | 此图层中不存在具有此名称的属性。 |
| InvalidOperationException | 属性未被锁定。 |
| InvalidOperationException | 此要素未设置该属性的值。 |

## 备注

如果图层不要求其要素拥有该图层定义的所有属性的值，则在请求缺失的值时，此方法可能会抛出 InvalidOperationException。处理此类图层时，建议使用 [`GetValueOrDefault`](../getvalueordefault/)。

### 另见

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)

---

## GetValue&lt;T&gt;(string) {#getvalue_1}

获取属性的值。

```csharp
public T GetValue<T>(string attributeName)
```

| 参数 | 描述 |
| --- | --- |
| T | 值的期望类型。 |
| attributeName | 属性的名称。 |

### 返回值

属性的值。

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

此方法会自动将值转换为泛型类型参数中请求的类型。如果图层不要求其要素拥有该图层定义的所有属性的值，则在请求缺失的值时，此方法可能会抛出 InvalidOperationException。处理此类图层时，建议使用 [`GetValueOrDefault`](../getvalueordefault/)。

### 另见

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)


