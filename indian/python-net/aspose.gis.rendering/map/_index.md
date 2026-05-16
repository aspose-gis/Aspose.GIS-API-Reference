---
title: "Map क्लास"
type: docs
weight: 100
url: /hi/python-net/aspose.gis.rendering/map/
---

**Summary:** Map is a collection of layers that can be rendered on top of each other via [Renderer](/psd/python-net/aspose.gis.rendering/renderer/).

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.Map

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [Map()](#Map__1) | <c>Map</c> क्लास का नया इंस्टेंस बनाता है। |
| [Map(width, height)](#Map_width_height_2) | <c>Map</c> क्लास का नया इंस्टेंस बनाता है। |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | r/w | मानचित्र का पृष्ठभूमि रंग। डिफ़ॉल्ट रूप से . |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | मानचित्र को रेंडर करने की सीमाएँ निर्दिष्ट करता है।<br/>यदि <see langword=\"null\" /> पर सेट किया जाता है, तो सभी लेयर्स में सभी ज्यामितियों को शामिल करने के लिए रेंडरिंग के दौरान विस्तार की गणना की जाती है। |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | मानचित्र की दृश्य ऊँचाई। |
| padding | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | विस्तार में जोड़ने के लिए पैडिंग निर्दिष्ट करता है। |
| resolution | double | r/w | इस मानचित्र को रेंडर करने और [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) के बीच रूपांतरण के लिए उपयोग की जाने वाली रेज़ोल्यूशन। डिफ़ॉल्ट रूप से 96। |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | मानचित्र का [Map.spatial_reference_system](/psd/python-net/aspose.gis.rendering/map/)। |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | मानचित्र की दृश्य चौड़ाई। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [add(features_sequence)](#add_features_sequence_1) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) को मानचित्र में बनाता और जोड़ता है। लेयर्स को जोड़ने के क्रम में रेंडर किया जाता है। |
| [add(features_sequence, symbolizer)](#add_features_sequence_symbolizer_2) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) को मानचित्र में बनाता और जोड़ता है। लेयर्स को जोड़ने के क्रम में रेंडर किया जाता है। |
| [add(features_sequence, symbolizer, labeling)](#add_features_sequence_symbolizer_labeling_3) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) को मानचित्र में बनाता और जोड़ता है। लेयर्स को जोड़ने के क्रम में रेंडर किया जाता है। |
| [add(layer, colorizer, keep_open)](#add_layer_colorizer_keep_open_4) | डिफ़ॉल्ट कलराइज़र के साथ एक [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) बनाता है और इसे मानचित्र में जोड़ता है। |
| [add(layer, keep_open)](#add_layer_keep_open_5) | डिफ़ॉल्ट सिंबलाइज़र के साथ एक [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) बनाता है और इसे मानचित्र में जोड़ता है। लेयर्स को जोड़ने के क्रम में रेंडर किया जाता है। |
| [add(layer, symbolizer, keep_open)](#add_layer_symbolizer_keep_open_6) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) को मानचित्र में बनाता और जोड़ता है। लेयर्स को जोड़ने के क्रम में रेंडर किया जाता है। |
| [add(layer, symbolizer, labeling, default_reference_system, keep_open)](#add_layer_symbolizer_labeling_default_reference_system_keep_open_7) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) को मानचित्र में बनाता और जोड़ता है। लेयर्स को जोड़ने के क्रम में रेंडर किया जाता है। |
| [add(layer, symbolizer, labeling, keep_open)](#add_layer_symbolizer_labeling_keep_open_8) | [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) को मानचित्र में बनाता और जोड़ता है। लेयर्स को जोड़ने के क्रम में रेंडर किया जाता है। |
| [add(map_layer)](#add_map_layer_9) | मानचित्र में एक लेयर जोड़ता है। लेयर्स जोड़ने के क्रम में रेंडर की जाती हैं। |
| [render(output_path, renderer)](#render_output_path_renderer_10) | मानचित्र को फ़ाइल में रेंडर करता है। |
| [render(output_path, renderer)](#render_output_path_renderer_11) | मानचित्र को फ़ाइल में रेंडर करता है। |


### Constructor: Map() {#Map__1}


```
 Map() 
```

<c>Map</c> क्लास का नया इंस्टेंस बनाता है।

### Constructor: Map(width, height) {#Map_width_height_2}


```
 Map(width, height) 
```

<c>Map</c> क्लास का नया इंस्टेंस बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | मानचित्र की चौड़ाई। |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | मानचित्र की ऊँचाई। |

### Method: add(features_sequence) {#add_features_sequence_1}


```
 add(features_sequence) 
```

[VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) को मानचित्र में बनाता और जोड़ता है। लेयर्स को जोड़ने के क्रम में रेंडर किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | एक फीचर अनुक्रम जिसे [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) द्वारा दर्शाया जाता है। |

### Method: add(features_sequence, symbolizer) {#add_features_sequence_symbolizer_2}


```
 add(features_sequence, symbolizer) 
```

[VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) को मानचित्र में बनाता और जोड़ता है। लेयर्स को जोड़ने के क्रम में रेंडर किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | एक फीचर अनुक्रम जिसे [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) द्वारा दर्शाया जाता है। |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | रेंडरिंग के लिए उपयोग करने वाला एक सिम्बोलाइज़र। यदि <see langword=\"null\" />, तो डिफ़ॉल्ट सिम्बोलाइज़र उपयोग किया जाता है। |

### Method: add(features_sequence, symbolizer, labeling) {#add_features_sequence_symbolizer_labeling_3}


```
 add(features_sequence, symbolizer, labeling) 
```

[VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) को मानचित्र में बनाता और जोड़ता है। लेयर्स को जोड़ने के क्रम में रेंडर किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | एक फीचर अनुक्रम जिसे [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) द्वारा दर्शाया जाता है। |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | रेंडरिंग के लिए उपयोग करने वाला एक सिम्बोलाइज़र। |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | लेयर में फीचर्स को लेबल करने के लिए उपयोग किया जाने वाला लेबलिंग। यदि <see langword=\"null\" />, तो [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) उपयोग किया जाएगा। |

### Method: add(layer, colorizer, keep_open) {#add_layer_colorizer_keep_open_4}


```
 add(layer, colorizer, keep_open) 
```

डिफ़ॉल्ट कलराइज़र के साथ एक [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) बनाता है और इसे मानचित्र में जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | एक वेक्टर लेयर जिसे [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) द्वारा दर्शाया जाता है। |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | रेंडरिंग के लिए उपयोग किया जाने वाला एक कलराइज़र। यदि <see langword=\"null\" />, तो डिफ़ॉल्ट कलराइज़र उपयोग किया जाता है। |
| keep_open | bool | <see langword=\"true\" /> रास्टर लेयर को [Map](/psd/python-net/aspose.gis.rendering/map/) ऑब्जेक्ट डिस्पोज़ होने के बाद खुला रखने के लिए;<br/>            <see langword=\"false\" /> लेयर को डिस्पोज़ करने के लिए। |

### Method: add(layer, keep_open) {#add_layer_keep_open_5}


```
 add(layer, keep_open) 
```

डिफ़ॉल्ट सिंबलाइज़र के साथ एक [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) बनाता है और इसे मानचित्र में जोड़ता है। लेयर्स को जोड़ने के क्रम में रेंडर किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक वेक्टर लेयर जिसे [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) द्वारा दर्शाया जाता है। |
| keep_open | bool | <see langword=\"true\" /> वेक्टर लेयर को [Map](/psd/python-net/aspose.gis.rendering/map/) ऑब्जेक्ट डिस्पोज़ होने के बाद खुला रखने के लिए;<br/>            <see langword=\"false\" /> लेयर को डिस्पोज़ करने के लिए। |

### Method: add(layer, symbolizer, keep_open) {#add_layer_symbolizer_keep_open_6}


```
 add(layer, symbolizer, keep_open) 
```

[VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) को मानचित्र में बनाता और जोड़ता है। लेयर्स को जोड़ने के क्रम में रेंडर किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक वेक्टर लेयर जिसे [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) द्वारा दर्शाया जाता है। |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | रेंडरिंग के लिए उपयोग करने वाला एक सिम्बोलाइज़र। यदि <see langword=\"null\" />, तो डिफ़ॉल्ट सिम्बोलाइज़र उपयोग किया जाता है। |
| keep_open | bool | <see langword=\"true\" /> वेक्टर लेयर को [Map](/psd/python-net/aspose.gis.rendering/map/) ऑब्जेक्ट डिस्पोज़ होने के बाद खुला रखने के लिए;<br/>            <see langword=\"false\" /> लेयर को डिस्पोज़ करने के लिए। |

### Method: add(layer, symbolizer, labeling, default_reference_system, keep_open) {#add_layer_symbolizer_labeling_default_reference_system_keep_open_7}


```
 add(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

[VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) को मानचित्र में बनाता और जोड़ता है। लेयर्स को जोड़ने के क्रम में रेंडर किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक वेक्टर लेयर जिसे [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) द्वारा दर्शाया जाता है। |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | रेंडरिंग के लिए उपयोग करने वाला एक सिम्बोलाइज़र। यदि <see langword=\"null\" />, तो डिफ़ॉल्ट सिम्बोलाइज़र उपयोग किया जाता है। |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | लेयर में फीचर्स को लेबल करने के लिए उपयोग किया जाने वाला लेबलिंग। यदि <see langword=\"null\" />, तो डिफ़ॉल्ट [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) उपयोग किया जाएगा। |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | यदि स्रोत स्पैशियल रेफ़रेंस (लेयर\\सीक्वेंस) अनुपलब्ध है तो उसके लिए मान निर्दिष्ट करता है। डिफ़ॉल्ट null उपयोग किया जाएगा। |
| keep_open | bool | <see langword=\"true\" /> लेयर को [Map](/psd/python-net/aspose.gis.rendering/map/) ऑब्जेक्ट डिस्पोज़ होने के बाद खुला रखने के लिए; अन्यथा, <see langword=\"false\" />। |

### Method: add(layer, symbolizer, labeling, keep_open) {#add_layer_symbolizer_labeling_keep_open_8}


```
 add(layer, symbolizer, labeling, keep_open) 
```

[VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) को मानचित्र में बनाता और जोड़ता है। लेयर्स को जोड़ने के क्रम में रेंडर किया जाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक वेक्टर लेयर जिसे [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) द्वारा दर्शाया जाता है। |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | रेंडरिंग के लिए उपयोग करने वाला एक सिम्बोलाइज़र। यदि <see langword=\"null\" />, तो डिफ़ॉल्ट सिम्बोलाइज़र उपयोग किया जाता है। |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | लेयर में फीचर्स को लेबल करने के लिए उपयोग किया जाने वाला लेबलिंग। यदि <see langword=\"null\" />, तो डिफ़ॉल्ट [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) उपयोग किया जाएगा। |
| keep_open | bool | <see langword=\"true\" /> लेयर को [Map](/psd/python-net/aspose.gis.rendering/map/) ऑब्जेक्ट डिस्पोज़ होने के बाद खुला रखने के लिए; अन्यथा, <see langword=\"false\" />। |

### Method: add(map_layer) {#add_map_layer_9}


```
 add(map_layer) 
```

मानचित्र में एक लेयर जोड़ता है। लेयर्स जोड़ने के क्रम में रेंडर की जाती हैं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| map_layer | [MapLayer](/psd/python-net/aspose.gis.rendering/maplayer) | जोड़ने के लिए लेयर। |

### Method: render(output_path, renderer) {#render_output_path_renderer_10}


```
 render(output_path, renderer) 
```

मानचित्र को फ़ाइल में रेंडर करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| output_path | string | आउटपुट फ़ाइल का पथ। |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | उपयोग करने के लिए रेंडरर। |

### Method: render(output_path, renderer) {#render_output_path_renderer_11}


```
 render(output_path, renderer) 
```

मानचित्र को फ़ाइल में रेंडर करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | आउटपुट फ़ाइल का पथ। |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | उपयोग करने के लिए रेंडरर। |

