---
title: "Класс CircularString"
type: docs
weight: 10
url: /ru/python-net/aspose.gis.geometries/circularstring/
---

**Summary:** A multi-vertex curve with circular interpolation between points.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.CircularString

**Inheritance:** IGeometry, ICurve, ICircularString, Curve

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [CircularString()](#CircularString__1) | Инициализирует новый экземпляр класса [CircularString](/psd/python-net/aspose.gis.geometries/circularstring/) . |
| [CircularString(collection)](#CircularString_collection_2) | Инициализирует новый экземпляр класса [CircularString](/psd/python-net/aspose.gis.geometries/circularstring/) . |
| [CircularString(other)](#CircularString_other_3) | Инициализирует новый экземпляр класса [CircularString](/psd/python-net/aspose.gis.geometries/circularstring/) . |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| coordinate_dimension | int | r | Возвращает количество координатных измерений для этой [Geometry](/psd/python-net/aspose.gis.geometries/geometry/). |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | Возвращает топологическое измерение этой [Geometry](/psd/python-net/aspose.gis.geometries/geometry/). |
| end_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | Возвращает копию конечной точки кривой. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | Возвращает тип геометрии. |
| has_curve_geometry | bool | r | Возвращает значение, указывающее, является ли эта геометрия или содержит кривую (не линейную) геометрию. |
| has_m | bool | r/w | Возвращает значение, указывающее, имеет ли этот экземпляр координату M. |
| has_z | bool | r/w | Возвращает значение, указывающее, имеет ли этот экземпляр координату Z. |
| is_closed | bool | r | Получает значение, указывающее, замкнута ли кривая. <br/>            Кривая считается замкнутой, если её начальная точка равна конечной точке. |
| is_empty | bool | r | Возвращает значение, указывающее, пуст ли этот экземпляр. |
| is_simple | bool | r | Возвращает значение, указывающее, является ли этот экземпляр простым с точки зрения SFA. |
| is_valid | bool | r | Возвращает значение, указывающее, является ли этот экземпляр действительным. |
| null [static] | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | r | Возвращает экземпляр нулевой геометрии. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Получает SpatialReferenceSystem этого экземпляра.<br/>            Это свойство может быть <see langword="null" />, если SpatialReferenceSystem не установлен.<br/>            Присвоение нового SpatialReferenceSystem не выполнит преобразование координат, изменится только ссылка. |
| start_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | Возвращает копию начальной точки кривой. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add_point(point)](#add_point_point_1) | Добавляет точку в конец круговой строки. |
| [add_point(x, y)](#add_point_x_y_2) | Добавляет точку в конец круговой строки. |
| [add_point(x, y, z)](#add_point_x_y_z_3) | Добавляет точку в конец круговой строки. |
| [add_point(x, y, z, m)](#add_point_x_y_z_m_4) | Добавляет точку в конец круговой строки. |
| [as_binary()](#as_binary__5) | Преобразует эту геометрию в её представление Well-Known Binary. |
| [as_binary(variant)](#as_binary_variant_6) | Преобразует эту геометрию в её представление Well-Known Binary. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_7) | Экспортирует эту геометрию в представление изображения. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_8) | Экспортирует эту геометрию в представление изображения. |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_9) | Экспортирует эту геометрию в представление изображения. |
| [as_text()](#as_text__10) | Преобразует эту геометрию в её представление Well-Known Text. |
| [as_text(variant)](#as_text_variant_11) | Преобразует эту геометрию в её представление Well-Known Text. |
| [as_text(variant, format)](#as_text_variant_format_12) | Преобразует эту геометрию в её представление Well-Known Text. |
| [clone()](#clone__13) | Создаёт клон этого экземпляра. |
| [covered_by(other)](#covered_by_other_14) | Определяет, покрывается ли эта геометрия указанной геометрией. |
| [covers(other)](#covers_other_15) | Определяет, покрывает ли эта геометрия указанную геометрию. |
| [crosses(other)](#crosses_other_16) | Определяет, пересекаются ли эта геометрия и указанная геометрия. |
| [difference(other)](#difference_other_17) | Вычитает указанную геометрию из этой геометрии. |
| [disjoint(other)](#disjoint_other_18) | Определяет, не пересекается ли эта геометрия с указанной геометрией. |
| [from_binary(wkb)](#from_binary_wkb_19) | Создаёт геометрию из её представления в формате Well-Known Binary. |
| [from_binary(wkb, spatial_reference_system)](#from_binary_wkb_spatial_reference_system_20) | Создаёт геометрию из её представления в формате Well-Known Binary. |
| [from_text(wkt)](#from_text_wkt_21) | Создаёт геометрию из её представления в формате Well-Known Text. |
| [from_text(wkt, spatial_reference_system)](#from_text_wkt_spatial_reference_system_22) | Создаёт геометрию из её представления в формате Well-Known Text. |
| [get_area()](#get_area__23) | Вычисляет площадь этой геометрии. |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_24) | Вычисляет буферную область вокруг этой геометрии. |
| [get_centroid()](#get_centroid__25) | Вычисляет центр масс этой геометрии. |
| [get_convex_hull()](#get_convex_hull__26) | Вычисляет выпуклую оболочку этой геометрии. |
| [get_distance_to(other)](#get_distance_to_other_27) | Вычисляет минимальное расстояние между этой геометрией и указанной геометрией. |
| [get_extent()](#get_extent__28) | Вычисляет и возвращает ограничивающий объём этой геометрии. |
| [get_length()](#get_length__29) | Вычисляет длину этой геометрии. |
| [intersection(other)](#intersection_other_30) | Создаёт пересечение между этой геометрией и указанной геометрией. |
| [intersects(extent)](#intersects_extent_31) | Определяет, пересекает ли эта геометрия указанный охват. |
| [intersects(other)](#intersects_other_32) | Определяет, пересекаются ли эта геометрия и указанная геометрия. |
| [overlaps(other)](#overlaps_other_33) | Определяет, перекрывается ли эта геометрия с указанной геометрией. |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_34) | Определяет, соответствует ли матрица пересечения DE-9IM этой геометрии и указанной геометрии заданному шаблону. |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__35) | Получает полигоны, представленные в виде линий этой геометрии. |
| reverse() | Изменяет порядок точек в этом [CircularString](/psd/python-net/aspose.gis.geometries/circularstring/) на обратный. |
| [round_m(digits)](#round_m_digits_36) | Округляет координату M до указанного количества знаков после запятой. |
| [round_xy(digits)](#round_xy_digits_37) | Округляет координаты X и Y до указанного количества знаков после запятой. |
| [round_z(digits)](#round_z_digits_38) | Округляет координату Z до указанного количества знаков после запятой. |
| set_empty() | Делает эту [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) пустой. |
| [spatially_contains(other)](#spatially_contains_other_39) | Определяет, содержит ли эта геометрия пространственно указанную геометрию. |
| [spatially_equals(other)](#spatially_equals_other_40) | Определяет, равна ли эта геометрия пространственно указанной геометрии. |
| [sym_difference(other)](#sym_difference_other_41) | Создает симметричную разность между этой геометрией и указанной геометрией. |
| [to_editable()](#to_editable__42) | Получает редактируемую копию этой геометрии. |
| [to_linear_geometry()](#to_linear_geometry__43) | Получает приближённую или эквивалентную нелинейную версию этой геометрии, используя значение <c>tolerance</c> по умолчанию. |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_44) | Получает приближённую или эквивалентную нелинейную версию этой геометрии, используя указанное значение <c>tolerance</c>. |
| [to_svg(extent)](#to_svg_extent_45) | Преобразует эту геометрию в представление Svg. |
| [touches(other)](#touches_other_46) | Определяет, соприкасаются ли эта геометрия и указанная геометрия. |
| [union(other)](#union_other_47) | Объединяет эту геометрию и указанную геометрию. |
| [union(other)](#union_other_48) | Объединяет эту геометрию и указанную геометрию. |
| [within(extent)](#within_extent_49) | Определяет, находится ли эта геометрия внутри указанного охвата. |
| [within(other)](#within_other_50) | Определяет, находится ли эта геометрия внутри указанной геометрии. |


### Constructor: CircularString() {#CircularString__1}


```
 CircularString() 
```

Инициализирует новый экземпляр класса [CircularString](/psd/python-net/aspose.gis.geometries/circularstring/) .

### Constructor: CircularString(collection) {#CircularString_collection_2}


```
 CircularString(collection) 
```

Инициализирует новый экземпляр класса [CircularString](/psd/python-net/aspose.gis.geometries/circularstring/) .

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| коллекция | System.Collections.Generic.IEnumerable<IPoint> | Коллекция точек. |

### Constructor: CircularString(other) {#CircularString_other_3}


```
 CircularString(other) 
```

Инициализирует новый экземпляр класса [CircularString](/psd/python-net/aspose.gis.geometries/circularstring/) .

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [ICircularString](/psd/python-net/aspose.gis.geometries/icircularstring) | Другая строка, из которой копировать данные. |

### Method: add_point(point) {#add_point_point_1}


```
 add_point(point) 
```

Добавляет точку в конец круговой строки.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Точка для добавления. |

### Method: add_point(x, y) {#add_point_x_y_2}


```
 add_point(x, y) 
```

Добавляет точку в конец круговой строки.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | double | Значение координаты X. |
| y | double | Значение координаты Y. |

### Method: add_point(x, y, z) {#add_point_x_y_z_3}


```
 add_point(x, y, z) 
```

Добавляет точку в конец круговой строки.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | double | Значение координаты X. |
| y | double | Значение координаты Y. |
| z | double | Значение координаты Z. |

### Method: add_point(x, y, z, m) {#add_point_x_y_z_m_4}


```
 add_point(x, y, z, m) 
```

Добавляет точку в конец круговой строки.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | double | Значение координаты X. |
| y | double | Значение координаты Y. |
| z | double | Значение координаты Z. |
| m | double | Значение координаты M. |

### Method: as_binary() {#as_binary__5}


```
 as_binary() 
```

Преобразует эту геометрию в её представление Well-Known Binary.

**Returns**

| Тип | Описание |
| :- | :- |
| byte | Представление этой геометрии в формате Well-Known Binary. |


### Method: as_binary(variant) {#as_binary_variant_6}


```
 as_binary(variant) 
```

Преобразует эту геометрию в её представление Well-Known Binary.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| variant | [WkbVariant](/psd/python-net/aspose.gis.geometries/wkbvariant) | Вариант Well-Known Binary для использования. |

**Returns**

| Тип | Описание |
| :- | :- |
| byte | Представление этой геометрии в формате Well-Known Binary. |


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_7}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

Экспортирует эту геометрию в представление изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к выходному изображению. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Ширина карты. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Высота карты. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Рендерер для использования. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Символизатор для рендеринга. Если <see langword=\"null\" />, используется символизатор по умолчанию. |

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_8}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

Экспортирует эту геометрию в представление изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| output_path | string | Путь к выходному изображению. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Ширина карты. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Высота карты. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Рендерер для использования. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Символизатор для рендеринга. Если <see langword=\"null\" />, используется символизатор по умолчанию. |

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_9}


```
 as_image(width, height, renderer, symbolizer) 
```

Экспортирует эту геометрию в представление изображения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Ширина карты. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Высота карты. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Рендерер для использования. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Символизатор для рендеринга. Если <see langword=\"null\" />, используется символизатор по умолчанию. |

**Returns**

| Тип | Описание |
| :- | :- |
| _io.BufferedRandom | Изображение в виде потока |


### Method: as_text() {#as_text__10}


```
 as_text() 
```

Преобразует эту геометрию в её представление Well-Known Text.

**Returns**

| Тип | Описание |
| :- | :- |
| string | Представление этой геометрии в формате Well-Known Text. |


### Method: as_text(variant) {#as_text_variant_11}


```
 as_text(variant) 
```

Преобразует эту геометрию в её представление Well-Known Text.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | Вариант Well-Known Text для использования. |

**Returns**

| Тип | Описание |
| :- | :- |
| string | Представление этой геометрии в формате Well-Known Text. |


### Method: as_text(variant, format) {#as_text_variant_format_12}


```
 as_text(variant, format) 
```

Преобразует эту геометрию в её представление Well-Known Text.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | Вариант Well-Known Text для использования. |
| format | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Формат координат для преобразования в строку. См. [NumericFormat](/psd/python-net/aspose.gis/numericformat/) для получения. |

**Returns**

| Тип | Описание |
| :- | :- |
| string | Представление этой геометрии в формате Well-Known Text. |


### Method: clone() {#clone__13}


```
 clone() 
```

Создаёт клон этого экземпляра.

**Returns**

| Тип | Описание |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | Клон этого экземпляра |


### Method: covered_by(other) {#covered_by_other_14}


```
 covered_by(other) 
```

Определяет, покрывается ли эта геометрия указанной геометрией.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <see langword=\"true\" /> если эта геометрия \"пространственно покрывается\" другой геометрией. <see langword=\"false\" /> в противном случае. |


### Method: covers(other) {#covers_other_15}


```
 covers(other) 
```

Определяет, покрывает ли эта геометрия указанную геометрию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <see langword=\"true\" /> если эта геометрия \"пространственно покрывает\" другую геометрию. <see langword=\"false\" /> в противном случае. |


### Method: crosses(other) {#crosses_other_16}


```
 crosses(other) 
```

Определяет, пересекаются ли эта геометрия и указанная геометрия.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <see langword=\"true\" /> если эта геометрия \"пространственно пересекает\" другую геометрию. <see langword=\"false\" /> в противном случае. |


### Method: difference(other) {#difference_other_17}


```
 difference(other) 
```

Вычитает указанную геометрию из этой геометрии.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия для вычитания. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия, представляющая разность этой геометрии и аргумента. Результирующая геометрия содержит<br/>            набор точек, присутствующих в этой геометрии, но отсутствующих в аргументе. |


### Method: disjoint(other) {#disjoint_other_18}


```
 disjoint(other) 
```

Определяет, не пересекается ли эта геометрия с указанной геометрией.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <see langword=\"true\" /> если эта геометрия \"пространственно разобщена\" с другой геометрией. <see langword=\"false\" /> в противном случае. |


### Method: from_binary(wkb)  [static] {#from_binary_wkb_19}


```
 from_binary(wkb) 
```

Создаёт геометрию из её представления в формате Well-Known Binary.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| wkb | byte | Представление геометрии в формате Well-Known Binary. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия, представленная аргументом. |


### Method: from_binary(wkb, spatial_reference_system)  [static] {#from_binary_wkb_spatial_reference_system_20}


```
 from_binary(wkb, spatial_reference_system) 
```

Создаёт геометрию из её представления в формате Well-Known Binary.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| wkb | byte | Представление геометрии в формате Well-Known Binary. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Система пространственных координат, назначаемая геометрии. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия, представленная аргументом. |


### Method: from_text(wkt)  [static] {#from_text_wkt_21}


```
 from_text(wkt) 
```

Создаёт геометрию из её представления в формате Well-Known Text.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| wkt | string | Представление геометрии в формате Well-Known Text. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия, представленная аргументом. |


### Method: from_text(wkt, spatial_reference_system)  [static] {#from_text_wkt_spatial_reference_system_22}


```
 from_text(wkt, spatial_reference_system) 
```

Создаёт геометрию из её представления в формате Well-Known Text.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| wkt | string | Представление геометрии в формате Well-Known Text. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Система пространственных координат, назначаемая геометрии. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия, представленная аргументом. |


### Method: get_area() {#get_area__23}


```
 get_area() 
```

Вычисляет площадь этой геометрии.

**Returns**

| Тип | Описание |
| :- | :- |
| double | Площадь этой геометрии.<br/>            Сумма площадей элементов этой геометрии, если эта геометрия является [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_24}


```
 get_buffer(distance, quadrant_segments) 
```

Вычисляет буферную область вокруг этой геометрии.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| расстояние | double | Ширина буферной зоны (в единицах пространственной ссылки). |
| quadrant_segments | int | Количество сегментов, используемых для аппроксимации 90‑градусного изгиба.<br/>            Чем больше это число, тем лучше получается аппроксимация кривых.<br/>            По умолчанию 30. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия, представляющая все точки, находящиеся на заданном расстоянии от<br/>            этой геометрии.<br/>            Тип результата может быть либо [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/), [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/), либо [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/). |


### Method: get_centroid() {#get_centroid__25}


```
 get_centroid() 
```

Вычисляет центр масс этой геометрии.

**Returns**

| Тип | Описание |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Центроид этой геометрии. Если эта геометрия пуста, возвращается пустая точка.<br/>            Центроид равен центроиду геометрий наивысшего измерения в этой геометрии<br/>            (например, если в геометрии содержатся как точки, так и линии, к центроиду учитываются только линии). |


### Method: get_convex_hull() {#get_convex_hull__26}


```
 get_convex_hull() 
```

Вычисляет выпуклую оболочку этой геометрии.

**Returns**

| Тип | Описание |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия, представляющая выпуклую оболочку этой геометрии.<br/>            Если у этой геометрии нет точек, результатом является [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/).<br/>            Если у этой геометрии только одна точка, результатом является эта точка.<br/>            Если у этой геометрии только две точки, результатом является [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) с этими точками.<br/>            Если у этой геометрии три и более точек, результатом является [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/), представляющий выпуклую<br/>            оболочку вокруг всех точек геометрий. |


### Method: get_distance_to(other) {#get_distance_to_other_27}


```
 get_distance_to(other) 
```

Вычисляет минимальное расстояние между этой геометрией и указанной геометрией.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия, к которой вычисляется расстояние. |

**Returns**

| Тип | Описание |
| :- | :- |
| double | Если обе геометрии не являются [IGeometry.is_empty](/psd/python-net/aspose.gis.geometries/igeometry/) - расстояние между ближайшими точками геометрий.<br/>            Если хотя бы одна геометрия пуста, возвращается -1. |


### Method: get_extent() {#get_extent__28}


```
 get_extent() 
```

Вычисляет и возвращает ограничивающий объём этой геометрии.

**Returns**

| Тип | Описание |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Граничный охват этой геометрии. |


### Method: get_length() {#get_length__29}


```
 get_length() 
```

Вычисляет длину этой геометрии.

**Returns**

| Тип | Описание |
| :- | :- |
| double | Длина этой геометрии.<br/>            Периметр, если это [Polygon](/psd/python-net/aspose.gis.geometries/polygon/).<br/>            Сумма длин элементов этой геометрии, если эта геометрия является [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: intersection(other) {#intersection_other_30}


```
 intersection(other) 
```

Создаёт пересечение между этой геометрией и указанной геометрией.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия для вычисления пересечения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия, представляющая пересечение этой геометрии и аргумента. Результирующая геометрия содержит<br/>            набор точек, присутствующих как в этой геометрии, так и в аргументе. |


### Method: intersects(extent) {#intersects_extent_31}


```
 intersects(extent) 
```

Определяет, пересекает ли эта геометрия указанный охват.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Охват. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <see langword=\"true\" /> если эта геометрия пересекает область; <see langword=\"false\" /> иначе. |


### Method: intersects(other) {#intersects_other_32}


```
 intersects(other) 
```

Определяет, пересекаются ли эта геометрия и указанная геометрия.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <see langword=\"true\" /> если эта геометрия \"пространственно пересекает\" другую геометрию. <see langword=\"false\" /> иначе. |


### Method: overlaps(other) {#overlaps_other_33}


```
 overlaps(other) 
```

Определяет, перекрывается ли эта геометрия с указанной геометрией.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <see langword=\"true\" /> если эта геометрия \"пространственно перекрывается\" с другой геометрией. <see langword=\"false\" /> иначе. |


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_34}


```
 relate(other, intersection_pattern_matrix) 
```

Определяет, соответствует ли матрица пересечения DE-9IM этой геометрии и указанной геометрии заданному шаблону.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия. |
| intersection_pattern_matrix | string | Шаблон для сопоставления.<br/>            Это должна быть строка длиной 9 символов.<br/>            Каждый символ строки представляет ожидаемое измерение пересечения:<br/>            <ul><br/>            <li>символ 0 — между внутренними частями геометрий.</li><br/>            <li>символ 1 — между внутренней частью этой геометрии и границей другой геометрии.</li><br/>            <li>символ 2 — между внутренней частью этой геометрии и внешней частью другой геометрии.</li><br/>            <li>символ 3 — между границей этой геометрии и внутренней частью другой геометрии.</li><br/>            <li>символ 4 — между границами геометрий.</li><br/>            <li>символ 5 — между границей этой геометрии и внешней частью другой геометрии.</li><br/>            <li>символ 6 — между внешней частью этой геометрии и внутренней частью другой геометрии.</li><br/>            <li>символ 7 — между внешней частью этой геометрии и границей другой геометрии.</li><br/>            <li>символ 8 — между внешними частями геометрий.</li><br/>            </ul><br/>            Возможные значения каждого символа:<br/>            <ul><br/>            <li>* — любое значение;</li><br/>            <li>F — отсутствие пересечения;</li><br/>            <li>T — любое пересечение;</li><br/>            <li>0 — точечное пересечение (например, общая точка);</li><br/>            <li>1 — линейное пересечение (например, общий отрезок линии);</li><br/>            <li>2 — площадное пересечение (например, общая часть полигона);</li><br/>            </ul><br/>            Например, шаблон пересечения \"F0*******\" означает, что не должно быть пересечения между внутренними частями геометрий, а пересечение границ геометрий должно быть точкой.<br/>            См. спецификацию OpenGIS Simple Features для получения более подробной информации о шаблоне матрицы пересечений. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <see langword=\"true\" /> если эта матрица пересечений соответствует шаблону; <see langword=\"false\" /> иначе. |


### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__35}


```
 replace_polygons_by_lines() 
```

Получает полигоны, представленные в виде линий этой геометрии.

**Returns**

| Тип | Описание |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия, не содержащая полигональных геометрий. Применяются следующие преобразования:<br/>            <ul><br/>            <li> [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) преобразуются в линейные<br/>            (преобразуются в [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/))</li><br/>            <li>[GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) объединяются в [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)</li><br/>            </ul> |


### Method: round_m(digits) {#round_m_digits_36}


```
 round_m(digits) 
```

Округляет координату M до указанного количества знаков после запятой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| цифры | int | Количество знаков после запятой. |

### Method: round_xy(digits) {#round_xy_digits_37}


```
 round_xy(digits) 
```

Округляет координаты X и Y до указанного количества знаков после запятой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| цифры | int | Количество знаков после запятой. |

### Method: round_z(digits) {#round_z_digits_38}


```
 round_z(digits) 
```

Округляет координату Z до указанного количества знаков после запятой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| цифры | int | Количество знаков после запятой. |

### Method: spatially_contains(other) {#spatially_contains_other_39}


```
 spatially_contains(other) 
```

Определяет, содержит ли эта геометрия пространственно указанную геометрию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <see langword=\"true\" /> если эта геометрия \"пространственно содержит\" другую геометрию. <see langword=\"false\" /> иначе. |


### Method: spatially_equals(other) {#spatially_equals_other_40}


```
 spatially_equals(other) 
```

Определяет, равна ли эта геометрия пространственно указанной геометрии.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <see langword=\"true\" /> если эта геометрия \"пространственно равна\" указанной геометрии. <see langword=\"false\" /> иначе. |


### Method: sym_difference(other) {#sym_difference_other_41}


```
 sym_difference(other) 
```

Создает симметричную разность между этой геометрией и указанной геометрией.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия, с которой вычисляется симметричная разность. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия, представляющая симметричную разность этой геометрии и аргумента. Результирующая геометрия содержит<br/> набор точек, присутствующих в одной из геометрий, но не в обеих. |


### Method: to_editable() {#to_editable__42}


```
 to_editable() 
```

Получает редактируемую копию этой геометрии.

**Returns**

| Тип | Описание |
| :- | :- |
| [CircularString](/psd/python-net/aspose.gis.geometries/circularstring) | Редактируемая копия этой геометрии. |


### Method: to_linear_geometry() {#to_linear_geometry__43}


```
 to_linear_geometry() 
```

Получает приближённую или эквивалентную нелинейную версию этой геометрии, используя значение <c>tolerance</c> по умолчанию.

**Returns**

| Тип | Описание |
| :- | :- |
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | Объект [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) приближается или эквивалентен этой кривой.<br/>            Это эквивалент <DOM Element: class at 0x2a1791540d0>.ICurve.to_linear_geometry()(float) с<br/>            значением по умолчанию <c>tolerance</c>. Значение <c>tolerance</c> по умолчанию зависит от [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)<br/>            этой геометрии:<br/>            <ul><br/>            <li> Для проецируемой СК допуск составляет 0.001 метра (в единицах СК) </li><br/>            <li> Для географической СК допуск составляет <c>1e-5</c> градусов (в единицах СК) </li><br/>            <li> Для неизвестной СК допуск составляет <c>1e-5</c> </li><br/>            </ul><br/>            Для получения более подробной информации о применяемых преобразованиях см. спецификацию <DOM Element: class at 0x2a1791540d0>.ICurve.to_linear_geometry()(float). |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_44}


```
 to_linear_geometry(tolerance) 
```

Получает приближённую или эквивалентную нелинейную версию этой геометрии, используя указанное значение <c>tolerance</c>.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| допуск | double | Значение <c>tolerance</c> для использования. Результат гарантировано будет находиться на расстоянии менее <c>tolerance</c> от<br/> изогнутой геометрии, если только количество точек, необходимых для линеаризации геометрии, не превысит максимум на квадрант,<br/> в настоящее время равный 10000 точек. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | Объект [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/), который приближает или эквивалентен этой кривой:<br/>             <ul><br/>             Если этот объект является [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) сам по себе, результат эквивалентен этому объекту<br/>             Если этот объект является [ICircularString](/psd/python-net/aspose.gis.geometries/icircularstring/), результат — линейзация круговой строки с указанным <paramref name="tolerance" /><br/>             Если этот объект является [ICompoundCurve](/psd/python-net/aspose.gis.geometries/icompoundcurve/), все кривые из него линейзируются и затем объединяются в [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/)<br/>            </ul> |


### Method: to_svg(extent) {#to_svg_extent_45}


```
 to_svg(extent) 
```

Преобразует эту геометрию в представление Svg.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Область для преобразования этой геометрии в SVG |

**Returns**

| Тип | Описание |
| :- | :- |
| string | Представление в SVG. |


### Method: touches(other) {#touches_other_46}


```
 touches(other) 
```

Определяет, соприкасаются ли эта геометрия и указанная геометрия.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <see langword=\"true\" /> если эта геометрия \"пространственно касается\" другой геометрии. <see langword=\"false\" /> иначе. |


### Method: union(other) {#union_other_47}


```
 union(other) 
```

Объединяет эту геометрию и указанную геометрию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия для объединения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия, представляющая объединение этой геометрии и аргумента. Результирующая геометрия содержит<br/> набор точек, присутствующих в этой геометрии или в аргументе. |


### Method: union(other) {#union_other_48}


```
 union(other) 
```

Объединяет эту геометрию и указанную геометрию.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [IGeometry[]](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия для объединения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия, представляющая объединение этой геометрии и аргумента. Результирующая геометрия содержит<br/> набор точек, присутствующих в этой геометрии или в аргументе. |


### Method: within(extent) {#within_extent_49}


```
 within(extent) 
```

Определяет, находится ли эта геометрия внутри указанного охвата.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Охват. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <see langword=\"true\" /> если эта геометрия находится в пределах области; <see langword=\"false\" /> иначе. |


### Method: within(other) {#within_other_50}


```
 within(other) 
```

Определяет, находится ли эта геометрия внутри указанной геометрии.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <see langword=\"true\" /> если эта геометрия \"пространственно находится внутри\" другой геометрии. <see langword=\"false\" /> иначе. |


