---
title: "Класс VectorMapLayer"
type: docs
weight: 390
url: /ru/python-net/aspose.gis.rendering/vectormaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a vector layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.VectorMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [VectorMapLayer(features_sequence)](#VectorMapLayer_features_sequence_1) | Создаёт новый экземпляр с символизатором по умолчанию. |
| [VectorMapLayer(features_sequence, symbolizer)](#VectorMapLayer_features_sequence_symbolizer_2) | Создаёт новый экземпляр с символизатором по умолчанию. |
| [VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system)](#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3) | Создаёт новый экземпляр с символизатором по умолчанию. |
| [VectorMapLayer(layer, keep_open)](#VectorMapLayer_layer_keep_open_4) | Создаёт новый экземпляр с символизатором по умолчанию. |
| [VectorMapLayer(layer, symbolizer, keep_open)](#VectorMapLayer_layer_symbolizer_keep_open_5) | Создаёт новый экземпляр. |
| [VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6) | Создаёт новый экземпляр. |
| [VectorMapLayer(layer, symbolizer, labeling, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_keep_open_7) | Создаёт новый экземпляр. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | r | Последовательность объектов, представляемая этим <c>VectorMapLayer</c>. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | r/w | Указывает параметры искажения (warp) слоя карты. |
| opacity | double | r/w | Непрозрачность слоя. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | r/w | Символизатор, используемый для отрисовки объектов слоя. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [import_sld(path, options)](#import_sld_path_options_1) | Импортирует стиль из файла Styled Layer Descriptor, расположенного по указанному пути. |
| [import_sld(path, options)](#import_sld_path_options_2) | Импортирует стиль из файла Styled Layer Descriptor, расположенного по указанному пути. |
| [import_sld_from_string(sld, options)](#import_sld_from_string_sld_options_3) | Импортирует стиль из указанной строки Styled Layer Descriptor. |


### Constructor: VectorMapLayer(features_sequence) {#VectorMapLayer_features_sequence_1}


```
 VectorMapLayer(features_sequence) 
```

Создаёт новый экземпляр с символизатором по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Последовательность объектов. |

### Constructor: VectorMapLayer(features_sequence, symbolizer) {#VectorMapLayer_features_sequence_symbolizer_2}


```
 VectorMapLayer(features_sequence, symbolizer) 
```

Создаёт новый экземпляр с символизатором по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Последовательность объектов. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Символизатор, используемый для отрисовки слоя. Если <see langword=\"null\" />, будет использован символизатор по умолчанию. |

### Constructor: VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) {#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3}


```
 VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) 
```

Создаёт новый экземпляр с символизатором по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Последовательность объектов. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Символизатор, используемый для отрисовки слоя. Если <see langword=\"null\" />, будет использован символизатор по умолчанию. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Подпись, используемая для маркировки объектов в слое. Если <see langword=\"null\" />, будет использовано [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) по умолчанию. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Указывает значение для исходной пространственной привязки (слой\\последовательность), если оно отсутствует. По умолчанию будет использовано null. |

### Constructor: VectorMapLayer(layer, keep_open) {#VectorMapLayer_layer_keep_open_4}


```
 VectorMapLayer(layer, keep_open) 
```

Создаёт новый экземпляр с символизатором по умолчанию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Векторный слой. |
| keep_open | bool | <see langword="true" /> чтобы оставить слой открытым после освобождения объекта [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/); в противном случае <see langword="false" />. |

### Constructor: VectorMapLayer(layer, symbolizer, keep_open) {#VectorMapLayer_layer_symbolizer_keep_open_5}


```
 VectorMapLayer(layer, symbolizer, keep_open) 
```

Создаёт новый экземпляр.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Векторный слой. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Символизатор, используемый для отрисовки слоя. Если <see langword=\"null\" />, будет использован символизатор по умолчанию. |
| keep_open | bool | <see langword="true" /> чтобы оставить слой открытым после освобождения объекта [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/); в противном случае <see langword="false" />. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6}


```
 VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

Создаёт новый экземпляр.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Векторный слой. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Символизатор, используемый для отрисовки слоя. Если <see langword=\"null\" />, будет использован символизатор по умолчанию. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Подпись, используемая для маркировки объектов в слое. Если <see langword=\"null\" />, будет использовано [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) по умолчанию. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Указывает значение для исходной пространственной привязки (слой\\последовательность), если оно отсутствует. По умолчанию будет использовано null. |
| keep_open | bool | <see langword="true" /> чтобы оставить слой открытым после освобождения объекта [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/); в противном случае <see langword="false" />. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_keep_open_7}


```
 VectorMapLayer(layer, symbolizer, labeling, keep_open) 
```

Создаёт новый экземпляр.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Векторный слой. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Символизатор, используемый для отрисовки слоя. Если <see langword=\"null\" />, будет использован символизатор по умолчанию. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Подпись, используемая для маркировки объектов в слое. Если <see langword=\"null\" />, будет использовано [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) по умолчанию. |
| keep_open | bool | <see langword="true" /> чтобы оставить слой открытым после освобождения объекта [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/); в противном случае <see langword="false" />. |

### Method: import_sld(path, options) {#import_sld_path_options_1}


```
 import_sld(path, options) 
```

Импортирует стиль из файла Styled Layer Descriptor, расположенного по указанному пути.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь к файлу Styled Layer Descriptor. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Параметры импорта. |

### Method: import_sld(path, options) {#import_sld_path_options_2}


```
 import_sld(path, options) 
```

Импортирует стиль из файла Styled Layer Descriptor, расположенного по указанному пути.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к файлу Styled Layer Descriptor. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Параметры импорта. |

### Method: import_sld_from_string(sld, options) {#import_sld_from_string_sld_options_3}


```
 import_sld_from_string(sld, options) 
```

Импортирует стиль из указанной строки Styled Layer Descriptor.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| sld | string | Описание стилизованного слоя. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Параметры импорта. |

