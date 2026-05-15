---
title: "RasterLayer 类"
type: docs
weight: 70
url: /zh/python-net/aspose.gis.raster/rasterlayer/
---

**Summary:** Represents a raster layer.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.RasterLayer

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| band_count | int | r | 获取栅格图层中的波段数量。 |
| bounds | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | r | 获取栅格范围。 |
| cell_size | [IRasterCellSize](/psd/python-net/aspose.gis.raster/irastercellsize) | r | 获取栅格的单元格或像素大小。 |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | 获取实例化此图层的 [RasterLayer.driver](/psd/python-net/aspose.gis.raster/rasterlayer/)。 |
| height | int | r | 获取栅格的像素高度。它也被称为行数。 |
| no_data_values | [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | r | 获取表示栅格背景或“无数据”的值。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | 获取栅格的空间参考系统。<br/>            如果未知，则可能为 <see langword="null" />。 |
| upper_left_x | double | r | 获取栅格左上角的 X 坐标。 |
| upper_left_y | double | r | 获取栅格左上角的 Y 坐标。 |
| width | int | r | 获取栅格的像素宽度。它也被称为列数。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [crop(geometry, masks)](#crop_geometry_masks_1) | 使用形状表单（和波段掩码）裁剪栅格图层。 |
| [crop(masks)](#crop_masks_2) | 使用波段掩码裁剪栅格图层)。 |
| [get_band(index)](#get_band_index_3) | 按指定索引获取波段。 |
| [get_extent()](#get_extent__4) | 计算此图层的空间范围。 |
| [get_spatial_point(cell_x, cell_y)](#get_spatial_point_cell_x_cell_y_5) | 将指定的列和行转换为空间坐标。 |
| [get_statistics(band_index, exclude_nodata_value)](#get_statistics_band_index_exclude_nodata_value_6) | 计算包括计数、总和、平均值、最小值、最大值在内的汇总统计信息。 |
| [get_values(cell_x, cell_y)](#get_values_cell_x_cell_y_7) | 读取指定单元格中的值。 |
| [get_values_dump(rect)](#get_values_dump_rect_8) | 将指定块中的值读取为一维数组。 |
| [warp(options)](#warp_options_9) | 将栅格图层扭曲到另一个。 |


### Method: crop(geometry, masks) {#crop_geometry_masks_1}


```
 crop(geometry, masks) 
```

使用形状表单（和波段掩码）裁剪栅格图层。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 几何表示形状表单。 |
| 掩码 | double | 裁剪层的掩码 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | 裁剪后的栅格层。如果未找到交叉，则返回 <see langword="null" />。 |


### Method: crop(masks) {#crop_masks_2}


```
 crop(masks) 
```

使用波段掩码裁剪栅格图层)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 掩码 | double | 裁剪层的掩码 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | 裁剪后的栅格层。如果未找到交叉，则返回 <see langword="null" />。 |


### Method: get_band(index) {#get_band_index_3}


```
 get_band(index) 
```

按指定索引获取波段。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | int | 波段编号从 0 开始，如果未指定，则默认波段为 0。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IRasterBand](/psd/python-net/aspose.gis.raster/irasterband) | 返回关于栅格波段的基本元数据。 |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

计算此图层的空间范围。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | 此图层的空间范围。 |


### Method: get_spatial_point(cell_x, cell_y) {#get_spatial_point_cell_x_cell_y_5}


```
 get_spatial_point(cell_x, cell_y) 
```

将指定的列和行转换为空间坐标。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cell_x | int | 列（x 坐标）的值。编号从 0 开始。 |
| cell_y | int | 行（y 坐标）的值。编号从 0 开始。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | 根据列和行返回左上角的 x 坐标。 |


### Method: get_statistics(band_index, exclude_nodata_value) {#get_statistics_band_index_exclude_nodata_value_6}


```
 get_statistics(band_index, exclude_nodata_value) 
```

计算包括计数、总和、平均值、最小值、最大值在内的汇总统计信息。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| band_index | int | 波段的索引。编号从 0 开始。 |
| exclude_nodata_value | bool | 允许排除 'nodata' 值。如果 'excludeNodataValue' 设置为 false，则所有像素都被视为有效。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [RasterStatistics](/psd/python-net/aspose.gis.raster/rasterstatistics) | 汇总统计信息。 |


### Method: get_values(cell_x, cell_y) {#get_values_cell_x_cell_y_7}


```
 get_values(cell_x, cell_y) 
```

读取指定单元格中的值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| cell_x | int | 列（x 坐标）的值。编号从 0 开始。 |
| cell_y | int | 行（y 坐标）的值。编号从 0 开始。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | 栅格值。 |


### Method: get_values_dump(rect) {#get_values_dump_rect_8}


```
 get_values_dump(rect) 
```

将指定块中的值读取为一维数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | 读取转储的栅格单元块。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IRasterValues[]](/psd/python-net/aspose.gis.raster/irastervalues) | 值的转储。 |


### Method: warp(options) {#warp_options_9}


```
 warp(options) 
```

将栅格图层扭曲到另一个。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| options | [WarpOptions](/psd/python-net/aspose.gis.raster/warpoptions) | 重投影过程的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | 变形栅格层。 |


