---
title: "VectorMapLayer क्लास"
type: docs
weight: 390
url: /hi/python-net/aspose.gis.rendering/vectormaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a vector layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.VectorMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [VectorMapLayer(features_sequence)](#VectorMapLayer_features_sequence_1) | डिफ़ॉल्ट सिम्बोलाइज़र के साथ नया इंस्टेंस बनाता है। |
| [VectorMapLayer(features_sequence, symbolizer)](#VectorMapLayer_features_sequence_symbolizer_2) | डिफ़ॉल्ट सिम्बोलाइज़र के साथ नया इंस्टेंस बनाता है। |
| [VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system)](#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3) | डिफ़ॉल्ट सिम्बोलाइज़र के साथ नया इंस्टेंस बनाता है। |
| [VectorMapLayer(layer, keep_open)](#VectorMapLayer_layer_keep_open_4) | डिफ़ॉल्ट सिम्बोलाइज़र के साथ नया इंस्टेंस बनाता है। |
| [VectorMapLayer(layer, symbolizer, keep_open)](#VectorMapLayer_layer_symbolizer_keep_open_5) | नया इंस्टेंस बनाता है। |
| [VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6) | नया इंस्टेंस बनाता है। |
| [VectorMapLayer(layer, symbolizer, labeling, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_keep_open_7) | नया इंस्टेंस बनाता है। |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | r | इस <c>VectorMapLayer</c> द्वारा दर्शाया गया फीचर अनुक्रम। |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | r/w | मानचित्र लेयर के वार्प विकल्प निर्दिष्ट करता है। |
| opacity | double | r/w | लेयर की अपारदर्शिता। |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | r/w | लेयर के फीचर्स को रेंडर करने के लिए उपयोग किया जाने वाला सिम्बोलाइज़र। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [import_sld(path, options)](#import_sld_path_options_1) | निर्दिष्ट पथ पर स्थित Styled Layer Descriptor फ़ाइल से स्टाइल आयात करता है। |
| [import_sld(path, options)](#import_sld_path_options_2) | निर्दिष्ट पथ पर स्थित Styled Layer Descriptor फ़ाइल से स्टाइल आयात करता है। |
| [import_sld_from_string(sld, options)](#import_sld_from_string_sld_options_3) | निर्दिष्ट Styled Layer Descriptor स्ट्रिंग से स्टाइल आयात करता है। |


### Constructor: VectorMapLayer(features_sequence) {#VectorMapLayer_features_sequence_1}


```
 VectorMapLayer(features_sequence) 
```

डिफ़ॉल्ट सिम्बोलाइज़र के साथ नया इंस्टेंस बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | फ़ीचर अनुक्रम। |

### Constructor: VectorMapLayer(features_sequence, symbolizer) {#VectorMapLayer_features_sequence_symbolizer_2}


```
 VectorMapLayer(features_sequence, symbolizer) 
```

डिफ़ॉल्ट सिम्बोलाइज़र के साथ नया इंस्टेंस बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | फ़ीचर अनुक्रम। |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | लेयर को रेंडर करने के लिए उपयोग किया जाने वाला सिम्बोलाइज़र। यदि <see langword=\"null\" />, तो डिफ़ॉल्ट सिम्बोलाइज़र उपयोग किया जाएगा। |

### Constructor: VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) {#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3}


```
 VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) 
```

डिफ़ॉल्ट सिम्बोलाइज़र के साथ नया इंस्टेंस बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | फ़ीचर अनुक्रम। |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | लेयर को रेंडर करने के लिए उपयोग किया जाने वाला सिम्बोलाइज़र। यदि <see langword=\"null\" />, तो डिफ़ॉल्ट सिम्बोलाइज़र उपयोग किया जाएगा। |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | लेयर में फीचर्स को लेबल करने के लिए उपयोग किया जाने वाला लेबलिंग। यदि <see langword=\"null\" />, तो डिफ़ॉल्ट [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) उपयोग किया जाएगा। |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | यदि स्रोत स्पैशियल रेफ़रेंस (लेयर\\सीक्वेंस) अनुपलब्ध है तो उसके लिए मान निर्दिष्ट करता है। डिफ़ॉल्ट null उपयोग किया जाएगा। |

### Constructor: VectorMapLayer(layer, keep_open) {#VectorMapLayer_layer_keep_open_4}


```
 VectorMapLayer(layer, keep_open) 
```

डिफ़ॉल्ट सिम्बोलाइज़र के साथ नया इंस्टेंस बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | वेक्टर लेयर। |
| keep_open | bool | <see langword=\"true\" /> लेयर को खुला रखने के लिए जब [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) ऑब्जेक्ट नष्ट हो जाए; अन्यथा, <see langword=\"false\" />। |

### Constructor: VectorMapLayer(layer, symbolizer, keep_open) {#VectorMapLayer_layer_symbolizer_keep_open_5}


```
 VectorMapLayer(layer, symbolizer, keep_open) 
```

नया इंस्टेंस बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | वेक्टर लेयर। |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | लेयर को रेंडर करने के लिए उपयोग किया जाने वाला सिम्बोलाइज़र। यदि <see langword=\"null\" />, तो डिफ़ॉल्ट सिम्बोलाइज़र उपयोग किया जाएगा। |
| keep_open | bool | <see langword=\"true\" /> लेयर को खुला रखने के लिए जब [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) ऑब्जेक्ट नष्ट हो जाए; अन्यथा, <see langword=\"false\" />। |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6}


```
 VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

नया इंस्टेंस बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | वेक्टर लेयर। |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | लेयर को रेंडर करने के लिए उपयोग किया जाने वाला सिम्बोलाइज़र। यदि <see langword=\"null\" />, तो डिफ़ॉल्ट सिम्बोलाइज़र उपयोग किया जाएगा। |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | लेयर में फीचर्स को लेबल करने के लिए उपयोग किया जाने वाला लेबलिंग। यदि <see langword=\"null\" />, तो डिफ़ॉल्ट [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) उपयोग किया जाएगा। |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | यदि स्रोत स्पैशियल रेफ़रेंस (लेयर\\सीक्वेंस) अनुपलब्ध है तो उसके लिए मान निर्दिष्ट करता है। डिफ़ॉल्ट null उपयोग किया जाएगा। |
| keep_open | bool | <see langword=\"true\" /> लेयर को खुला रखने के लिए जब [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) ऑब्जेक्ट नष्ट हो जाए; अन्यथा, <see langword=\"false\" />। |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_keep_open_7}


```
 VectorMapLayer(layer, symbolizer, labeling, keep_open) 
```

नया इंस्टेंस बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | वेक्टर लेयर। |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | लेयर को रेंडर करने के लिए उपयोग किया जाने वाला सिम्बोलाइज़र। यदि <see langword=\"null\" />, तो डिफ़ॉल्ट सिम्बोलाइज़र उपयोग किया जाएगा। |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | लेयर में फीचर्स को लेबल करने के लिए उपयोग किया जाने वाला लेबलिंग। यदि <see langword=\"null\" />, तो डिफ़ॉल्ट [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) उपयोग किया जाएगा। |
| keep_open | bool | <see langword=\"true\" /> लेयर को खुला रखने के लिए जब [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) ऑब्जेक्ट नष्ट हो जाए; अन्यथा, <see langword=\"false\" />। |

### Method: import_sld(path, options) {#import_sld_path_options_1}


```
 import_sld(path, options) 
```

निर्दिष्ट पथ पर स्थित Styled Layer Descriptor फ़ाइल से स्टाइल आयात करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | Styled Layer Descriptor फ़ाइल का पथ। |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | आयात विकल्प। |

### Method: import_sld(path, options) {#import_sld_path_options_2}


```
 import_sld(path, options) 
```

निर्दिष्ट पथ पर स्थित Styled Layer Descriptor फ़ाइल से स्टाइल आयात करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Styled Layer Descriptor फ़ाइल का पथ। |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | आयात विकल्प। |

### Method: import_sld_from_string(sld, options) {#import_sld_from_string_sld_options_3}


```
 import_sld_from_string(sld, options) 
```

निर्दिष्ट Styled Layer Descriptor स्ट्रिंग से स्टाइल आयात करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| sld | string | स्टाइल्ड लेयर डिस्क्रिप्टर। |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | आयात विकल्प। |

