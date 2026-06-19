---
title: "SpatialReferenceSystemTransformation.Transform"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "SpatialReferenceSystemTransformation 方法。将几何体从源空间参考系统转换到目标空间参考系统"
type: docs
weight: 40
url: /zh/net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation/transform/
---
## SpatialReferenceSystemTransformation.Transform method

将几何体从源空间参考系统转换到目标空间参考系统。

```csharp
public Geometry Transform(IGeometry geometry)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 几何体 | IGeometry | 要转换的几何体。 |

### 返回值

目标空间参考系统中的新几何体。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 几何体为 `null`。 |
| ArgumentException | 几何体 [`SpatialReferenceSystem`](../../../aspose.gis.geometries/igeometry/spatialreferencesystem/) 不为 `null` 且不等同于 [`Source`](../source/) |
| [TransformationException](../../transformationexception/) | 转换失败。 |

### 另见

* class [Geometry](../../../aspose.gis.geometries/geometry/)
* interface [IGeometry](../../../aspose.gis.geometries/igeometry/)
* class [SpatialReferenceSystemTransformation](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystemtransformation/)
* assembly [Aspose.GIS](../../../)


