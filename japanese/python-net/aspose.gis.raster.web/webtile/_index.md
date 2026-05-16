---
title: "WebTile クラス"
type: docs
weight: 10
url: /ja/python-net/aspose.gis.raster.web/webtile/
---

**Summary:** Abstract Web Tile Model.

**Module:** [aspose.gis.raster.web](/psd/python-net/aspose.gis.raster.web/)

**Full Name:** aspose.gis.raster.web.WebTile

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| cell_x | int | r | タイルの X 列です。 |
| cell_y | int | r | タイルの Y 行です。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [as_binary()](#as_binary__1) | 画像のバイトシーケンスを返します |
| [as_path()](#as_path__2) | タイルのコンテンツを URL またはファイルへのパスとして提示します。 |
| [as_raster()](#as_raster__3) | タイル コンテンツを Raster レイヤーとして提示します。 |
| [get_extent()](#get_extent__4) | このレイヤーの空間範囲を提示します。 |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

画像のバイトシーケンスを返します

**Returns**

| 型 | 説明 |
| :- | :- |
| byte | バイトシーケンス |


### Method: as_path() {#as_path__2}


```
 as_path() 
```

タイルのコンテンツを URL またはファイルへのパスとして提示します。

**Returns**

| 型 | 説明 |
| :- | :- |
| string | ファイルへの URL またはパス |


### Method: as_raster() {#as_raster__3}


```
 as_raster() 
```

タイル コンテンツを Raster レイヤーとして提示します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Raster。 |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

このレイヤーの空間範囲を提示します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | このレイヤーの空間範囲。 |


