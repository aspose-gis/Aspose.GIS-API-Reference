---
title: "类 WarpOptions"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.Raster.WarpOptions 类。栅格变形的选项"
type: docs
weight: 3870
url: /zh/net/aspose.gis.raster/warpoptions/
---
## WarpOptions class

栅格扭曲的选项。

```csharp
public class WarpOptions
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [WarpOptions](warpoptions/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [CellHeight](../../aspose.gis.raster/warpoptions/cellheight/) { get; set; } | 指定栅格单元格的新高度（以目标地理参考单位为单位）。如果该值设置为 0，则会自动计算 [`CellHeight`](./cellheight/)。默认值为 \"0\"。 |
| [CellWidth](../../aspose.gis.raster/warpoptions/cellwidth/) { get; set; } | 指定栅格单元格的新宽度（以目标地理参考单位为单位）。如果该值设置为 0，则会自动计算 [`CellWidth`](./cellwidth/)。默认值为 \"0\"。 |
| [DefaultSpatialReferenceSystem](../../aspose.gis.raster/warpoptions/defaultspatialreferencesystem/) { get; set; } | 如果缺少源空间参考，则指定其值。 |
| [Height](../../aspose.gis.raster/warpoptions/height/) { get; set; } | 指定输出栅格的高度（以像素和列数计）。如果该值设置为 0，则会自动计算高度。默认值为 \"0\"。 |
| [TargetExtent](../../aspose.gis.raster/warpoptions/targetextent/) { get; set; } | 指定要变形的栅格图层的边界。如果设置为 `null`，则在变形过程中计算范围，以包含栅格的所有单元格。 |
| [TargetSpatialReferenceSystem](../../aspose.gis.raster/warpoptions/targetspatialreferencesystem/) { get; set; } | 指定目标空间参考。如果设置为 `null`，则使用默认或源空间参考。 |
| [Width](../../aspose.gis.raster/warpoptions/width/) { get; set; } | 指定输出栅格的宽度（以像素和列数计）。如果该值设置为 0，则会自动计算宽度。默认值为 \"0\"。 |

### 另见

* namespace [Aspose.Gis.Raster](../../aspose.gis.raster/)
* assembly [Aspose.GIS](../../)


