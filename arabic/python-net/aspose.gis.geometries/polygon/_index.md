---
title: "فئة Polygon"
type: docs
weight: 310
url: /ar/python-net/aspose.gis.geometries/polygon/
---

**Summary:** A [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) is a planar surface,<br/>            defined by 1 exterior boundary and 0 or more interior boundaries.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.Polygon

**Inheritance:** IGeometry, ISurface, IPolygon, ICurvePolygon, Surface

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Polygon()](#Polygon__1) | يُنشئ نسخة جديدة من الفئة [Polygon](/psd/python-net/aspose.gis.geometries/polygon/). |
| [Polygon(exterior_ring)](#Polygon_exterior_ring_2) | يُنشئ نسخة جديدة من الفئة [Polygon](/psd/python-net/aspose.gis.geometries/polygon/). |
| [Polygon(exterior_ring, interior_rings)](#Polygon_exterior_ring_interior_rings_3) | يُنشئ نسخة جديدة من الفئة [Polygon](/psd/python-net/aspose.gis.geometries/polygon/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| coordinate_dimension | int | r | يحصل على عدد أبعاد الإحداثيات لهذا [Geometry](/psd/python-net/aspose.gis.geometries/geometry/). |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | يحصل على البُعد الطوبولوجي لهذا [Geometry](/psd/python-net/aspose.gis.geometries/geometry/). |
| exterior_ring | [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring) | r/w | يحصل على الحلقة الخارجية. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | يحصل على نوع الهندسة. |
| has_curve_geometry | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه الهندسة أو تحتوي على هندسة منحنية (غير خطية). |
| has_m | bool | قراءة/كتابة | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على إحداثية M. |
| has_z | bool | قراءة/كتابة | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يحتوي على إحداثية Z. |
| interior_rings_count | int | r | يحصل على عدد الحلقات الداخلية. |
| is_empty | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن فارغًا. |
| is_simple | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن بسيطًا من منظور SFA. |
| is_valid | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن صالحًا. |
| null [static] | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | r | يحصل على كائن من الهندسة الفارغة. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | يحصل على SpatialReferenceSystem لهذا الكائن.<br/>            يمكن أن تكون هذه الخاصية <see langword=\"null\" />، إذا كان SpatialReferenceSystem غير معروف.<br/>            تعيين SpatialReferenceSystem جديد لن يقوم بأي تحويل إحداثي، فقط سيتغير المرجع. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_interior_ring(ring)](#add_interior_ring_ring_1) | يضيف حلقة داخلية. |
| [as_binary()](#as_binary__2) | يحوّل هذه الهندسة إلى تمثيلها الثنائي المعروف. |
| [as_binary(variant)](#as_binary_variant_3) | يحوّل هذه الهندسة إلى تمثيلها الثنائي المعروف. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_4) | يصدّر هذه الهندسة إلى تمثيل صورة. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_5) | يصدّر هذه الهندسة إلى تمثيل صورة. |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_6) | يصدّر هذه الهندسة إلى تمثيل صورة. |
| [as_text()](#as_text__7) | يحوّل هذه الهندسة إلى تمثيلها النصي المعروف. |
| [as_text(variant)](#as_text_variant_8) | يحوّل هذه الهندسة إلى تمثيلها النصي المعروف. |
| [as_text(variant, format)](#as_text_variant_format_9) | يحوّل هذه الهندسة إلى تمثيلها النصي المعروف. |
| [clone()](#clone__10) | ينسخ هذا الكائن. |
| [covered_by(other)](#covered_by_other_11) | يحدد ما إذا كانت هذه الهندسة مغطاة بواسطة هندسة محددة. |
| [covers(other)](#covers_other_12) | يحدد ما إذا كانت هذه الهندسة تغطي هندسة محددة. |
| [crosses(other)](#crosses_other_13) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تتقاطع. |
| [difference(other)](#difference_other_14) | يطرح هندسة محددة من هذه الهندسة. |
| [disjoint(other)](#disjoint_other_15) | يحدد ما إذا كانت هذه الهندسة منفصلة عن هندسة محددة. |
| [from_binary(wkb)](#from_binary_wkb_16) | ينشئ هندسة من تمثيلها الثنائي المعروف. |
| [from_binary(wkb, spatial_reference_system)](#from_binary_wkb_spatial_reference_system_17) | ينشئ هندسة من تمثيلها الثنائي المعروف. |
| [from_text(wkt)](#from_text_wkt_18) | ينشئ هندسة من تمثيلها النصي المعروف. |
| [from_text(wkt, spatial_reference_system)](#from_text_wkt_spatial_reference_system_19) | ينشئ هندسة من تمثيلها النصي المعروف. |
| [get_area()](#get_area__20) | يحسب مساحة هذه الهندسة. |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_21) | يحسب منطقة عازلة حول هذه الهندسة. |
| [get_centroid()](#get_centroid__22) | يحسب مركز الثقل لهذه الهندسة. |
| [get_convex_hull()](#get_convex_hull__23) | يحسب الغلاف المحدب لهذه الهندسة. |
| [get_distance_to(other)](#get_distance_to_other_24) | يحسب الحد الأدنى للمسافة بين هذه الهندسة وهندسة محددة. |
| [get_extent()](#get_extent__25) | يحسب ويعيد نطاقًا محيطًا لهذه الهندسة. |
| [get_interior_ring(index)](#get_interior_ring_index_26) | يحصل على الحلقة الداخلية حسب فهرستها. |
| [get_length()](#get_length__27) | يحسب طول هذه الهندسة. |
| [get_point_on_surface()](#get_point_on_surface__28) | يجد نقطة مضمونة أن تكون على هذا المضلع. |
| [intersection(other)](#intersection_other_29) | يبني تقاطعًا بين هذه الهندسة وهندسة محددة. |
| [intersects(extent)](#intersects_extent_30) | يحدد ما إذا كانت هذه الهندسة تتقاطع مع نطاق محدد. |
| [intersects(other)](#intersects_other_31) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تتقاطع. |
| [overlaps(other)](#overlaps_other_32) | يحدد ما إذا كانت هذه الهندسة تتداخل مع هندسة محددة. |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_33) | يحدد ما إذا كانت مصفوفة تقاطع DE-9IM لهذه الهندسة وهندسة محددة تطابق النمط المقدم. |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__34) | يحصل على المضلعات الممثلة كخطوط لهذه الهندسة. |
| [round_m(digits)](#round_m_digits_35) | يقرب إحداثي M إلى عدد محدد من الأرقام العشرية. |
| [round_xy(digits)](#round_xy_digits_36) | يقرب إحداثيات X و Y إلى عدد محدد من الأرقام العشرية. |
| [round_z(digits)](#round_z_digits_37) | يقرب إحداثي Z إلى عدد محدد من الأرقام العشرية. |
| set_empty() | يجعل هذه [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) فارغة. |
| [spatially_contains(other)](#spatially_contains_other_38) | يحدد ما إذا كانت هذه الهندسة تحتوي مكانيًا على هندسة محددة. |
| [spatially_equals(other)](#spatially_equals_other_39) | يحدد ما إذا كانت هذه الهندسة مساوية مكانيًا لهندسة محددة. |
| [sym_difference(other)](#sym_difference_other_40) | يبني فرقًا متماثلًا بين هذه الهندسة وهندسة محددة. |
| [to_editable()](#to_editable__41) | يحصل على نسخة قابلة للتحرير من هذه الهندسة. |
| [to_linear_geometry()](#to_linear_geometry__42) | يحصل على نسخة تقريبية أو مكافئة غير منحنية من هذه الهندسة باستخدام <c>tolerance</c> الافتراضية. |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_43) | يحصل على نسخة تقريبية أو مكافئة غير منحنية من هذه الهندسة باستخدام <c>tolerance</c> المحددة. |
| [to_svg(extent)](#to_svg_extent_44) | يترجم هذه الهندسة إلى تمثيل Svg. |
| [touches(other)](#touches_other_45) | يحدد ما إذا كانت هذه الهندسة وهندسة محددة تلامسان. |
| [union(other)](#union_other_46) | يوحد هذه الهندسة وهندسة محددة. |
| [union(other)](#union_other_47) | يوحد هذه الهندسة وهندسة محددة. |
| [within(extent)](#within_extent_48) | يحدد ما إذا كانت هذه الهندسة داخل نطاق محدد. |
| [within(other)](#within_other_49) | يحدد ما إذا كانت هذه الهندسة داخل هندسة محددة. |


### Constructor: Polygon() {#Polygon__1}


```
 Polygon() 
```

يُنشئ نسخة جديدة من الفئة [Polygon](/psd/python-net/aspose.gis.geometries/polygon/).

### Constructor: Polygon(exterior_ring) {#Polygon_exterior_ring_2}


```
 Polygon(exterior_ring) 
```

يُنشئ نسخة جديدة من الفئة [Polygon](/psd/python-net/aspose.gis.geometries/polygon/).

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| exterior_ring | [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring) | الحلقة الخارجية. |

### Constructor: Polygon(exterior_ring, interior_rings) {#Polygon_exterior_ring_interior_rings_3}


```
 Polygon(exterior_ring, interior_rings) 
```

يُنشئ نسخة جديدة من الفئة [Polygon](/psd/python-net/aspose.gis.geometries/polygon/).

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| exterior_ring | [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring) | الحلقة الخارجية. |
| interior_rings | System.Collections.Generic.IEnumerable<ILinearRing> | الحلقات الداخلية. |

### Method: add_interior_ring(ring) {#add_interior_ring_ring_1}


```
 add_interior_ring(ring) 
```

يضيف حلقة داخلية.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| ring | [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring) | الحلقة المراد إضافتها. |

### Method: as_binary() {#as_binary__2}


```
 as_binary() 
```

يحوّل هذه الهندسة إلى تمثيلها الثنائي المعروف.

**Returns**

| نوع | وصف |
| :- | :- |
| byte | تمثيل Well-Known Binary لهذه الهندسة. |


### Method: as_binary(variant) {#as_binary_variant_3}


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


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_4}


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

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_5}


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

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_6}


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


### Method: as_text() {#as_text__7}


```
 as_text() 
```

يحوّل هذه الهندسة إلى تمثيلها النصي المعروف.

**Returns**

| نوع | وصف |
| :- | :- |
| string | تمثيل Well-Known Text لهذه الهندسة. |


### Method: as_text(variant) {#as_text_variant_8}


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


### Method: as_text(variant, format) {#as_text_variant_format_9}


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


### Method: clone() {#clone__10}


```
 clone() 
```

ينسخ هذا الكائن.

**Returns**

| نوع | وصف |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | نسخة متماثلة من هذه الحالة |


### Method: covered_by(other) {#covered_by_other_11}


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


### Method: covers(other) {#covers_other_12}


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


### Method: crosses(other) {#crosses_other_13}


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


### Method: difference(other) {#difference_other_14}


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


### Method: disjoint(other) {#disjoint_other_15}


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


### Method: from_binary(wkb)  [static] {#from_binary_wkb_16}


```
 from_binary(wkb) 
```

ينشئ هندسة من تمثيلها الثنائي المعروف.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| wkb | byte | تمثيل ثنائي معروف (Well-Known Binary) لهندسة. |

**Returns**

| نوع | وصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة ممثلة بالمعامل. |


### Method: from_binary(wkb, spatial_reference_system)  [static] {#from_binary_wkb_spatial_reference_system_17}


```
 from_binary(wkb, spatial_reference_system) 
```

ينشئ هندسة من تمثيلها الثنائي المعروف.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| wkb | byte | تمثيل ثنائي معروف (Well-Known Binary) لهندسة. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني الذي سيُعيّن إلى الهندسة. |

**Returns**

| نوع | وصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة ممثلة بالمعامل. |


### Method: from_text(wkt)  [static] {#from_text_wkt_18}


```
 from_text(wkt) 
```

ينشئ هندسة من تمثيلها النصي المعروف.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| wkt | string | تمثيل نص معروف (Well-Known Text) لهندسة. |

**Returns**

| نوع | وصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة ممثلة بالمعامل. |


### Method: from_text(wkt, spatial_reference_system)  [static] {#from_text_wkt_spatial_reference_system_19}


```
 from_text(wkt, spatial_reference_system) 
```

ينشئ هندسة من تمثيلها النصي المعروف.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| wkt | string | تمثيل نص معروف (Well-Known Text) لهندسة. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني الذي سيُعيّن إلى الهندسة. |

**Returns**

| نوع | وصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة ممثلة بالمعامل. |


### Method: get_area() {#get_area__20}


```
 get_area() 
```

يحسب مساحة هذه الهندسة.

**Returns**

| نوع | وصف |
| :- | :- |
| double | مساحة هذه الهندسة.<br/>            مجموع مساحات عناصر هذه الهندسة إذا كانت هذه الهندسة [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_21}


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


### Method: get_centroid() {#get_centroid__22}


```
 get_centroid() 
```

يحسب مركز الثقل لهذه الهندسة.

**Returns**

| نوع | وصف |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | مركز الثقل لهذه الهندسة. إذا كانت هذه الهندسة فارغة تُرجع نقطة فارغة.<br/>            مركز الثقل يساوي مركز الثقل لأعلى أبعاد الهندسات في هذه الهندسة<br/>            (مثلاً إذا كانت النقاط والخطوط موجودة في الهندسة، فإن الخطوط فقط تساهم في مركز الثقل). |


### Method: get_convex_hull() {#get_convex_hull__23}


```
 get_convex_hull() 
```

يحسب الغلاف المحدب لهذه الهندسة.

**Returns**

| نوع | وصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | هندسة تمثل الغلاف المحدب لهذه الهندسة.<br/>            إذا لم تحتوي هذه الهندسة على نقاط فإن النتيجة هي [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/).<br/>            إذا كان لهذه الهندسة نقطة واحدة فقط فإن النتيجة هي تلك النقطة.<br/>            إذا كان لهذه الهندسة نقطتين فقط فإن النتيجة هي [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) مع النقاط.<br/>            إذا كان لهذه الهندسة ثلاث نقاط أو أكثر فإن النتيجة هي [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/) الذي يمثل غلافًا محدبًا<br/>            حول جميع نقاط الهندسات. |


### Method: get_distance_to(other) {#get_distance_to_other_24}


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


### Method: get_extent() {#get_extent__25}


```
 get_extent() 
```

يحسب ويعيد نطاقًا محيطًا لهذه الهندسة.

**Returns**

| نوع | وصف |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | امتداد حدودي لهذه الهندسة. |


### Method: get_interior_ring(index) {#get_interior_ring_index_26}


```
 get_interior_ring(index) 
```

يحصل على الحلقة الداخلية حسب فهرستها.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الفهرس | int | الفهرس. |

**Returns**

| نوع | وصف |
| :- | :- |
| [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring) | الحلقة الداخلية. |


### Method: get_length() {#get_length__27}


```
 get_length() 
```

يحسب طول هذه الهندسة.

**Returns**

| نوع | وصف |
| :- | :- |
| double | طول هذه الهندسة.<br/>            المحيط إذا كانت هذه [Polygon](/psd/python-net/aspose.gis.geometries/polygon/).<br/>            مجموع أطوال عناصر هذه الهندسة إذا كانت هذه الهندسة [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: get_point_on_surface() {#get_point_on_surface__28}


```
 get_point_on_surface() 
```

يجد نقطة مضمونة أن تكون على هذا المضلع.

**Returns**

| نوع | وصف |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | نقطة على هذا المضلع. نقطة فارغة إذا لم يكن لهذا المضلع داخل. |


### Method: intersection(other) {#intersection_other_29}


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


### Method: intersects(extent) {#intersects_extent_30}


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


### Method: intersects(other) {#intersects_other_31}


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


### Method: overlaps(other) {#overlaps_other_32}


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


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_33}


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


### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__34}


```
 replace_polygons_by_lines() 
```

يحصل على المضلعات الممثلة كخطوط لهذه الهندسة.

**Returns**

| نوع | وصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | شكل هندسي لا يحتوي على أشكال مضلع. يتم تطبيق التحويلات التالية:<br/> <ul><br/> <li> يتم تحويل [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s إلى خطية<br/> (تحويل إلى [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s)</li><br/> <li> يتم دمج [GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s في [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s</li><br/> </ul> |


### Method: round_m(digits) {#round_m_digits_35}


```
 round_m(digits) 
```

يقرب إحداثي M إلى عدد محدد من الأرقام العشرية.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الأرقام | int | عدد الأرقام العشرية. |

### Method: round_xy(digits) {#round_xy_digits_36}


```
 round_xy(digits) 
```

يقرب إحداثيات X و Y إلى عدد محدد من الأرقام العشرية.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الأرقام | int | عدد الأرقام العشرية. |

### Method: round_z(digits) {#round_z_digits_37}


```
 round_z(digits) 
```

يقرب إحداثي Z إلى عدد محدد من الأرقام العشرية.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الأرقام | int | عدد الأرقام العشرية. |

### Method: spatially_contains(other) {#spatially_contains_other_38}


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


### Method: spatially_equals(other) {#spatially_equals_other_39}


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


### Method: sym_difference(other) {#sym_difference_other_40}


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


### Method: to_editable() {#to_editable__41}


```
 to_editable() 
```

يحصل على نسخة قابلة للتحرير من هذه الهندسة.

**Returns**

| نوع | وصف |
| :- | :- |
| [Polygon](/psd/python-net/aspose.gis.geometries/polygon) | نسخة قابلة للتحرير من هذا الشكل الهندسي. |


### Method: to_linear_geometry() {#to_linear_geometry__42}


```
 to_linear_geometry() 
```

يحصل على نسخة تقريبية أو مكافئة غير منحنية من هذه الهندسة باستخدام <c>tolerance</c> الافتراضية.

**Returns**

| نوع | وصف |
| :- | :- |
| [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon) | ‏[IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) يقترب أو يعادل هذا <c>ISurface</c>.<br/> هذا هو المكافئ لـ <DOM Element: class at 0x2a1793609d0>.ISurface.to_linear_geometry()(float) مع<br/> <c>tolerance</c> الافتراضية. قيمة <c>tolerance</c> الافتراضية تعتمد على [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)<br/> لهذا الشكل الهندسي:<br/> <ul><br/> <li> بالنسبة لنظام الإحداثيات المُسقَّط Tolerance هو 0.001 متر (بوحدات نظام الإحداثيات) </li><br/> <li> بالنسبة لنظام الإحداثيات الجغرافي Tolerance هو <c>1e-5</c> درجة (بوحدات نظام الإحداثيات) </li><br/> <li> بالنسبة لنظام إحداثيات غير معروف Tolerance هو <c>1e-5</c> </li><br/> </ul><br/> لمزيد من التفاصيل حول التحويلات المطبقة راجع مواصفة <DOM Element: class at 0x2a1793609d0>.ISurface.to_linear_geometry()(float). |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_43}


```
 to_linear_geometry(tolerance) 
```

يحصل على نسخة تقريبية أو مكافئة غير منحنية من هذه الهندسة باستخدام <c>tolerance</c> المحددة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| التحمل | double | ‏<c>tolerance</c> المراد استخدامها. يضمن أن تكون النتيجة أقل من <c>tolerance</c> بعيدًا عن الشكل الهندسي المنحني، ما لم يتجاوز عدد النقاط اللازمة لتقويم الشكل الهندسي الحد الأقصى لكل ربع،<br/> وهو حاليًا يساوي 10000 نقطة. |

**Returns**

| نوع | وصف |
| :- | :- |
| [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon) | ‏[IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) يقترب أو يعادل هذا <c>ISurface</c>:<br/> <ul><br/> <li> إذا كان هذا الكائن هو [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) نفسه فإن النتيجة تعادل هذا الكائن</li><br/> <li> إذا لم يكن هذا الكائن هو [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) فإنه يتم تقويمه وإنشاء [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/)</li><br/> </ul> |


### Method: to_svg(extent) {#to_svg_extent_44}


```
 to_svg(extent) 
```

يترجم هذه الهندسة إلى تمثيل Svg.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | النطاق لترجمة هذا الشكل الهندسي إلى Svg |

**Returns**

| نوع | وصف |
| :- | :- |
| string | تمثيل Svg. |


### Method: touches(other) {#touches_other_45}


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


### Method: union(other) {#union_other_46}


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


### Method: union(other) {#union_other_47}


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


### Method: within(extent) {#within_extent_48}


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


### Method: within(other) {#within_other_49}


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


