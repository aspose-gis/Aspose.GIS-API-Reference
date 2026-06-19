---
title: "类 NumericFormat"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.NumericFormat 类。NumericFormat 用于在文本中格式化常见数值类型"
type: docs
weight: 3440
url: /zh/net/aspose.gis/numericformat/
---
## NumericFormat class

`NumericFormat` 用于在文本中格式化常见数值类型。

```csharp
public abstract class NumericFormat
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [RoundTrip](../../aspose.gis/numericformat/roundtrip/) { get; } | 转换并尝试确保被转换为字符串的数值能够解析回相同的数值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Flat](../../aspose.gis/numericformat/flat/)(int) | 将数字转换为不使用科学计数法的定点文本。 |
| static [General](../../aspose.gis/numericformat/general/)(int) | 根据数字类型以及是否存在精度说明符，将数字转换为定点或科学计数法中更紧凑的形式。推荐使用。 |

## 备注

有三种 `NumericFormat` 类型：General - 定点或科学计数法。某些位数是有效的。RoundTrip - 定点或科学计数法。最大位数是有效的。Flat - 定点计数法。某些位数是有效的。`NumericFormat` 可以通过 [`AsText`](../../aspose.gis.geometries/igeometry/astext/) 设置到 [`IGeometry`](../../aspose.gis.geometries/igeometry/)，以在将几何体转换为其 Well-Known Text（WKT）表示时指定数值格式。

### 另见

* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


