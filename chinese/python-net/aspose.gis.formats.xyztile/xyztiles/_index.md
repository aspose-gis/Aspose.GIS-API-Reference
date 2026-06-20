---
title: "XyzTiles 类"
type: docs
weight: 20
url: /zh/python-net/aspose.gis.formats.xyztile/xyztiles/
---

**Summary:** A XyzTiles provide access to [XyzTile](/psd/python-net/aspose.gis.formats.xyztile/xyztile/) objects.

**Module:** [aspose.gis.formats.xyztile](/psd/python-net/aspose.gis.formats.xyztile/)

**Full Name:** aspose.gis.formats.xyztile.XyzTiles

**Inheritance:** WebTiles

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XyzTiles(connection)](#XyzTiles_connection_1) | 创建一个 [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) 实例。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_tile(zoom, x, y)](#get_tile_zoom_x_y_1) | 加载指定的瓦片。 |
| [get_tile(zoom, x, y, tile_size)](#get_tile_zoom_x_y_tile_size_2) | 加载指定的瓦片。 |
| [get_tiles(zoom, extent)](#get_tiles_zoom_extent_3) | 根据空间边界框和缩放级别加载瓦片。 |
| [get_tiles(zoom, extent, tile_size)](#get_tiles_zoom_extent_tile_size_4) | 根据空间边界框和缩放级别加载瓦片。 |


### Constructor: XyzTiles(connection) {#XyzTiles_connection_1}


```
 XyzTiles(connection) 
```

创建一个 [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) 实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| connection | [XyzConnection](/psd/python-net/aspose.gis.formats.xyztile/xyzconnection) | 包含网络选项的连接。 |

### Method: get_tile(zoom, x, y) {#get_tile_zoom_x_y_1}


```
 get_tile(zoom, x, y) 
```

加载指定的瓦片。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| zoom | 整数 | 加载瓦片的缩放级别。最高缩放级别为 0。大多数瓦片提供商的最大缩放级别约为 22。 |
| x | 整数 | 瓦片的 x 列。 |
| y | 整数 | 瓦片的 y 行。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | 网络瓦片。 |


### Method: get_tile(zoom, x, y, tile_size) {#get_tile_zoom_x_y_tile_size_2}


```
 get_tile(zoom, x, y, tile_size) 
```

加载指定的瓦片。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| zoom | 整数 | 加载瓦片的缩放级别。最高缩放级别为 0。大多数瓦片提供商的最大缩放级别约为 22。 |
| x | 整数 | 瓦片的 x 列。 |
| y | 整数 | 瓦片的 y 行。 |
| tile_size | 整数 | 瓦片大小，默认是 256（这是瓦片大小的标准） |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | 网络瓦片。 |


### Method: get_tiles(zoom, extent) {#get_tiles_zoom_extent_3}


```
 get_tiles(zoom, extent) 
```

根据空间边界框和缩放级别加载瓦片。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| zoom | 整数 | 加载瓦片的缩放级别。最高缩放级别为 0。大多数瓦片提供商的最大缩放级别约为 22。 |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 加载瓦片的边界框。如果缺失，将使用 Wgs84 空间参考。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | 网页瓦片。 |


### Method: get_tiles(zoom, extent, tile_size) {#get_tiles_zoom_extent_tile_size_4}


```
 get_tiles(zoom, extent, tile_size) 
```

根据空间边界框和缩放级别加载瓦片。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| zoom | 整数 | 加载瓦片的缩放级别。最高缩放级别为 0。大多数瓦片提供商的最大缩放级别约为 22。 |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 加载瓦片的边界框。如果缺失，将使用 Wgs84 空间参考。 |
| tile_size | 整数 | 瓦片大小，默认是 256（这是瓦片大小的标准） |

**Returns**

| 类型 | 描述 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | 网页瓦片。 |


