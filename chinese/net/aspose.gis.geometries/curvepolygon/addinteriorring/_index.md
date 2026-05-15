---
title: "CurvePolygon.AddInteriorRing"
second_title: "Aspose.GIS for .NET API 参考"
description: "CurvePolygon 方法. 添加内部环"
type: docs
weight: 100
url: /zh/net/aspose.gis.geometries/curvepolygon/addinteriorring/
---
## CurvePolygon.AddInteriorRing method

添加内部环。

```csharp
public void AddInteriorRing(ICurve ring)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 环 | ICurve | 要添加的环。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 此几何体的 [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) 与参数的 [`SpatialReferenceSystem`](../spatialreferencesystem/) 均不为 `null` 且彼此不相等。 |

### 另见

* interface [ICurve](../../icurve/)
* class [CurvePolygon](../)
* namespace [Aspose.Gis.Geometries](../../curvepolygon/)
* assembly [Aspose.GIS](../../../)


