---
title: "فئة LinearRing"
type: docs
weight: 240
url: /ar/python-net/aspose.gis.geometries/linearring/
---

**Summary:** A [LinearRing](/psd/python-net/aspose.gis.geometries/linearring/) is a [LineString](/psd/python-net/aspose.gis.geometries/linestring/) that is both closed and simple.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.LinearRing

**Inheritance:** IGeometry, ICurve, ILineString, ILinearRing, LineString

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [LinearRing()](#LinearRing__1) | يُنشئ مثلاً جديداً من الفئة [LinearRing](/psd/python-net/aspose.gis.geometries/linearring/). |
| [LinearRing(collection)](#LinearRing_collection_2) | يُنشئ مثلاً جديداً من الفئة [LinearRing](/psd/python-net/aspose.gis.geometries/linearring/). |
| [LinearRing(other)](#LinearRing_other_3) | يُنشئ مثلاً جديداً من الفئة [LinearRing](/psd/python-net/aspose.gis.geometries/linearring/). |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| coordinate_dimension | int | r | يحصل على عدد أبعاد الإحداثيات لهذا [Geometry](/psd/python-net/aspose.gis.geometries/geometry/). |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | يحصل على البُعد الطوبولوجي لهذا [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/).<br/>            إذا كان البُعد غير معروف (مثلاً لمجموعة GEOMETRYCOLLECTION فارغة) يتم إرجاع [GeometryDimension.POINT](/psd/python-net/aspose.gis.geometries/geometrydimension/). |
| end_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | يرجع نسخة من نقطة النهاية للمنحنى. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | يحصل على نوع الهندسة. |
| has_curve_geometry | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه الهندسة أو تحتوي على هندسة منحنية (غير خطية). |
| has_m | bool | r/w | يحصل على قيمة تشير إلى ما إذا كان لهذا الكائن إحداثية M. |
| has_z | bool | r/w | يحصل على قيمة تشير إلى ما إذا كان لهذا الكائن إحداثية Z. |
| is_closed | bool | r | يحصل على قيمة تشير إلى ما إذا كان المنحنى مغلقًا.<br/>            يكون المنحنى مغلقًا إذا كانت نقطة البداية مساوية لنقطة النهاية. |
| is_empty | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن فارغًا. |
| is_simple | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن بسيطًا من منظور SFA. |
| is_valid | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن صالحًا. |
| null [static] | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | r | يحصل على كائن من نوع هندسة فارغة (null). |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | يحصل على SpatialReferenceSystem لهذا الكائن.<br/>            يمكن أن تكون هذه الخاصية <see langword="null" /> إذا لم يتم تعيين SpatialReferenceSystem.<br/>            تعيين SpatialReferenceSystem جديد لن يقوم بأي تحويل إحداثيات، فقط سيتغير المرجع. |
| start_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | يرجع نسخة من نقطة البداية للمنحنى. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_point(point)](#add_point_point_1) | يضيف نقطة إلى نهاية الخط. |
| [add_point(x, y)](#add_point_x_y_2) | يضيف نقطة إلى نهاية الخط. |
| [add_point(x, y, z)](#add_point_x_y_z_3) | يضيف نقطة إلى نهاية الخط. |
| [add_point(x, y, z, m)](#add_point_x_y_z_m_4) | يضيف نقطة إلى نهاية الخط. |
| [as_binary()](#as_binary__5) | يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Binary. |
| [as_binary(variant)](#as_binary_variant_6) | يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Binary. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_7) | يصدّر هذه الهندسة إلى تمثيل صورة. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_8) | يصدّر هذه الهندسة إلى تمثيل صورة. |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_9) | يصدّر هذه الهندسة إلى تمثيل صورة. |
| [as_text()](#as_text__10) | يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Text. |
| [as_text(variant)](#as_text_variant_11) | يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Text. |
| [as_text(variant, format)](#as_text_variant_format_12) | يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Text. |
| [clone()](#clone__13) | ينسخ هذا الكائن. |
| [covered_by(other)](#covered_by_other_14) | يحدد ما إذا كانت هذه الهندسة مغطاة بواسطة هندسة محددة. |
| [covers(other)](#covers_other_15) | يحدد ما إذا كانت هذه الهندسة تغطي هندسة محددة. |
| [crosses(other)](#crosses_other_16) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تتقاطع. |
| [difference(other)](#difference_other_17) | يطرح هندسة محددة من هذه الهندسة. |
| [disjoint(other)](#disjoint_other_18) | يحدد ما إذا كانت هذه الهندسة منفصلة عن هندسة محددة. |
| [from_binary(wkb)](#from_binary_wkb_19) | ينشئ هندسة من تمثيلها الثنائي المعروف. |
| [from_binary(wkb, spatial_reference_system)](#from_binary_wkb_spatial_reference_system_20) | ينشئ هندسة من تمثيلها الثنائي المعروف. |
| [from_text(wkt)](#from_text_wkt_21) | ينشئ هندسة من تمثيلها النصي المعروف. |
| [from_text(wkt, spatial_reference_system)](#from_text_wkt_spatial_reference_system_22) | ينشئ هندسة من تمثيلها النصي المعروف. |
| [get_area()](#get_area__23) | يحسب مساحة هذه الهندسة. |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_24) | يحسب منطقة العازلة حول هذه الهندسة. |
| [get_centroid()](#get_centroid__25) | يحسب مركز الثقل لهذه الهندسة. |
| [get_convex_hull()](#get_convex_hull__26) | يحسب الغلاف المحدب لهذه الهندسة. |
| [get_distance_to(other)](#get_distance_to_other_27) | يحسب المسافة الدنيا بين هذه الهندسة وهندسة محددة. |
| [get_extent()](#get_extent__28) | يحسب ويعيد نطاقًا محيطًا لهذه الهندسة. |
| [get_length()](#get_length__29) | يحسب طول هذه الهندسة. |
| [intersection(other)](#intersection_other_30) | يبني تقاطعًا بين هذه الهندسة وهندسة محددة. |
| [intersects(extent)](#intersects_extent_31) | يحدد ما إذا كانت هذه الهندسة تتقاطع مع نطاق محدد. |
| [intersects(other)](#intersects_other_32) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تتقاطع. |
| [is_clockwise()](#is_clockwise__33) | يحدد ما إذا كان الحلقة لها دوران باتجاه عقارب الساعة. |
| [overlaps(other)](#overlaps_other_34) | يحدد ما إذا كانت هذه الهندسة تتداخل مع هندسة محددة. |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_35) | يحدد ما إذا كانت مصفوفة تقاطع DE-9IM لهذه الهندسة وهندسة محددة تطابق النمط المقدم. |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__36) | يحصل على المضلعات الممثلة كخطوط لهذه الهندسة. |
| reverse() | يعكس ترتيب النقاط في هذا [LineString](/psd/python-net/aspose.gis.geometries/linestring/). |
| [round_m(digits)](#round_m_digits_37) | يقرب إحداثي M إلى عدد محدد من الأرقام العشرية. |
| [round_xy(digits)](#round_xy_digits_38) | يقرب إحداثيات X و Y إلى عدد محدد من الأرقام العشرية. |
| [round_z(digits)](#round_z_digits_39) | يقرب إحداثي Z إلى عدد محدد من الأرقام العشرية. |
| set_empty() | يجعل هذه [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) فارغة. |
| [spatially_contains(other)](#spatially_contains_other_40) | يحدد ما إذا كانت هذه الهندسة تحتوي مكانيًا على هندسة محددة. |
| [spatially_equals(other)](#spatially_equals_other_41) | يحدد ما إذا كانت هذه الهندسة مساوية مكانيًا لهندسة محددة. |
| [sym_difference(other)](#sym_difference_other_42) | يبني فرقًا متماثلًا بين هذه الهندسة وهندسة محددة. |
| [to_editable()](#to_editable__43) | يحصل على نسخة قابلة للتحرير من هذه الهندسة. |
| [to_linear_geometry()](#to_linear_geometry__44) | يحصل على نسخة تقريبية أو مكافئة غير منحنية من هذه الهندسة باستخدام <c>tolerance</c> الافتراضي. |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_45) | يحصل على نسخة تقريبية أو مكافئة غير منحنية من هذه الهندسة باستخدام <c>tolerance</c> المحدد. |
| [to_svg(extent)](#to_svg_extent_46) | يحوّل هذه الهندسة إلى تمثيل Svg. |
| [touches(other)](#touches_other_47) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تلامسان. |
| [union(other)](#union_other_48) | يوحد هذه الهندسة وهندسة محددة. |
| [union(other)](#union_other_49) | يوحد هذه الهندسة وهندسة محددة. |
| [within(extent)](#within_extent_50) | يحدد ما إذا كانت هذه الهندسة داخل نطاق محدد. |
| [within(other)](#within_other_51) | يحدد ما إذا كانت هذه الهندسة داخل هندسة محددة. |


### Constructor: LinearRing() {#LinearRing__1}


```
 LinearRing() 
```

يُنشئ مثلاً جديداً من الفئة [LinearRing](/psd/python-net/aspose.gis.geometries/linearring/).

### Constructor: LinearRing(collection) {#LinearRing_collection_2}


```
 LinearRing(collection) 
```

يُنشئ مثلاً جديداً من الفئة [LinearRing](/psd/python-net/aspose.gis.geometries/linearring/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| مجموعة | System.Collections.Generic.IEnumerable<IPoint> | مجموعة النقاط. |

### Constructor: LinearRing(other) {#LinearRing_other_3}


```
 LinearRing(other) 
```

يُنشئ مثلاً جديداً من الفئة [LinearRing](/psd/python-net/aspose.gis.geometries/linearring/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | الخط الآخر لنسخ البيانات منه. |

### Method: add_point(point) {#add_point_point_1}


```
 add_point(point) 
```

يضيف نقطة إلى نهاية الخط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | النقطة التي ستُضاف. |

### Method: add_point(x, y) {#add_point_x_y_2}


```
 add_point(x, y) 
```

يضيف نقطة إلى نهاية الخط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | double | القيمة لإحداثي X. |
| y | double | القيمة لإحداثي Y. |

### Method: add_point(x, y, z) {#add_point_x_y_z_3}


```
 add_point(x, y, z) 
```

يضيف نقطة إلى نهاية الخط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | double | القيمة لإحداثي X. |
| y | double | القيمة لإحداثي Y. |
| z | double | القيمة لإحداثي Z. |

### Method: add_point(x, y, z, m) {#add_point_x_y_z_m_4}


```
 add_point(x, y, z, m) 
```

يضيف نقطة إلى نهاية الخط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | double | القيمة لإحداثي X. |
| y | double | القيمة لإحداثي Y. |
| z | double | القيمة لإحداثي Z. |
| m | double | القيمة لإحداثي M. |

### Method: as_binary() {#as_binary__5}


```
 as_binary() 
```

يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Binary.

**Returns**

| نوع | الوصف |
| :- | :- |
| byte | تمثيل Well-Known Binary لهذه الهندسة. |


### Method: as_binary(variant) {#as_binary_variant_6}


```
 as_binary(variant) 
```

يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Binary.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| variant | [WkbVariant](/psd/python-net/aspose.gis.geometries/wkbvariant) | متغيّر Well-Known Binary للاستخدام. |

**Returns**

| نوع | الوصف |
| :- | :- |
| byte | تمثيل Well-Known Binary لهذه الهندسة. |


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_7}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

يصدّر هذه الهندسة إلى تمثيل صورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى صورة الإخراج. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | عرض الخريطة. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | ارتفاع الخريطة. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | المُعالج للاستخدام. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | مُرمّز للاستخدام في التصيير. إذا كان <see langword="null" />, يُستخدم المُرمّز الافتراضي. |

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_8}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

يصدّر هذه الهندسة إلى تمثيل صورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| output_path | string | المسار إلى صورة الإخراج. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | عرض الخريطة. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | ارتفاع الخريطة. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | المُعالج للاستخدام. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | مُرمّز للاستخدام في التصيير. إذا كان <see langword="null" />, يُستخدم المُرمّز الافتراضي. |

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_9}


```
 as_image(width, height, renderer, symbolizer) 
```

يصدّر هذه الهندسة إلى تمثيل صورة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | عرض الخريطة. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | ارتفاع الخريطة. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | المُعالج للاستخدام. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | مُرمّز للاستخدام في التصيير. إذا كان <see langword="null" />, يُستخدم المُرمّز الافتراضي. |

**Returns**

| نوع | الوصف |
| :- | :- |
| _io.BufferedRandom | الصورة كتيار |


### Method: as_text() {#as_text__10}


```
 as_text() 
```

يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Text.

**Returns**

| نوع | الوصف |
| :- | :- |
| string | تمثيل Well-Known Text لهذه الهندسة. |


### Method: as_text(variant) {#as_text_variant_11}


```
 as_text(variant) 
```

يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Text.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | متغيّر Well-Known Text للاستخدام. |

**Returns**

| نوع | الوصف |
| :- | :- |
| string | تمثيل Well-Known Text لهذه الهندسة. |


### Method: as_text(variant, format) {#as_text_variant_format_12}


```
 as_text(variant, format) 
```

يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Text.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | متغيّر Well-Known Text للاستخدام. |
| format | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | تنسيق الإحداثيات للتحويل إلى سلسلة. راجع [NumericFormat](/psd/python-net/aspose.gis/numericformat/) للحصول عليه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| string | تمثيل Well-Known Text لهذه الهندسة. |


### Method: clone() {#clone__13}


```
 clone() 
```

ينسخ هذا الكائن.

**Returns**

| نوع | الوصف |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | نسخة هذا الكائن |


### Method: covered_by(other) {#covered_by_other_14}


```
 covered_by(other) 
```

يحدد ما إذا كانت هذه الهندسة مغطاة بواسطة هندسة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <see langword="true" /> إذا كانت هذه الهندسة "مغطاة مكانيًا بواسطة" هندسة أخرى. <see langword="false" /> خلاف ذلك. |


### Method: covers(other) {#covers_other_15}


```
 covers(other) 
```

يحدد ما إذا كانت هذه الهندسة تغطي هندسة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <see langword="true" /> إذا كانت هذه الهندسة "تغطي مكانيًا" هندسة أخرى. <see langword="false" /> خلاف ذلك. |


### Method: crosses(other) {#crosses_other_16}


```
 crosses(other) 
```

يحدد ما إذا كانت هذه الهندسة وهندسة محددة تتقاطع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <see langword="true" /> إذا كانت هذه الهندسة "تعبر مكانيًا" هندسة أخرى. <see langword="false" /> خلاف ذلك. |


### Method: difference(other) {#difference_other_17}


```
 difference(other) 
```

يطرح هندسة محددة من هذه الهندسة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة للطرح. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة تمثل الفرق بين هذه الهندسة ومعطى. هندسة النتيجة تحتوي على<br/>            مجموعة نقاط موجودة في هذه الهندسة ولكنها غير موجودة في المعطى. |


### Method: disjoint(other) {#disjoint_other_18}


```
 disjoint(other) 
```

يحدد ما إذا كانت هذه الهندسة منفصلة عن هندسة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <see langword=\"true\" /> إذا كانت هذه الهندسة \"متباعدة مكانيًا\" عن هندسة أخرى. <see langword=\"false\" /> غير ذلك. |


### Method: from_binary(wkb)  [static] {#from_binary_wkb_19}


```
 from_binary(wkb) 
```

ينشئ هندسة من تمثيلها الثنائي المعروف.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| wkb | byte | تمثيل Well-Known Binary لهندسة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة ممثلة بالمعطى. |


### Method: from_binary(wkb, spatial_reference_system)  [static] {#from_binary_wkb_spatial_reference_system_20}


```
 from_binary(wkb, spatial_reference_system) 
```

ينشئ هندسة من تمثيلها الثنائي المعروف.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| wkb | byte | تمثيل Well-Known Binary لهندسة. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني الذي سيُعيّن إلى الهندسة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة ممثلة بالمعطى. |


### Method: from_text(wkt)  [static] {#from_text_wkt_21}


```
 from_text(wkt) 
```

ينشئ هندسة من تمثيلها النصي المعروف.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| wkt | string | تمثيل Well-Known Text لهندسة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة ممثلة بالمعطى. |


### Method: from_text(wkt, spatial_reference_system)  [static] {#from_text_wkt_spatial_reference_system_22}


```
 from_text(wkt, spatial_reference_system) 
```

ينشئ هندسة من تمثيلها النصي المعروف.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| wkt | string | تمثيل Well-Known Text لهندسة. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني الذي سيُعيّن إلى الهندسة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة ممثلة بالمعطى. |


### Method: get_area() {#get_area__23}


```
 get_area() 
```

يحسب مساحة هذه الهندسة.

**Returns**

| نوع | الوصف |
| :- | :- |
| double | مساحة هذه الهندسة.<br/>            مجموع مساحات عناصر هذه الهندسة إذا كانت هذه الهندسة [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_24}


```
 get_buffer(distance, quadrant_segments) 
```

يحسب منطقة العازلة حول هذه الهندسة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسافة | double | عرض منطقة المخزن المؤقت (بوحدات نظام الإحداثيات المكاني). |
| quadrant_segments | int | عدد القطاعات المستخدمة لتقريب انحناء 90 درجة.<br/>            كلما كان هذا العدد أكبر، كلما كان تقريب المنحنيات أفضل.<br/>            القيمة الافتراضية هي 30. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة تمثل جميع النقاط التي تقع ضمن مسافة محددة من<br/>            هذه الهندسة.<br/>            نوع النتيجة يكون إما [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/)، أو [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/)، أو [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/). |


### Method: get_centroid() {#get_centroid__25}


```
 get_centroid() 
```

يحسب مركز الثقل لهذه الهندسة.

**Returns**

| نوع | الوصف |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | مركز الثقل لهذه الهندسة. إذا كانت هذه الهندسة فارغة تُرجَع نقطة فارغة.<br/>            مركز الثقل يساوي مركز الثقل لأعلى أبعاد الهندسات في هذه الهندسة<br/>            (مثال: إذا كانت الهندسة تحتوي على نقاط وخطوط، فإن الخطوط فقط تساهم في مركز الثقل). |


### Method: get_convex_hull() {#get_convex_hull__26}


```
 get_convex_hull() 
```

يحسب الغلاف المحدب لهذه الهندسة.

**Returns**

| نوع | الوصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة تمثل الغلاف المحدب لهذه الهندسة.<br/>            إذا لم تحتوي هذه الهندسة على نقاط فإن النتيجة هي [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/).<br/>            إذا كانت هذه الهندسة تحتوي على نقطة واحدة فقط فإن النتيجة هي تلك النقطة.<br/>            إذا كانت هذه الهندسة تحتوي على نقطتين فقط فإن النتيجة هي [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) بالنقاط.<br/>            إذا كانت هذه الهندسة تحتوي على ثلاث نقاط أو أكثر فإن النتيجة هي [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/) الذي يمثل غلافًا محدبًا<br/>            حول جميع نقاط الهندسات. |


### Method: get_distance_to(other) {#get_distance_to_other_27}


```
 get_distance_to(other) 
```

يحسب المسافة الدنيا بين هذه الهندسة وهندسة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة لإيجاد المسافة إليها. |

**Returns**

| نوع | الوصف |
| :- | :- |
| double | إذا لم تكن كلتا الشكلين الهندسيين غير [IGeometry.is_empty](/psd/python-net/aspose.gis.geometries/igeometry/) - تكون المسافة بين أقرب نقطتين من الشكلين.<br/>            إذا كان أحد الشكلين على الأقل فارغًا يتم إرجاع -1. |


### Method: get_extent() {#get_extent__28}


```
 get_extent() 
```

يحسب ويعيد نطاقًا محيطًا لهذه الهندسة.

**Returns**

| نوع | الوصف |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | امتداد حدودي لهذه الهندسة. |


### Method: get_length() {#get_length__29}


```
 get_length() 
```

يحسب طول هذه الهندسة.

**Returns**

| نوع | الوصف |
| :- | :- |
| double | طول هذه الهندسة.<br/>            المحيط إذا كانت هذه [Polygon](/psd/python-net/aspose.gis.geometries/polygon/).<br/>            مجموع أطوال عناصر هذه الهندسة إذا كانت هذه الهندسة [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: intersection(other) {#intersection_other_30}


```
 intersection(other) 
```

يبني تقاطعًا بين هذه الهندسة وهندسة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة لحساب التقاطع معها. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة تمثل تقاطع هذه الهندسة ومعطى. هندسة النتيجة تحتوي على<br/>            مجموعة نقاط موجودة في كل من هذه الهندسة والمعطى. |


### Method: intersects(extent) {#intersects_extent_31}


```
 intersects(extent) 
```

يحدد ما إذا كانت هذه الهندسة تتقاطع مع نطاق محدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | الامتداد. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <see langword="true" /> إذا كان هذا الشكل الهندسي يتقاطع مع النطاق؛ <see langword="false" /> وإلا. |


### Method: intersects(other) {#intersects_other_32}


```
 intersects(other) 
```

يحدد ما إذا كانت هذه الهندسة وهندسة محددة تتقاطع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <see langword="true" /> إذا كان هذا الشكل الهندسي \"يتقاطع مكانيًا\" مع شكل هندسي آخر. <see langword="false" /> وإلا. |


### Method: is_clockwise() {#is_clockwise__33}


```
 is_clockwise() 
```

يحدد ما إذا كان الحلقة لها دوران باتجاه عقارب الساعة.

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <see langword="true" /> إذا كان باتجاه عقارب الساعة؛ وإلا <see langword="false" />. |


### Method: overlaps(other) {#overlaps_other_34}


```
 overlaps(other) 
```

يحدد ما إذا كانت هذه الهندسة تتداخل مع هندسة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <see langword="true" /> إذا كان هذا الشكل الهندسي \"يتداخل مكانيًا\" مع شكل هندسي آخر. <see langword="false" /> وإلا. |


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_35}


```
 relate(other, intersection_pattern_matrix) 
```

يحدد ما إذا كانت مصفوفة تقاطع DE-9IM لهذه الهندسة وهندسة محددة تطابق النمط المقدم.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة. |
| intersection_pattern_matrix | string | نمط للمطابقة معه.<br/>            يجب أن تكون هذه سلسلة بطول يساوي 9.<br/>            كل حرف من السلسلة يمثل البُعد المتوقع لتقاطع:<br/>            <ul><br/>            <li>الحرف 0 - بين داخل الأشكال الهندسية.</li><br/>            <li>الحرف 1 - بين داخل هذا الشكل الهندسي وحدود شكل هندسي آخر.</li><br/>            <li>الحرف 2 - بين داخل هذا الشكل الهندسي وخارج شكل هندسي آخر.</li><br/>            <li>الحرف 3 - بين حدود هذا الشكل الهندسي وداخل شكل هندسي آخر.</li><br/>            <li>الحرف 4 - بين حدود الأشكال الهندسية.</li><br/>            <li>الحرف 5 - بين حدود هذا الشكل الهندسي وخارج شكل هندسي آخر.</li><br/>            <li>الحرف 6 - بين خارج هذا الشكل الهندسي وداخل شكل هندسي آخر.</li><br/>            <li>الحرف 7 - بين خارج هذا الشكل الهندسي وحدود شكل هندسي آخر.</li><br/>            <li>الحرف 8 - بين خارج الأشكال الهندسية.</li><br/>            </ul><br/>            القيم الممكنة لكل حرف هي:<br/>            <ul><br/>            <li>* - أي قيمة؛</li><br/>            <li>F - لا تقاطع؛</li><br/>            <li>T - أي تقاطع؛</li><br/>            <li>0 - تقاطع نقطة (مثال: نقطة مشتركة);</li><br/>            <li>1 - تقاطع خط (مثال: قطعة خط مشتركة);</li><br/>            <li>2 - تقاطع مساحة (مثال: جزء مشترك من مضلع);</li><br/>            </ul><br/>            على سبيل المثال، نمط التقاطع \"F0*******\" يعني أنه لا يجب أن يكون هناك تقاطع بين داخل الأشكال الهندسية<br/>            ويجب أن يكون تقاطع حدود الأشكال الهندسية نقطة.<br/>            راجع مواصفة OpenGIS Simple Features لمزيد من التفاصيل حول نمط مصفوفة التقاطع. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <see langword="true" /> إذا كانت مصفوفة التقاطع هذه تطابق النمط؛ <see langword="false" /> وإلا. |


### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__36}


```
 replace_polygons_by_lines() 
```

يحصل على المضلعات الممثلة كخطوط لهذه الهندسة.

**Returns**

| نوع | الوصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | شكل هندسي لا يحتوي على أشكال مضلعة. تم تطبيق التحويلات التالية:<br/>            <ul><br/>            <li> يتم تحويل [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s إلى خطية<br/>            (تحويل إلى [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s)</li><br/>            <li> يتم دمج [GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s في [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s</li><br/>            </ul> |


### Method: round_m(digits) {#round_m_digits_37}


```
 round_m(digits) 
```

يقرب إحداثي M إلى عدد محدد من الأرقام العشرية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| أرقام | int | عدد الأرقام العشرية. |

### Method: round_xy(digits) {#round_xy_digits_38}


```
 round_xy(digits) 
```

يقرب إحداثيات X و Y إلى عدد محدد من الأرقام العشرية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| أرقام | int | عدد الأرقام العشرية. |

### Method: round_z(digits) {#round_z_digits_39}


```
 round_z(digits) 
```

يقرب إحداثي Z إلى عدد محدد من الأرقام العشرية.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| أرقام | int | عدد الأرقام العشرية. |

### Method: spatially_contains(other) {#spatially_contains_other_40}


```
 spatially_contains(other) 
```

يحدد ما إذا كانت هذه الهندسة تحتوي مكانيًا على هندسة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <see langword="true" /> إذا كان هذا الشكل الهندسي \"يحتوي مكانيًا\" على شكل هندسي آخر. <see langword="false" /> وإلا. |


### Method: spatially_equals(other) {#spatially_equals_other_41}


```
 spatially_equals(other) 
```

يحدد ما إذا كانت هذه الهندسة مساوية مكانيًا لهندسة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <see langword="true" /> إذا كان هذا الشكل الهندسي \"يساوي مكانيًا\" الشكل الهندسي المحدد. <see langword="false" /> وإلا. |


### Method: sym_difference(other) {#sym_difference_other_42}


```
 sym_difference(other) 
```

يبني فرقًا متماثلًا بين هذه الهندسة وهندسة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | شكل هندسي لحساب الفرق المتناظر معه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | شكل هندسي يمثل الفرق المتناظر بين هذا الشكل الهندسي ومعطى. الشكل الناتج يحتوي على<br/>            مجموعة نقاط موجودة في أحد الشكلين ولكن ليست موجودة في كليهما. |


### Method: to_editable() {#to_editable__43}


```
 to_editable() 
```

يحصل على نسخة قابلة للتحرير من هذه الهندسة.

**Returns**

| نوع | الوصف |
| :- | :- |
| [LinearRing](/psd/python-net/aspose.gis.geometries/linearring) | نسخة قابلة للتحرير من هذا الشكل الهندسي. |


### Method: to_linear_geometry() {#to_linear_geometry__44}


```
 to_linear_geometry() 
```

يحصل على نسخة تقريبية أو مكافئة غير منحنية من هذه الهندسة باستخدام <c>tolerance</c> الافتراضي.

**Returns**

| نوع | الوصف |
| :- | :- |
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | أ [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) التي تقرب أو تعادل هذا المنحنى.<br/>            هذا هو ما يعادل <DOM Element: class at 0x2a1791540d0>.ICurve.to_linear_geometry()(float) مع<br/>            <c>tolerance</c> الافتراضي. قيمة <c>tolerance</c> الافتراضية تعتمد على [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)<br/>            لهذه الهندسة:<br/>            <ul><br/>            <li> بالنسبة لنظام الإحداثيات المسقطة (SRS) يكون التسامح 0.001 متر (بوحدات SRS) </li><br/>            <li> بالنسبة لنظام الإحداثيات الجغرافي (SRS) يكون التسامح <c>1e-5</c> درجة (بوحدات SRS) </li><br/>            <li> بالنسبة لنظام إحداثيات غير معروف يكون التسامح <c>1e-5</c> </li><br/>            </ul><br/>            لمزيد من التفاصيل حول التحويلات المطبقة راجع مواصفات <DOM Element: class at 0x2a1791540d0>.ICurve.to_linear_geometry()(float) المواصفات. |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_45}


```
 to_linear_geometry(tolerance) 
```

يحصل على نسخة تقريبية أو مكافئة غير منحنية من هذه الهندسة باستخدام <c>tolerance</c> المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| التسامح | double | ‏<c>tolerance</c> المراد استخدامها. يتم ضمان أن النتيجة تكون أقل من <c>tolerance</c> بعيدًا عن الشكل المنحني<br/>             ما لم يتجاوز عدد النقاط اللازمة لتقويم الشكل الحد الأقصى لكل ربع،<br/>             وهو حاليًا يساوي 10000 نقطة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | A [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) التي تقرب أو تعادل هذا المنحنى:<br/>             <ul><br/>             إذا كان هذا الكائن هو [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) نفسه فإن النتيجة تعادل هذا الكائن<br/>             إذا كان هذا الكائن هو [ICircularString](/psd/python-net/aspose.gis.geometries/icircularstring/) فإن النتيجة هي السلسلة الدائرية التي تم تحويلها إلى خطية باستخدام <paramref name="tolerance" /> المحدد<br/>             إذا كان هذا الكائن هو [ICompoundCurve](/psd/python-net/aspose.gis.geometries/icompoundcurve/) - جميع المنحنيات منه تُحول إلى خطية ثم تُدمج في [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/)<br/>            </ul> |


### Method: to_svg(extent) {#to_svg_extent_46}


```
 to_svg(extent) 
```

يحوّل هذه الهندسة إلى تمثيل Svg.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | النطاق لتحويل هذا الشكل الهندسي إلى Svg |

**Returns**

| نوع | الوصف |
| :- | :- |
| string | تمثيل Svg. |


### Method: touches(other) {#touches_other_47}


```
 touches(other) 
```

يحدد ما إذا كانت هذه الهندسة وهندسة محددة تلامسان.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <see langword="true" /> إذا كان هذا الشكل الهندسي \"يلمس مكانيًا\" شكل هندسي آخر. <see langword="false" /> وإلا. |


### Method: union(other) {#union_other_48}


```
 union(other) 
```

يوحد هذه الهندسة وهندسة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | شكل هندسي للاتحاد معه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | شكل هندسي يمثل اتحاد هذا الشكل الهندسي ومعطى. الشكل الناتج يحتوي على<br/>            مجموعة نقاط موجودة في هذا الشكل الهندسي أو في المعطى. |


### Method: union(other) {#union_other_49}


```
 union(other) 
```

يوحد هذه الهندسة وهندسة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | [IGeometry[]](/psd/python-net/aspose.gis.geometries/igeometry) | شكل هندسي للاتحاد معه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | شكل هندسي يمثل اتحاد هذا الشكل الهندسي ومعطى. الشكل الناتج يحتوي على<br/>            مجموعة نقاط موجودة في هذا الشكل الهندسي أو في المعطى. |


### Method: within(extent) {#within_extent_50}


```
 within(extent) 
```

يحدد ما إذا كانت هذه الهندسة داخل نطاق محدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | الامتداد. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <see langword="true" /> إذا كان هذا الشكل الهندسي داخل النطاق؛ <see langword="false" /> وإلا. |


### Method: within(other) {#within_other_51}


```
 within(other) 
```

يحدد ما إذا كانت هذه الهندسة داخل هندسة محددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <see langword="true" /> إذا كان هذا الشكل الهندسي \"داخل مكانيًا\" شكل هندسي آخر. <see langword="false" /> وإلا. |


