---
title: "GeneratorTiles クラス"
type: docs
weight: 10
url: /ja/python-net/aspose.gis.geotools/generatortiles/
---

**Summary:** Generator of tiles

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeneratorTiles

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **説明** |
| :- | :- |
| [generate_tiles(layer, out_directory, zoom, extent, options)](#generate_tiles_layer_out_directory_zoom_extent_options_1) | ズーム付きでタイルを生成し、出力ディレクトリに保存します |
| [generate_tiles(layer, out_directory, zoom, options)](#generate_tiles_layer_out_directory_zoom_options_2) | ズーム付きでタイルを生成し、出力ディレクトリに保存します |
| [generate_tiles(layers, out_directory, zoom, extent, options)](#generate_tiles_layers_out_directory_zoom_extent_options_3) | ズーム付きでタイルを生成し、出力ディレクトリに保存します |
| [generate_tiles(layers, out_directory, zoom, options)](#generate_tiles_layers_out_directory_zoom_options_4) | ズーム付きでタイルを生成し、出力ディレクトリに保存します |


### Method: generate_tiles(layer, out_directory, zoom, extent, options)  [static] {#generate_tiles_layer_out_directory_zoom_extent_options_1}


```
 generate_tiles(layer, out_directory, zoom, extent, options) 
```

ズーム付きでタイルを生成し、出力ディレクトリに保存します

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) |  |
| out_directory | string | 出力ディレクトリ |
| zoom | int | タイルのズームレベル |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | タイルをレンダリングするためのバウンディングボックス |
| options | [GeneratorTilesRenderOptions](/psd/python-net/aspose.gis.geotools/generatortilesrenderoptions) | タイルをレンダリングするためのオプション |

### Method: generate_tiles(layer, out_directory, zoom, options)  [static] {#generate_tiles_layer_out_directory_zoom_options_2}


```
 generate_tiles(layer, out_directory, zoom, options) 
```

ズーム付きでタイルを生成し、出力ディレクトリに保存します

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) |  |
| out_directory | string | 出力ディレクトリ |
| zoom | int | タイルのズームレベル |
| options | [GeneratorTilesRenderOptions](/psd/python-net/aspose.gis.geotools/generatortilesrenderoptions) | タイルをレンダリングするためのオプション |

### Method: generate_tiles(layers, out_directory, zoom, extent, options)  [static] {#generate_tiles_layers_out_directory_zoom_extent_options_3}


```
 generate_tiles(layers, out_directory, zoom, extent, options) 
```

ズーム付きでタイルを生成し、出力ディレクトリに保存します

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| layers | System.Collections.Generic.IEnumerable<VectorLayer> | 入力レイヤー |
| out_directory | string | 出力ディレクトリ |
| zoom | int | タイルのズームレベル |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | タイルをレンダリングするためのバウンディングボックス |
| options | [GeneratorTilesRenderOptions](/psd/python-net/aspose.gis.geotools/generatortilesrenderoptions) | タイルをレンダリングするためのオプション |

### Method: generate_tiles(layers, out_directory, zoom, options)  [static] {#generate_tiles_layers_out_directory_zoom_options_4}


```
 generate_tiles(layers, out_directory, zoom, options) 
```

ズーム付きでタイルを生成し、出力ディレクトリに保存します

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| layers | System.Collections.Generic.IEnumerable<VectorLayer> | 入力レイヤー |
| out_directory | string | 出力ディレクトリ |
| zoom | int | タイルのズームレベル |
| options | [GeneratorTilesRenderOptions](/psd/python-net/aspose.gis.geotools/generatortilesrenderoptions) | タイルをレンダリングするためのオプション |

