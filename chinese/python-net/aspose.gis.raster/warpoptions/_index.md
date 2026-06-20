---
title: "WarpOptions 类"
type: docs
weight: 100
url: /zh/python-net/aspose.gis.raster/warpoptions/
---

**Summary:** Options for raster warping.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.WarpOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WarpOptions()](#WarpOptions__1) | 初始化 WarpOptions 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cell_height | double | r/w | 指定栅格单元格的新高度（以目标地理参考单位计）。<br/>            如果该值设置为 0，则 [WarpOptions.cell_height](/psd/python-net/aspose.gis.raster/warpoptions/) 将自动计算。默认值为 "0"。 |
| cell_width | double | r/w | 指定栅格单元格的新宽度（以目标地理参考单位计）。<br/>            如果该值设置为 0，则 [WarpOptions.cell_width](/psd/python-net/aspose.gis.raster/warpoptions/) 将自动计算。默认值为 "0"。 |
| default_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | 如果缺少源空间参考，则指定其值。 |
| 高度 | 整数 | r/w | 指定输出栅格的高度（以像素和列计）。<br/>            如果该值设置为 0，则高度将自动计算。默认值为 "0"。 |
| target_extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | 指定要进行扭曲的栅格图层的边界。<br/>            如果设置为 <see langword="null" />，则在扭曲期间计算范围，以包括栅格中的所有单元格。 |
| target_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | 指定目标空间参考。<br/>            如果设置为 <see langword="null" />，则使用默认或源空间参考。 |
| width | 整数 | r/w | 指定输出栅格的宽度（以像素和列计）。<br/>            如果该值设置为 0，则宽度将自动计算。默认值为 "0"。 |


### Constructor: WarpOptions() {#WarpOptions__1}


```
 WarpOptions() 
```

初始化 WarpOptions 类的新实例

