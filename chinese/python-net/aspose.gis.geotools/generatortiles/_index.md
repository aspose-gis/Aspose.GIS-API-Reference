---
title: "GeneratorTiles 类"
type: docs
weight: 10
url: /zh/python-net/aspose.gis.geotools/generatortiles/
---

**Summary:** Generator of tiles

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeneratorTiles

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [generate_tiles(layer, out_directory, zoom, extent, options)](#generate_tiles_layer_out_directory_zoom_extent_options_1) | 生成带有缩放的瓦片到输出目录 |
| [generate_tiles(layer, out_directory, zoom, options)](#generate_tiles_layer_out_directory_zoom_options_2) | 生成带有缩放的瓦片到输出目录 |
| [generate_tiles(layers, out_directory, zoom, extent, options)](#generate_tiles_layers_out_directory_zoom_extent_options_3) | 生成带有缩放的瓦片到输出目录 |
| [generate_tiles(layers, out_directory, zoom, options)](#generate_tiles_layers_out_directory_zoom_options_4) | 生成带有缩放的瓦片到输出目录 |


### Method: generate_tiles(layer, out_directory, zoom, extent, options)  [static] {#generate_tiles_layer_out_directory_zoom_extent_options_1}


```
 generate_tiles(layer, out_directory, zoom, extent, options) 
```

生成带有缩放的瓦片到输出目录

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) |  |
| out_directory | string | 输出目录 |
| zoom | 整数 | 瓦片的缩放级别 |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 用于渲染瓦片的边界框 |
| options | [GeneratorTilesRenderOptions](/psd/python-net/aspose.gis.geotools/generatortilesrenderoptions) | 渲染瓦片的选项 |

### Method: generate_tiles(layer, out_directory, zoom, options)  [static] {#generate_tiles_layer_out_directory_zoom_options_2}


```
 generate_tiles(layer, out_directory, zoom, options) 
```

生成带有缩放的瓦片到输出目录

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) |  |
| out_directory | string | 输出目录 |
| zoom | 整数 | 瓦片的缩放级别 |
| options | [GeneratorTilesRenderOptions](/psd/python-net/aspose.gis.geotools/generatortilesrenderoptions) | 渲染瓦片的选项 |

### Method: generate_tiles(layers, out_directory, zoom, extent, options)  [static] {#generate_tiles_layers_out_directory_zoom_extent_options_3}


```
 generate_tiles(layers, out_directory, zoom, extent, options) 
```

生成带有缩放的瓦片到输出目录

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layers | System.Collections.Generic.IEnumerable<VectorLayer> | 输入图层 |
| out_directory | string | 输出目录 |
| zoom | 整数 | 瓦片的缩放级别 |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 用于渲染瓦片的边界框 |
| options | [GeneratorTilesRenderOptions](/psd/python-net/aspose.gis.geotools/generatortilesrenderoptions) | 渲染瓦片的选项 |

### Method: generate_tiles(layers, out_directory, zoom, options)  [static] {#generate_tiles_layers_out_directory_zoom_options_4}


```
 generate_tiles(layers, out_directory, zoom, options) 
```

生成带有缩放的瓦片到输出目录

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layers | System.Collections.Generic.IEnumerable<VectorLayer> | 输入图层 |
| out_directory | string | 输出目录 |
| zoom | 整数 | 瓦片的缩放级别 |
| options | [GeneratorTilesRenderOptions](/psd/python-net/aspose.gis.geotools/generatortilesrenderoptions) | 渲染瓦片的选项 |

