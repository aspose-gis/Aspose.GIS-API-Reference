---
title: "接口 ICurvePolygon"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.Geometries.ICurvePolygon 接口。由 1 条外部边界和 0 条或多条内部边界定义的平面表面"
type: docs
weight: 2770
url: /zh/net/aspose.gis.geometries/icurvepolygon/
---
## ICurvePolygon interface

一个平面表面，由 1 条外部边界和 0 条或多条内部边界定义。

```csharp
public interface ICurvePolygon : IEquatable<ICurvePolygon>, ISurface
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ExteriorRing](../../aspose.gis.geometries/icurvepolygon/exteriorring/) { get; } | 获取外部环。 |
| [InteriorRingsCount](../../aspose.gis.geometries/icurvepolygon/interiorringscount/) { get; } | 获取内部环的数量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetInteriorRing](../../aspose.gis.geometries/icurvepolygon/getinteriorring/)(int) | 通过索引获取内部环。 |

### 另见

* interface [ISurface](../isurface/)
* namespace [Aspose.Gis.Geometries](../../aspose.gis.geometries/)
* assembly [Aspose.GIS](../../)


