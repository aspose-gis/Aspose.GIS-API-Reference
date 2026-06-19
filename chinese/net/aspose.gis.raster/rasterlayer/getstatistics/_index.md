---
title: "RasterLayer.GetStatistics"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "RasterLayer 方法。计算包括计数、求和、均值、最小值、最大值的汇总统计信息"
type: docs
weight: 160
url: /zh/net/aspose.gis.raster/rasterlayer/getstatistics/
---
## RasterLayer.GetStatistics method

计算包括计数、总和、均值、最小值、最大值在内的汇总统计信息。

```csharp
public RasterStatistics GetStatistics(int bandIndex = 0, bool excludeNodataValue = true)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| bandIndex | Int32 | 波段的索引。编号从 0 开始。 |
| excludeNodataValue | Boolean | 允许排除 'nodata' 值。如果 'excludeNodataValue' 设置为 false，则所有像素都会被考虑。 |

### 返回值

汇总统计信息。

### 另见

* class [RasterStatistics](../../rasterstatistics/)
* class [RasterLayer](../)
* namespace [Aspose.Gis.Raster](../../rasterlayer/)
* assembly [Aspose.GIS](../../../)


