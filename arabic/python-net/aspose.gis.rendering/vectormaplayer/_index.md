---
title: "فئة VectorMapLayer"
type: docs
weight: 390
url: /ar/python-net/aspose.gis.rendering/vectormaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a vector layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.VectorMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [VectorMapLayer(features_sequence)](#VectorMapLayer_features_sequence_1) | ينشئ نسخة جديدة مع المُرمّز الافتراضي. |
| [VectorMapLayer(features_sequence, symbolizer)](#VectorMapLayer_features_sequence_symbolizer_2) | ينشئ نسخة جديدة مع المُرمّز الافتراضي. |
| [VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system)](#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3) | ينشئ نسخة جديدة مع المُرمّز الافتراضي. |
| [VectorMapLayer(layer, keep_open)](#VectorMapLayer_layer_keep_open_4) | ينشئ نسخة جديدة مع المُرمّز الافتراضي. |
| [VectorMapLayer(layer, symbolizer, keep_open)](#VectorMapLayer_layer_symbolizer_keep_open_5) | ينشئ نسخة جديدة. |
| [VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6) | ينشئ نسخة جديدة. |
| [VectorMapLayer(layer, symbolizer, labeling, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_keep_open_7) | ينشئ نسخة جديدة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | r | تسلسل الميزات الممثلة بواسطة هذا <c>VectorMapLayer</c>. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | r/w | يحدد خيارات الالتواء لطبقة الخريطة. |
| opacity | double | r/w | شفافية الطبقة. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | r/w | المُرمّز لاستخدامه في عرض ميزات الطبقة. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [import_sld(path, options)](#import_sld_path_options_1) | يستورد النمط من ملف وصف الطبقة المُنسق الموجود في المسار المحدد. |
| [import_sld(path, options)](#import_sld_path_options_2) | يستورد النمط من ملف وصف الطبقة المُنسق الموجود في المسار المحدد. |
| [import_sld_from_string(sld, options)](#import_sld_from_string_sld_options_3) | يستورد النمط من سلسلة وصف الطبقة المُنسقة المحددة. |


### Constructor: VectorMapLayer(features_sequence) {#VectorMapLayer_features_sequence_1}


```
 VectorMapLayer(features_sequence) 
```

ينشئ نسخة جديدة مع المُرمّز الافتراضي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | تسلسل الميزات. |

### Constructor: VectorMapLayer(features_sequence, symbolizer) {#VectorMapLayer_features_sequence_symbolizer_2}


```
 VectorMapLayer(features_sequence, symbolizer) 
```

ينشئ نسخة جديدة مع المُرمّز الافتراضي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | تسلسل الميزات. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | المُرمّز لاستخدامه في عرض الطبقة. إذا كان <see langword=\"null\" />, سيتم استخدام المُرمّز الافتراضي. |

### Constructor: VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) {#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3}


```
 VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) 
```

ينشئ نسخة جديدة مع المُرمّز الافتراضي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | تسلسل الميزات. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | المُرمّز لاستخدامه في عرض الطبقة. إذا كان <see langword=\"null\" />, سيتم استخدام المُرمّز الافتراضي. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | التسمية لاستخدامها لتسمية الميزات في الطبقة. إذا كان <see langword=\"null\" />, سيتم استخدام [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) الافتراضي. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | يحدد قيمة للمرجع المكاني المصدر (الطبقة\\التسلسل) إذا كانت مفقودة. سيتم استخدام القيمة الافتراضية null. |

### Constructor: VectorMapLayer(layer, keep_open) {#VectorMapLayer_layer_keep_open_4}


```
 VectorMapLayer(layer, keep_open) 
```

ينشئ نسخة جديدة مع المُرمّز الافتراضي.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة متجهة. |
| keep_open | bool | <see langword=\"true\" /> لترك الطبقة مفتوحة بعد التخلص من كائن [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/)؛ وإلا، <see langword=\"false\" />. |

### Constructor: VectorMapLayer(layer, symbolizer, keep_open) {#VectorMapLayer_layer_symbolizer_keep_open_5}


```
 VectorMapLayer(layer, symbolizer, keep_open) 
```

ينشئ نسخة جديدة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة متجهة. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | المُرمّز لاستخدامه في عرض الطبقة. إذا كان <see langword=\"null\" />, سيتم استخدام المُرمّز الافتراضي. |
| keep_open | bool | <see langword=\"true\" /> لترك الطبقة مفتوحة بعد التخلص من كائن [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/)؛ وإلا، <see langword=\"false\" />. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6}


```
 VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

ينشئ نسخة جديدة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة متجهة. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | المُرمّز لاستخدامه في عرض الطبقة. إذا كان <see langword=\"null\" />, سيتم استخدام المُرمّز الافتراضي. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | التسمية لاستخدامها لتسمية الميزات في الطبقة. إذا كان <see langword=\"null\" />, سيتم استخدام [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) الافتراضي. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | يحدد قيمة للمرجع المكاني المصدر (الطبقة\\التسلسل) إذا كانت مفقودة. سيتم استخدام القيمة الافتراضية null. |
| keep_open | bool | <see langword=\"true\" /> لترك الطبقة مفتوحة بعد التخلص من كائن [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/)؛ وإلا، <see langword=\"false\" />. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_keep_open_7}


```
 VectorMapLayer(layer, symbolizer, labeling, keep_open) 
```

ينشئ نسخة جديدة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة متجهة. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | المُرمّز لاستخدامه في عرض الطبقة. إذا كان <see langword=\"null\" />, سيتم استخدام المُرمّز الافتراضي. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | التسمية لاستخدامها لتسمية الميزات في الطبقة. إذا كان <see langword=\"null\" />, سيتم استخدام [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) الافتراضي. |
| keep_open | bool | <see langword=\"true\" /> لترك الطبقة مفتوحة بعد التخلص من كائن [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/)؛ وإلا، <see langword=\"false\" />. |

### Method: import_sld(path, options) {#import_sld_path_options_1}


```
 import_sld(path, options) 
```

يستورد النمط من ملف وصف الطبقة المُنسق الموجود في المسار المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار إلى ملف وصف الطبقة المُنسق. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | خيارات الاستيراد. |

### Method: import_sld(path, options) {#import_sld_path_options_2}


```
 import_sld(path, options) 
```

يستورد النمط من ملف وصف الطبقة المُنسق الموجود في المسار المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى ملف وصف الطبقة المُنسق. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | خيارات الاستيراد. |

### Method: import_sld_from_string(sld, options) {#import_sld_from_string_sld_options_3}


```
 import_sld_from_string(sld, options) 
```

يستورد النمط من سلسلة وصف الطبقة المُنسقة المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| sld | string | وصف الطبقة المنسقة. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | خيارات الاستيراد. |

