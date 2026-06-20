---
title: "MultiLineString 类"
type: docs
weight: 260
url: /zh/python-net/aspose.gis.geometries/multilinestring/
---

**Summary:** A [MultiLineString](/psd/python-net/aspose.gis.geometries/multilinestring/) is a one-dimensional [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/) <br/>            whose elements are [LineString](/psd/python-net/aspose.gis.geometries/linestring/)s.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.MultiLineString

**Inheritance:** IGeometry, IGeometryCollection, IMultiCurve, IMultiLineString, MultiCurve

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MultiLineString()](#MultiLineString__1) | 初始化 [MultiLineString](/psd/python-net/aspose.gis.geometries/multilinestring/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| coordinate_dimension | int | r | 获取此 [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) 的坐标维度数量。 |
| 计数 | 整数 | r | 获取此集合中几何对象的数量。 |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | 获取此 [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) 的拓扑维度。 |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | 获取几何体的类型。 |
| has_curve_geometry | bool | r | 获取一个值，指示此几何体是否为或包含曲线（非线性）几何体。 |
| has_m | bool | r/w | 获取一个值，指示此实例是否具有 M 坐标。 |
| has_z | bool | r/w | 获取一个值，指示此实例是否具有 Z 坐标。 |
| is_closed | bool | r | 确定此曲线是否闭合。 |
| is_empty | bool | r | 获取一个值，指示此实例是否为空（表示空点集）。 |
| is_simple | bool | r | 获取一个值，指示此实例从 SFA 角度是否为简单。 |
| is_valid | bool | r | 获取一个值，指示此实例是否有效。 |
| null [static] | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | r | 获取一个 null geometry 实例。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | 获取此实例的 SpatialReferenceSystem。<br/>            如果 SpatialReferenceSystem 未知，此属性可以为 <see langword="null" />。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(geometry)](#add_geometry_1) | 将指定的几何体添加到集合中。 |
| [add_range(geometries)](#add_range_geometries_2) | 将指定的多个几何体添加到集合中。 |
| [as_binary()](#as_binary__3) | 将此几何体转换为其 Well-Known Binary 表示形式。 |
| [as_binary(variant)](#as_binary_variant_4) | 将此几何体转换为其 Well-Known Binary 表示形式。 |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_5) | 将此几何体导出为图像表示形式。 |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_6) | 将此几何体导出为图像表示形式。 |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_7) | 将此几何体导出为图像表示形式。 |
| [as_text()](#as_text__8) | 将此几何体转换为其 Well-Known Text 表示形式。 |
| [as_text(variant)](#as_text_variant_9) | 将此几何体转换为其 Well-Known Text 表示形式。 |
| [as_text(variant, format)](#as_text_variant_format_10) | 将此几何体转换为其 Well-Known Text 表示形式。 |
| [clone()](#clone__11) | 克隆此实例。 |
| [covered_by(other)](#covered_by_other_12) | 确定此几何体是否被指定的几何体覆盖。 |
| [covers(other)](#covers_other_13) | 确定此几何体是否覆盖指定的几何体。 |
| [crosses(other)](#crosses_other_14) | 确定此几何体与指定几何体是否相交。 |
| [difference(other)](#difference_other_15) | 从此几何体中减去指定的几何体。 |
| [disjoint(other)](#disjoint_other_16) | 确定此几何体是否与指定几何体不相交。 |
| [from_binary(wkb)](#from_binary_wkb_17) | 从其 Well-Known Binary 表示创建几何体。 |
| [from_binary(wkb, spatial_reference_system)](#from_binary_wkb_spatial_reference_system_18) | 从其 Well-Known Binary 表示创建几何体。 |
| [from_text(wkt)](#from_text_wkt_19) | 从其 Well-Known Text 表示创建几何体。 |
| [from_text(wkt, spatial_reference_system)](#from_text_wkt_spatial_reference_system_20) | 从其 Well-Known Text 表示创建几何体。 |
| [get_area()](#get_area__21) | 计算此几何体的面积。 |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_22) | 计算此几何体周围的缓冲区。 |
| [get_centroid()](#get_centroid__23) | 计算此几何体的质心。 |
| [get_convex_hull()](#get_convex_hull__24) | 计算此几何体的凸包。 |
| [get_distance_to(other)](#get_distance_to_other_25) | 计算此几何体与指定几何体之间的最小距离。 |
| [get_extent()](#get_extent__26) | 计算并返回此几何体的边界范围。 |
| [get_length()](#get_length__27) | 计算此几何体的长度。 |
| [get_point_on_surface()](#get_point_on_surface__28) | 查找一个保证位于此集合中某个表面的点。 |
| [intersection(other)](#intersection_other_29) | 构建此几何体与指定几何体的交集。 |
| [intersects(extent)](#intersects_extent_30) | 确定此几何体是否与指定范围相交。 |
| [intersects(other)](#intersects_other_31) | 确定此几何体与指定几何体是否相交。 |
| [overlaps(other)](#overlaps_other_32) | 确定此几何体是否与指定几何体重叠。 |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_33) | 确定此几何体与指定几何体的 DE-9IM 交叉矩阵是否匹配提供的模式。 |
| [remove_at(index)](#remove_at_index_34) | 从集合中移除指定的几何体。 |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__35) | 获取此几何体中表示为线的多边形。 |
| [round_m(digits)](#round_m_digits_36) | 将 M 坐标四舍五入到指定的小数位数。 |
| [round_xy(digits)](#round_xy_digits_37) | 将 X 和 Y 坐标四舍五入到指定的小数位数。 |
| [round_z(digits)](#round_z_digits_38) | 将 Z 坐标四舍五入到指定的小数位数。 |
| set_empty() | 使此 [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) 为空。 |
| [spatially_contains(other)](#spatially_contains_other_39) | 确定此几何体在空间上是否包含指定几何体。 |
| [spatially_equals(other)](#spatially_equals_other_40) | 确定此几何体在空间上是否等于指定几何体。 |
| [sym_difference(other)](#sym_difference_other_41) | 在此几何体与指定几何体之间构建对称差。 |
| [to_editable()](#to_editable__42) | 获取此几何体的可编辑副本。 |
| [to_linear_geometry()](#to_linear_geometry__43) | 使用默认的 <c>tolerance</c> 获取此几何体的近似或等效的非曲线版本。 |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_44) | 使用指定的 <c>tolerance</c> 获取此几何体的近似或等效的非曲线版本。 |
| [to_svg(extent)](#to_svg_extent_45) | 将此几何体转换为 Svg 表示。 |
| [touches(other)](#touches_other_46) | 确定此几何体与指定几何体是否相接。 |
| [union(other)](#union_other_47) | 合并此几何体和指定几何体。 |
| [union(other)](#union_other_48) | 合并此几何体和指定几何体。 |
| [within(extent)](#within_extent_49) | 确定此几何体是否位于指定范围内。 |
| [within(other)](#within_other_50) | 确定此几何体是否位于指定几何体内部。 |


### Constructor: MultiLineString() {#MultiLineString__1}


```
 MultiLineString() 
```

初始化 [MultiLineString](/psd/python-net/aspose.gis.geometries/multilinestring/) 类的新实例。

### Method: add(geometry) {#add_geometry_1}


```
 add(geometry) 
```

将指定的几何体添加到集合中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 要添加的几何体。 |

### Method: add_range(geometries) {#add_range_geometries_2}


```
 add_range(geometries) 
```

将指定的多个几何体添加到集合中。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 几何体 | System.Collections.Generic.IEnumerable<IGeometry> | 要添加的几何体。 |

### Method: as_binary() {#as_binary__3}


```
 as_binary() 
```

将此几何体转换为其 Well-Known Binary 表示形式。

**Returns**

| 类型 | 描述 |
| :- | :- |
| byte | 此几何体的 Well-Known Binary 表示。 |


### Method: as_binary(variant) {#as_binary_variant_4}


```
 as_binary(variant) 
```

将此几何体转换为其 Well-Known Binary 表示形式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| variant | [WkbVariant](/psd/python-net/aspose.gis.geometries/wkbvariant) | 要使用的 Well-Known Binary 变体。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| byte | 此几何体的 Well-Known Binary 表示。 |


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_5}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

将此几何体导出为图像表示形式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 输出图像的路径。 |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | 地图的宽度。 |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | 地图的高度。 |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | 要使用的渲染器。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 用于渲染的符号化器。如果 <see langword="null" />，则使用默认符号化器。 |

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_6}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

将此几何体导出为图像表示形式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| output_path | string | 输出图像的路径。 |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | 地图的宽度。 |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | 地图的高度。 |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | 要使用的渲染器。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 用于渲染的符号化器。如果 <see langword="null" />，则使用默认符号化器。 |

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_7}


```
 as_image(width, height, renderer, symbolizer) 
```

将此几何体导出为图像表示形式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | 地图的宽度。 |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | 地图的高度。 |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | 要使用的渲染器。 |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | 用于渲染的符号化器。如果 <see langword="null" />，则使用默认符号化器。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| _io.BufferedRandom | 图像作为流。 |


### Method: as_text() {#as_text__8}


```
 as_text() 
```

将此几何体转换为其 Well-Known Text 表示形式。

**Returns**

| 类型 | 描述 |
| :- | :- |
| string | 此几何体的 Well-Known Text 表示。 |


### Method: as_text(variant) {#as_text_variant_9}


```
 as_text(variant) 
```

将此几何体转换为其 Well-Known Text 表示形式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | 要使用的 Well-Known Text 变体。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| string | 此几何体的 Well-Known Text 表示。 |


### Method: as_text(variant, format) {#as_text_variant_format_10}


```
 as_text(variant, format) 
```

将此几何体转换为其 Well-Known Text 表示形式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | 要使用的 Well-Known Text 变体。 |
| format | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | 用于转换为字符串的坐标格式。请参阅 [NumericFormat](/psd/python-net/aspose.gis/numericformat/) 获取。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| string | 此几何体的 Well-Known Text 表示。 |


### Method: clone() {#clone__11}


```
 clone() 
```

克隆此实例。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | 此实例的克隆。 |


### Method: covered_by(other) {#covered_by_other_12}


```
 covered_by(other) 
```

确定此几何体是否被指定的几何体覆盖。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 几何体。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <see langword="true" /> 如果此几何体被另一个几何体“空间覆盖”。 <see langword="false" /> 否则。 |


### Method: covers(other) {#covers_other_13}


```
 covers(other) 
```

确定此几何体是否覆盖指定的几何体。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 几何体。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <see langword="true" /> 如果此几何体“空间覆盖”另一个几何体。 <see langword="false" /> 否则。 |


### Method: crosses(other) {#crosses_other_14}


```
 crosses(other) 
```

确定此几何体与指定几何体是否相交。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 几何体。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <see langword="true" /> 如果此几何体“空间相交”另一个几何体。 <see langword="false" /> 否则。 |


### Method: difference(other) {#difference_other_15}


```
 difference(other) 
```

从此几何体中减去指定的几何体。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 用于减法的几何体。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 表示此几何体与参数之间差异的几何体。结果几何体包含<br/>            在此几何体中存在但在参数中不存在的点集。 |


### Method: disjoint(other) {#disjoint_other_16}


```
 disjoint(other) 
```

确定此几何体是否与指定几何体不相交。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 几何体。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <see langword=\"true\" /> 如果此几何体与另一个几何体“空间上不相交”。 <see langword=\"false\" /> 否则。 |


### Method: from_binary(wkb)  [static] {#from_binary_wkb_17}


```
 from_binary(wkb) 
```

从其 Well-Known Binary 表示创建几何体。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| wkb | byte | 几何体的 Well-Known Binary 表示。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 由参数表示的几何体。 |


### Method: from_binary(wkb, spatial_reference_system)  [static] {#from_binary_wkb_spatial_reference_system_18}


```
 from_binary(wkb, spatial_reference_system) 
```

从其 Well-Known Binary 表示创建几何体。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| wkb | byte | 几何体的 Well-Known Binary 表示。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 要分配给几何体的空间参考系统。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 由参数表示的几何体。 |


### Method: from_text(wkt)  [static] {#from_text_wkt_19}


```
 from_text(wkt) 
```

从其 Well-Known Text 表示创建几何体。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| wkt | string | 几何体的 Well-Known Text 表示。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 由参数表示的几何体。 |


### Method: from_text(wkt, spatial_reference_system)  [static] {#from_text_wkt_spatial_reference_system_20}


```
 from_text(wkt, spatial_reference_system) 
```

从其 Well-Known Text 表示创建几何体。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| wkt | string | 几何体的 Well-Known Text 表示。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 要分配给几何体的空间参考系统。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 由参数表示的几何体。 |


### Method: get_area() {#get_area__21}


```
 get_area() 
```

计算此几何体的面积。

**Returns**

| 类型 | 描述 |
| :- | :- |
| double | 此几何体的面积。<br/>            如果此几何体是 [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/)，则为其元素面积的总和。 |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_22}


```
 get_buffer(distance, quadrant_segments) 
```

计算此几何体周围的缓冲区。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 距离 | double | 缓冲区宽度（以空间参考单位计）。 |
| quadrant_segments | 整数 | 用于近似 90 度曲率的段数。<br/>            该数值越大，对曲线的近似越好。<br/>            默认值为 30。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 表示所有位于距离此几何体指定距离范围内的点的几何体。<br/>            结果的类型可以是 [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/)、[IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) 或 [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/)。 |


### Method: get_centroid() {#get_centroid__23}


```
 get_centroid() 
```

计算此几何体的质心。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | 此几何体的质心。如果此几何体为空，则返回空点。<br/>            质心等于此几何体中最高维度几何体的质心<br/>            （例如，如果几何体同时包含点和线，则仅线的质心会被计入）。 |


### Method: get_convex_hull() {#get_convex_hull__24}


```
 get_convex_hull() 
```

计算此几何体的凸包。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 表示此几何体凸包的几何体。<br/>            如果此几何体没有点，则结果为 [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/)。<br/>            如果此几何体只有一个点，则结果就是该点。<br/>            如果此几何体只有两个点，则结果为带有这两个点的 [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/)。<br/>            如果此几何体有三个或更多点，则结果为表示所有几何体点凸包的 [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/)。 |


### Method: get_distance_to(other) {#get_distance_to_other_25}


```
 get_distance_to(other) 
```

计算此几何体与指定几何体之间的最小距离。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 用于寻找距离的几何体。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| double | 如果两个几何体都不是 [IGeometry.is_empty](/psd/python-net/aspose.gis.geometries/igeometry/)——则返回几何体最近点之间的距离。<br/>            如果至少有一个几何体为空，则返回 -1。 |


### Method: get_extent() {#get_extent__26}


```
 get_extent() 
```

计算并返回此几何体的边界范围。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | 此几何体的边界范围。 |


### Method: get_length() {#get_length__27}


```
 get_length() 
```

计算此几何体的长度。

**Returns**

| 类型 | 描述 |
| :- | :- |
| double | 此几何体的长度。<br/>            如果它是 [Polygon](/psd/python-net/aspose.gis.geometries/polygon/)，则为周长。<br/>            如果此几何体是 [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/)，则为其元素长度的总和。 |


### Method: get_point_on_surface() {#get_point_on_surface__28}


```
 get_point_on_surface() 
```

查找一个保证位于此集合中某个表面的点。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | 位于某个表面上的点。如果此集合不包含表面或所有表面均为空，则返回空点。 |


### Method: intersection(other) {#intersection_other_29}


```
 intersection(other) 
```

构建此几何体与指定几何体的交集。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 用于计算交集的几何体。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 表示此几何体与参数交集的几何体。结果几何体包含<br/>            同时存在于此几何体和参数中的点集。 |


### Method: intersects(extent) {#intersects_extent_30}


```
 intersects(extent) 
```

确定此几何体是否与指定范围相交。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 范围。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <see langword=\"true\" /> 如果此几何体与范围相交；<see langword=\"false\" /> 否则。 |


### Method: intersects(other) {#intersects_other_31}


```
 intersects(other) 
```

确定此几何体与指定几何体是否相交。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 几何体。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <see langword=\"true\" /> 如果此几何体“空间相交”另一个几何体。<see langword=\"false\" /> 否则。 |


### Method: overlaps(other) {#overlaps_other_32}


```
 overlaps(other) 
```

确定此几何体是否与指定几何体重叠。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 几何体。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <see langword=\"true\" /> 如果此几何体“空间重叠”另一个几何体。<see langword=\"false\" /> 否则。 |


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_33}


```
 relate(other, intersection_pattern_matrix) 
```

确定此几何体与指定几何体的 DE-9IM 交叉矩阵是否匹配提供的模式。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 几何体。 |
| intersection_pattern_matrix | string | 用于匹配的模式。<br/>            这应该是长度为 9 的字符串。<br/>            字符串的每个字符表示预期的相交维度：<br/>            <ul><br/>            <li>字符 0 - 几何体内部之间。</li><br/>            <li>字符 1 - 此几何体内部与另一几何体边界之间。</li><br/>            <li>字符 2 - 此几何体内部与另一几何体外部之间。</li><br/>            <li>字符 3 - 此几何体边界与另一几何体内部之间。</li><br/>            <li>字符 4 - 几何体边界之间。</li><br/>            <li>字符 5 - 此几何体边界与另一几何体外部之间。</li><br/>            <li>字符 6 - 此几何体外部与另一几何体内部之间。</li><br/>            <li>字符 7 - 此几何体外部与另一几何体边界之间。</li><br/>            <li>字符 8 - 几何体外部之间。</li><br/>            </ul><br/>            每个字符的可能取值为：<br/>            <ul><br/>            <li>* - 任意值；</li><br/>            <li>F - 无相交；</li><br/>            <li>T - 任意相交；</li><br/>            <li>0 - 点相交（例如共享点）；</li><br/>            <li>1 - 线相交（例如共享线段）；</li><br/>            <li>2 - 面相交（例如共享多边形部分）；</li><br/>            </ul><br/>            例如，交叉模式 \"F0*******\" 表示几何体内部之间不应有相交，而几何体边界之间的相交必须是一个点。<br/>            有关交叉矩阵模式的更多细节，请参阅 OpenGIS Simple Features Specification。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <see langword=\"true\" /> 如果此交叉矩阵匹配模式；<see langword=\"false\" /> 否则。 |


### Method: remove_at(index) {#remove_at_index_34}


```
 remove_at(index) 
```

从集合中移除指定的几何体。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| index | 整数 | 要移除的几何体的索引。 |

### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__35}


```
 replace_polygons_by_lines() 
```

获取此几何体中表示为线的多边形。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IGeometryCollection](/psd/python-net/aspose.gis.geometries/igeometrycollection) | 一种没有多边形几何体的几何体。应用以下转换：<br/>            <ul><br/>            <li> [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) 被线性化<br/>            (转换为 [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/))</li><br/>            <li>[GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) 被合并为 [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)</li><br/>            </ul> |


### Method: round_m(digits) {#round_m_digits_36}


```
 round_m(digits) 
```

将 M 坐标四舍五入到指定的小数位数。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| digits | 整数 | 小数位数。 |

### Method: round_xy(digits) {#round_xy_digits_37}


```
 round_xy(digits) 
```

将 X 和 Y 坐标四舍五入到指定的小数位数。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| digits | 整数 | 小数位数。 |

### Method: round_z(digits) {#round_z_digits_38}


```
 round_z(digits) 
```

将 Z 坐标四舍五入到指定的小数位数。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| digits | 整数 | 小数位数。 |

### Method: spatially_contains(other) {#spatially_contains_other_39}


```
 spatially_contains(other) 
```

确定此几何体在空间上是否包含指定几何体。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 几何体。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <see langword=\"true\" /> 如果此几何体“空间包含”另一个几何体。<see langword=\"false\" /> 否则。 |


### Method: spatially_equals(other) {#spatially_equals_other_40}


```
 spatially_equals(other) 
```

确定此几何体在空间上是否等于指定几何体。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 几何体。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <see langword=\"true\" /> 如果此几何体“空间等于”指定的几何体。<see langword=\"false\" /> 否则。 |


### Method: sym_difference(other) {#sym_difference_other_41}


```
 sym_difference(other) 
```

在此几何体与指定几何体之间构建对称差。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 用于计算对称差的几何体。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 表示此几何体与参数的对称差的几何体。结果几何体包含<br/> 出现在其中一个几何体但不同时出现在两者中的点集合。 |


### Method: to_editable() {#to_editable__42}


```
 to_editable() 
```

获取此几何体的可编辑副本。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [MultiLineString](/psd/python-net/aspose.gis.geometries/multilinestring) | 此几何体的可编辑副本。 |


### Method: to_linear_geometry() {#to_linear_geometry__43}


```
 to_linear_geometry() 
```

使用默认的 <c>tolerance</c> 获取此几何体的近似或等效的非曲线版本。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IMultiLineString](/psd/python-net/aspose.gis.geometries/imultilinestring) | 一个近似或等价于此 [IMultiCurve](/psd/python-net/aspose.gis.geometries/imulticurve/) 的 [IMultiLineString](/psd/python-net/aspose.gis.geometries/imultilinestring/)。<br/>            这相当于 <DOM Element: class at 0x2a179241f70>.IMultiCurve.to_linear_geometry()(float) 使用默认的 <c>tolerance</c>。默认的 <c>tolerance</c> 值取决于此几何体的 [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)<br/>            ：<ul><br/>            <li> 对于投影坐标系，容差为 0.001 米（以坐标系单位计） </li><br/>            <li> 对于地理坐标系，容差为 <c>1e-5</c> 度（以坐标系单位计） </li><br/>            <li> 对于未知坐标系，容差为 <c>1e-5</c> </li><br/>            </ul><br/>            有关应用的转换的更多细节，请参阅 <DOM Element: class at 0x2a179241f70>.IMultiCurve.to_linear_geometry()(float) 规范。 |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_44}


```
 to_linear_geometry(tolerance) 
```

使用指定的 <c>tolerance</c> 获取此几何体的近似或等效的非曲线版本。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| tolerance | double | 使用的 <c>tolerance</c>。结果保证距离曲线几何体的 <c>tolerance</c> 小于该值，除非线性化几何体所需的点数超过每象限的最大值，<br/> 当前为 10000 点。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IMultiLineString](/psd/python-net/aspose.gis.geometries/imultilinestring) | 一个近似或等价于此 [IMultiCurve](/psd/python-net/aspose.gis.geometries/imulticurve/) 的 [IMultiLineString](/psd/python-net/aspose.gis.geometries/imultilinestring/)：<br/>             <ul><br/>             如果此对象本身是 [IMultiLineString](/psd/python-net/aspose.gis.geometries/imultilinestring/)，结果等价于该对象<br/>             如果此对象不是 [IMultiLineString]，则所有曲线被线性化并创建新的 <c>IMultiLineString</c><br/>            </ul> |


### Method: to_svg(extent) {#to_svg_extent_45}


```
 to_svg(extent) 
```

将此几何体转换为 Svg 表示。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 将此几何体转换为 Svg 的范围 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| string | Svg 表示。 |


### Method: touches(other) {#touches_other_46}


```
 touches(other) 
```

确定此几何体与指定几何体是否相接。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 几何体。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <see langword=\"true\" /> 如果此几何体“空间相切”另一个几何体。<see langword=\"false\" /> 否则。 |


### Method: union(other) {#union_other_47}


```
 union(other) 
```

合并此几何体和指定几何体。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 用于合并的几何体。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 表示此几何体与参数的并集的几何体。结果几何体包含<br/> 出现在此几何体或参数中的点集合。 |


### Method: union(other) {#union_other_48}


```
 union(other) 
```

合并此几何体和指定几何体。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [IGeometry[]](/psd/python-net/aspose.gis.geometries/igeometry) | 用于合并的几何体。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 表示此几何体与参数的并集的几何体。结果几何体包含<br/> 出现在此几何体或参数中的点集合。 |


### Method: within(extent) {#within_extent_49}


```
 within(extent) 
```

确定此几何体是否位于指定范围内。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 范围。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <see langword=\"true\" /> 如果此几何体在范围内；<see langword=\"false\" /> 否则。 |


### Method: within(other) {#within_other_50}


```
 within(other) 
```

确定此几何体是否位于指定几何体内部。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | 几何体。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | <see langword=\"true\" /> 如果此几何体“空间位于”另一个几何体内部。<see langword=\"false\" /> 否则。 |


