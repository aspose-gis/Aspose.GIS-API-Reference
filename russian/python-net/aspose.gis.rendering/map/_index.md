---
title: "Класс Map"
type: docs
weight: 100
url: /ru/python-net/aspose.gis.rendering/map/
---

**Summary:** Map is a collection of layers that can be rendered on top of each other via [Renderer](/psd/python-net/aspose.gis.rendering/renderer/).

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.Map

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [Map()](#Map__1) | Создаёт новый экземпляр класса <c>Map</c>. |
| [Map(width, height)](#Map_width_height_2) | Создаёт новый экземпляр класса <c>Map</c>. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | r/w | Цвет фона карты. По умолчанию . |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | Указывает границы карты для отрисовки.<br/>            Если установлено в <see langword="null" />, область рассчитывается во время отрисовки, чтобы включить все геометрии во всех слоях. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Визуальная высота карты. |
| padding | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Указывает отступ, добавляемый к области. |
| resolution | double | r/w | Разрешение, используемое для отрисовки этой карты и преобразования между [Measurement](/psd/python-net/aspose.gis.rendering/measurement/). По умолчанию 96. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [Map.spatial_reference_system](/psd/python-net/aspose.gis.rendering/map/) карты. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Визуальная ширина карты. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add(features_sequence)](#add_features_sequence_1) | Создаёт и добавляет [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) на карту. Слои отрисовываются в порядке добавления. |
| [add(features_sequence, symbolizer)](#add_features_sequence_symbolizer_2) | Создаёт и добавляет [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) на карту. Слои отрисовываются в порядке добавления. |
| [add(features_sequence, symbolizer, labeling)](#add_features_sequence_symbolizer_labeling_3) | Создаёт и добавляет [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) на карту. Слои отрисовываются в порядке добавления. |
| [add(layer, colorizer, keep_open)](#add_layer_colorizer_keep_open_4) | Создаёт [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) с цветовым преобразователем по умолчанию и добавляет его на карту. |
| [add(layer, keep_open)](#add_layer_keep_open_5) | Создаёт [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) с символизатором по умолчанию и добавляет его на карту. Слои отрисовываются в порядке добавления. |
| [add(layer, symbolizer, keep_open)](#add_layer_symbolizer_keep_open_6) | Создаёт и добавляет [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) на карту. Слои отрисовываются в порядке добавления. |
| [add(layer, symbolizer, labeling, default_reference_system, keep_open)](#add_layer_symbolizer_labeling_default_reference_system_keep_open_7) | Создаёт и добавляет [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) на карту. Слои отрисовываются в порядке добавления. |
| [add(layer, symbolizer, labeling, keep_open)](#add_layer_symbolizer_labeling_keep_open_8) | Создаёт и добавляет [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) на карту. Слои отрисовываются в порядке добавления. |
| [add(map_layer)](#add_map_layer_9) | Добавляет слой на карту. Слои отображаются в порядке добавления. |
| [render(output_path, renderer)](#render_output_path_renderer_10) | Отрисовывает карту в файл. |
| [render(output_path, renderer)](#render_output_path_renderer_11) | Отрисовывает карту в файл. |


### Constructor: Map() {#Map__1}


```
 Map() 
```

Создаёт новый экземпляр класса <c>Map</c>.

### Constructor: Map(width, height) {#Map_width_height_2}


```
 Map(width, height) 
```

Создаёт новый экземпляр класса <c>Map</c>.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Ширина карты. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Высота карты. |

### Method: add(features_sequence) {#add_features_sequence_1}


```
 add(features_sequence) 
```

Создаёт и добавляет [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) на карту. Слои отрисовываются в порядке добавления.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Последовательность объектов для представления с помощью [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |

### Method: add(features_sequence, symbolizer) {#add_features_sequence_symbolizer_2}


```
 add(features_sequence, symbolizer) 
```

Создаёт и добавляет [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) на карту. Слои отрисовываются в порядке добавления.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Последовательность объектов для представления с помощью [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Символизатор для рендеринга. Если <see langword=\"null\" />, используется символизатор по умолчанию. |

### Method: add(features_sequence, symbolizer, labeling) {#add_features_sequence_symbolizer_labeling_3}


```
 add(features_sequence, symbolizer, labeling) 
```

Создаёт и добавляет [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) на карту. Слои отрисовываются в порядке добавления.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Последовательность объектов для представления с помощью [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Символизатор, используемый для отрисовки. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Подпись, используемая для маркировки объектов в слое. Если <see langword=\"null\" />, будет использовано [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |

### Method: add(layer, colorizer, keep_open) {#add_layer_colorizer_keep_open_4}


```
 add(layer, colorizer, keep_open) 
```

Создаёт [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) с цветовым преобразователем по умолчанию и добавляет его на карту.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | Векторный слой для представления с помощью [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/). |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | Колоризатор, используемый для отрисовки. Если <see langword=\"null\" />, используется колоризатор по умолчанию. |
| keep_open | bool | <see langword=\"true\" /> чтобы оставить растровый слой открытым после освобождения объекта [Map](/psd/python-net/aspose.gis.rendering/map/);<br/>            <see langword=\"false\" /> чтобы освободить слой. |

### Method: add(layer, keep_open) {#add_layer_keep_open_5}


```
 add(layer, keep_open) 
```

Создаёт [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) с символизатором по умолчанию и добавляет его на карту. Слои отрисовываются в порядке добавления.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Векторный слой для представления с помощью [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| keep_open | bool | <see langword=\"true\" /> чтобы оставить векторный слой открытым после освобождения объекта [Map](/psd/python-net/aspose.gis.rendering/map/);<br/>            <see langword=\"false\" /> чтобы освободить слой. |

### Method: add(layer, symbolizer, keep_open) {#add_layer_symbolizer_keep_open_6}


```
 add(layer, symbolizer, keep_open) 
```

Создаёт и добавляет [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) на карту. Слои отрисовываются в порядке добавления.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Векторный слой для представления с помощью [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Символизатор для рендеринга. Если <see langword=\"null\" />, используется символизатор по умолчанию. |
| keep_open | bool | <see langword=\"true\" /> чтобы оставить векторный слой открытым после освобождения объекта [Map](/psd/python-net/aspose.gis.rendering/map/);<br/>            <see langword=\"false\" /> чтобы освободить слой. |

### Method: add(layer, symbolizer, labeling, default_reference_system, keep_open) {#add_layer_symbolizer_labeling_default_reference_system_keep_open_7}


```
 add(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

Создаёт и добавляет [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) на карту. Слои отрисовываются в порядке добавления.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Векторный слой для представления с помощью [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Символизатор для рендеринга. Если <see langword=\"null\" />, используется символизатор по умолчанию. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Подпись, используемая для маркировки объектов в слое. Если <see langword=\"null\" />, будет использовано [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) по умолчанию. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Указывает значение для исходной пространственной привязки (слой\\последовательность), если оно отсутствует. По умолчанию будет использовано null. |
| keep_open | bool | <see langword=\"true\" /> чтобы оставить слой открытым после освобождения объекта [Map](/psd/python-net/aspose.gis.rendering/map/); иначе <see langword=\"false\" />. |

### Method: add(layer, symbolizer, labeling, keep_open) {#add_layer_symbolizer_labeling_keep_open_8}


```
 add(layer, symbolizer, labeling, keep_open) 
```

Создаёт и добавляет [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) на карту. Слои отрисовываются в порядке добавления.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Векторный слой для представления с помощью [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Символизатор для рендеринга. Если <see langword=\"null\" />, используется символизатор по умолчанию. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Подпись, используемая для маркировки объектов в слое. Если <see langword=\"null\" />, будет использовано [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) по умолчанию. |
| keep_open | bool | <see langword=\"true\" /> чтобы оставить слой открытым после освобождения объекта [Map](/psd/python-net/aspose.gis.rendering/map/); иначе <see langword=\"false\" />. |

### Method: add(map_layer) {#add_map_layer_9}


```
 add(map_layer) 
```

Добавляет слой на карту. Слои отображаются в порядке добавления.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| map_layer | [MapLayer](/psd/python-net/aspose.gis.rendering/maplayer) | Слой, который будет добавлен. |

### Method: render(output_path, renderer) {#render_output_path_renderer_10}


```
 render(output_path, renderer) 
```

Отрисовывает карту в файл.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| output_path | string | Путь к выходному файлу. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | Рендерер для использования. |

### Method: render(output_path, renderer) {#render_output_path_renderer_11}


```
 render(output_path, renderer) 
```

Отрисовывает карту в файл.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к выходному файлу. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | Рендерер для использования. |

