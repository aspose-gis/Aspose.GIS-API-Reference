---
title: "IGeometry.AsText"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "IGeometry 方法。将此几何对象转换为其 WellKnown Text 表示。"
type: docs
weight: 120
url: /zh/net/aspose.gis.geometries/igeometry/astext/
---
## AsText() {#astext}

将此几何体转换为其 Well-Known Text 表示。

```csharp
public string AsText()
```

### 返回值

此几何体的 Well-Known Text 表示。

## 备注

此方法的输出采用 Iso WKT 变体。

### 另见

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
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
| NotSupportedException | 请求的 WKT 变体不支持该几何对象。以下几何对象仅在 Iso WKT 变体中受支持：[`CircularString`](../../circularstring/)[`CompoundCurve`](../../compoundcurve/)[`CurvePolygon`](../../curvepolygon/)[`MultiCurve`](../../multicurve/)[`MultiSurface`](../../multisurface/) 其他所有几何对象均受任何 WKT 变体支持。 |
| ArgumentOutOfRangeException | *variant* 不是有效的[`WktVariant`](../../wktvariant/)。 |

### 另见

* enum [WktVariant](../../wktvariant/)
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
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
| format | NumericFormat | 用于转换为字符串的坐标格式。请参阅 [`NumericFormat`](../../../aspose.gis/numericformat/) 以获取它。 |

### 返回值

此几何体的 Well-Known Text 表示。

### 异常

| 异常 | 条件 |
| --- | --- |
| NotSupportedException | 几何体无法以请求的 WKT 变体表示。当前当几何体的[`HasCurveGeometry`](../hascurvegeometry/) 为 `true` 且 WKT 变体为 SimpleFeatureAccessOutdated 时会出现此情况。 |
| ArgumentOutOfRangeException | *variant* 不是有效的[`WktVariant`](../../wktvariant/)。 |

### 另见

* enum [WktVariant](../../wktvariant/)
* class [NumericFormat](../../../aspose.gis/numericformat/)
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


