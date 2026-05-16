---
title: "IMultiSurface क्लास"
type: docs
weight: 190
url: /hi/python-net/aspose.gis.geometries/imultisurface/
---

**Summary:** A [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/) is a one-dimensional [IGeometryCollection](/psd/python-net/aspose.gis.geometries/igeometrycollection/) whose elements are [ISurface](/psd/python-net/aspose.gis.geometries/isurface/)s.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.IMultiSurface

**Inheritance:** IGeometryCollection, IGeometry

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| गिनती | इंट | r | इस संग्रह में ज्यामितियों की संख्या प्राप्त करता है। |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | इस [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) का टोपोलॉजिकल आयाम प्राप्त करता है।<br/>            यदि आयाम अज्ञात है (जैसे कि खाली GEOMETRYCOLLECTION के लिए) [GeometryDimension.POINT](/psd/python-net/aspose.gis.geometries/geometrydimension/) लौटाया जाता है। |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | ज्यामिति का प्रकार प्राप्त करता है। |
| has_curve_geometry | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि यह ज्यामिति वक्र (रेखीय नहीं) ज्यामिति है या इसमें वक्र ज्यामिति शामिल है। |
| has_m | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि इस उदाहरण में M निर्देशांक है या नहीं। |
| has_z | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि इस उदाहरण में Z निर्देशांक है या नहीं। |
| is_empty | bool | r | यह मान प्राप्त करता है जो दर्शाता है कि यह इंस्टेंस खाली है (खाली बिंदु सेट का प्रतिनिधित्व करता है)। |
| is_simple | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि यह उदाहरण SFA के दृष्टिकोण से सरल है या नहीं। |
| is_valid | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि यह उदाहरण वैध है या नहीं। |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | इस इंस्टेंस का SpatialReferenceSystem प्राप्त करता है।<br/>            यदि SpatialReferenceSystem अज्ञात है तो यह प्रॉपर्टी <see langword="null" /> हो सकती है। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [as_binary()](#as_binary__1) | इस ज्यामिति को उसके Well-Known Binary प्रतिनिधित्व में परिवर्तित करता है। |
| [as_binary(variant)](#as_binary_variant_2) | इस ज्यामिति को उसके Well-Known Binary प्रतिनिधित्व में परिवर्तित करता है। |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_3) | इस ज्यामिति को छवि प्रतिनिधित्व में निर्यात करता है। |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_4) | इस ज्यामिति को छवि प्रतिनिधित्व में निर्यात करता है। |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_5) | इस ज्यामिति को छवि प्रतिनिधित्व में निर्यात करता है। |
| [as_text()](#as_text__6) | इस ज्यामिति को उसके Well-Known Text प्रतिनिधित्व में परिवर्तित करता है। |
| [as_text(variant)](#as_text_variant_7) | इस ज्यामिति को उसके Well-Known Text प्रतिनिधित्व में परिवर्तित करता है। |
| [as_text(variant, format)](#as_text_variant_format_8) | इस ज्यामिति को उसके Well-Known Text प्रतिनिधित्व में परिवर्तित करता है। |
| [clone()](#clone__9) | इस उदाहरण की प्रतिलिपि बनाता है। |
| [covered_by(other)](#covered_by_other_10) | निर्धारित करता है कि यह ज्यामिति निर्दिष्ट ज्यामिति द्वारा कवर की गई है या नहीं। |
| [covers(other)](#covers_other_11) | निर्धारित करता है कि यह ज्यामिति निर्दिष्ट ज्यामिति को कवर करती है या नहीं। |
| [crosses(other)](#crosses_other_12) | निर्धारित करता है कि यह ज्यामिति और निर्दिष्ट ज्यामिति क्रॉस करती हैं। |
| [difference(other)](#difference_other_13) | इस ज्यामिति से निर्दिष्ट ज्यामिति घटाता है। |
| [disjoint(other)](#disjoint_other_14) | निर्धारित करता है कि यह ज्यामिति निर्दिष्ट ज्यामिति से अलग है। |
| [get_area()](#get_area__15) | इस ज्यामिति का क्षेत्रफल गणना करता है। |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_16) | इस ज्यामिति के चारों ओर एक बफ़र क्षेत्र गणना करता है। |
| [get_centroid()](#get_centroid__17) | इस ज्यामिति का केंद्रबिंदु गणना करता है। |
| [get_convex_hull()](#get_convex_hull__18) | इस ज्यामिति का कॉन्वेक्स हुल गणना करता है। |
| [get_distance_to(other)](#get_distance_to_other_19) | इस ज्यामिति और निर्दिष्ट ज्यामिति के बीच न्यूनतम दूरी गणना करता है। |
| [get_extent()](#get_extent__20) | इस ज्यामिति का बाउंडिंग विस्तार गणना करता है और लौटाता है। |
| [get_length()](#get_length__21) | इस ज्यामिति की लंबाई गणना करता है। |
| [get_point_on_surface()](#get_point_on_surface__22) | इस संग्रह में सतहों में से किसी एक पर स्थित होने की गारंटी वाला बिंदु खोजता है। |
| [intersection(other)](#intersection_other_23) | इस ज्यामिति और निर्दिष्ट ज्यामिति के बीच प्रतिच्छेदन बनाता है। |
| [intersects(extent)](#intersects_extent_24) | निर्धारित करता है कि यह ज्यामिति निर्दिष्ट विस्तार को प्रतिच्छेद करती है या नहीं। |
| [intersects(other)](#intersects_other_25) | निर्धारित करता है कि यह ज्यामिति और निर्दिष्ट ज्यामिति प्रतिच्छेद करती हैं या नहीं। |
| [overlaps(other)](#overlaps_other_26) | निर्धारित करता है कि यह ज्यामिति निर्दिष्ट ज्यामिति के साथ ओवरलैप करती है या नहीं। |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_27) | निर्धारित करता है कि इस ज्यामिति और निर्दिष्ट ज्यामिति का DE-9IM प्रतिच्छेद मैट्रिक्स प्रदान किए गए पैटर्न से मेल खाता है या नहीं। |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__28) | इस ज्यामिति की रेखाओं के रूप में प्रतिनिधित्व किए गए बहुभुज प्राप्त करता है। |
| [spatially_contains(other)](#spatially_contains_other_29) | निर्धारित करता है कि यह ज्यामिति स्थानिक रूप से निर्दिष्ट ज्यामिति को शामिल करती है या नहीं। |
| [spatially_equals(other)](#spatially_equals_other_30) | निर्धारित करता है कि यह ज्यामिति स्थानिक रूप से निर्दिष्ट ज्यामिति के बराबर है या नहीं। |
| [sym_difference(other)](#sym_difference_other_31) | इस ज्यामिति और निर्दिष्ट ज्यामिति के बीच सममित अंतर बनाता है। |
| [to_editable()](#to_editable__32) | इस ज्यामिति की एक संपादन योग्य प्रति प्राप्त करता है। |
| [to_linear_geometry()](#to_linear_geometry__33) | डिफ़ॉल्ट <c>tolerance</c> का उपयोग करके इस ज्यामिति का अनुमानित या समतुल्य गैर-वक्र संस्करण प्राप्त करता है। |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_34) | निर्दिष्ट <c>tolerance</c> का उपयोग करके इस ज्यामिति का अनुमानित या समतुल्य गैर-वक्र संस्करण प्राप्त करता है। |
| [touches(other)](#touches_other_35) | निर्धारित करता है कि यह ज्यामिति और निर्दिष्ट ज्यामिति स्पर्श करती हैं या नहीं। |
| [union(other)](#union_other_36) | इस ज्यामिति और निर्दिष्ट ज्यामिति को मिलाता है। |
| [union(other)](#union_other_37) | इस ज्यामिति और निर्दिष्ट ज्यामिति को मिलाता है। |
| [within(extent)](#within_extent_38) | निर्धारित करता है कि यह ज्यामिति निर्दिष्ट सीमा के भीतर है या नहीं। |
| [within(other)](#within_other_39) | निर्धारित करता है कि यह ज्यामिति निर्दिष्ट ज्यामिति के भीतर है या नहीं। |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

इस ज्यामिति को उसके Well-Known Binary प्रतिनिधित्व में परिवर्तित करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| byte | इस ज्यामिति का Well-Known Binary प्रतिनिधित्व। |


### Method: as_binary(variant) {#as_binary_variant_2}


```
 as_binary(variant) 
```

इस ज्यामिति को उसके Well-Known Binary प्रतिनिधित्व में परिवर्तित करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| variant | [WkbVariant](/psd/python-net/aspose.gis.geometries/wkbvariant) | उपयोग करने के लिए Well-Known Binary वैरिएंट। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| byte | इस ज्यामिति का Well-Known Binary प्रतिनिधित्व। |


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_3}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

इस ज्यामिति को छवि प्रतिनिधित्व में निर्यात करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | आउटपुट छवि का पथ। |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | मानचित्र की चौड़ाई। |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | मानचित्र की ऊँचाई। |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | उपयोग करने के लिए रेंडरर। |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | रेंडरिंग के लिए उपयोग करने वाला एक सिम्बोलाइज़र। यदि <see langword=\"null\" />, तो डिफ़ॉल्ट सिम्बोलाइज़र उपयोग किया जाता है। |

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_4}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

इस ज्यामिति को छवि प्रतिनिधित्व में निर्यात करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| output_path | string | आउटपुट छवि का पथ। |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | मानचित्र की चौड़ाई। |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | मानचित्र की ऊँचाई। |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | उपयोग करने के लिए रेंडरर। |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | रेंडरिंग के लिए उपयोग करने वाला एक सिम्बोलाइज़र। यदि <see langword=\"null\" />, तो डिफ़ॉल्ट सिम्बोलाइज़र उपयोग किया जाता है। |

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_5}


```
 as_image(width, height, renderer, symbolizer) 
```

इस ज्यामिति को छवि प्रतिनिधित्व में निर्यात करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | मानचित्र की चौड़ाई। |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | मानचित्र की ऊँचाई। |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | उपयोग करने के लिए रेंडरर। |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | रेंडरिंग के लिए उपयोग करने वाला एक सिम्बोलाइज़र। यदि <see langword=\"null\" />, तो डिफ़ॉल्ट सिम्बोलाइज़र उपयोग किया जाता है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| _io.BufferedRandom | छवि को स्ट्रीम के रूप में |


### Method: as_text() {#as_text__6}


```
 as_text() 
```

इस ज्यामिति को उसके Well-Known Text प्रतिनिधित्व में परिवर्तित करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | इस ज्यामिति का Well-Known Text प्रतिनिधित्व। |


### Method: as_text(variant) {#as_text_variant_7}


```
 as_text(variant) 
```

इस ज्यामिति को उसके Well-Known Text प्रतिनिधित्व में परिवर्तित करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | उपयोग करने के लिए Well-Known Text वैरिएंट। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | इस ज्यामिति का Well-Known Text प्रतिनिधित्व। |


### Method: as_text(variant, format) {#as_text_variant_format_8}


```
 as_text(variant, format) 
```

इस ज्यामिति को उसके Well-Known Text प्रतिनिधित्व में परिवर्तित करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | उपयोग करने के लिए Well-Known Text वैरिएंट। |
| format | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | स्ट्रिंग में रूपांतरण के लिए समन्वय स्वरूप। इसे प्राप्त करने के लिए [NumericFormat](/psd/python-net/aspose.gis/numericformat/) देखें। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | इस ज्यामिति का Well-Known Text प्रतिनिधित्व। |


### Method: clone() {#clone__9}


```
 clone() 
```

इस उदाहरण की प्रतिलिपि बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | इस इंस्टेंस की क्लोन |


### Method: covered_by(other) {#covered_by_other_10}


```
 covered_by(other) 
```

निर्धारित करता है कि यह ज्यामिति निर्दिष्ट ज्यामिति द्वारा कवर की गई है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | एक ज्यामिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <see langword=\"true\" /> यदि यह ज्यामिति किसी अन्य ज्यामिति द्वारा \"स्थानिक रूप से कवर\" की गई है। अन्यथा <see langword=\"false\" />। |


### Method: covers(other) {#covers_other_11}


```
 covers(other) 
```

निर्धारित करता है कि यह ज्यामिति निर्दिष्ट ज्यामिति को कवर करती है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | एक ज्यामिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <see langword=\"true\" /> यदि यह ज्यामिति किसी अन्य ज्यामिति को \"स्थानिक रूप से कवर\" करती है। अन्यथा <see langword=\"false\" />। |


### Method: crosses(other) {#crosses_other_12}


```
 crosses(other) 
```

निर्धारित करता है कि यह ज्यामिति और निर्दिष्ट ज्यामिति क्रॉस करती हैं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | एक ज्यामिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <see langword=\"true\" /> यदि यह ज्यामिति किसी अन्य ज्यामिति को \"स्थानिक रूप से क्रॉस\" करती है। अन्यथा <see langword=\"false\" />। |


### Method: difference(other) {#difference_other_13}


```
 difference(other) 
```

इस ज्यामिति से निर्दिष्ट ज्यामिति घटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | घटाने के लिए एक ज्यामिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | यह ज्यामिति और एक तर्क के अंतर को दर्शाने वाली एक ज्यामिति। परिणामस्वरूप ज्यामिति में<br/>            वह बिंदु सेट शामिल है जो इस ज्यामिति में मौजूद है लेकिन तर्क में नहीं है। |


### Method: disjoint(other) {#disjoint_other_14}


```
 disjoint(other) 
```

निर्धारित करता है कि यह ज्यामिति निर्दिष्ट ज्यामिति से अलग है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | एक ज्यामिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <see langword=\"true\" /> यदि यह ज्यामिति किसी अन्य ज्यामिति से "स्थानिक रूप से अलग" है। <see langword=\"false\" /> अन्यथा। |


### Method: get_area() {#get_area__15}


```
 get_area() 
```

इस ज्यामिति का क्षेत्रफल गणना करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| double | इस ज्यामिति का क्षेत्रफल।<br/>            यदि यह ज्यामिति एक [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/) है तो इस ज्यामिति के तत्वों के क्षेत्रों का योग। |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_16}


```
 get_buffer(distance, quadrant_segments) 
```

इस ज्यामिति के चारों ओर एक बफ़र क्षेत्र गणना करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| दूरी | double | बफ़र क्षेत्र की चौड़ाई (Spatial Reference इकाइयों में)। |
| quadrant_segments | इंट | वक्रता के 90 डिग्री को अनुमानित करने के लिए उपयोग किए जाने वाले खंडों की संख्या।<br/>            यह संख्या जितनी बड़ी होगी, वक्रों का अनुमान उतना ही बेहतर होगा।<br/>            डिफ़ॉल्ट 30 है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | एक ज्यामिति जो निर्दिष्ट दूरी के भीतर इस ज्यामिति से सभी बिंदुओं को दर्शाती है।<br/>            परिणाम का प्रकार या तो [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/), [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) या [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/) हो सकता है। |


### Method: get_centroid() {#get_centroid__17}


```
 get_centroid() 
```

इस ज्यामिति का केंद्रबिंदु गणना करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | इस ज्यामिति का केंद्रबिंदु। यदि यह ज्यामिति खाली है तो एक खाली बिंदु लौटाया जाता है।<br/>            केंद्रबिंदु इस ज्यामिति में सबसे उच्च आयाम वाली ज्यामितियों के केंद्रबिंदु के बराबर होता है<br/>            (उदाहरण के लिए, यदि ज्यामिति में बिंदु और रेखाएँ दोनों हैं, तो केवल रेखाएँ ही केंद्रबिंदु में योगदान देती हैं)। |


### Method: get_convex_hull() {#get_convex_hull__18}


```
 get_convex_hull() 
```

इस ज्यामिति का कॉन्वेक्स हुल गणना करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | इस ज्यामिति का कॉन्वेक्स हुल दर्शाने वाली एक ज्यामिति।<br/>            यदि इस ज्यामिति में कोई बिंदु नहीं है तो परिणाम [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/) होगा।<br/>            यदि इस ज्यामिति में केवल एक बिंदु है तो परिणाम वह बिंदु होगा।<br/>            यदि इस ज्यामिति में केवल दो बिंदु हैं तो परिणाम बिंदुओं के साथ [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) होगा।<br/>            यदि इस ज्यामिति में तीन या अधिक बिंदु हैं तो परिणाम [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/) होगा जो सभी ज्यामितियों के बिंदुओं के चारों ओर एक कॉन्वेक्स<br/>            हुल दर्शाता है। |


### Method: get_distance_to(other) {#get_distance_to_other_19}


```
 get_distance_to(other) 
```

इस ज्यामिति और निर्दिष्ट ज्यामिति के बीच न्यूनतम दूरी गणना करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | दूरी खोजने के लिए एक ज्यामिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| double | यदि दोनों ज्यामितियां [IGeometry.is_empty](/psd/python-net/aspose.gis.geometries/igeometry/) नहीं हैं - तो ज्यामितियों के निकटतम बिंदुओं के बीच की दूरी।<br/>            यदि कम से कम एक ज्यामिति खाली है तो -1 लौटाया जाता है। |


### Method: get_extent() {#get_extent__20}


```
 get_extent() 
```

इस ज्यामिति का बाउंडिंग विस्तार गणना करता है और लौटाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | इस ज्यामिति का बाउंडिंग विस्तार। |


### Method: get_length() {#get_length__21}


```
 get_length() 
```

इस ज्यामिति की लंबाई गणना करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| double | इस ज्यामिति की लंबाई।<br/>            यदि यह एक [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) है तो परिमाप।<br/>            यदि यह एक [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/) है तो इस ज्यामिति के तत्वों की लंबाइयों का योग। |


### Method: get_point_on_surface() {#get_point_on_surface__22}


```
 get_point_on_surface() 
```

इस संग्रह में सतहों में से किसी एक पर स्थित होने की गारंटी वाला बिंदु खोजता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | सतहों में से किसी एक पर बिंदु। यदि इस संग्रह में सतहें नहीं हैं या सभी सतहें खाली हैं तो एक खाली बिंदु। |


### Method: intersection(other) {#intersection_other_23}


```
 intersection(other) 
```

इस ज्यामिति और निर्दिष्ट ज्यामिति के बीच प्रतिच्छेदन बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | छेदन गणना करने के लिए एक ज्यामिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | एक ज्यामिति जो इस ज्यामिति और एक तर्क के छेदन को दर्शाती है। परिणामस्वरूप ज्यामिति में<br/>            वह बिंदु सेट शामिल है जो इस ज्यामिति और तर्क दोनों में मौजूद है। |


### Method: intersects(extent) {#intersects_extent_24}


```
 intersects(extent) 
```

निर्धारित करता है कि यह ज्यामिति निर्दिष्ट विस्तार को प्रतिच्छेद करती है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | विस्तार। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <see langword=\"true\" /> यदि यह ज्यामिति सीमा को प्रतिच्छेद करती है; <see langword=\"false\" /> अन्यथा. |


### Method: intersects(other) {#intersects_other_25}


```
 intersects(other) 
```

निर्धारित करता है कि यह ज्यामिति और निर्दिष्ट ज्यामिति प्रतिच्छेद करती हैं या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | एक ज्यामिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <see langword=\"true\" /> यदि यह ज्यामिति \"स्थानिक रूप से प्रतिच्छेद\" करती है किसी अन्य ज्यामिति को। <see langword=\"false\" /> अन्यथा. |


### Method: overlaps(other) {#overlaps_other_26}


```
 overlaps(other) 
```

निर्धारित करता है कि यह ज्यामिति निर्दिष्ट ज्यामिति के साथ ओवरलैप करती है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | एक ज्यामिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <see langword=\"true\" /> यदि यह ज्यामिति \"स्थानिक रूप से ओवरलैप\" करती है किसी अन्य ज्यामिति को। <see langword=\"false\" /> अन्यथा. |


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_27}


```
 relate(other, intersection_pattern_matrix) 
```

निर्धारित करता है कि इस ज्यामिति और निर्दिष्ट ज्यामिति का DE-9IM प्रतिच्छेद मैट्रिक्स प्रदान किए गए पैटर्न से मेल खाता है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | एक ज्यामिति। |
| intersection_pattern_matrix | string | मैच करने के लिए एक पैटर्न।<br/>            यह 9 अक्षरों की लंबाई वाली स्ट्रिंग होनी चाहिए।<br/>            स्ट्रिंग का प्रत्येक अक्षर प्रतिच्छेद के अपेक्षित आयाम को दर्शाता है:<br/>            <ul><br/>            <li>अक्षर 0 - ज्यामितियों के आंतरिक भागों के बीच।</li><br/>            <li>अक्षर 1 - इस ज्यामिति के आंतरिक भाग और किसी अन्य ज्यामिति की सीमा के बीच।</li><br/>            <li>अक्षर 2 - इस ज्यामिति के आंतरिक भाग और किसी अन्य ज्यामिति के बाहरी भाग के बीच।</li><br/>            <li>अक्षर 3 - इस ज्यामिति की सीमा और किसी अन्य ज्यामिति के आंतरिक भाग के बीच।</li><br/>            <li>अक्षर 4 - दोनों ज्यामितियों की सीमाओं के बीच।</li><br/>            <li>अक्षर 5 - इस ज्यामिति की सीमा और किसी अन्य ज्यामिति के बाहरी भाग के बीच।</li><br/>            <li>अक्षर 6 - इस ज्यामिति के बाहरी भाग और किसी अन्य ज्यामिति के आंतरिक भाग के बीच।</li><br/>            <li>अक्षर 7 - इस ज्यामिति के बाहरी भाग और किसी अन्य ज्यामिति की सीमा के बीच।</li><br/>            <li>अक्षर 8 - दोनों ज्यामितियों के बाहरी भागों के बीच।</li><br/>            </ul><br/>            प्रत्येक अक्षर के संभावित मान हैं:<br/>            <ul><br/>            <li>* - कोई भी मान;</li><br/>            <li>F - कोई प्रतिच्छेद नहीं;</li><br/>            <li>T - कोई भी प्रतिच्छेद;</li><br/>            <li>0 - बिंदु प्रतिच्छेद (उदा. साझा बिंदु);</li><br/>            <li>1 - रेखा प्रतिच्छेद (उदा. साझा रेखा खंड);</li><br/>            <li>2 - क्षेत्र प्रतिच्छेद (उदा. साझा बहुभुज भाग);</li><br/>            </ul><br/>            उदाहरण के लिए, \"F0*******\" प्रतिच्छेद पैटर्न का अर्थ है कि ज्यामितियों के आंतरिक भागों के बीच कोई प्रतिच्छेद नहीं होना चाहिए और सीमाओं के बीच का प्रतिच्छेद बिंदु होना चाहिए।<br/>            अधिक विवरण के लिए OpenGIS Simple Features Specification देखें कि प्रतिच्छेद मैट्रिक्स पैटर्न क्या है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <see langword=\"true\" /> यदि यह प्रतिच्छेद मैट्रिक्स पैटर्न से मेल खाता है; <see langword=\"false\" /> अन्यथा. |


### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__28}


```
 replace_polygons_by_lines() 
```

इस ज्यामिति की रेखाओं के रूप में प्रतिनिधित्व किए गए बहुभुज प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IGeometryCollection](/psd/python-net/aspose.gis.geometries/igeometrycollection) | एक ज्यामिति, जिसमें कोई बहुभुज ज्यामिति नहीं है। निम्नलिखित रूपांतरण लागू किए जाते हैं:<br/>            <ul><br/>            <li> [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) को रैखिक किया जाता है (जिसे [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/) में बदला जाता है)</li><br/>            <li>[GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) को [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/) में जोड़ा जाता है</li><br/>            </ul> |


### Method: spatially_contains(other) {#spatially_contains_other_29}


```
 spatially_contains(other) 
```

निर्धारित करता है कि यह ज्यामिति स्थानिक रूप से निर्दिष्ट ज्यामिति को शामिल करती है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | एक ज्यामिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <see langword=\"true\" /> यदि यह ज्यामिति किसी अन्य ज्यामिति को \"स्थानिक रूप से सम्मिलित\" करती है। <see langword=\"false\" /> अन्यथा. |


### Method: spatially_equals(other) {#spatially_equals_other_30}


```
 spatially_equals(other) 
```

निर्धारित करता है कि यह ज्यामिति स्थानिक रूप से निर्दिष्ट ज्यामिति के बराबर है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | एक ज्यामिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <see langword=\"true\" /> यदि यह ज्यामिति निर्दिष्ट ज्यामिति के \"स्थानिक रूप से समान\" है। <see langword=\"false\" /> अन्यथा. |


### Method: sym_difference(other) {#sym_difference_other_31}


```
 sym_difference(other) 
```

इस ज्यामिति और निर्दिष्ट ज्यामिति के बीच सममित अंतर बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | एक ज्यामिति जिसके साथ सममित अंतर की गणना की जाएगी। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | एक ज्यामिति जो इस ज्यामिति और एक तर्क के सममित अंतर को दर्शाती है। परिणामस्वरूप ज्यामिति में<br/>            बिंदु सेट होता है जो किसी एक ज्यामिति में मौजूद है लेकिन दोनों में नहीं। |


### Method: to_editable() {#to_editable__32}


```
 to_editable() 
```

इस ज्यामिति की एक संपादन योग्य प्रति प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [MultiSurface](/psd/python-net/aspose.gis.geometries/multisurface) | इस ज्यामिति की एक संपादन योग्य प्रति। |


### Method: to_linear_geometry() {#to_linear_geometry__33}


```
 to_linear_geometry() 
```

डिफ़ॉल्ट <c>tolerance</c> का उपयोग करके इस ज्यामिति का अनुमानित या समतुल्य गैर-वक्र संस्करण प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon) | एक [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/) जो इस [IMultiSurface](/psd/python-net/aspose.gis.geometries/imultisurface/) के समान या समतुल्य है।<br/> यह <DOM Element: class at 0x2a1792e8790>.IMultiSurface.to_linear_geometry()(float) के बराबर है, डिफ़ॉल्ट <c>tolerance</c> के साथ। डिफ़ॉल्ट <c>tolerance</c> का मान इस ज्यामिति के [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) पर निर्भर करता है:<br/><ul><br/><li> प्रोजेक्टेड SRS के लिए टॉलरेंस 0.001 मीटर (SRS इकाइयों में) </li><br/><li> जियोग्राफिक SRS के लिए टॉलरेंस <c>1e-5</c> डिग्री (SRS इकाइयों में) </li><br/><li> अज्ञात SRS के लिए टॉलरेंस <c>1e-5</c> </li><br/></ul><br/> लागू किए गए रूपांतरणों के बारे में अधिक विवरण के लिए <DOM Element: class at 0x2a1792e8790>.IMultiSurface.to_linear_geometry()(float) विनिर्देशन देखें। |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_34}


```
 to_linear_geometry(tolerance) 
```

निर्दिष्ट <c>tolerance</c> का उपयोग करके इस ज्यामिति का अनुमानित या समतुल्य गैर-वक्र संस्करण प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| टॉलरेंस | double | उपयोग करने के लिए <c>tolerance</c>। परिणाम यह सुनिश्चित करता है कि यह <c>tolerance</c> से कम दूरी पर हो वक्रित ज्यामिति से,<br/>             जब तक कि ज्यामिति को रैखिक करने के लिए आवश्यक बिंदुओं की संख्या प्रति-चतुर्थांश अधिकतम, जो वर्तमान में 10000 बिंदु है, से अधिक न हो। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon) | एक [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/) जो इस [IMultiSurface](/psd/python-net/aspose.gis.geometries/imultisurface/) के समान या समतुल्य है:<br/><ul><br/> यदि यह ऑब्जेक्ट स्वयं एक [IMultiPolygon] है तो परिणाम इस ऑब्जेक्ट के बराबर है<br/> यदि यह ऑब्जेक्ट एक [IMultiPolygon] नहीं है - सभी सतहों को रैखिक किया जाता है और नया <c>IMultiPolygon</c> बनाया जाता है<br/></ul> |


### Method: touches(other) {#touches_other_35}


```
 touches(other) 
```

निर्धारित करता है कि यह ज्यामिति और निर्दिष्ट ज्यामिति स्पर्श करती हैं या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | एक ज्यामिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <see langword=\"true\" /> यदि यह ज्यामिति किसी अन्य ज्यामिति को \"स्थानिक रूप से स्पर्श\" करती है। <see langword=\"false\" /> अन्यथा. |


### Method: union(other) {#union_other_36}


```
 union(other) 
```

इस ज्यामिति और निर्दिष्ट ज्यामिति को मिलाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | एक ज्यामिति जिसके साथ मिलाया जाएगा। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | एक ज्यामिति जो इस ज्यामिति और एक तर्क के संघ को दर्शाती है। परिणामस्वरूप ज्यामिति में<br/>            बिंदु सेट होता है जो इस ज्यामिति में या तर्क में मौजूद है। |


### Method: union(other) {#union_other_37}


```
 union(other) 
```

इस ज्यामिति और निर्दिष्ट ज्यामिति को मिलाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| other | [IGeometry[]](/psd/python-net/aspose.gis.geometries/igeometry) | एक ज्यामिति जिसके साथ मिलाया जाएगा। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | एक ज्यामिति जो इस ज्यामिति और एक तर्क के संघ को दर्शाती है। परिणामस्वरूप ज्यामिति में<br/>            बिंदु सेट होता है जो इस ज्यामिति में या तर्क में मौजूद है। |


### Method: within(extent) {#within_extent_38}


```
 within(extent) 
```

निर्धारित करता है कि यह ज्यामिति निर्दिष्ट सीमा के भीतर है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | विस्तार। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <see langword=\"true\" /> यदि यह ज्यामिति सीमा के भीतर है; <see langword=\"false\" /> अन्यथा. |


### Method: within(other) {#within_other_39}


```
 within(other) 
```

निर्धारित करता है कि यह ज्यामिति निर्दिष्ट ज्यामिति के भीतर है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | एक ज्यामिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <see langword=\"true\" /> यदि यह ज्यामिति किसी अन्य ज्यामिति के \"स्थानिक रूप से भीतर\" है। <see langword=\"false\" /> अन्यथा. |


