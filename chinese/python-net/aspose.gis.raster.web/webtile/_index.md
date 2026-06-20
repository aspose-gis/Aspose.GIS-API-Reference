---
title: "WebTile 类"
type: docs
weight: 10
url: /zh/python-net/aspose.gis.raster.web/webtile/
---

**Summary:** Abstract Web Tile Model.

**Module:** [aspose.gis.raster.web](/psd/python-net/aspose.gis.raster.web/)

**Full Name:** aspose.gis.raster.web.WebTile

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cell_x | 整数 | r | 瓦片的 X 列。 |
| cell_y | 整数 | r | 瓦片的 Y 行。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [as_binary()](#as_binary__1) | 返回图像字节序列 |
| [as_path()](#as_path__2) | 将瓦片内容呈现为 URL 或文件路径。 |
| [as_raster()](#as_raster__3) | 以栅格图层的形式呈现瓦片内容。 |
| [get_extent()](#get_extent__4) | 呈现此图层的空间范围。 |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

返回图像字节序列

**Returns**

| 类型 | 描述 |
| :- | :- |
| byte | 字节序列 |


### Method: as_path() {#as_path__2}


```
 as_path() 
```

将瓦片内容呈现为 URL 或文件路径。

**Returns**

| 类型 | 描述 |
| :- | :- |
| string | 文件的 URL 或路径 |


### Method: as_raster() {#as_raster__3}


```
 as_raster() 
```

以栅格图层的形式呈现瓦片内容。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | 栅格。 |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

呈现此图层的空间范围。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | 此图层的空间范围。 |


