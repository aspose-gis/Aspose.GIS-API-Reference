---
title: "GeneratorTiles 클래스"
type: docs
weight: 10
url: /ko/python-net/aspose.gis.geotools/generatortiles/
---

**Summary:** Generator of tiles

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeneratorTiles

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [generate_tiles(layer, out_directory, zoom, extent, options)](#generate_tiles_layer_out_directory_zoom_extent_options_1) | 줌을 사용하여 타일을 출력 디렉터리에 생성합니다 |
| [generate_tiles(layer, out_directory, zoom, options)](#generate_tiles_layer_out_directory_zoom_options_2) | 줌을 사용하여 타일을 출력 디렉터리에 생성합니다 |
| [generate_tiles(layers, out_directory, zoom, extent, options)](#generate_tiles_layers_out_directory_zoom_extent_options_3) | 줌을 사용하여 타일을 출력 디렉터리에 생성합니다 |
| [generate_tiles(layers, out_directory, zoom, options)](#generate_tiles_layers_out_directory_zoom_options_4) | 줌을 사용하여 타일을 출력 디렉터리에 생성합니다 |


### Method: generate_tiles(layer, out_directory, zoom, extent, options)  [static] {#generate_tiles_layer_out_directory_zoom_extent_options_1}


```
 generate_tiles(layer, out_directory, zoom, extent, options) 
```

줌을 사용하여 타일을 출력 디렉터리에 생성합니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) |  |
| out_directory | string | 출력 디렉터리 |
| zoom | int | 타일의 줌 레벨 |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 타일을 렌더링할 경계 상자 |
| options | [GeneratorTilesRenderOptions](/psd/python-net/aspose.gis.geotools/generatortilesrenderoptions) | 타일 렌더링 옵션 |

### Method: generate_tiles(layer, out_directory, zoom, options)  [static] {#generate_tiles_layer_out_directory_zoom_options_2}


```
 generate_tiles(layer, out_directory, zoom, options) 
```

줌을 사용하여 타일을 출력 디렉터리에 생성합니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) |  |
| out_directory | string | 출력 디렉터리 |
| zoom | int | 타일의 줌 레벨 |
| options | [GeneratorTilesRenderOptions](/psd/python-net/aspose.gis.geotools/generatortilesrenderoptions) | 타일 렌더링 옵션 |

### Method: generate_tiles(layers, out_directory, zoom, extent, options)  [static] {#generate_tiles_layers_out_directory_zoom_extent_options_3}


```
 generate_tiles(layers, out_directory, zoom, extent, options) 
```

줌을 사용하여 타일을 출력 디렉터리에 생성합니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| layers | System.Collections.Generic.IEnumerable<VectorLayer> | 입력 레이어 |
| out_directory | string | 출력 디렉터리 |
| zoom | int | 타일의 줌 레벨 |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 타일을 렌더링할 경계 상자 |
| options | [GeneratorTilesRenderOptions](/psd/python-net/aspose.gis.geotools/generatortilesrenderoptions) | 타일 렌더링 옵션 |

### Method: generate_tiles(layers, out_directory, zoom, options)  [static] {#generate_tiles_layers_out_directory_zoom_options_4}


```
 generate_tiles(layers, out_directory, zoom, options) 
```

줌을 사용하여 타일을 출력 디렉터리에 생성합니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| layers | System.Collections.Generic.IEnumerable<VectorLayer> | 입력 레이어 |
| out_directory | string | 출력 디렉터리 |
| zoom | int | 타일의 줌 레벨 |
| options | [GeneratorTilesRenderOptions](/psd/python-net/aspose.gis.geotools/generatortilesrenderoptions) | 타일 렌더링 옵션 |

