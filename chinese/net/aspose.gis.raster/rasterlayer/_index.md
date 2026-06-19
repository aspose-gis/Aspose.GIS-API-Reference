---
title: "类 RasterLayer"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.Raster.RasterLayer 类。表示一个栅格图层"
type: docs
weight: 3830
url: /zh/net/aspose.gis.raster/rasterlayer/
---
## RasterLayer class

表示一个栅格图层。

```csharp
public abstract class RasterLayer : IDisposable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| abstract [BandCount](../../aspose.gis.raster/rasterlayer/bandcount/) { get; } | 获取栅格图层中的波段数量。 |
| [Bounds](../../aspose.gis.raster/rasterlayer/bounds/) { get; } | 获取栅格范围。 |
| abstract [CellSize](../../aspose.gis.raster/rasterlayer/cellsize/) { get; } | 获取栅格的单元格或像素大小。 |
| abstract [Driver](../../aspose.gis.raster/rasterlayer/driver/) { get; } | 获取实例化此图层的 [`Driver`](./driver/)。 |
| abstract [Height](../../aspose.gis.raster/rasterlayer/height/) { get; } | 获取栅格的像素高度。也称为行数。 |
| abstract [NoDataValues](../../aspose.gis.raster/rasterlayer/nodatavalues/) { get; } | 获取表示栅格背景或“无数据”的值。 |
| abstract [SpatialReferenceSystem](../../aspose.gis.raster/rasterlayer/spatialreferencesystem/) { get; } | 获取栅格的空间参考系统。如果未知，则可以为 `null`。 |
| abstract [UpperLeftX](../../aspose.gis.raster/rasterlayer/upperleftx/) { get; } | 获取栅格左上角的 x 坐标。 |
| abstract [UpperLeftY](../../aspose.gis.raster/rasterlayer/upperlefty/) { get; } | 获取栅格左上角的 y 坐标。 |
| abstract [Width](../../aspose.gis.raster/rasterlayer/width/) { get; } | 获取栅格的像素宽度。也称为列数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Crop](../../aspose.gis.raster/rasterlayer/crop/#crop_1)(double[]) | 使用波段掩码裁剪栅格图层)。 |
| [Crop](../../aspose.gis.raster/rasterlayer/crop/#crop)(IGeometry, double[]) | 使用形状（以及波段掩码）裁剪栅格图层。 |
| [Dispose](../../aspose.gis.raster/rasterlayer/dispose/)() | 释放 `RasterLayer` 使用的资源。 |
| abstract [GetBand](../../aspose.gis.raster/rasterlayer/getband/)(int) | 按指定索引获取波段。 |
| virtual [GetExtent](../../aspose.gis.raster/rasterlayer/getextent/)() | 计算此图层的空间范围。 |
| [GetSpatialPoint](../../aspose.gis.raster/rasterlayer/getspatialpoint/)(int, int) | 将指定的列和行转换为空间坐标。 |
| [GetStatistics](../../aspose.gis.raster/rasterlayer/getstatistics/)(int, bool) | 计算包括计数、总和、均值、最小值、最大值在内的汇总统计信息。 |
| [GetValues](../../aspose.gis.raster/rasterlayer/getvalues/)(int, int) | 读取指定单元格中的值。 |
| [GetValuesDump](../../aspose.gis.raster/rasterlayer/getvaluesdump/)(RasterRect) | 将指定块的值读取为一维数组。 |
| [GetValuesOnExpression](../../aspose.gis.raster/rasterlayer/getvaluesonexpression/)(RasterRect, RasterReadExpression) | 在表达式中读取并处理波段值。 |
| override [ToString](../../aspose.gis.raster/rasterlayer/tostring/)() | 返回表示当前对象的字符串。 |
| [Warp](../../aspose.gis.raster/rasterlayer/warp/)(WarpOptions) | 将栅格图层变形到另一个。 |

### 另见

* namespace [Aspose.Gis.Raster](../../aspose.gis.raster/)
* assembly [Aspose.GIS](../../)


