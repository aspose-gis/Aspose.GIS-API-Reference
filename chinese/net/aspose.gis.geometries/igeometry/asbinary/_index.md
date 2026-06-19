---
title: "IGeometry.AsBinary"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "IGeometry 方法。将此几何转换为其 WellKnown Binary 表示"
type: docs
weight: 100
url: /zh/net/aspose.gis.geometries/igeometry/asbinary/
---
## AsBinary() {#asbinary}

将此几何体转换为其 Well-Known Binary 表示。

```csharp
public byte[] AsBinary()
```

### 返回值

此几何体的 Well-Known Binary 表示。

## 备注

此方法的输出采用 Iso WKB 变体。

### 另见

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)

---

## AsBinary(WkbVariant) {#asbinary_1}

将此几何体转换为其 Well-Known Binary 表示。

```csharp
public byte[] AsBinary(WkbVariant variant)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 变体 | WkbVariant | 要使用的 Well-Known Binary 变体。 |

### 返回值

此几何体的 Well-Known Binary 表示。

### 异常

| 异常 | 条件 |
| --- | --- |
| NotSupportedException | 几何体无法以请求的 WKB 变体表示。目前当几何体的 [`HasCurveGeometry`](../hascurvegeometry/) 为 `true` 且 WKB 变体为 SimpleFeatureAccessOutdated 时会出现此情况。 |
| ArgumentOutOfRangeException | *variant* 不是有效的 [`WkbVariant`](../../wkbvariant/)。 |

### 另见

* enum [WkbVariant](../../wkbvariant/)
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


