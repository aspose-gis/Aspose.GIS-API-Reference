---
title: "Класс ICompoundCurve"
type: docs
weight: 80
url: /ru/python-net/aspose.gis.geometries/icompoundcurve/
---

**Summary:** A curve that represents a sequence of contiguous curves such that adjacent curves are joined at their end points.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.ICompoundCurve

**Inheritance:** ICurve, IGeometry

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| count | int | r | Получает количество кривых в [ICompoundCurve](/psd/python-net/aspose.gis.geometries/icompoundcurve/). |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | Возвращает топологическое измерение этой [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/).<br/>            Если измерение неизвестно (например, для пустой GEOMETRYCOLLECTION), возвращается [GeometryDimension.POINT](/psd/python-net/aspose.gis.geometries/geometrydimension/). |
| end_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | Возвращает копию конечной точки кривой. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | Возвращает тип геометрии. |
| has_curve_geometry | bool | r | Возвращает значение, указывающее, является ли эта геометрия или содержит кривую (не линейную) геометрию. |
| has_m | bool | r | Возвращает значение, указывающее, имеет ли этот экземпляр координату M. |
| has_z | bool | r | Возвращает значение, указывающее, имеет ли этот экземпляр координату Z. |
| is_closed | bool | r | Возвращает значение, указывающее, замкнута ли кривая.<br/>            Кривая считается замкнутой, если её начальная точка равна конечной. |
| is_empty | bool | r | Возвращает значение, указывающее, пустой ли этот экземпляр (представляет пустой набор точек). |
| is_simple | bool | r | Возвращает значение, указывающее, является ли этот экземпляр простым с точки зрения SFA. |
| is_valid | bool | r | Возвращает значение, указывающее, является ли этот экземпляр действительным. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Возвращает SpatialReferenceSystem этого экземпляра.<br/>            Это свойство может быть <see langword="null" />, если SpatialReferenceSystem неизвестна. |
| start_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | Возвращает копию начальной точки кривой. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [as_binary()](#as_binary__1) | Преобразует эту геометрию в её представление Well-Known Binary. |
| [as_binary(variant)](#as_binary_variant_2) | Преобразует эту геометрию в её представление Well-Known Binary. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_3) | Экспортирует эту геометрию в представление изображения. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_4) | Экспортирует эту геометрию в представление изображения. |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_5) | Экспортирует эту геометрию в представление изображения. |
| [as_text()](#as_text__6) | Преобразует эту геометрию в её представление Well-Known Text. |
| [as_text(variant)](#as_text_variant_7) | Преобразует эту геометрию в её представление Well-Known Text. |
| [as_text(variant, format)](#as_text_variant_format_8) | Преобразует эту геометрию в её представление Well-Known Text. |
| [clone()](#clone__9) | Создаёт клон этого экземпляра. |
| [covered_by(other)](#covered_by_other_10) | Определяет, покрывается ли эта геометрия указанной геометрией. |
| [covers(other)](#covers_other_11) | Определяет, покрывает ли эта геометрия указанную геометрию. |
| [crosses(other)](#crosses_other_12) | Определяет, пересекаются ли эта геометрия и указанная геометрия. |
| [difference(other)](#difference_other_13) | Вычитает указанную геометрию из этой геометрии. |
| [disjoint(other)](#disjoint_other_14) | Определяет, не пересекается ли эта геометрия с указанной геометрией. |
| [get_area()](#get_area__15) | Вычисляет площадь этой геометрии. |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_16) | Вычисляет буферную область вокруг этой геометрии. |
| [get_centroid()](#get_centroid__17) | Вычисляет центр масс этой геометрии. |
| [get_convex_hull()](#get_convex_hull__18) | Вычисляет выпуклую оболочку этой геометрии. |
| [get_distance_to(other)](#get_distance_to_other_19) | Вычисляет минимальное расстояние между этой геометрией и указанной геометрией. |
| [get_extent()](#get_extent__20) | Вычисляет и возвращает ограничивающий объём этой геометрии. |
| [get_length()](#get_length__21) | Вычисляет длину этой геометрии. |
| [intersection(other)](#intersection_other_22) | Создаёт пересечение между этой геометрией и указанной геометрией. |
| [intersects(extent)](#intersects_extent_23) | Определяет, пересекает ли эта геометрия указанный охват. |
| [intersects(other)](#intersects_other_24) | Определяет, пересекаются ли эта геометрия и указанная геометрия. |
| [overlaps(other)](#overlaps_other_25) | Определяет, перекрывается ли эта геометрия с указанной геометрией. |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_26) | Определяет, соответствует ли матрица пересечения DE-9IM этой геометрии и указанной геометрии заданному шаблону. |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__27) | Получает полигоны, представленные в виде линий этой геометрии. |
| [spatially_contains(other)](#spatially_contains_other_28) | Определяет, содержит ли эта геометрия пространственно указанную геометрию. |
| [spatially_equals(other)](#spatially_equals_other_29) | Определяет, равна ли эта геометрия пространственно указанной геометрии. |
| [sym_difference(other)](#sym_difference_other_30) | Создает симметричную разность между этой геометрией и указанной геометрией. |
| [to_editable()](#to_editable__31) | Получает редактируемую копию этой геометрии. |
| [to_linear_geometry()](#to_linear_geometry__32) | Получает приближённую или эквивалентную нелинейную версию этой геометрии, используя значение <c>tolerance</c> по умолчанию. |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_33) | Получает приближённую или эквивалентную нелинейную версию этой геометрии, используя указанное значение <c>tolerance</c>. |
| [touches(other)](#touches_other_34) | Определяет, соприкасаются ли эта геометрия и указанная геометрия. |
| [union(other)](#union_other_35) | Объединяет эту геометрию и указанную геометрию. |
| [union(other)](#union_other_36) | Объединяет эту геометрию и указанную геометрию. |
| [within(extent)](#within_extent_37) | Определяет, находится ли эта геометрия внутри указанного охвата. |
| [within(other)](#within_other_38) | Определяет, находится ли эта геометрия внутри указанной геометрии. |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

Преобразует эту геометрию в её представление Well-Known Binary.

**Returns**

| Тип | Описание |
| :- | :- |
| byte | Представление этой геометрии в формате Well-Known Binary. |


### Method: as_binary(variant) {#as_binary_variant_2}


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


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_3}


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

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_4}


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

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_5}


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


### Method: as_text() {#as_text__6}


```
 as_text() 
```

Преобразует эту геометрию в её представление Well-Known Text.

**Returns**

| Тип | Описание |
| :- | :- |
| string | Представление этой геометрии в формате Well-Known Text. |


### Method: as_text(variant) {#as_text_variant_7}


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


### Method: as_text(variant, format) {#as_text_variant_format_8}


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


### Method: clone() {#clone__9}


```
 clone() 
```

Создаёт клон этого экземпляра.

**Returns**

| Тип | Описание |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | Клон этого экземпляра |


### Method: covered_by(other) {#covered_by_other_10}


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


### Method: covers(other) {#covers_other_11}


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


### Method: crosses(other) {#crosses_other_12}


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


### Method: difference(other) {#difference_other_13}


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


### Method: disjoint(other) {#disjoint_other_14}


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


### Method: get_area() {#get_area__15}


```
 get_area() 
```

Вычисляет площадь этой геометрии.

**Returns**

| Тип | Описание |
| :- | :- |
| double | Площадь этой геометрии.<br/>            Сумма площадей элементов этой геометрии, если эта геометрия является [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_16}


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


### Method: get_centroid() {#get_centroid__17}


```
 get_centroid() 
```

Вычисляет центр масс этой геометрии.

**Returns**

| Тип | Описание |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Центроид этой геометрии. Если эта геометрия пуста, возвращается пустая точка.<br/>            Центроид равен центроиду геометрий наивысшего измерения в этой геометрии<br/>            (например, если в геометрии содержатся как точки, так и линии, к центроиду учитываются только линии). |


### Method: get_convex_hull() {#get_convex_hull__18}


```
 get_convex_hull() 
```

Вычисляет выпуклую оболочку этой геометрии.

**Returns**

| Тип | Описание |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия, представляющая выпуклую оболочку этой геометрии.<br/>            Если у этой геометрии нет точек, результатом является [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/).<br/>            Если у этой геометрии только одна точка, результатом является эта точка.<br/>            Если у этой геометрии только две точки, результатом является [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) с этими точками.<br/>            Если у этой геометрии три и более точек, результатом является [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/), представляющий выпуклую<br/>            оболочку вокруг всех точек геометрий. |


### Method: get_distance_to(other) {#get_distance_to_other_19}


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


### Method: get_extent() {#get_extent__20}


```
 get_extent() 
```

Вычисляет и возвращает ограничивающий объём этой геометрии.

**Returns**

| Тип | Описание |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Граничный охват этой геометрии. |


### Method: get_length() {#get_length__21}


```
 get_length() 
```

Вычисляет длину этой геометрии.

**Returns**

| Тип | Описание |
| :- | :- |
| double | Длина этой геометрии.<br/>            Периметр, если это [Polygon](/psd/python-net/aspose.gis.geometries/polygon/).<br/>            Сумма длин элементов этой геометрии, если эта геометрия является [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: intersection(other) {#intersection_other_22}


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


### Method: intersects(extent) {#intersects_extent_23}


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


### Method: intersects(other) {#intersects_other_24}


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


### Method: overlaps(other) {#overlaps_other_25}


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


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_26}


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


### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__27}


```
 replace_polygons_by_lines() 
```

Получает полигоны, представленные в виде линий этой геометрии.

**Returns**

| Тип | Описание |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Геометрия, не содержащая полигональных геометрий. Применяются следующие преобразования:<br/>            <ul><br/>            <li> [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) преобразуются в линейные<br/>            (преобразуются в [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/))</li><br/>            <li>[GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) объединяются в [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)</li><br/>            </ul> |


### Method: spatially_contains(other) {#spatially_contains_other_28}


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


### Method: spatially_equals(other) {#spatially_equals_other_29}


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


### Method: sym_difference(other) {#sym_difference_other_30}


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


### Method: to_editable() {#to_editable__31}


```
 to_editable() 
```

Получает редактируемую копию этой геометрии.

**Returns**

| Тип | Описание |
| :- | :- |
| [CompoundCurve](/psd/python-net/aspose.gis.geometries/compoundcurve) | Редактируемая копия этой геометрии. |


### Method: to_linear_geometry() {#to_linear_geometry__32}


```
 to_linear_geometry() 
```

Получает приближённую или эквивалентную нелинейную версию этой геометрии, используя значение <c>tolerance</c> по умолчанию.

**Returns**

| Тип | Описание |
| :- | :- |
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | Геометрия без криволинейных геометрий. Это эквивалент <DOM Element: class at 0x2a1791a70d0>.IGeometry.to_linear_geometry()(float) с<br/>            значением по умолчанию <c>tolerance</c>. Значение <c>tolerance</c> по умолчанию определяется [IGeometry.spatial_reference_system](/psd/python-net/aspose.gis.geometries/igeometry/)<br/>            этой геометрии:<br/>            <ul><br/>            <li> Для проецируемой SRS допускается 0.001 метра (в единицах SRS) </li><br/>            <li> Для географической SRS допускается <c>1e-5</c> градусов (в единицах SRS) </li><br/>            <li> Для неизвестной SRS допускается <c>1e-5</c> </li><br/>            </ul><br/>            Для получения более подробной информации о применяемых преобразованиях обратитесь к спецификации <DOM Element: class at 0x2a1791a70d0>.IGeometry.to_linear_geometry()(float). |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_33}


```
 to_linear_geometry(tolerance) 
```

Получает приближённую или эквивалентную нелинейную версию этой геометрии, используя указанное значение <c>tolerance</c>.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| допуск | double | Значение <c>tolerance</c>, которое следует использовать. Результат гарантированно будет находиться на расстоянии менее <c>tolerance</c> от криволинейной геометрии,<br/>            если только количество точек, необходимых для линеаризации геометрии, не превысит максимально допустимое количество точек на квадрант,<br/>            которое в настоящее время равно 10000 точек. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | Геометрия без криволинейных геометрий. Применяются следующие преобразования:<br/>            <ul><br/>            <li> [GeometryType.CIRCULAR_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/) преобразуются в линейные<br/>            (преобразуются в [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/) с указанным <paramref name="tolerance" />) </li><br/>            <li> [GeometryType.COMPOUND_CURVE](/psd/python-net/aspose.gis.geometries/geometrytype/) объединяются в <c>LineString</c> </li><br/>            <li> [GeometryType.CURVE_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) преобразуются в [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) </li><br/>            <li> [GeometryType.MULTI_CURVE](/psd/python-net/aspose.gis.geometries/geometrytype/) преобразуются в [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/) </li><br/>            <li> [GeometryType.MULTI_SURFACE](/psd/python-net/aspose.gis.geometries/geometrytype/) преобразуются в [GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/) </li><br/>            </ul><br/>            В результате свойство [IGeometry.has_curve_geometry](/psd/python-net/aspose.gis.geometries/igeometry/) выходной геометрии равно <see langword="false" />. |


### Method: touches(other) {#touches_other_34}


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


### Method: union(other) {#union_other_35}


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


### Method: union(other) {#union_other_36}


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


### Method: within(extent) {#within_extent_37}


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


### Method: within(other) {#within_other_38}


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


