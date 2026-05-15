---
title: "类 Feature"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.Feature 类。由几何对象和用户自定义属性组成的地理要素"
type: docs
weight: 1620
url: /zh/net/aspose.gis/feature/
---
## Feature class

由几何形状和用户定义属性组成的地理要素。

```csharp
public class Feature
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Geometry](../../aspose.gis/feature/geometry/) { get; set; } | 获取或设置要素的几何对象。不能为 `null`，使用 [`Null`](../../aspose.gis.geometries/geometry/null/) 表示缺失的几何对象。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CopyValues](../../aspose.gis/feature/copyvalues/)(Feature) | 从另一个要素复制属性值。 |
| [GetValue](../../aspose.gis/feature/getvalue/#getvalue)(string) | 获取属性的值。 |
| [GetValue&lt;T&gt;](../../aspose.gis/feature/getvalue/#getvalue_1)(string) | 获取属性的值。 |
| [GetValueOrDefault](../../aspose.gis/feature/getvalueordefault/#getvalueordefault)(string, object) | 获取属性的值，如果该值未设置或为 `null`，则返回 [`DefaultValue`](../featureattribute/defaultvalue/)。 |
| [GetValueOrDefault&lt;T&gt;](../../aspose.gis/feature/getvalueordefault/#getvalueordefault_1)(string) | 获取属性的值，如果该值未设置或为 `null`，则返回 [`DefaultValue`](../featureattribute/defaultvalue/)。 |
| [GetValueOrDefault&lt;T&gt;](../../aspose.gis/feature/getvalueordefault/#getvalueordefault_2)(string, object) | 获取属性的值，如果该值未设置或为 `null`，则返回 [`DefaultValue`](../featureattribute/defaultvalue/)。 |
| [GetValues](../../aspose.gis/feature/getvalues/)(object[], object) | 返回所有属性的值，以数组形式。 |
| [GetValuesDump](../../aspose.gis/feature/getvaluesdump/)(object) | 返回所有属性的值，以数组形式。考虑使用[`GetValues`](./getvalues/)方法以避免额外的内存分配。 |
| [GetValuesList&lt;T&gt;](../../aspose.gis/feature/getvalueslist/)(string, string, int) | 获取属性序列的值，作为列表。 |
| [IsValueNull](../../aspose.gis/feature/isvaluenull/)(string) | 确定指定属性是否已显式设置为 `null` 值。 |
| [IsValueSet](../../aspose.gis/feature/isvalueset/)(string) | 检查此特性中是否已设置属性值。 |
| [SetValue&lt;T&gt;](../../aspose.gis/feature/setvalue/)(string, T) | 设置属性的新值。 |
| [SetValueNull](../../aspose.gis/feature/setvaluenull/)(string) | 将属性的值设置为 `null`。 |
| [SetValues](../../aspose.gis/feature/setvalues/)(object[]) | 为所有属性设置新值。同时考虑使用[`CopyValues`](./copyvalues/)方法，以在一次调用中简化设置值的过程。 |
| [UnsetValue](../../aspose.gis/feature/unsetvalue/)(string) | 从此特性中移除属性值。 |

### 另见

* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


