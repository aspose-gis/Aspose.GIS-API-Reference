---
title: "Geometry.GetBuffer"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Geometry 方法。计算此几何对象周围的缓冲区"
type: docs
weight: 210
url: /zh/net/aspose.gis.geometries/geometry/getbuffer/
---
## Geometry.GetBuffer method

计算此几何体周围的缓冲区。

```csharp
public IGeometry GetBuffer(double distance, int quadrantSegments = 30)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| distance | Double | 缓冲区宽度。 |
| quadrantSegments | Int32 | 用于近似 90 度曲率的段数。该数字越大，曲线的近似效果越好。默认值为 30。 |

### 返回值

表示所有位于此几何对象指定距离范围内的点的几何对象。结果类型可以是 [`Null`](../null/)、[`IPolygon`](../../ipolygon/) 或 [`IMultiPolygon`](../../imultipolygon/)。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 此几何对象无效，导致无法完成操作。 |
| ArgumentOutOfRangeException | 象限段数小于或等于 0。 |

### 另见

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


