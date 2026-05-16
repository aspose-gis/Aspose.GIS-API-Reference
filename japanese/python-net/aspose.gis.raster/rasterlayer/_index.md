---
title: "RasterLayer クラス"
type: docs
weight: 70
url: /ja/python-net/aspose.gis.raster/rasterlayer/
---

**Summary:** Represents a raster layer.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.RasterLayer

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| band_count | int | r | ラスターレイヤーのバンド数を取得します。 |
| bounds | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | r | ラスタの境界を取得します。 |
| cell_size | [IRasterCellSize](/psd/python-net/aspose.gis.raster/irastercellsize) | r | ラスタのセルまたはピクセルサイズを取得します。 |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | このレイヤーをインスタンス化した [RasterLayer.driver](/psd/python-net/aspose.gis.raster/rasterlayer/) を取得します。 |
| 高さ | int | r | ラスタの高さ（ピクセル単位）を取得します。また、行数としても知られています。 |
| no_data_values | [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | r | ラスタの背景または「データなし」を表す値を取得します。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | ラスタの空間参照系を取得します。<br/>            不明な場合は <see langword="null" /> になる可能性があります。 |
| upper_left_x | double | r | ラスタの左上隅の X 座標を取得します。 |
| upper_left_y | double | r | ラスタの左上隅の Y 座標を取得します。 |
| width | int | r | ラスタの幅（ピクセル単位）を取得します。また、列数としても知られています。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [crop(geometry, masks)](#crop_geometry_masks_1) | シェイプフォーム（およびバンドマスク）を使用してラスタレイヤーを切り取ります。 |
| [crop(masks)](#crop_masks_2) | バンドマスクを使用してラスタレイヤーを切り取ります。 |
| [get_band(index)](#get_band_index_3) | 指定されたインデックスでバンドを取得します。 |
| [get_extent()](#get_extent__4) | このレイヤーの空間範囲を計算します。 |
| [get_spatial_point(cell_x, cell_y)](#get_spatial_point_cell_x_cell_y_5) | 指定された列と行を空間座標に変換します。 |
| [get_statistics(band_index, exclude_nodata_value)](#get_statistics_band_index_exclude_nodata_value_6) | カウント、合計、平均、最小、最大からなる要約統計を計算します。 |
| [get_values(cell_x, cell_y)](#get_values_cell_x_cell_y_7) | 指定されたセルの値を読み取ります。 |
| [get_values_dump(rect)](#get_values_dump_rect_8) | 指定されたブロックの値を 1 次元配列として読み取ります。 |
| [warp(options)](#warp_options_9) | ラスタレイヤーを別のものにワープします。 |


### Method: crop(geometry, masks) {#crop_geometry_masks_1}


```
 crop(geometry, masks) 
```

シェイプフォーム（およびバンドマスク）を使用してラスタレイヤーを切り取ります。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | ジオメトリはシェイプフォームを表します。 |
| マスク | double | クロップレイヤーのマスク |

**Returns**

| 型 | 説明 |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | 切り取られたラスターレイヤーです。交差が見つからない場合は <see langword="null" /> を返します。 |


### Method: crop(masks) {#crop_masks_2}


```
 crop(masks) 
```

バンドマスクを使用してラスタレイヤーを切り取ります。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| マスク | double | クロップレイヤーのマスク |

**Returns**

| 型 | 説明 |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | 切り取られたラスターレイヤーです。交差が見つからない場合は <see langword="null" /> を返します。 |


### Method: get_band(index) {#get_band_index_3}


```
 get_band(index) 
```

指定されたインデックスでバンドを取得します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| index | int | バンド番号は0から始まり、指定されていない場合はバンドは0とみなされます。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IRasterBand](/psd/python-net/aspose.gis.raster/irasterband) | ラスターバンドに関する基本的なメタデータを返します。 |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

このレイヤーの空間範囲を計算します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | このレイヤーの空間範囲。 |


### Method: get_spatial_point(cell_x, cell_y) {#get_spatial_point_cell_x_cell_y_5}


```
 get_spatial_point(cell_x, cell_y) 
```

指定された列と行を空間座標に変換します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| cell_x | int | 列（x座標）の値です。番号は0から始まります。 |
| cell_y | int | 行（y座標）の値です。番号は0から始まります。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | 列と行が与えられたとき、左上隅のx座標を返します。 |


### Method: get_statistics(band_index, exclude_nodata_value) {#get_statistics_band_index_exclude_nodata_value_6}


```
 get_statistics(band_index, exclude_nodata_value) 
```

カウント、合計、平均、最小、最大からなる要約統計を計算します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| band_index | int | バンドのインデックス。番号は 0 から始まります。 |
| exclude_nodata_value | bool | 「nodata」値を除外できるようにします。'excludeNodataValue' が false に設定されている場合、すべてのピクセルが対象となります。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [RasterStatistics](/psd/python-net/aspose.gis.raster/rasterstatistics) | 要約統計情報です。 |


### Method: get_values(cell_x, cell_y) {#get_values_cell_x_cell_y_7}


```
 get_values(cell_x, cell_y) 
```

指定されたセルの値を読み取ります。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| cell_x | int | 列（x座標）の値です。番号は0から始まります。 |
| cell_y | int | 行（y座標）の値です。番号は0から始まります。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | ラスタ値です。 |


### Method: get_values_dump(rect) {#get_values_dump_rect_8}


```
 get_values_dump(rect) 
```

指定されたブロックの値を 1 次元配列として読み取ります。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| rect | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | ダンプが読み取られるラスタセルのブロックです。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IRasterValues[]](/psd/python-net/aspose.gis.raster/irastervalues) | 値のダンプです。 |


### Method: warp(options) {#warp_options_9}


```
 warp(options) 
```

ラスタレイヤーを別のものにワープします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| options | [WarpOptions](/psd/python-net/aspose.gis.raster/warpoptions) | 再投影手順のオプションです。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | ワープラスターレイヤーです。 |


