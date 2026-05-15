---
title: "Geometry.AsText"
second_title: "Aspose.GIS for .NET API 参考"
description: "Geometry 方法。将此几何体转换为其 WellKnown Text 表示"
type: docs
weight: 130
url: /zh/net/aspose.gis.geometries/geometry/astext/
---
## AsText() {#astext}

将此几何体转换为其 Well-Known Text 表示。

```csharp
public string AsText()
```

### 返回值

此几何体的 Well-Known Text 表示。

## 备注

此方法的输出采用 Iso WKT 变体。默认数值格式为[`General`](../../../aspose.gis/numericformat/general/)（精度为“0”）。

### 另见

* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)

---

## AsText(WktVariant) {#astext_1}

将此几何体转换为其 Well-Known Text 表示。

```csharp
public string AsText(WktVariant variant)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 变体 | WktVariant | 要使用的 Well-Known Text 变体。 |

### 返回值

此几何体的 Well-Known Text 表示。

### 异常

| 异常 | 条件 |
| --- | --- |
| NotSupportedException | 几何体无法以请求的 WKT 变体表示。目前当几何体的[`HasCurveGeometry`](../hascurvegeometry/) 为 `true` 且 WKT 变体为 SimpleFeatureAccessOutdated 时会出现此情况。 |
| ArgumentOutOfRangeException | *variant* 不是有效的[`WktVariant`](../../wktvariant/)。 |

## 备注

默认数值格式为 [`General`](../../../aspose.gis/numericformat/general/)（精度为 "0"）。

### 另见

* enum [WktVariant](../../wktvariant/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)

---

## AsText(WktVariant, NumericFormat) {#astext_2}

将此几何体转换为其 Well-Known Text 表示。

```csharp
public string AsText(WktVariant variant, NumericFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 变体 | WktVariant | 要使用的 Well-Known Text 变体。 |
| format | NumericFormat | 坐标格式用于转换为字符串。请参阅 [`NumericFormat`](../../../aspose.gis/numericformat/) 获取它。 |

### 返回值

此几何体的 Well-Known Text 表示。

### 异常

| 异常 | 条件 |
| --- | --- |
| NotSupportedException | 几何体无法以请求的 WKT 变体表示。目前当几何体的[`HasCurveGeometry`](../hascurvegeometry/) 为 `true` 且 WKT 变体为 SimpleFeatureAccessOutdated 时会出现此情况。 |
| ArgumentOutOfRangeException | *variant* 不是有效的[`WktVariant`](../../wktvariant/)。 |

### 另见

* enum [WktVariant](../../wktvariant/)
* class [NumericFormat](../../../aspose.gis/numericformat/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


