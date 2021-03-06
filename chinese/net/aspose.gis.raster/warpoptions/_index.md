---
title: WarpOptions
second_title: Aspose.GIS for .NET API 参考
description: 光栅变形选项
type: docs
weight: 1320
url: /zh/net/aspose.gis.raster/warpoptions/
---
## WarpOptions class

光栅变形选项。

```csharp
public class WarpOptions
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [WarpOptions](warpoptions)() | 默认构造函数。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| [CellHeight](../../aspose.gis.raster/warpoptions/cellheight) { get; set; } | 指定光栅单元的新高度（以目标地理参考单位）。 如果该值设置为 0，则自动计算[`CellHeight`](./cellheight)。默认值为“0”。 |
| [CellWidth](../../aspose.gis.raster/warpoptions/cellwidth) { get; set; } | 指定光栅单元的新宽度（以目标地理参考单位）。 如果该值设置为 0，则自动计算[`CellWidth`](./cellwidth)。默认值为“0”。 |
| [DefaultSpatialReferenceSystem](../../aspose.gis.raster/warpoptions/defaultspatialreferencesystem) { get; set; } | 指定源空间参考的值（如果缺少）。 |
| [Height](../../aspose.gis.raster/warpoptions/height) { get; set; } | 以像素和列为单位指定输出光栅高度。 如果该值设置为 0，则自动计算高度。默认值为“0”。 |
| [TargetExtent](../../aspose.gis.raster/warpoptions/targetextent) { get; set; } | 指定要扭曲的栅格图层的边界。 如果设置为`null`，则在变形期间计算范围以包括栅格中的所有像元。 |
| [TargetSpatialReferenceSystem](../../aspose.gis.raster/warpoptions/targetspatialreferencesystem) { get; set; } | 指定目标空间参考。 如果设置为`null`，则使用默认或源空间参考。 |
| [Width](../../aspose.gis.raster/warpoptions/width) { get; set; } | 以像素和列为单位指定输出栅格宽度。 如果该值设置为 0，则自动计算宽度。默认值为“0”。 |

### 也可以看看

* 命名空间 [Aspose.Gis.Raster](../../aspose.gis.raster)
* 部件 [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
