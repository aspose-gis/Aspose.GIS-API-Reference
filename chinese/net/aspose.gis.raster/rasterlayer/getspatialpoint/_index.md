---
title: "RasterLayer.GetSpatialPoint"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "RasterLayer 方法。将指定的列和行转换为空间坐标"
type: docs
weight: 150
url: /zh/net/aspose.gis.raster/rasterlayer/getspatialpoint/
---
## RasterLayer.GetSpatialPoint method

将指定的列和行转换为空间坐标。

```csharp
public IPoint GetSpatialPoint(int cellX, int cellY)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cellX | Int32 | 列（x 坐标）的值。编号从 0 开始。 |
| cellY | Int32 | 行（y 坐标）的值。编号从 0 开始。 |

### 返回值

返回给定列和行的左上角的 x 坐标。

## 备注

如果任一参数超出栅格相应维度的范围，则会返回栅格外的坐标，假设栅格网格在栅格边界之外仍然适用。

### 另见

* interface [IPoint](../../../aspose.gis.geometries/ipoint/)
* class [RasterLayer](../)
* namespace [Aspose.Gis.Raster](../../rasterlayer/)
* assembly [Aspose.GIS](../../../)


