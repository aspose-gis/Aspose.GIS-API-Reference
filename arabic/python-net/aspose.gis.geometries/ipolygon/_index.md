---
title: "فئة IPolygon"
type: docs
weight: 210
url: /ar/python-net/aspose.gis.geometries/ipolygon/
---

**Summary:** A [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) whose boundaries are defined by linear rings.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.IPolygon

**Inheritance:** ICurvePolygon, ISurface, IGeometry

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | يحصل على البُعد الطوبولوجي لهذا [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/).<br/>            إذا كان البُعد غير معروف (مثلاً لمجموعة GEOMETRYCOLLECTION فارغة) يتم إرجاع [GeometryDimension.POINT](/psd/python-net/aspose.gis.geometries/geometrydimension/). |
| exterior_ring | [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring) | r | يحصل على الحلقة الخارجية. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | يحصل على نوع الهندسة. |
| has_curve_geometry | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه الهندسة أو تحتوي على هندسة منحنية (غير خطية). |
| has_m | bool | r | يحصل على قيمة تشير إلى ما إذا كان لهذا الكائن إحداثية M. |
| has_z | bool | r | يحصل على قيمة تشير إلى ما إذا كان لهذا الكائن إحداثية Z. |
| interior_rings_count | int | r | يحصل على عدد الحلقات الداخلية. |
| is_empty | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه الحالة فارغة (تمثل مجموعة نقاط فارغة). |
| is_simple | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن بسيطًا من منظور SFA. |
| is_valid | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن صالحًا. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | يحصل على نظام الإحداثيات المكاني (SpatialReferenceSystem) لهذه الحالة.<br/>            يمكن أن تكون هذه الخاصية <see langword=\"null\" /> إذا كان نظام الإحداثيات المكاني غير معروف. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [as_binary()](#as_binary__1) | يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Binary. |
| [as_binary(variant)](#as_binary_variant_2) | يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Binary. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_3) | يصدّر هذه الهندسة إلى تمثيل صورة. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_4) | يصدّر هذه الهندسة إلى تمثيل صورة. |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_5) | يصدّر هذه الهندسة إلى تمثيل صورة. |
| [as_text()](#as_text__6) | يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Text. |
| [as_text(variant)](#as_text_variant_7) | يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Text. |
| [as_text(variant, format)](#as_text_variant_format_8) | يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Text. |
| [clone()](#clone__9) | ينسخ هذا الكائن. |
| [covered_by(other)](#covered_by_other_10) | يحدد ما إذا كانت هذه الهندسة مغطاة بواسطة هندسة محددة. |
| [covers(other)](#covers_other_11) | يحدد ما إذا كانت هذه الهندسة تغطي هندسة محددة. |
| [crosses(other)](#crosses_other_12) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تتقاطع. |
| [difference(other)](#difference_other_13) | يطرح هندسة محددة من هذه الهندسة. |
| [disjoint(other)](#disjoint_other_14) | يحدد ما إذا كانت هذه الهندسة منفصلة عن هندسة محددة. |
| [get_area()](#get_area__15) | يحسب مساحة هذه الهندسة. |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_16) | يحسب منطقة العازلة حول هذه الهندسة. |
| [get_centroid()](#get_centroid__17) | يحسب مركز الثقل لهذه الهندسة. |
| [get_convex_hull()](#get_convex_hull__18) | يحسب الغلاف المحدب لهذه الهندسة. |
| [get_distance_to(other)](#get_distance_to_other_19) | يحسب المسافة الدنيا بين هذه الهندسة وهندسة محددة. |
| [get_extent()](#get_extent__20) | يحسب ويعيد نطاقًا محيطًا لهذه الهندسة. |
| [get_interior_ring(index)](#get_interior_ring_index_21) | يحصل على الحلقة الداخلية بحسب فهرستها. |
| [get_length()](#get_length__22) | يحسب طول هذه الهندسة. |
| [get_point_on_surface()](#get_point_on_surface__23) | يجد نقطة مضمونة أن تكون على هذا السطح. |
| [intersection(other)](#intersection_other_24) | يبني تقاطعًا بين هذه الهندسة وهندسة محددة. |
| [intersects(extent)](#intersects_extent_25) | يحدد ما إذا كانت هذه الهندسة تتقاطع مع نطاق محدد. |
| [intersects(other)](#intersects_other_26) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تتقاطع. |
| [overlaps(other)](#overlaps_other_27) | يحدد ما إذا كانت هذه الهندسة تتداخل مع هندسة محددة. |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_28) | يحدد ما إذا كانت مصفوفة تقاطع DE-9IM لهذه الهندسة وهندسة محددة تطابق النمط المقدم. |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__29) | يحصل على المضلعات الممثلة كخطوط لهذه الهندسة. |
| [spatially_contains(other)](#spatially_contains_other_30) | يحدد ما إذا كانت هذه الهندسة تحتوي مكانيًا على هندسة محددة. |
| [spatially_equals(other)](#spatially_equals_other_31) | يحدد ما إذا كانت هذه الهندسة مساوية مكانيًا لهندسة محددة. |
| [sym_difference(other)](#sym_difference_other_32) | يبني فرقًا متماثلًا بين هذه الهندسة وهندسة محددة. |
| [to_editable()](#to_editable__33) | يحصل على نسخة قابلة للتحرير من هذه الهندسة. |
| [to_linear_geometry()](#to_linear_geometry__34) | يحصل على نسخة تقريبية أو مكافئة غير منحنية من هذه الهندسة باستخدام <c>tolerance</c> الافتراضي. |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_35) | يحصل على نسخة تقريبية أو مكافئة غير منحنية من هذه الهندسة باستخدام <c>tolerance</c> المحدد. |
| [touches(other)](#touches_other_36) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تلامسان. |
| [union(other)](#union_other_37) | يوحد هذه الهندسة وهندسة محددة. |
| [union(other)](#union_other_38) | يوحد هذه الهندسة وهندسة محددة. |
| [within(extent)](#within_extent_39) | يحدد ما إذا كانت هذه الهندسة داخل نطاق محدد. |
| [within(other)](#within_other_40) | يحدد ما إذا كانت هذه الهندسة داخل هندسة محددة. |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Binary.

**Returns**

| نوع | الوصف |
| :- | :- |
| byte | تمثيل Well-Known Binary لهذه الهندسة. |


### Method: as_binary(variant) {#as_binary_variant_2}


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


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_3}


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

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_4}


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

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_5}


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


### Method: as_text() {#as_text__6}


```
 as_text() 
```

يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Text.

**Returns**

| نوع | الوصف |
| :- | :- |
| string | تمثيل Well-Known Text لهذه الهندسة. |


### Method: as_text(variant) {#as_text_variant_7}


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


### Method: as_text(variant, format) {#as_text_variant_format_8}


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


### Method: clone() {#clone__9}


```
 clone() 
```

ينسخ هذا الكائن.

**Returns**

| نوع | الوصف |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | نسخة هذا الكائن |


### Method: covered_by(other) {#covered_by_other_10}


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


### Method: covers(other) {#covers_other_11}


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


### Method: crosses(other) {#crosses_other_12}


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


### Method: difference(other) {#difference_other_13}


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


### Method: disjoint(other) {#disjoint_other_14}


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


### Method: get_area() {#get_area__15}


```
 get_area() 
```

يحسب مساحة هذه الهندسة.

**Returns**

| نوع | الوصف |
| :- | :- |
| double | مساحة هذه الهندسة.<br/>            مجموع مساحات عناصر هذه الهندسة إذا كانت هذه الهندسة [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_16}


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


### Method: get_centroid() {#get_centroid__17}


```
 get_centroid() 
```

يحسب مركز الثقل لهذه الهندسة.

**Returns**

| نوع | الوصف |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | مركز الثقل لهذه الهندسة. إذا كانت هذه الهندسة فارغة تُرجَع نقطة فارغة.<br/>            مركز الثقل يساوي مركز الثقل لأعلى أبعاد الهندسات في هذه الهندسة<br/>            (مثال: إذا كانت الهندسة تحتوي على نقاط وخطوط، فإن الخطوط فقط تساهم في مركز الثقل). |


### Method: get_convex_hull() {#get_convex_hull__18}


```
 get_convex_hull() 
```

يحسب الغلاف المحدب لهذه الهندسة.

**Returns**

| نوع | الوصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة تمثل الغلاف المحدب لهذه الهندسة.<br/>            إذا لم تحتوي هذه الهندسة على نقاط فإن النتيجة هي [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/).<br/>            إذا كانت هذه الهندسة تحتوي على نقطة واحدة فقط فإن النتيجة هي تلك النقطة.<br/>            إذا كانت هذه الهندسة تحتوي على نقطتين فقط فإن النتيجة هي [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) بالنقاط.<br/>            إذا كانت هذه الهندسة تحتوي على ثلاث نقاط أو أكثر فإن النتيجة هي [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/) الذي يمثل غلافًا محدبًا<br/>            حول جميع نقاط الهندسات. |


### Method: get_distance_to(other) {#get_distance_to_other_19}


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


### Method: get_extent() {#get_extent__20}


```
 get_extent() 
```

يحسب ويعيد نطاقًا محيطًا لهذه الهندسة.

**Returns**

| نوع | الوصف |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | امتداد حدودي لهذه الهندسة. |


### Method: get_interior_ring(index) {#get_interior_ring_index_21}


```
 get_interior_ring(index) 
```

يحصل على الحلقة الداخلية بحسب فهرستها.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| index | int | الفهرس. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring) | الحلقة الداخلية. |


### Method: get_length() {#get_length__22}


```
 get_length() 
```

يحسب طول هذه الهندسة.

**Returns**

| نوع | الوصف |
| :- | :- |
| double | طول هذه الهندسة.<br/>            المحيط إذا كانت هذه [Polygon](/psd/python-net/aspose.gis.geometries/polygon/).<br/>            مجموع أطوال عناصر هذه الهندسة إذا كانت هذه الهندسة [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: get_point_on_surface() {#get_point_on_surface__23}


```
 get_point_on_surface() 
```

يجد نقطة مضمونة أن تكون على هذا السطح.

**Returns**

| نوع | الوصف |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | نقطة على هذا السطح. نقطة فارغة إذا لم يكن لهذا السطح داخل. |


### Method: intersection(other) {#intersection_other_24}


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


### Method: intersects(extent) {#intersects_extent_25}


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


### Method: intersects(other) {#intersects_other_26}


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


### Method: overlaps(other) {#overlaps_other_27}


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


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_28}


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


### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__29}


```
 replace_polygons_by_lines() 
```

يحصل على المضلعات الممثلة كخطوط لهذه الهندسة.

**Returns**

| نوع | الوصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | شكل هندسي لا يحتوي على أشكال مضلعة. تم تطبيق التحويلات التالية:<br/>            <ul><br/>            <li> يتم تحويل [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s إلى خطية<br/>            (تحويل إلى [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s)</li><br/>            <li> يتم دمج [GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s في [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s</li><br/>            </ul> |


### Method: spatially_contains(other) {#spatially_contains_other_30}


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


### Method: spatially_equals(other) {#spatially_equals_other_31}


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


### Method: sym_difference(other) {#sym_difference_other_32}


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


### Method: to_editable() {#to_editable__33}


```
 to_editable() 
```

يحصل على نسخة قابلة للتحرير من هذه الهندسة.

**Returns**

| نوع | الوصف |
| :- | :- |
| [Polygon](/psd/python-net/aspose.gis.geometries/polygon) | نسخة قابلة للتحرير من هذا الشكل الهندسي. |


### Method: to_linear_geometry() {#to_linear_geometry__34}


```
 to_linear_geometry() 
```

يحصل على نسخة تقريبية أو مكافئة غير منحنية من هذه الهندسة باستخدام <c>tolerance</c> الافتراضي.

**Returns**

| نوع | الوصف |
| :- | :- |
| [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon) | شكل هندسي لا يحتوي على أشكال هندسية منحنية. هذا يعادل <DOM Element: class at 0x2a1791a70d0>.IGeometry.to_linear_geometry()(float) مع<br/>            <c>tolerance</c> الافتراضية. يتم تعريف <c>tolerance</c> الافتراضية بواسطة [IGeometry.spatial_reference_system](/psd/python-net/aspose.gis.geometries/igeometry/)<br/>            لهذا الشكل الهندسي:<br/>            <ul><br/>            <li> بالنسبة لنظام إحداثيات مكاني (SRS) الإسقاطي، تكون التسامح 0.001 متر (بوحدات SRS) </li><br/>            <li> بالنسبة لنظام إحداثيات مكاني جغرافي، تكون التسامح <c>1e-5</c> درجة (بوحدات SRS) </li><br/>            <li> بالنسبة لنظام إحداثيات مكاني غير معروف، تكون التسامح <c>1e-5</c> </li><br/>            </ul><br/>            لمزيد من التفاصيل حول التحويلات المطبقة راجع مواصفة <DOM Element: class at 0x2a1791a70d0>.IGeometry.to_linear_geometry()(float). |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_35}


```
 to_linear_geometry(tolerance) 
```

يحصل على نسخة تقريبية أو مكافئة غير منحنية من هذه الهندسة باستخدام <c>tolerance</c> المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| التسامح | double | <c>tolerance</c> المراد استخدامها. النتيجة مضمونة أن تكون أقل من <c>tolerance</c> بعيدًا عن الشكل الهندسي المنحني، ما لم يتجاوز عدد النقاط اللازمة لتقويم الشكل الهندسي الحد الأقصى لكل ربع وهو حاليًا يساوي 10000 نقطة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon) | شكل هندسي لا يحتوي على أشكال هندسية منحنية. يتم تطبيق التحويلات التالية:<br/>            <ul><br/>            <li> يتم تقويم [GeometryType.CIRCULAR_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s<br/>            (تحويلها إلى [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s مع <paramref name=\"tolerance\" /> المحدد) </li><br/>            <li> يتم دمج [GeometryType.COMPOUND_CURVE](/psd/python-net/aspose.gis.geometries/geometrytype/)s في <c>LineString</c>s </li><br/>            <li> يتم تحويل [GeometryType.CURVE_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s إلى [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s </li><br/>            <li> يتم تحويل [GeometryType.MULTI_CURVE](/psd/python-net/aspose.gis.geometries/geometrytype/)s إلى [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s </li><br/>            <li> يتم تحويل [GeometryType.MULTI_SURFACE](/psd/python-net/aspose.gis.geometries/geometrytype/)s إلى [GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s </li><br/>            </ul><br/>            نتيجةً لذلك، تكون قيمة [IGeometry.has_curve_geometry](/psd/python-net/aspose.gis.geometries/igeometry/) للشكل الهندسي الناتج <see langword=\"false\" />. |


### Method: touches(other) {#touches_other_36}


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


### Method: union(other) {#union_other_37}


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


### Method: union(other) {#union_other_38}


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


### Method: within(extent) {#within_extent_39}


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


### Method: within(other) {#within_other_40}


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


