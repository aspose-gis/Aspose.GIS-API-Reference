---
title: "XyzTiles クラス"
type: docs
weight: 20
url: /ja/python-net/aspose.gis.formats.xyztile/xyztiles/
---

**Summary:** A XyzTiles provide access to [XyzTile](/psd/python-net/aspose.gis.formats.xyztile/xyztile/) objects.

**Module:** [aspose.gis.formats.xyztile](/psd/python-net/aspose.gis.formats.xyztile/)

**Full Name:** aspose.gis.formats.xyztile.XyzTiles

**Inheritance:** WebTiles

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [XyzTiles(connection)](#XyzTiles_connection_1) | [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) のインスタンスを作成します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_tile(zoom, x, y)](#get_tile_zoom_x_y_1) | 指定されたタイルを読み込みます。 |
| [get_tile(zoom, x, y, tile_size)](#get_tile_zoom_x_y_tile_size_2) | 指定されたタイルを読み込みます。 |
| [get_tiles(zoom, extent)](#get_tiles_zoom_extent_3) | 空間バウンディングボックスとズームレベルでタイルを読み込みます。 |
| [get_tiles(zoom, extent, tile_size)](#get_tiles_zoom_extent_tile_size_4) | 空間バウンディングボックスとズームレベルでタイルを読み込みます。 |


### Constructor: XyzTiles(connection) {#XyzTiles_connection_1}


```
 XyzTiles(connection) 
```

[XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) のインスタンスを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| connection | [XyzConnection](/psd/python-net/aspose.gis.formats.xyztile/xyzconnection) | Web オプションを含む接続です。 |

### Method: get_tile(zoom, x, y) {#get_tile_zoom_x_y_1}


```
 get_tile(zoom, x, y) 
```

指定されたタイルを読み込みます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| zoom | int | タイルを読み込むためのズームレベルです。最高のズームレベルは 0 です。ほとんどのタイルプロバイダーは最大で約 22 のズームレベルを持ちます。 |
| x | int | タイルの x 列です。 |
| y | int | タイルの y 行です。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | Web タイルです。 |


### Method: get_tile(zoom, x, y, tile_size) {#get_tile_zoom_x_y_tile_size_2}


```
 get_tile(zoom, x, y, tile_size) 
```

指定されたタイルを読み込みます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| zoom | int | タイルを読み込むためのズームレベルです。最高のズームレベルは 0 です。ほとんどのタイルプロバイダーは最大で約 22 のズームレベルを持ちます。 |
| x | int | タイルの x 列です。 |
| y | int | タイルの y 行です。 |
| tile_size | int | タイルのサイズで、デフォルトは 256 です（タイルサイズの標準です）。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | Web タイルです。 |


### Method: get_tiles(zoom, extent) {#get_tiles_zoom_extent_3}


```
 get_tiles(zoom, extent) 
```

空間バウンディングボックスとズームレベルでタイルを読み込みます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| zoom | int | タイルを読み込むためのズームレベルです。最高のズームレベルは 0 です。ほとんどのタイルプロバイダーは最大で約 22 のズームレベルを持ちます。 |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | タイルを読み込むためのバウンディングボックスです。欠落している場合は Wgs84 空間参照が使用されます。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | このウェブタイルです。 |


### Method: get_tiles(zoom, extent, tile_size) {#get_tiles_zoom_extent_tile_size_4}


```
 get_tiles(zoom, extent, tile_size) 
```

空間バウンディングボックスとズームレベルでタイルを読み込みます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| zoom | int | タイルを読み込むためのズームレベルです。最高のズームレベルは 0 です。ほとんどのタイルプロバイダーは最大で約 22 のズームレベルを持ちます。 |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | タイルを読み込むためのバウンディングボックスです。欠落している場合は Wgs84 空間参照が使用されます。 |
| tile_size | int | タイルのサイズで、デフォルトは 256 です（タイルサイズの標準です）。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | このウェブタイルです。 |


