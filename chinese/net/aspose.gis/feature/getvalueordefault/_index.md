---
title: "Feature.GetValueOrDefault"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Feature 方法。获取属性的值；如果值未设置或为 null，则返回 DefaultValue"
type: docs
weight: 40
url: /zh/net/aspose.gis/feature/getvalueordefault/
---
## GetValueOrDefault&lt;T&gt;(string) {#getvalueordefault_1}

获取属性的值，或者如果值未设置或为 `null`，则返回 [`DefaultValue`](../../featureattribute/defaultvalue/)。

```csharp
public T GetValueOrDefault<T>(string attributeName)
```

| 参数 | 描述 |
| --- | --- |
| T | 所需的值类型。 |
| attributeName | 属性的名称。 |

### 返回值

属性的值。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 属性名称为 `null`。 |
| ArgumentException | 此图层中不存在具有此名称的属性。 |
| InvalidOperationException | 该属性未锁定。 |
| InvalidOperationException | 此要素未设置此属性的值。 |
| InvalidCastException | 请求的类型未实现 IConvertible。 |
| InvalidCastException | 属性的值为 `null`，但请求的类型是值类型。 |
| FormatException | 转换失败，因为值的格式不正确。 |
| OverflowException | 转换失败，因溢出。 |

## 备注

此方法会自动将值转换为泛型类型参数中请求的类型。

### 另见

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)

---

## GetValueOrDefault(string, object) {#getvalueordefault}

获取属性的值，或者如果值未设置或为 `null`，则返回 [`DefaultValue`](../../featureattribute/defaultvalue/)。

```csharp
public object GetValueOrDefault(string attributeName, object defaultValue = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| attributeName | 字符串 | 属性的名称。 |
| defaultValue | Object | 如果属性值缺失时返回的值。默认值为 `null`。 |

### 返回值

属性的值。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 属性名称为 `null`。 |
| ArgumentException | 此图层中不存在具有此名称的属性。 |
| InvalidOperationException | 该属性未锁定。 |
| InvalidOperationException | 此要素未设置此属性的值。 |

### 另见

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)

---

## GetValueOrDefault&lt;T&gt;(string, object) {#getvalueordefault_2}

获取属性的值，或者如果值未设置或为 `null`，则返回 [`DefaultValue`](../../featureattribute/defaultvalue/)。

```csharp
public T GetValueOrDefault<T>(string attributeName, object defaultValue)
```

| 参数 | 描述 |
| --- | --- |
| T | 所需的值类型。 |
| attributeName | 属性的名称。 |
| defaultValue | 如果属性值缺失时返回的值。 |

### 返回值

属性的值。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 属性名称为 `null`。 |
| ArgumentException | 此图层中不存在具有此名称的属性。 |
| InvalidOperationException | 该属性未锁定。 |
| InvalidOperationException | 此要素未设置此属性的值。 |
| InvalidCastException | 请求的类型未实现 IConvertible。 |
| InvalidCastException | 属性的值为 `null`，但请求的类型是值类型。 |
| FormatException | 转换失败，因为值的格式不正确。 |
| OverflowException | 转换失败，因溢出。 |

## 备注

此方法会自动将值转换为泛型类型参数中请求的类型。

### 另见

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)


