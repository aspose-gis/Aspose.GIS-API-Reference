---
title: "VectorMapLayer 클래스"
type: docs
weight: 390
url: /ko/python-net/aspose.gis.rendering/vectormaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a vector layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.VectorMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [VectorMapLayer(features_sequence)](#VectorMapLayer_features_sequence_1) | 기본 심볼라이저로 새 인스턴스를 생성합니다. |
| [VectorMapLayer(features_sequence, symbolizer)](#VectorMapLayer_features_sequence_symbolizer_2) | 기본 심볼라이저로 새 인스턴스를 생성합니다. |
| [VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system)](#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3) | 기본 심볼라이저로 새 인스턴스를 생성합니다. |
| [VectorMapLayer(layer, keep_open)](#VectorMapLayer_layer_keep_open_4) | 기본 심볼라이저로 새 인스턴스를 생성합니다. |
| [VectorMapLayer(layer, symbolizer, keep_open)](#VectorMapLayer_layer_symbolizer_keep_open_5) | 새 인스턴스를 생성합니다. |
| [VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6) | 새 인스턴스를 생성합니다. |
| [VectorMapLayer(layer, symbolizer, labeling, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_keep_open_7) | 새 인스턴스를 생성합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | r | 이 <c>VectorMapLayer</c>가 표현하는 피처 시퀀스입니다. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | r/w | 맵 레이어의 워프 옵션을 지정합니다. |
| opacity | double | r/w | 레이어의 불투명도. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | r/w | 레이어의 피처를 렌더링할 심볼라이저입니다. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [import_sld(path, options)](#import_sld_path_options_1) | 지정된 경로에 있는 Styled Layer Descriptor 파일에서 스타일을 가져옵니다. |
| [import_sld(path, options)](#import_sld_path_options_2) | 지정된 경로에 있는 Styled Layer Descriptor 파일에서 스타일을 가져옵니다. |
| [import_sld_from_string(sld, options)](#import_sld_from_string_sld_options_3) | 지정된 Styled Layer Descriptor 문자열에서 스타일을 가져옵니다. |


### Constructor: VectorMapLayer(features_sequence) {#VectorMapLayer_features_sequence_1}


```
 VectorMapLayer(features_sequence) 
```

기본 심볼라이저로 새 인스턴스를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 피처 시퀀스. |

### Constructor: VectorMapLayer(features_sequence, symbolizer) {#VectorMapLayer_features_sequence_symbolizer_2}


```
 VectorMapLayer(features_sequence, symbolizer) 
```

기본 심볼라이저로 새 인스턴스를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 피처 시퀀스. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 레이어를 렌더링할 심볼라이저입니다. <see langword=\"null\" />인 경우 기본 심볼라이저가 사용됩니다. |

### Constructor: VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) {#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3}


```
 VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) 
```

기본 심볼라이저로 새 인스턴스를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 피처 시퀀스. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 레이어를 렌더링할 심볼라이저입니다. <see langword=\"null\" />인 경우 기본 심볼라이저가 사용됩니다. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | 레이어의 피처에 레이블을 지정할 라벨링입니다. <see langword=\"null\" />인 경우 기본 [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/)이 사용됩니다. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 소스 공간 참조(레이어\\시퀀스)가 없을 경우 값을 지정합니다. 기본값인 null이 사용됩니다. |

### Constructor: VectorMapLayer(layer, keep_open) {#VectorMapLayer_layer_keep_open_4}


```
 VectorMapLayer(layer, keep_open) 
```

기본 심볼라이저로 새 인스턴스를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 벡터 레이어. |
| keep_open | bool | <see langword=\"true\" />는 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 객체가 해제된 후 레이어를 열어 둡니다; 그렇지 않으면 <see langword=\"false\" />입니다. |

### Constructor: VectorMapLayer(layer, symbolizer, keep_open) {#VectorMapLayer_layer_symbolizer_keep_open_5}


```
 VectorMapLayer(layer, symbolizer, keep_open) 
```

새 인스턴스를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 벡터 레이어. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 레이어를 렌더링할 심볼라이저입니다. <see langword=\"null\" />인 경우 기본 심볼라이저가 사용됩니다. |
| keep_open | bool | <see langword=\"true\" />는 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 객체가 해제된 후 레이어를 열어 둡니다; 그렇지 않으면 <see langword=\"false\" />입니다. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6}


```
 VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

새 인스턴스를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 벡터 레이어. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 레이어를 렌더링할 심볼라이저입니다. <see langword=\"null\" />인 경우 기본 심볼라이저가 사용됩니다. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | 레이어의 피처에 레이블을 지정할 라벨링입니다. <see langword=\"null\" />인 경우 기본 [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/)이 사용됩니다. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 소스 공간 참조(레이어\\시퀀스)가 없을 경우 값을 지정합니다. 기본값인 null이 사용됩니다. |
| keep_open | bool | <see langword=\"true\" />는 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 객체가 해제된 후 레이어를 열어 둡니다; 그렇지 않으면 <see langword=\"false\" />입니다. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_keep_open_7}


```
 VectorMapLayer(layer, symbolizer, labeling, keep_open) 
```

새 인스턴스를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 벡터 레이어. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 레이어를 렌더링할 심볼라이저입니다. <see langword=\"null\" />인 경우 기본 심볼라이저가 사용됩니다. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | 레이어의 피처에 레이블을 지정할 라벨링입니다. <see langword=\"null\" />인 경우 기본 [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/)이 사용됩니다. |
| keep_open | bool | <see langword=\"true\" />는 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 객체가 해제된 후 레이어를 열어 둡니다; 그렇지 않으면 <see langword=\"false\" />입니다. |

### Method: import_sld(path, options) {#import_sld_path_options_1}


```
 import_sld(path, options) 
```

지정된 경로에 있는 Styled Layer Descriptor 파일에서 스타일을 가져옵니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | Styled Layer Descriptor 파일 경로입니다. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | 가져오기 옵션입니다. |

### Method: import_sld(path, options) {#import_sld_path_options_2}


```
 import_sld(path, options) 
```

지정된 경로에 있는 Styled Layer Descriptor 파일에서 스타일을 가져옵니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Styled Layer Descriptor 파일 경로입니다. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | 가져오기 옵션입니다. |

### Method: import_sld_from_string(sld, options) {#import_sld_from_string_sld_options_3}


```
 import_sld_from_string(sld, options) 
```

지정된 Styled Layer Descriptor 문자열에서 스타일을 가져옵니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| sld | string | 스타일 레이어 디스크립터. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | 가져오기 옵션입니다. |

