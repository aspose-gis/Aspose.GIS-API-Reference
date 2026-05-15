---
title: "LineString.Item"
second_title: "Aspose.GIS for .NET API 参考"
description: "LineString 属性。获取或设置指定索引处的 IPoint"
type: docs
weight: 80
url: /zh/net/aspose.gis.geometries/linestring/item/
---
## LineString indexer

获取或设置指定索引处的 [`IPoint`](../../ipoint/)。

```csharp
public IPoint this[int index] { get; set; }
```

| 参数 | 描述 |
| --- | --- |
| 索引 | 该索引。 |

### Property Value

该 [`IPoint`](../../ipoint/)。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 索引超出范围。 |
| ArgumentNullException | 该值为 `null`。 |
| ArgumentException | 点为空。 |
| ArgumentException | 此几何体的 [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) 与参数的 [`SpatialReferenceSystem`](../spatialreferencesystem/) 均不为 `null` 且彼此不相等。 |

### 另见

* interface [IPoint](../../ipoint/)
* class [LineString](../)
* namespace [Aspose.Gis.Geometries](../../linestring/)
* assembly [Aspose.GIS](../../../)


