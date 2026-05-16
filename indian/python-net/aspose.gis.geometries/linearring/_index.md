---
title: "LinearRing क्लास"
type: docs
weight: 240
url: /hi/python-net/aspose.gis.geometries/linearring/
---

**Summary:** A [LinearRing](/psd/python-net/aspose.gis.geometries/linearring/) is a [LineString](/psd/python-net/aspose.gis.geometries/linestring/) that is both closed and simple.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.LinearRing

**Inheritance:** IGeometry, ICurve, ILineString, ILinearRing, LineString

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [LinearRing()](#LinearRing__1) | [LinearRing](/psd/python-net/aspose.gis.geometries/linearring/) क्लास का नया उदाहरण प्रारंभ करता है। |
| [LinearRing(collection)](#LinearRing_collection_2) | [LinearRing](/psd/python-net/aspose.gis.geometries/linearring/) क्लास का नया उदाहरण प्रारंभ करता है। |
| [LinearRing(other)](#LinearRing_other_3) | [LinearRing](/psd/python-net/aspose.gis.geometries/linearring/) क्लास का नया उदाहरण प्रारंभ करता है। |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| coordinate_dimension | int | r | इस [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) के लिए निर्देशांक आयामों की संख्या प्राप्त करता है। |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | इस [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) का टोपोलॉजिकल आयाम प्राप्त करता है।<br/>            यदि आयाम अज्ञात है (जैसे कि खाली GEOMETRYCOLLECTION के लिए) [GeometryDimension.POINT](/psd/python-net/aspose.gis.geometries/geometrydimension/) लौटाया जाता है। |
| end_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | वक्र के अंत बिंदु की एक प्रति लौटाता है। |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | ज्यामिति का प्रकार प्राप्त करता है। |
| has_curve_geometry | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि यह ज्यामिति वक्र (रेखीय नहीं) ज्यामिति है या इसमें वक्र ज्यामिति शामिल है। |
| has_m | bool | r/w | एक मान प्राप्त करता है जो दर्शाता है कि इस उदाहरण में M निर्देशांक है या नहीं। |
| has_z | bool | r/w | एक मान प्राप्त करता है जो दर्शाता है कि इस उदाहरण में Z निर्देशांक है या नहीं। |
| is_closed | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि वक्र बंद है या नहीं।<br/> एक वक्र तब बंद होता है जब उसका प्रारंभ बिंदु अंत बिंदु के बराबर हो। |
| is_empty | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि यह उदाहरण खाली है या नहीं। |
| is_simple | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि यह उदाहरण SFA के दृष्टिकोण से सरल है या नहीं। |
| is_valid | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि यह उदाहरण वैध है या नहीं। |
| null [static] | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | r | null ज्यामिति का एक उदाहरण प्राप्त करता है। |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | इस इंस्टेंस का SpatialReferenceSystem प्राप्त करता है।<br/> यह प्रॉपर्टी <see langword="null" /> हो सकती है, यदि SpatialReferenceSystem सेट नहीं है।<br/> नया SpatialReferenceSystem असाइन करने से कोई कोऑर्डिनेट ट्रांसफ़ॉर्मेशन नहीं होगा, केवल संदर्भ बदल जाएगा। |
| start_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | वक्र के प्रारंभ बिंदु की एक प्रति लौटाता है। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [add_point(point)](#add_point_point_1) | रेखा के अंत में एक बिंदु जोड़ता है। |
| [add_point(x, y)](#add_point_x_y_2) | रेखा के अंत में एक बिंदु जोड़ता है। |
| [add_point(x, y, z)](#add_point_x_y_z_3) | रेखा के अंत में एक बिंदु जोड़ता है। |
| [add_point(x, y, z, m)](#add_point_x_y_z_m_4) | रेखा के अंत में एक बिंदु जोड़ता है। |
| [as_binary()](#as_binary__5) | इस ज्यामिति को उसके Well-Known Binary प्रतिनिधित्व में परिवर्तित करता है। |
| [as_binary(variant)](#as_binary_variant_6) | इस ज्यामिति को उसके Well-Known Binary प्रतिनिधित्व में परिवर्तित करता है। |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_7) | इस ज्यामिति को छवि प्रतिनिधित्व में निर्यात करता है। |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_8) | इस ज्यामिति को छवि प्रतिनिधित्व में निर्यात करता है। |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_9) | इस ज्यामिति को छवि प्रतिनिधित्व में निर्यात करता है। |
| [as_text()](#as_text__10) | इस ज्यामिति को उसके Well-Known Text प्रतिनिधित्व में परिवर्तित करता है। |
| [as_text(variant)](#as_text_variant_11) | इस ज्यामिति को उसके Well-Known Text प्रतिनिधित्व में परिवर्तित करता है। |
| [as_text(variant, format)](#as_text_variant_format_12) | इस ज्यामिति को उसके Well-Known Text प्रतिनिधित्व में परिवर्तित करता है। |
| [clone()](#clone__13) | इस उदाहरण की प्रतिलिपि बनाता है। |
| [covered_by(other)](#covered_by_other_14) | निर्धारित करता है कि यह ज्यामिति निर्दिष्ट ज्यामिति द्वारा कवर की गई है या नहीं। |
| [covers(other)](#covers_other_15) | निर्धारित करता है कि यह ज्यामिति निर्दिष्ट ज्यामिति को कवर करती है या नहीं। |
| [crosses(other)](#crosses_other_16) | निर्धारित करता है कि यह ज्यामिति और निर्दिष्ट ज्यामिति क्रॉस करती हैं। |
| [difference(other)](#difference_other_17) | इस ज्यामिति से निर्दिष्ट ज्यामिति घटाता है। |
| [disjoint(other)](#disjoint_other_18) | निर्धारित करता है कि यह ज्यामिति निर्दिष्ट ज्यामिति से अलग है। |
| [from_binary(wkb)](#from_binary_wkb_19) | उसके Well-Known Binary प्रतिनिधित्व से एक ज्यामिति बनाता है। |
| [from_binary(wkb, spatial_reference_system)](#from_binary_wkb_spatial_reference_system_20) | उसके Well-Known Binary प्रतिनिधित्व से एक ज्यामिति बनाता है। |
| [from_text(wkt)](#from_text_wkt_21) | उसके Well-Known Text प्रतिनिधित्व से एक ज्यामिति बनाता है। |
| [from_text(wkt, spatial_reference_system)](#from_text_wkt_spatial_reference_system_22) | उसके Well-Known Text प्रतिनिधित्व से एक ज्यामिति बनाता है। |
| [get_area()](#get_area__23) | इस ज्यामिति का क्षेत्रफल गणना करता है। |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_24) | इस ज्यामिति के चारों ओर एक बफ़र क्षेत्र गणना करता है। |
| [get_centroid()](#get_centroid__25) | इस ज्यामिति का केंद्रबिंदु गणना करता है। |
| [get_convex_hull()](#get_convex_hull__26) | इस ज्यामिति का कॉन्वेक्स हुल गणना करता है। |
| [get_distance_to(other)](#get_distance_to_other_27) | इस ज्यामिति और निर्दिष्ट ज्यामिति के बीच न्यूनतम दूरी गणना करता है। |
| [get_extent()](#get_extent__28) | इस ज्यामिति का बाउंडिंग विस्तार गणना करता है और लौटाता है। |
| [get_length()](#get_length__29) | इस ज्यामिति की लंबाई गणना करता है। |
| [intersection(other)](#intersection_other_30) | इस ज्यामिति और निर्दिष्ट ज्यामिति के बीच प्रतिच्छेदन बनाता है। |
| [intersects(extent)](#intersects_extent_31) | निर्धारित करता है कि यह ज्यामिति निर्दिष्ट विस्तार को प्रतिच्छेद करती है या नहीं। |
| [intersects(other)](#intersects_other_32) | निर्धारित करता है कि यह ज्यामिति और निर्दिष्ट ज्यामिति प्रतिच्छेद करती हैं या नहीं। |
| [is_clockwise()](#is_clockwise__33) | निर्धारित करता है कि रिंग का घड़ी की दिशा में वाइंडिंग है। |
| [overlaps(other)](#overlaps_other_34) | निर्धारित करता है कि यह ज्यामिति निर्दिष्ट ज्यामिति के साथ ओवरलैप करती है या नहीं। |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_35) | निर्धारित करता है कि इस ज्यामिति और निर्दिष्ट ज्यामिति का DE-9IM प्रतिच्छेद मैट्रिक्स प्रदान किए गए पैटर्न से मेल खाता है या नहीं। |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__36) | इस ज्यामिति की रेखाओं के रूप में प्रतिनिधित्व किए गए बहुभुज प्राप्त करता है। |
| reverse() | इस [LineString](/psd/python-net/aspose.gis.geometries/linestring/) में बिंदुओं का क्रम उलटता है। |
| [round_m(digits)](#round_m_digits_37) | M निर्देशांक को निर्दिष्ट दशमलव अंकों की संख्या तक गोल करता है। |
| [round_xy(digits)](#round_xy_digits_38) | X और Y निर्देशांक को निर्दिष्ट दशमलव अंकों की संख्या तक गोल करता है। |
| [round_z(digits)](#round_z_digits_39) | Z निर्देशांक को निर्दिष्ट दशमलव अंकों की संख्या तक गोल करता है। |
| set_empty() | इस [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) को खाली बनाता है। |
| [spatially_contains(other)](#spatially_contains_other_40) | निर्धारित करता है कि यह ज्यामिति स्थानिक रूप से निर्दिष्ट ज्यामिति को शामिल करती है या नहीं। |
| [spatially_equals(other)](#spatially_equals_other_41) | निर्धारित करता है कि यह ज्यामिति स्थानिक रूप से निर्दिष्ट ज्यामिति के बराबर है या नहीं। |
| [sym_difference(other)](#sym_difference_other_42) | इस ज्यामिति और निर्दिष्ट ज्यामिति के बीच सममित अंतर बनाता है। |
| [to_editable()](#to_editable__43) | इस ज्यामिति की एक संपादन योग्य प्रति प्राप्त करता है। |
| [to_linear_geometry()](#to_linear_geometry__44) | डिफ़ॉल्ट <c>tolerance</c> का उपयोग करके इस ज्यामिति का अनुमानित या समतुल्य गैर-वक्र संस्करण प्राप्त करता है। |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_45) | निर्दिष्ट <c>tolerance</c> का उपयोग करके इस ज्यामिति का अनुमानित या समतुल्य गैर-वक्र संस्करण प्राप्त करता है। |
| [to_svg(extent)](#to_svg_extent_46) | इस ज्यामिति को Svg प्रतिनिधित्व में अनुवादित करता है। |
| [touches(other)](#touches_other_47) | निर्धारित करता है कि यह ज्यामिति और निर्दिष्ट ज्यामिति स्पर्श करती हैं या नहीं। |
| [union(other)](#union_other_48) | इस ज्यामिति और निर्दिष्ट ज्यामिति को मिलाता है। |
| [union(other)](#union_other_49) | इस ज्यामिति और निर्दिष्ट ज्यामिति को मिलाता है। |
| [within(extent)](#within_extent_50) | निर्धारित करता है कि यह ज्यामिति निर्दिष्ट सीमा के भीतर है या नहीं। |
| [within(other)](#within_other_51) | निर्धारित करता है कि यह ज्यामिति निर्दिष्ट ज्यामिति के भीतर है या नहीं। |


### Constructor: LinearRing() {#LinearRing__1}


```
 LinearRing() 
```

[LinearRing](/psd/python-net/aspose.gis.geometries/linearring/) क्लास का नया उदाहरण प्रारंभ करता है।

### Constructor: LinearRing(collection) {#LinearRing_collection_2}


```
 LinearRing(collection) 
```

[LinearRing](/psd/python-net/aspose.gis.geometries/linearring/) क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| संग्रह | System.Collections.Generic.IEnumerable<IPoint> | बिंदुओं का संग्रह। |

### Constructor: LinearRing(other) {#LinearRing_other_3}


```
 LinearRing(other) 
```

[LinearRing](/psd/python-net/aspose.gis.geometries/linearring/) क्लास का नया उदाहरण प्रारंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| other | [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | डेटा कॉपी करने के लिए दूसरी रेखा। |

### Method: add_point(point) {#add_point_point_1}


```
 add_point(point) 
```

रेखा के अंत में एक बिंदु जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | जोड़ने के लिए बिंदु। |

### Method: add_point(x, y) {#add_point_x_y_2}


```
 add_point(x, y) 
```

रेखा के अंत में एक बिंदु जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | double | X निर्देशांक का मान। |
| y | double | Y निर्देशांक का मान। |

### Method: add_point(x, y, z) {#add_point_x_y_z_3}


```
 add_point(x, y, z) 
```

रेखा के अंत में एक बिंदु जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | double | X निर्देशांक का मान। |
| y | double | Y निर्देशांक का मान। |
| z | double | Z निर्देशांक का मान। |

### Method: add_point(x, y, z, m) {#add_point_x_y_z_m_4}


```
 add_point(x, y, z, m) 
```

रेखा के अंत में एक बिंदु जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | double | X निर्देशांक का मान। |
| y | double | Y निर्देशांक का मान। |
| z | double | Z निर्देशांक का मान। |
| m | double | M निर्देशांक का मान। |

### Method: as_binary() {#as_binary__5}


```
 as_binary() 
```

इस ज्यामिति को उसके Well-Known Binary प्रतिनिधित्व में परिवर्तित करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| byte | इस ज्यामिति का Well-Known Binary प्रतिनिधित्व। |


### Method: as_binary(variant) {#as_binary_variant_6}


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


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_7}


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

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_8}


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

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_9}


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


### Method: as_text() {#as_text__10}


```
 as_text() 
```

इस ज्यामिति को उसके Well-Known Text प्रतिनिधित्व में परिवर्तित करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | इस ज्यामिति का Well-Known Text प्रतिनिधित्व। |


### Method: as_text(variant) {#as_text_variant_11}


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


### Method: as_text(variant, format) {#as_text_variant_format_12}


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


### Method: clone() {#clone__13}


```
 clone() 
```

इस उदाहरण की प्रतिलिपि बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | इस इंस्टेंस की क्लोन |


### Method: covered_by(other) {#covered_by_other_14}


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


### Method: covers(other) {#covers_other_15}


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


### Method: crosses(other) {#crosses_other_16}


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


### Method: difference(other) {#difference_other_17}


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


### Method: disjoint(other) {#disjoint_other_18}


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


### Method: from_binary(wkb)  [static] {#from_binary_wkb_19}


```
 from_binary(wkb) 
```

उसके Well-Known Binary प्रतिनिधित्व से एक ज्यामिति बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| wkb | byte | ज्यामिति का वेल-नॉन् बाइनरी प्रतिनिधित्व। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | तर्क द्वारा प्रतिनिधित्व की गई एक ज्यामिति। |


### Method: from_binary(wkb, spatial_reference_system)  [static] {#from_binary_wkb_spatial_reference_system_20}


```
 from_binary(wkb, spatial_reference_system) 
```

उसके Well-Known Binary प्रतिनिधित्व से एक ज्यामिति बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| wkb | byte | ज्यामिति का वेल-नॉन् बाइनरी प्रतिनिधित्व। |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | ज्यामिति को सौंपा जाने वाला स्पैशियल रेफ़रेंस सिस्टम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | तर्क द्वारा प्रतिनिधित्व की गई एक ज्यामिति। |


### Method: from_text(wkt)  [static] {#from_text_wkt_21}


```
 from_text(wkt) 
```

उसके Well-Known Text प्रतिनिधित्व से एक ज्यामिति बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| wkt | string | ज्यामिति का वेल-नॉन् टेक्स्ट प्रतिनिधित्व। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | तर्क द्वारा प्रतिनिधित्व की गई एक ज्यामिति। |


### Method: from_text(wkt, spatial_reference_system)  [static] {#from_text_wkt_spatial_reference_system_22}


```
 from_text(wkt, spatial_reference_system) 
```

उसके Well-Known Text प्रतिनिधित्व से एक ज्यामिति बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| wkt | string | ज्यामिति का वेल-नॉन् टेक्स्ट प्रतिनिधित्व। |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | ज्यामिति को सौंपा जाने वाला स्पैशियल रेफ़रेंस सिस्टम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | तर्क द्वारा प्रतिनिधित्व की गई एक ज्यामिति। |


### Method: get_area() {#get_area__23}


```
 get_area() 
```

इस ज्यामिति का क्षेत्रफल गणना करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| double | इस ज्यामिति का क्षेत्रफल।<br/>            यदि यह ज्यामिति एक [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/) है तो इस ज्यामिति के तत्वों के क्षेत्रों का योग। |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_24}


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


### Method: get_centroid() {#get_centroid__25}


```
 get_centroid() 
```

इस ज्यामिति का केंद्रबिंदु गणना करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | इस ज्यामिति का केंद्रबिंदु। यदि यह ज्यामिति खाली है तो एक खाली बिंदु लौटाया जाता है।<br/>            केंद्रबिंदु इस ज्यामिति में सबसे उच्च आयाम वाली ज्यामितियों के केंद्रबिंदु के बराबर होता है<br/>            (उदाहरण के लिए, यदि ज्यामिति में बिंदु और रेखाएँ दोनों हैं, तो केवल रेखाएँ ही केंद्रबिंदु में योगदान देती हैं)। |


### Method: get_convex_hull() {#get_convex_hull__26}


```
 get_convex_hull() 
```

इस ज्यामिति का कॉन्वेक्स हुल गणना करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | इस ज्यामिति का कॉन्वेक्स हुल दर्शाने वाली एक ज्यामिति।<br/>            यदि इस ज्यामिति में कोई बिंदु नहीं है तो परिणाम [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/) होगा।<br/>            यदि इस ज्यामिति में केवल एक बिंदु है तो परिणाम वह बिंदु होगा।<br/>            यदि इस ज्यामिति में केवल दो बिंदु हैं तो परिणाम बिंदुओं के साथ [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) होगा।<br/>            यदि इस ज्यामिति में तीन या अधिक बिंदु हैं तो परिणाम [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/) होगा जो सभी ज्यामितियों के बिंदुओं के चारों ओर एक कॉन्वेक्स<br/>            हुल दर्शाता है। |


### Method: get_distance_to(other) {#get_distance_to_other_27}


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


### Method: get_extent() {#get_extent__28}


```
 get_extent() 
```

इस ज्यामिति का बाउंडिंग विस्तार गणना करता है और लौटाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | इस ज्यामिति का बाउंडिंग विस्तार। |


### Method: get_length() {#get_length__29}


```
 get_length() 
```

इस ज्यामिति की लंबाई गणना करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| double | इस ज्यामिति की लंबाई।<br/>            यदि यह एक [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) है तो परिमाप।<br/>            यदि यह एक [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/) है तो इस ज्यामिति के तत्वों की लंबाइयों का योग। |


### Method: intersection(other) {#intersection_other_30}


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


### Method: intersects(extent) {#intersects_extent_31}


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


### Method: intersects(other) {#intersects_other_32}


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


### Method: is_clockwise() {#is_clockwise__33}


```
 is_clockwise() 
```

निर्धारित करता है कि रिंग का घड़ी की दिशा में वाइंडिंग है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <see langword="true" /> यदि घड़ी की दिशा में; अन्यथा <see langword="false" />. |


### Method: overlaps(other) {#overlaps_other_34}


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


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_35}


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


### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__36}


```
 replace_polygons_by_lines() 
```

इस ज्यामिति की रेखाओं के रूप में प्रतिनिधित्व किए गए बहुभुज प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | एक ज्यामिति, जिसमें कोई बहुभुज ज्यामिति नहीं है। निम्नलिखित रूपांतरण लागू किए जाते हैं:<br/>            <ul><br/>            <li> [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) को रैखिक किया जाता है (जिसे [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/) में बदला जाता है)</li><br/>            <li>[GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) को [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/) में जोड़ा जाता है</li><br/>            </ul> |


### Method: round_m(digits) {#round_m_digits_37}


```
 round_m(digits) 
```

M निर्देशांक को निर्दिष्ट दशमलव अंकों की संख्या तक गोल करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| अंकों | इंट | भिन्नात्मक अंकों की संख्या। |

### Method: round_xy(digits) {#round_xy_digits_38}


```
 round_xy(digits) 
```

X और Y निर्देशांक को निर्दिष्ट दशमलव अंकों की संख्या तक गोल करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| अंकों | इंट | भिन्नात्मक अंकों की संख्या। |

### Method: round_z(digits) {#round_z_digits_39}


```
 round_z(digits) 
```

Z निर्देशांक को निर्दिष्ट दशमलव अंकों की संख्या तक गोल करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| अंकों | इंट | भिन्नात्मक अंकों की संख्या। |

### Method: spatially_contains(other) {#spatially_contains_other_40}


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


### Method: spatially_equals(other) {#spatially_equals_other_41}


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


### Method: sym_difference(other) {#sym_difference_other_42}


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


### Method: to_editable() {#to_editable__43}


```
 to_editable() 
```

इस ज्यामिति की एक संपादन योग्य प्रति प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [LinearRing](/psd/python-net/aspose.gis.geometries/linearring) | इस ज्यामिति की एक संपादन योग्य प्रति। |


### Method: to_linear_geometry() {#to_linear_geometry__44}


```
 to_linear_geometry() 
```

डिफ़ॉल्ट <c>tolerance</c> का उपयोग करके इस ज्यामिति का अनुमानित या समतुल्य गैर-वक्र संस्करण प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | एक [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) जो इस वक्र के समान या समतुल्य है।<br/> यह <DOM Element: class at 0x2a1791540d0>.ICurve.to_linear_geometry()(float) के बराबर है, डिफ़ॉल्ट <c>tolerance</c> के साथ। डिफ़ॉल्ट <c>tolerance</c> का मान इस ज्यामिति के [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) पर निर्भर करता है:<br/><ul><br/><li> प्रोजेक्टेड SRS के लिए टॉलरेंस 0.001 मीटर (SRS इकाइयों में) </li><br/><li> जियोग्राफिक SRS के लिए टॉलरेंस <c>1e-5</c> डिग्री (SRS इकाइयों में) </li><br/><li> अज्ञात SRS के लिए टॉलरेंस <c>1e-5</c> </li><br/></ul><br/> लागू किए गए रूपांतरणों के बारे में अधिक विवरण के लिए <DOM Element: class at 0x2a1791540d0>.ICurve.to_linear_geometry()(float) विनिर्देशन देखें। |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_45}


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
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | एक [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) जो इस वक्र के समान या उसके बराबर है:<br/>             <ul><br/>             यदि यह वस्तु स्वयं [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) है तो परिणाम इस वस्तु के बराबर है<br/>             यदि यह वस्तु [ICircularString](/psd/python-net/aspose.gis.geometries/icircularstring/) है तो परिणाम निर्दिष्ट <paramref name="tolerance" /> के साथ रैखिकीकृत वृत्ताकार स्ट्रिंग है<br/>             यदि यह वस्तु [ICompoundCurve](/psd/python-net/aspose.gis.geometries/icompoundcurve/) है - उससे सभी वक्र रैखिकीकृत होते हैं और फिर [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) में जोड़े जाते हैं<br/>            </ul> |


### Method: to_svg(extent) {#to_svg_extent_46}


```
 to_svg(extent) 
```

इस ज्यामिति को Svg प्रतिनिधित्व में अनुवादित करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | इस ज्यामिति को Svg में अनुवादित करने के लिए सीमा |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | Svg प्रतिनिधित्व। |


### Method: touches(other) {#touches_other_47}


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


### Method: union(other) {#union_other_48}


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


### Method: union(other) {#union_other_49}


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


### Method: within(extent) {#within_extent_50}


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


### Method: within(other) {#within_other_51}


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


