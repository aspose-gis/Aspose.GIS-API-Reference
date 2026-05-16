---
title: "Map 클래스"
type: docs
weight: 100
url: /ko/python-net/aspose.gis.rendering/map/
---

**Summary:** Map is a collection of layers that can be rendered on top of each other via [Renderer](/psd/python-net/aspose.gis.rendering/renderer/).

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.Map

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Map()](#Map__1) | 새 <c>Map</c> 클래스 인스턴스를 생성합니다. |
| [Map(width, height)](#Map_width_height_2) | 새 <c>Map</c> 클래스 인스턴스를 생성합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | r/w | 지도의 배경색입니다. 기본값은 . |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | 렌더링할 지도의 경계를 지정합니다.<br/>            <see langword=\"null\" />으로 설정하면, 렌더링 중에 모든 레이어의 모든 기하학을 포함하도록 범위가 계산됩니다. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 지도의 시각적 높이. |
| padding | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 범위에 추가할 패딩을 지정합니다. |
| resolution | double | r/w | 이 지도를 렌더링하고 [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) 간 변환에 사용할 해상도입니다. 기본값은 96입니다. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | 지도의 [Map.spatial_reference_system](/psd/python-net/aspose.gis.rendering/map/). |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 지도의 시각적 너비. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(features_sequence)](#add_features_sequence_1) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/)을 생성하고 지도에 추가합니다. 레이어는 추가된 순서대로 렌더링됩니다. |
| [add(features_sequence, symbolizer)](#add_features_sequence_symbolizer_2) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/)을 생성하고 지도에 추가합니다. 레이어는 추가된 순서대로 렌더링됩니다. |
| [add(features_sequence, symbolizer, labeling)](#add_features_sequence_symbolizer_labeling_3) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/)을 생성하고 지도에 추가합니다. 레이어는 추가된 순서대로 렌더링됩니다. |
| [add(layer, colorizer, keep_open)](#add_layer_colorizer_keep_open_4) | 기본 컬러라이저를 사용한 [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/)을 생성하고 지도에 추가합니다. |
| [add(layer, keep_open)](#add_layer_keep_open_5) | 기본 심볼라이저를 사용한 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/)을 생성하고 지도에 추가합니다. 레이어는 추가된 순서대로 렌더링됩니다. |
| [add(layer, symbolizer, keep_open)](#add_layer_symbolizer_keep_open_6) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/)을 생성하고 지도에 추가합니다. 레이어는 추가된 순서대로 렌더링됩니다. |
| [add(layer, symbolizer, labeling, default_reference_system, keep_open)](#add_layer_symbolizer_labeling_default_reference_system_keep_open_7) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/)을 생성하고 지도에 추가합니다. 레이어는 추가된 순서대로 렌더링됩니다. |
| [add(layer, symbolizer, labeling, keep_open)](#add_layer_symbolizer_labeling_keep_open_8) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/)을 생성하고 지도에 추가합니다. 레이어는 추가된 순서대로 렌더링됩니다. |
| [add(map_layer)](#add_map_layer_9) | 맵에 레이어를 추가합니다. 레이어는 추가 순서대로 렌더링됩니다. |
| [render(output_path, renderer)](#render_output_path_renderer_10) | 맵을 파일로 렌더링합니다. |
| [render(output_path, renderer)](#render_output_path_renderer_11) | 맵을 파일로 렌더링합니다. |


### Constructor: Map() {#Map__1}


```
 Map() 
```

새 <c>Map</c> 클래스 인스턴스를 생성합니다.

### Constructor: Map(width, height) {#Map_width_height_2}


```
 Map(width, height) 
```

새 <c>Map</c> 클래스 인스턴스를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | 지도 너비입니다. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | 지도 높이입니다. |

### Method: add(features_sequence) {#add_features_sequence_1}


```
 add(features_sequence) 
```

[VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/)을 생성하고 지도에 추가합니다. 레이어는 추가된 순서대로 렌더링됩니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 로 표현할 피처 시퀀스입니다. |

### Method: add(features_sequence, symbolizer) {#add_features_sequence_symbolizer_2}


```
 add(features_sequence, symbolizer) 
```

[VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/)을 생성하고 지도에 추가합니다. 레이어는 추가된 순서대로 렌더링됩니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 로 표현할 피처 시퀀스입니다. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 렌더링에 사용할 심볼라이저입니다. <see langword=\"null\" />인 경우 기본 심볼라이저가 사용됩니다. |

### Method: add(features_sequence, symbolizer, labeling) {#add_features_sequence_symbolizer_labeling_3}


```
 add(features_sequence, symbolizer, labeling) 
```

[VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/)을 생성하고 지도에 추가합니다. 레이어는 추가된 순서대로 렌더링됩니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 로 표현할 피처 시퀀스입니다. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 렌더링에 사용할 심볼라이저입니다. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | 레이어의 피처에 레이블을 지정할 라벨링입니다. <see langword=\"null\" />인 경우, [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/)이 사용됩니다. |

### Method: add(layer, colorizer, keep_open) {#add_layer_colorizer_keep_open_4}


```
 add(layer, colorizer, keep_open) 
```

기본 컬러라이저를 사용한 [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/)을 생성하고 지도에 추가합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) 로 표현할 벡터 레이어입니다. |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | 렌더링에 사용할 컬러라이저입니다. <see langword=\"null\" />인 경우 기본 컬러라이저가 사용됩니다. |
| keep_open | bool | <see langword=\"true\" />: [Map](/psd/python-net/aspose.gis.rendering/map/) 객체가 해제된 후 래스터 레이어를 열어 둡니다;<br/>            <see langword=\"false\" />: 레이어를 해제합니다. |

### Method: add(layer, keep_open) {#add_layer_keep_open_5}


```
 add(layer, keep_open) 
```

기본 심볼라이저를 사용한 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/)을 생성하고 지도에 추가합니다. 레이어는 추가된 순서대로 렌더링됩니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 로 표현할 벡터 레이어입니다. |
| keep_open | bool | <see langword=\"true\" />: [Map](/psd/python-net/aspose.gis.rendering/map/) 객체가 해제된 후 벡터 레이어를 열어 둡니다;<br/>            <see langword=\"false\" />: 레이어를 해제합니다. |

### Method: add(layer, symbolizer, keep_open) {#add_layer_symbolizer_keep_open_6}


```
 add(layer, symbolizer, keep_open) 
```

[VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/)을 생성하고 지도에 추가합니다. 레이어는 추가된 순서대로 렌더링됩니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 로 표현할 벡터 레이어입니다. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 렌더링에 사용할 심볼라이저입니다. <see langword=\"null\" />인 경우 기본 심볼라이저가 사용됩니다. |
| keep_open | bool | <see langword=\"true\" />: [Map](/psd/python-net/aspose.gis.rendering/map/) 객체가 해제된 후 벡터 레이어를 열어 둡니다;<br/>            <see langword=\"false\" />: 레이어를 해제합니다. |

### Method: add(layer, symbolizer, labeling, default_reference_system, keep_open) {#add_layer_symbolizer_labeling_default_reference_system_keep_open_7}


```
 add(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

[VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/)을 생성하고 지도에 추가합니다. 레이어는 추가된 순서대로 렌더링됩니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 로 표현할 벡터 레이어입니다. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 렌더링에 사용할 심볼라이저입니다. <see langword=\"null\" />인 경우 기본 심볼라이저가 사용됩니다. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | 레이어의 피처에 레이블을 지정할 라벨링입니다. <see langword=\"null\" />인 경우 기본 [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/)이 사용됩니다. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 소스 공간 참조(레이어\\시퀀스)가 없을 경우 값을 지정합니다. 기본값인 null이 사용됩니다. |
| keep_open | bool | <see langword=\"true\" />: [Map](/psd/python-net/aspose.gis.rendering/map/) 객체가 해제된 후 레이어를 열어 둡니다; 그렇지 않으면 <see langword=\"false\" />. |

### Method: add(layer, symbolizer, labeling, keep_open) {#add_layer_symbolizer_labeling_keep_open_8}


```
 add(layer, symbolizer, labeling, keep_open) 
```

[VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/)을 생성하고 지도에 추가합니다. 레이어는 추가된 순서대로 렌더링됩니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 로 표현할 벡터 레이어입니다. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 렌더링에 사용할 심볼라이저입니다. <see langword=\"null\" />인 경우 기본 심볼라이저가 사용됩니다. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | 레이어의 피처에 레이블을 지정할 라벨링입니다. <see langword=\"null\" />인 경우 기본 [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/)이 사용됩니다. |
| keep_open | bool | <see langword=\"true\" />: [Map](/psd/python-net/aspose.gis.rendering/map/) 객체가 해제된 후 레이어를 열어 둡니다; 그렇지 않으면 <see langword=\"false\" />. |

### Method: add(map_layer) {#add_map_layer_9}


```
 add(map_layer) 
```

맵에 레이어를 추가합니다. 레이어는 추가 순서대로 렌더링됩니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| map_layer | [MapLayer](/psd/python-net/aspose.gis.rendering/maplayer) | 추가될 레이어입니다. |

### Method: render(output_path, renderer) {#render_output_path_renderer_10}


```
 render(output_path, renderer) 
```

맵을 파일로 렌더링합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| output_path | string | 출력 파일의 경로. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | 사용할 렌더러입니다. |

### Method: render(output_path, renderer) {#render_output_path_renderer_11}


```
 render(output_path, renderer) 
```

맵을 파일로 렌더링합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 출력 파일의 경로. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | 사용할 렌더러입니다. |

