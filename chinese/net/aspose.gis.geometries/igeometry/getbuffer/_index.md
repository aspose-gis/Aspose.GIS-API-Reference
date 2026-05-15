---
title: "IGeometry.GetBuffer"
second_title: "Aspose.GIS for .NET API 参考"
description: "IGeometry 方法。计算此几何对象周围的缓冲区。"
type: docs
weight: 200
url: /zh/net/aspose.gis.geometries/igeometry/getbuffer/
---
## IGeometry.GetBuffer method

计算此几何体周围的缓冲区。

```csharp
public IGeometry GetBuffer(double distance, int quadrantSegments = 30)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| distance | Double | 缓冲区宽度（以空间参考单位计）。 |
| quadrantSegments | Int32 | 用于近似 90 度曲率的段数。该数值越大，曲线的近似程度越好。默认值为 30。 |

### 返回值

表示距离此几何对象在指定距离范围内的所有点的几何对象。结果的类型可以是 [`Null`](../../geometry/null/)、[`IPolygon`](../../ipolygon/) 或 [`IMultiPolygon`](../../imultipolygon/)。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 此几何对象无效，导致无法完成操作。 |
| ArgumentOutOfRangeException | 象限段数小于或等于 0。 |

### 另见

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


