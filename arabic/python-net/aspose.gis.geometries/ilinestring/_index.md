---
title: "الفئة ILineString"
type: docs
weight: 130
url: /ar/python-net/aspose.gis.geometries/ilinestring/
---

**Summary:** A multi-vertex curve with linear interpolation between points.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.ILineString

**Inheritance:** ICurve, IGeometry

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | يحصل على البُعد الطوبولوجي لهذا [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/).<br/>            إذا كان البُعد غير معروف (مثال: لمجموعة GEOMETRYCOLLECTION فارغة) يتم إرجاع [GeometryDimension.POINT](/psd/python-net/aspose.gis.geometries/geometrydimension/) . |
| end_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | يرجع نسخة من نقطة النهاية للمنحنى. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | يحصل على نوع الهندسة. |
| has_curve_geometry | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه الهندسة أو تحتوي على هندسة منحنية (غير خطية). |
| has_m | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على إحداثية M. |
| has_z | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على إحداثية Z. |
| is_closed | bool | r | يحصل على قيمة تشير إلى ما إذا كان المنحنى مغلقاً.<br/> يكون المنحنى مغلقاً إذا كانت نقطة البداية مساوية لنقطة النهاية. |
| is_empty | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه الحالة فارغة (تمثل مجموعة النقاط الفارغة). |
| is_simple | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن بسيطًا من منظور SFA. |
| is_valid | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن صالحًا. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | يحصل على SpatialReferenceSystem لهذه الحالة.<br/>            يمكن أن تكون هذه الخاصية <see langword="null" /> إذا كان SpatialReferenceSystem غير معروف. |
| start_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | يرجع نسخة من نقطة البداية للمنحنى. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [as_binary()](#as_binary__1) | يحوّل هذه الهندسة إلى تمثيلها الثنائي المعروف. |
| [as_binary(variant)](#as_binary_variant_2) | يحوّل هذه الهندسة إلى تمثيلها الثنائي المعروف. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_3) | يصدّر هذه الهندسة إلى تمثيل صورة. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_4) | يصدّر هذه الهندسة إلى تمثيل صورة. |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_5) | يصدّر هذه الهندسة إلى تمثيل صورة. |
| [as_text()](#as_text__6) | يحوّل هذه الهندسة إلى تمثيلها النصي المعروف. |
| [as_text(variant)](#as_text_variant_7) | يحوّل هذه الهندسة إلى تمثيلها النصي المعروف. |
| [as_text(variant, format)](#as_text_variant_format_8) | يحوّل هذه الهندسة إلى تمثيلها النصي المعروف. |
| [clone()](#clone__9) | ينسخ هذا الكائن. |
| [covered_by(other)](#covered_by_other_10) | يحدد ما إذا كانت هذه الهندسة مغطاة بواسطة هندسة محددة. |
| [covers(other)](#covers_other_11) | يحدد ما إذا كانت هذه الهندسة تغطي هندسة محددة. |
| [crosses(other)](#crosses_other_12) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تتقاطع. |
| [difference(other)](#difference_other_13) | يطرح هندسة محددة من هذه الهندسة. |
| [disjoint(other)](#disjoint_other_14) | يحدد ما إذا كانت هذه الهندسة منفصلة عن هندسة محددة. |
| [get_area()](#get_area__15) | يحسب مساحة هذه الهندسة. |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_16) | يحسب منطقة عازلة حول هذه الهندسة. |
| [get_centroid()](#get_centroid__17) | يحسب مركز الثقل لهذه الهندسة. |
| [get_convex_hull()](#get_convex_hull__18) | يحسب الغلاف المحدب لهذه الهندسة. |
| [get_distance_to(other)](#get_distance_to_other_19) | يحسب الحد الأدنى للمسافة بين هذه الهندسة وهندسة محددة. |
| [get_extent()](#get_extent__20) | يحسب ويعيد نطاقًا محيطًا لهذه الهندسة. |
| [get_length()](#get_length__21) | يحسب طول هذه الهندسة. |
| [intersection(other)](#intersection_other_22) | يبني تقاطعًا بين هذه الهندسة وهندسة محددة. |
| [intersects(extent)](#intersects_extent_23) | يحدد ما إذا كانت هذه الهندسة تتقاطع مع نطاق محدد. |
| [intersects(other)](#intersects_other_24) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تتقاطع. |
| [overlaps(other)](#overlaps_other_25) | يحدد ما إذا كانت هذه الهندسة تتداخل مع هندسة محددة. |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_26) | يحدد ما إذا كانت مصفوفة تقاطع DE-9IM لهذه الهندسة وهندسة محددة تطابق النمط المقدم. |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__27) | يحصل على المضلعات الممثلة كخطوط لهذه الهندسة. |
| [spatially_contains(other)](#spatially_contains_other_28) | يحدد ما إذا كانت هذه الهندسة تحتوي مكانيًا على هندسة محددة. |
| [spatially_equals(other)](#spatially_equals_other_29) | يحدد ما إذا كانت هذه الهندسة مساوية مكانيًا لهندسة محددة. |
| [sym_difference(other)](#sym_difference_other_30) | يبني فرقًا متماثلًا بين هذه الهندسة وهندسة محددة. |
| [to_editable()](#to_editable__31) | يحصل على نسخة قابلة للتحرير من هذه الهندسة. |
| [to_linear_geometry()](#to_linear_geometry__32) | يحصل على نسخة تقريبية أو مكافئة غير منحنية من هذه الهندسة باستخدام <c>tolerance</c> الافتراضية. |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_33) | يحصل على نسخة تقريبية أو مكافئة غير منحنية من هذه الهندسة باستخدام <c>tolerance</c> المحددة. |
| [touches(other)](#touches_other_34) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تلامسان. |
| [union(other)](#union_other_35) | يوحد هذه الهندسة وهندسة محددة. |
| [union(other)](#union_other_36) | يوحد هذه الهندسة وهندسة محددة. |
| [within(extent)](#within_extent_37) | يحدد ما إذا كانت هذه الهندسة داخل نطاق محدد. |
| [within(other)](#within_other_38) | يحدد ما إذا كانت هذه الهندسة داخل هندسة محددة. |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

يحوّل هذه الهندسة إلى تمثيلها الثنائي المعروف.

**Returns**

| نوع | وصف |
| :- | :- |
| byte | تمثيل Well-Known Binary لهذه الهندسة. |


### Method: as_binary(variant) {#as_binary_variant_2}


```
 as_binary(variant) 
```

يحوّل هذه الهندسة إلى تمثيلها الثنائي المعروف.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| variant | [WkbVariant](/psd/python-net/aspose.gis.geometries/wkbvariant) | متغيّر Well-Known Binary للاستخدام. |

**Returns**

| نوع | وصف |
| :- | :- |
| byte | تمثيل Well-Known Binary لهذه الهندسة. |


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_3}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

يصدّر هذه الهندسة إلى تمثيل صورة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى صورة الإخراج. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | عرض الخريطة. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | ارتفاع الخريطة. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | المُصيّر للاستخدام. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | مُرمّز للاستخدام في التصيير. إذا كان <see langword="null" />, يُستخدم المُرمّز الافتراضي. |

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_4}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

يصدّر هذه الهندسة إلى تمثيل صورة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| output_path | string | المسار إلى صورة الإخراج. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | عرض الخريطة. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | ارتفاع الخريطة. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | المُصيّر للاستخدام. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | مُرمّز للاستخدام في التصيير. إذا كان <see langword="null" />, يُستخدم المُرمّز الافتراضي. |

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_5}


```
 as_image(width, height, renderer, symbolizer) 
```

يصدّر هذه الهندسة إلى تمثيل صورة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | عرض الخريطة. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | ارتفاع الخريطة. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | المُصيّر للاستخدام. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | مُرمّز للاستخدام في التصيير. إذا كان <see langword="null" />, يُستخدم المُرمّز الافتراضي. |

**Returns**

| نوع | وصف |
| :- | :- |
| _io.BufferedRandom | الصورة كتيار |


### Method: as_text() {#as_text__6}


```
 as_text() 
```

يحوّل هذه الهندسة إلى تمثيلها النصي المعروف.

**Returns**

| نوع | وصف |
| :- | :- |
| string | تمثيل Well-Known Text لهذه الهندسة. |


### Method: as_text(variant) {#as_text_variant_7}


```
 as_text(variant) 
```

يحوّل هذه الهندسة إلى تمثيلها النصي المعروف.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | متغيّر Well-Known Text للاستخدام. |

**Returns**

| نوع | وصف |
| :- | :- |
| string | تمثيل Well-Known Text لهذه الهندسة. |


### Method: as_text(variant, format) {#as_text_variant_format_8}


```
 as_text(variant, format) 
```

يحوّل هذه الهندسة إلى تمثيلها النصي المعروف.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | متغيّر Well-Known Text للاستخدام. |
| format | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | تنسيق الإحداثيات للتحويل إلى سلسلة. راجع [NumericFormat](/psd/python-net/aspose.gis/numericformat/) للحصول عليه. |

**Returns**

| نوع | وصف |
| :- | :- |
| string | تمثيل Well-Known Text لهذه الهندسة. |


### Method: clone() {#clone__9}


```
 clone() 
```

ينسخ هذا الكائن.

**Returns**

| نوع | وصف |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | نسخة متماثلة من هذه الحالة |


### Method: covered_by(other) {#covered_by_other_10}


```
 covered_by(other) 
```

يحدد ما إذا كانت هذه الهندسة مغطاة بواسطة هندسة محددة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | <see langword=\"true\" /> إذا كانت هذه الهندسة \"مغطاة مكانيًا بواسطة\" هندسة أخرى. <see langword=\"false\" /> خلاف ذلك. |


### Method: covers(other) {#covers_other_11}


```
 covers(other) 
```

يحدد ما إذا كانت هذه الهندسة تغطي هندسة محددة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | <see langword=\"true\" /> إذا كانت هذه الهندسة \"تغطي مكانيًا\" هندسة أخرى. <see langword=\"false\" /> خلاف ذلك. |


### Method: crosses(other) {#crosses_other_12}


```
 crosses(other) 
```

يحدد ما إذا كانت هذه الهندسة وهندسة محددة تتقاطع.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | <see langword=\"true\" /> إذا كانت هذه الهندسة \"تتقاطع مكانيًا\" مع هندسة أخرى. <see langword=\"false\" /> خلاف ذلك. |


### Method: difference(other) {#difference_other_13}


```
 difference(other) 
```

يطرح هندسة محددة من هذه الهندسة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة للطرح. |

**Returns**

| نوع | وصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة تمثل الفرق بين هذه الهندسة ومعامل. الهندسة الناتجة تحتوي على<br/>            مجموعة نقاط موجودة في هذه الهندسة ولكنها غير موجودة في المعامل. |


### Method: disjoint(other) {#disjoint_other_14}


```
 disjoint(other) 
```

يحدد ما إذا كانت هذه الهندسة منفصلة عن هندسة محددة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | <see langword=\"true\" /> إذا كانت هذه الهندسة \"متباعدة مكانيًا\" عن هندسة أخرى. <see langword=\"false\" /> خلاف ذلك. |


### Method: get_area() {#get_area__15}


```
 get_area() 
```

يحسب مساحة هذه الهندسة.

**Returns**

| نوع | وصف |
| :- | :- |
| double | مساحة هذه الهندسة.<br/>            مجموع مساحات عناصر هذه الهندسة إذا كانت هذه الهندسة [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_16}


```
 get_buffer(distance, quadrant_segments) 
```

يحسب منطقة عازلة حول هذه الهندسة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| distance | double | عرض منطقة التخزين المؤقت (بوحدات الإشارة المكانية). |
| quadrant_segments | int | عدد المقاطع المستخدمة لتقريب انحناء 90 درجة.<br/>            كلما كان هذا العدد أكبر، كلما كان التقريب للمنحنيات أفضل.<br/>            القيمة الافتراضية هي 30. |

**Returns**

| نوع | وصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة تمثل جميع النقاط التي تقع ضمن مسافة محددة من<br/>            هذه الهندسة.<br/>            نوع النتيجة إما [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/)، [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) أو [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/). |


### Method: get_centroid() {#get_centroid__17}


```
 get_centroid() 
```

يحسب مركز الثقل لهذه الهندسة.

**Returns**

| نوع | وصف |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | مركز الثقل لهذه الهندسة. إذا كانت هذه الهندسة فارغة تُرجع نقطة فارغة.<br/>            مركز الثقل يساوي مركز الثقل لأعلى أبعاد الهندسات في هذه الهندسة<br/>            (مثلاً إذا كانت النقاط والخطوط موجودة في الهندسة، فإن الخطوط فقط تساهم في مركز الثقل). |


### Method: get_convex_hull() {#get_convex_hull__18}


```
 get_convex_hull() 
```

يحسب الغلاف المحدب لهذه الهندسة.

**Returns**

| نوع | وصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة تمثل الغلاف المحدب لهذه الهندسة.<br/>            إذا لم تحتوي هذه الهندسة على نقاط فإن النتيجة هي [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/).<br/>            إذا كان لهذه الهندسة نقطة واحدة فقط فإن النتيجة هي تلك النقطة.<br/>            إذا كان لهذه الهندسة نقطتين فقط فإن النتيجة هي [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) مع النقاط.<br/>            إذا كان لهذه الهندسة ثلاث نقاط أو أكثر فإن النتيجة هي [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/) الذي يمثل غلافًا محدبًا<br/>            حول جميع نقاط الهندسات. |


### Method: get_distance_to(other) {#get_distance_to_other_19}


```
 get_distance_to(other) 
```

يحسب الحد الأدنى للمسافة بين هذه الهندسة وهندسة محددة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة لإيجاد المسافة إليها. |

**Returns**

| نوع | وصف |
| :- | :- |
| double | إذا لم تكن كلتا الأشكال الهندسية غير [IGeometry.is_empty](/psd/python-net/aspose.gis.geometries/igeometry/) - تكون المسافة بين أقرب نقطتين من الأشكال.<br/>            إذا كان هناك شكل هندسي واحد على الأقل فارغًا يتم إرجاع -1. |


### Method: get_extent() {#get_extent__20}


```
 get_extent() 
```

يحسب ويعيد نطاقًا محيطًا لهذه الهندسة.

**Returns**

| نوع | وصف |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | امتداد حدودي لهذه الهندسة. |


### Method: get_length() {#get_length__21}


```
 get_length() 
```

يحسب طول هذه الهندسة.

**Returns**

| نوع | وصف |
| :- | :- |
| double | طول هذه الهندسة.<br/>            المحيط إذا كانت هذه [Polygon](/psd/python-net/aspose.gis.geometries/polygon/).<br/>            مجموع أطوال عناصر هذه الهندسة إذا كانت هذه الهندسة [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: intersection(other) {#intersection_other_22}


```
 intersection(other) 
```

يبني تقاطعًا بين هذه الهندسة وهندسة محددة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة لحساب التقاطع معها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة تمثل تقاطع هذه الهندسة ومعامل. الهندسة الناتجة تحتوي على<br/>            مجموعة نقاط موجودة في كل من هذه الهندسة والمعامل. |


### Method: intersects(extent) {#intersects_extent_23}


```
 intersects(extent) 
```

يحدد ما إذا كانت هذه الهندسة تتقاطع مع نطاق محدد.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | الامتداد. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | <see langword=\"true\" /> إذا كان هذا الشكل الهندسي يتقاطع مع النطاق؛ <see langword=\"false\" /> وإلا. |


### Method: intersects(other) {#intersects_other_24}


```
 intersects(other) 
```

يحدد ما إذا كانت هذه الهندسة وهندسة محددة تتقاطع.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | <see langword=\"true\" /> إذا كان هذا الشكل الهندسي \"spatially intersects\" شكلًا هندسيًا آخر. <see langword=\"false\" /> وإلا. |


### Method: overlaps(other) {#overlaps_other_25}


```
 overlaps(other) 
```

يحدد ما إذا كانت هذه الهندسة تتداخل مع هندسة محددة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | <see langword=\"true\" /> إذا كان هذا الشكل الهندسي \"spatially overlaps\" شكلًا هندسيًا آخر. <see langword=\"false\" /> وإلا. |


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_26}


```
 relate(other, intersection_pattern_matrix) 
```

يحدد ما إذا كانت مصفوفة تقاطع DE-9IM لهذه الهندسة وهندسة محددة تطابق النمط المقدم.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة. |
| intersection_pattern_matrix | string | نمط للمطابقة معه.<br/> يجب أن تكون هذه سلسلة بطول يساوي 9.<br/> كل حرف من السلسلة يمثل البعد المتوقع للتقاطع:<br/> <ul><br/> <li>الحرف 0 - بين داخل الأشكال الهندسية.</li><br/> <li>الحرف 1 - بين داخل هذا الشكل الهندسي وحدود شكل هندسي آخر.</li><br/> <li>الحرف 2 - بين داخل هذا الشكل الهندسي وخارج شكل هندسي آخر.</li><br/> <li>الحرف 3 - بين حدود هذا الشكل الهندسي وداخل شكل هندسي آخر.</li><br/> <li>الحرف 4 - بين حدود الأشكال الهندسية.</li><br/> <li>الحرف 5 - بين حدود هذا الشكل الهندسي وخارج شكل هندسي آخر.</li><br/> <li>الحرف 6 - بين خارج هذا الشكل الهندسي وداخل شكل هندسي آخر.</li><br/> <li>الحرف 7 - بين خارج هذا الشكل الهندسي وحدود شكل هندسي آخر.</li><br/> <li>الحرف 8 - بين خارج الأشكال الهندسية.</li><br/> </ul><br/> القيم الممكنة لكل حرف هي:<br/> <ul><br/> <li>* - أي قيمة؛</li><br/> <li>F - لا تقاطع؛</li><br/> <li>T - أي تقاطع؛</li><br/> <li>0 - تقاطع نقطة (مثال: نقطة مشتركة);</li><br/> <li>1 - تقاطع خط (مثال: جزء خط مشترك);</li><br/> <li>2 - تقاطع مساحة (مثال: جزء مشترك من مضلع);</li><br/> </ul><br/> على سبيل المثال، نمط التقاطع \"F0*******\" يعني أنه لا يجب أن يكون هناك تقاطع بين داخل الأشكال الهندسية<br/> ويجب أن يكون تقاطع حدود الأشكال الهندسية نقطة.<br/> راجع مواصفة OpenGIS Simple Features لمزيد من التفاصيل حول نمط مصفوفة التقاطع. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | <see langword=\"true\" /> إذا كانت مصفوفة التقاطع هذه تطابق النمط؛ <see langword=\"false\" /> وإلا. |


### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__27}


```
 replace_polygons_by_lines() 
```

يحصل على المضلعات الممثلة كخطوط لهذه الهندسة.

**Returns**

| نوع | وصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | شكل هندسي لا يحتوي على أشكال مضلع. يتم تطبيق التحويلات التالية:<br/> <ul><br/> <li> يتم تحويل [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s إلى خطية<br/> (تحويل إلى [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s)</li><br/> <li> يتم دمج [GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s في [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s</li><br/> </ul> |


### Method: spatially_contains(other) {#spatially_contains_other_28}


```
 spatially_contains(other) 
```

يحدد ما إذا كانت هذه الهندسة تحتوي مكانيًا على هندسة محددة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | <see langword=\"true\" /> إذا كان هذا الشكل الهندسي \"spatially contains\" شكلًا هندسيًا آخر. <see langword=\"false\" /> وإلا. |


### Method: spatially_equals(other) {#spatially_equals_other_29}


```
 spatially_equals(other) 
```

يحدد ما إذا كانت هذه الهندسة مساوية مكانيًا لهندسة محددة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | <see langword=\"true\" /> إذا كان هذا الشكل الهندسي \"spatially equals\" إلى الشكل الهندسي المحدد. <see langword=\"false\" /> وإلا. |


### Method: sym_difference(other) {#sym_difference_other_30}


```
 sym_difference(other) 
```

يبني فرقًا متماثلًا بين هذه الهندسة وهندسة محددة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | شكل هندسي لحساب الفرق المتناظر معه. |

**Returns**

| نوع | وصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | شكل هندسي يمثل الفرق المتناظر بين هذا الشكل الهندسي ومعطى. يحتوي الشكل الهندسي الناتج على<br/> مجموعة نقاط موجودة في أحد الشكلين الهندسيين ولكن ليست موجودة في كليهما. |


### Method: to_editable() {#to_editable__31}


```
 to_editable() 
```

يحصل على نسخة قابلة للتحرير من هذه الهندسة.

**Returns**

| نوع | وصف |
| :- | :- |
| [LineString](/psd/python-net/aspose.gis.geometries/linestring) | نسخة قابلة للتحرير من هذا الشكل الهندسي. |


### Method: to_linear_geometry() {#to_linear_geometry__32}


```
 to_linear_geometry() 
```

يحصل على نسخة تقريبية أو مكافئة غير منحنية من هذه الهندسة باستخدام <c>tolerance</c> الافتراضية.

**Returns**

| نوع | وصف |
| :- | :- |
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | شكل هندسي لا يحتوي على أشكال منحنية. هذا يعادل <DOM Element: class at 0x2a1791a70d0>.IGeometry.to_linear_geometry()(float) مع<br/>            <c>tolerance</c> الافتراضية. <c>tolerance</c> الافتراضية محددة بواسطة [IGeometry.spatial_reference_system](/psd/python-net/aspose.gis.geometries/igeometry/)<br/>            لهذا الشكل الهندسي:<br/>            <ul><br/>            <li> بالنسبة لنظام الإحداثيات المسقطة SRS يكون التسامح 0.001 متر (بوحدات SRS) </li><br/>            <li> بالنسبة لنظام الإحداثيات الجغرافي SRS يكون التسامح <c>1e-5</c> درجة (بوحدات SRS) </li><br/>            <li> بالنسبة لنظام إحداثيات غير معروف يكون التسامح <c>1e-5</c> </li><br/>            </ul><br/>            لمزيد من التفاصيل حول التحويلات المطبقة راجع مواصفات <DOM Element: class at 0x2a1791a70d0>.IGeometry.to_linear_geometry()(float). |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_33}


```
 to_linear_geometry(tolerance) 
```

يحصل على نسخة تقريبية أو مكافئة غير منحنية من هذه الهندسة باستخدام <c>tolerance</c> المحددة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| التحمل | double | ال<c>tolerance</c> المراد استخدامه. النتيجة مضمونة أن تكون أقل من <c>tolerance</c> بعيدًا عن الشكل المنحني<br/>            ما لم يتجاوز عدد النقاط المطلوبة لتقويم الشكل الحد الأقصى لكل ربع<br/>            وهو حاليًا يساوي 10000 نقطة. |

**Returns**

| نوع | وصف |
| :- | :- |
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | شكل هندسي لا يحتوي على أشكال منحنية. يتم تطبيق التحويلات التالية:<br/>            <ul><br/>            <li> يتم تقويم [GeometryType.CIRCULAR_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s إلى خطوط مستقيمة (تحويل إلى [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s مع <paramref name="tolerance" /> المحدد) </li><br/>            <li> يتم دمج [GeometryType.COMPOUND_CURVE](/psd/python-net/aspose.gis.geometries/geometrytype/)s في <c>LineString</c>s </li><br/>            <li> يتم تحويل [GeometryType.CURVE_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s إلى [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s </li><br/>            <li> يتم تحويل [GeometryType.MULTI_CURVE](/psd/python-net/aspose.gis.geometries/geometrytype/)s إلى [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s </li><br/>            <li> يتم تحويل [GeometryType.MULTI_SURFACE](/psd/python-net/aspose.gis.geometries/geometrytype/)s إلى [GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s </li><br/>            </ul><br/>            نتيجةً لذلك، تكون الخاصية [IGeometry.has_curve_geometry](/psd/python-net/aspose.gis.geometries/igeometry/) للنتيجة <see langword="false" />. |


### Method: touches(other) {#touches_other_34}


```
 touches(other) 
```

يحدد ما إذا كانت هذه الهندسة وهندسة محددة تلامسان.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | <see langword=\"true\" /> إذا كان هذا الشكل الهندسي \"spatially touches\" شكلًا هندسيًا آخر. <see langword=\"false\" /> وإلا. |


### Method: union(other) {#union_other_35}


```
 union(other) 
```

يوحد هذه الهندسة وهندسة محددة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | شكل هندسي للاتحاد معه. |

**Returns**

| نوع | وصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | شكل هندسي يمثل اتحاد هذا الشكل الهندسي ومعطى. يحتوي الشكل الهندسي الناتج على<br/> مجموعة نقاط موجودة في هذا الشكل الهندسي أو في المعطى. |


### Method: union(other) {#union_other_36}


```
 union(other) 
```

يوحد هذه الهندسة وهندسة محددة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| other | [IGeometry[]](/psd/python-net/aspose.gis.geometries/igeometry) | شكل هندسي للاتحاد معه. |

**Returns**

| نوع | وصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | شكل هندسي يمثل اتحاد هذا الشكل الهندسي ومعطى. يحتوي الشكل الهندسي الناتج على<br/> مجموعة نقاط موجودة في هذا الشكل الهندسي أو في المعطى. |


### Method: within(extent) {#within_extent_37}


```
 within(extent) 
```

يحدد ما إذا كانت هذه الهندسة داخل نطاق محدد.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | الامتداد. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | <see langword=\"true\" /> إذا كان هذا الشكل الهندسي داخل النطاق؛ <see langword=\"false\" /> وإلا. |


### Method: within(other) {#within_other_38}


```
 within(other) 
```

يحدد ما إذا كانت هذه الهندسة داخل هندسة محددة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | <see langword=\"true\" /> إذا كان هذا الشكل الهندسي \"spatially within\" شكلًا هندسيًا آخر. <see langword=\"false\" /> وإلا. |


