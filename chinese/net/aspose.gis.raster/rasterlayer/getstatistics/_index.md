---
title: GetStatistics
second_title: Aspose.GIS for .NET API 参考
description: 计算由计数总和平均值最小值最大值组成的汇总统计数据
type: docs
weight: 160
url: /zh/net/aspose.gis.raster/rasterlayer/getstatistics/
---
## RasterLayer.GetStatistics method

计算由计数、总和、平均值、最小值、最大值组成的汇总统计数据。

```csharp
public RasterStatistics GetStatistics(int bandIndex = 0, bool excludeNodataValue = true)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| bandIndex | Int32 | 波段的索引。编号从 0 开始。 |
| excludeNodataValue | Boolean | 允许排除“nodata”值。如果 'excludeNodataValue' 设置为 false，则考虑所有像素。 |

### 返回值

汇总统计。

### 也可以看看

* class [RasterStatistics](../../rasterstatistics)
* class [RasterLayer](../../rasterlayer)
* 命名空间 [Aspose.Gis.Raster](../../rasterlayer)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->