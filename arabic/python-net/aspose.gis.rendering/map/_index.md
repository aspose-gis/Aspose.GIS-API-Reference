---
title: "فئة Map"
type: docs
weight: 100
url: /ar/python-net/aspose.gis.rendering/map/
---

**Summary:** Map is a collection of layers that can be rendered on top of each other via [Renderer](/psd/python-net/aspose.gis.rendering/renderer/).

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.Map

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Map()](#Map__1) | إنشاء نسخة جديدة من الفئة <c>Map</c>. |
| [Map(width, height)](#Map_width_height_2) | إنشاء نسخة جديدة من الفئة <c>Map</c>. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | r/w | لون خلفية الخريطة. القيمة الافتراضية هي . |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | يحدد حدود الخريطة للعرض.<br/>            إذا تم تعيينه إلى <see langword=\"null\" />, يتم حساب الامتداد أثناء العرض لتضمين جميع الأشكال في جميع الطبقات. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | الارتفاع البصري للخريطة. |
| padding | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | يحدد الحشو لإضافته إلى الامتداد. |
| resolution | double | r/w | الدقة المستخدمة لعرض هذه الخريطة وللتحويل بين [Measurement](/psd/python-net/aspose.gis.rendering/measurement/). القيمة الافتراضية هي 96. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | ‏[Map.spatial_reference_system](/psd/python-net/aspose.gis.rendering/map/) للخريطة. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | العرض البصري للخريطة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add(features_sequence)](#add_features_sequence_1) | إنشاء وإضافة [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة. |
| [add(features_sequence, symbolizer)](#add_features_sequence_symbolizer_2) | إنشاء وإضافة [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة. |
| [add(features_sequence, symbolizer, labeling)](#add_features_sequence_symbolizer_labeling_3) | إنشاء وإضافة [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة. |
| [add(layer, colorizer, keep_open)](#add_layer_colorizer_keep_open_4) | إنشاء [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) مع الـ colorizer الافتراضي وإضافته إلى الخريطة. |
| [add(layer, keep_open)](#add_layer_keep_open_5) | إنشاء [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) مع الـ symbolizer الافتراضي وإضافته إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة. |
| [add(layer, symbolizer, keep_open)](#add_layer_symbolizer_keep_open_6) | إنشاء وإضافة [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة. |
| [add(layer, symbolizer, labeling, default_reference_system, keep_open)](#add_layer_symbolizer_labeling_default_reference_system_keep_open_7) | إنشاء وإضافة [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة. |
| [add(layer, symbolizer, labeling, keep_open)](#add_layer_symbolizer_labeling_keep_open_8) | إنشاء وإضافة [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة. |
| [add(map_layer)](#add_map_layer_9) | يضيف طبقة إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة. |
| [render(output_path, renderer)](#render_output_path_renderer_10) | يقوم بتصدير الخريطة إلى ملف. |
| [render(output_path, renderer)](#render_output_path_renderer_11) | يقوم بتصدير الخريطة إلى ملف. |


### Constructor: Map() {#Map__1}


```
 Map() 
```

إنشاء نسخة جديدة من الفئة <c>Map</c>.

### Constructor: Map(width, height) {#Map_width_height_2}


```
 Map(width, height) 
```

إنشاء نسخة جديدة من الفئة <c>Map</c>.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | عرض الخريطة. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | ارتفاع الخريطة. |

### Method: add(features_sequence) {#add_features_sequence_1}


```
 add(features_sequence) 
```

إنشاء وإضافة [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | تسلسل الميزات لتمثيله بواسطة [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |

### Method: add(features_sequence, symbolizer) {#add_features_sequence_symbolizer_2}


```
 add(features_sequence, symbolizer) 
```

إنشاء وإضافة [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | تسلسل الميزات لتمثيله بواسطة [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | مُرمّز للاستخدام في التصيير. إذا كان <see langword="null" />, يُستخدم المُرمّز الافتراضي. |

### Method: add(features_sequence, symbolizer, labeling) {#add_features_sequence_symbolizer_labeling_3}


```
 add(features_sequence, symbolizer, labeling) 
```

إنشاء وإضافة [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | تسلسل الميزات لتمثيله بواسطة [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | مُرمّز لاستخدامه في العرض. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | التسمية لاستخدامها لتسمية الميزات في الطبقة. إذا كان <see langword=\"null\" />, سيتم استخدام [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |

### Method: add(layer, colorizer, keep_open) {#add_layer_colorizer_keep_open_4}


```
 add(layer, colorizer, keep_open) 
```

إنشاء [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) مع الـ colorizer الافتراضي وإضافته إلى الخريطة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | طبقة متجهة لتمثيلها بواسطة [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/). |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | مُلوّن لاستخدامه في العرض. إذا كان <see langword=\"null\" />, يتم استخدام المُلوّن الافتراضي. |
| keep_open | bool | <see langword=\"true\" /> لترك طبقة الراستر مفتوحة بعد التخلص من كائن [Map](/psd/python-net/aspose.gis.rendering/map/);<br/>            <see langword=\"false\" /> للتخلص من الطبقة. |

### Method: add(layer, keep_open) {#add_layer_keep_open_5}


```
 add(layer, keep_open) 
```

إنشاء [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) مع الـ symbolizer الافتراضي وإضافته إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة متجهة لتمثيلها بواسطة [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| keep_open | bool | <see langword=\"true\" /> لترك الطبقة المتجهة مفتوحة بعد التخلص من كائن [Map](/psd/python-net/aspose.gis.rendering/map/);<br/>            <see langword=\"false\" /> للتخلص من الطبقة. |

### Method: add(layer, symbolizer, keep_open) {#add_layer_symbolizer_keep_open_6}


```
 add(layer, symbolizer, keep_open) 
```

إنشاء وإضافة [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة متجهة لتمثيلها بواسطة [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | مُرمّز للاستخدام في التصيير. إذا كان <see langword="null" />, يُستخدم المُرمّز الافتراضي. |
| keep_open | bool | <see langword=\"true\" /> لترك الطبقة المتجهة مفتوحة بعد التخلص من كائن [Map](/psd/python-net/aspose.gis.rendering/map/);<br/>            <see langword=\"false\" /> للتخلص من الطبقة. |

### Method: add(layer, symbolizer, labeling, default_reference_system, keep_open) {#add_layer_symbolizer_labeling_default_reference_system_keep_open_7}


```
 add(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

إنشاء وإضافة [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة متجهة لتمثيلها بواسطة [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | مُرمّز للاستخدام في التصيير. إذا كان <see langword="null" />, يُستخدم المُرمّز الافتراضي. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | التسمية لاستخدامها لتسمية الميزات في الطبقة. إذا كان <see langword=\"null\" />, سيتم استخدام [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) الافتراضي. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | يحدد قيمة للمرجع المكاني المصدر (الطبقة\\التسلسل) إذا كانت مفقودة. سيتم استخدام القيمة الافتراضية null. |
| keep_open | bool | <see langword=\"true\" /> لترك الطبقة مفتوحة بعد التخلص من كائن [Map](/psd/python-net/aspose.gis.rendering/map/); وإلا، <see langword=\"false\" />. |

### Method: add(layer, symbolizer, labeling, keep_open) {#add_layer_symbolizer_labeling_keep_open_8}


```
 add(layer, symbolizer, labeling, keep_open) 
```

إنشاء وإضافة [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة متجهة لتمثيلها بواسطة [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | مُرمّز للاستخدام في التصيير. إذا كان <see langword="null" />, يُستخدم المُرمّز الافتراضي. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | التسمية لاستخدامها لتسمية الميزات في الطبقة. إذا كان <see langword=\"null\" />, سيتم استخدام [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) الافتراضي. |
| keep_open | bool | <see langword=\"true\" /> لترك الطبقة مفتوحة بعد التخلص من كائن [Map](/psd/python-net/aspose.gis.rendering/map/); وإلا، <see langword=\"false\" />. |

### Method: add(map_layer) {#add_map_layer_9}


```
 add(map_layer) 
```

يضيف طبقة إلى الخريطة. يتم عرض الطبقات بترتيب الإضافة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| map_layer | [MapLayer](/psd/python-net/aspose.gis.rendering/maplayer) | الطبقة التي سيتم إضافتها. |

### Method: render(output_path, renderer) {#render_output_path_renderer_10}


```
 render(output_path, renderer) 
```

يقوم بتصدير الخريطة إلى ملف.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| output_path | string | المسار إلى ملف الإخراج. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | المُعالج للاستخدام. |

### Method: render(output_path, renderer) {#render_output_path_renderer_11}


```
 render(output_path, renderer) 
```

يقوم بتصدير الخريطة إلى ملف.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى ملف الإخراج. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | المُعالج للاستخدام. |

