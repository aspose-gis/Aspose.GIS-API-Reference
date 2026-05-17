---
title: "Класс Extent"
type: docs
weight: 820
url: /ru/python-net/aspose.gis/extent/
---

**Summary:** A two-dimensional spatial bounding box.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Extent

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [Extent()](#Extent__1) | Создаёт новый экземпляр. |
| [Extent(srs)](#Extent_srs_2) | Создаёт новый экземпляр. |
| [Extent(x_min, y_min, x_max, y_max, srs)](#Extent_x_min_y_min_x_max_y_max_srs_3) | Создаёт новый экземпляр. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| center | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | r | Центр экстента. |
| высота | double | r | Высота экстента. |
| is_valid | bool | r | Определяет, является ли этот [Extent](/psd/python-net/aspose.gis/extent/) действительным. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) связан с этим экстентом.<br/>            Может быть <see langword=\"null\" />, если [Extent.spatial_reference_system](/psd/python-net/aspose.gis/extent/) неизвестен.<br/>            Используйте Aspose.Gis.Extent.GetTransformed(Aspose.Gis.SpatialReferencing.SpatialReferenceSystem)<br/>            для преобразования экстента между различными системами пространственных ссылок. |
| width | double | r | Ширина экстента. |
| x_max | double | r/w | Максимальное значение координаты X. |
| x_min | double | r/w | Минимальное значение координаты X. |
| y_max | double | r/w | Максимальное значение координаты Y. |
| y_min | double | r/w | Минимальное значение координаты Y. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [clone()](#clone__1) | Создаёт клон этого экземпляра. |
| [contains(extent)](#contains_extent_2) | Определяет, содержит ли этот диапазон аргумент. |
| [contains(geometry)](#contains_geometry_3) | Определяет, содержит ли этот диапазон аргумент. |
| [contains(x, y)](#contains_x_y_4) | Определяет, содержит ли этот диапазон координату, определённую аргументами. |
| [get_transformed(target_srs)](#get_transformed_target_srs_5) | Возвращает новый диапазон в указанной [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/), содержащий этот диапазон. |
| [grow(extent)](#grow_extent_6) | Увеличивает этот диапазон так, чтобы он включал аргумент. |
| [grow(x, y)](#grow_x_y_7) | Увеличивает этот диапазон так, чтобы он включал указанную точку. |
| [grow_x(value)](#grow_x_value_8) | Увеличивает этот диапазон вдоль оси X так, чтобы он включал указанное значение. |
| [grow_y(value)](#grow_y_value_9) | Увеличивает этот диапазон вдоль оси Y так, чтобы он включал указанное значение. |
| [intersects(extent)](#intersects_extent_10) | Определяет, пересекается ли этот диапазон с аргументом. |
| [intersects(geometry)](#intersects_geometry_11) | Определяет, пересекается ли этот диапазон с аргументом. |
| normalize() | Обменивает [Extent.x_min](/psd/python-net/aspose.gis/extent/) с [Extent.x_max](/psd/python-net/aspose.gis/extent/) если [Extent.width](/psd/python-net/aspose.gis/extent/) отрицательно и<br/>            [Extent.y_min](/psd/python-net/aspose.gis/extent/) с [Extent.y_max](/psd/python-net/aspose.gis/extent/) если [Extent.height](/psd/python-net/aspose.gis/extent/) отрицательно. |
| [to_polygon()](#to_polygon__12) | Преобразует этот диапазон в прямоугольный полигон, представляющий его. |


### Constructor: Extent() {#Extent__1}


```
 Extent() 
```

Создаёт новый экземпляр.

### Constructor: Extent(srs) {#Extent_srs_2}


```
 Extent(srs) 
```

Создаёт новый экземпляр.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) связанная с этим диапазоном.<br/>            Может быть <see langword=\"null\" /> чтобы указать, что SRS неизвестна. |

### Constructor: Extent(x_min, y_min, x_max, y_max, srs) {#Extent_x_min_y_min_x_max_y_max_srs_3}


```
 Extent(x_min, y_min, x_max, y_max, srs) 
```

Создаёт новый экземпляр.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x_min | double | Минимальное значение X. |
| y_min | double | Минимальное значение Y. |
| x_max | double | Максимальное значение X. |
| y_max | double | Максимальное значение Y. |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) связанная с этим диапазоном.<br/>            Может быть <see langword=\"null\" /> чтобы указать, что SRS неизвестна. |

### Method: clone() {#clone__1}


```
 clone() 
```

Создаёт клон этого экземпляра.

**Returns**

| Тип | Описание |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Клон этого экземпляра. |


### Method: contains(extent) {#contains_extent_2}


```
 contains(extent) 
```

Определяет, содержит ли этот диапазон аргумент.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Другой диапазон. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Значение, указывающее, содержит ли этот диапазон аргумент. |


### Method: contains(geometry) {#contains_geometry_3}


```
 contains(geometry) 
```

Определяет, содержит ли этот диапазон аргумент.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Геометрия для проверки включения. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Значение, указывающее, содержит ли этот диапазон аргумент. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Определяет, содержит ли этот диапазон координату, определённую аргументами.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | double | X координаты. |
| y | double | Y координаты. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Значение, указывающее, находится ли координата внутри ограничивающего прямоугольника. |


### Method: get_transformed(target_srs) {#get_transformed_target_srs_5}


```
 get_transformed(target_srs) 
```

Возвращает новый диапазон в указанной [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/), содержащий этот диапазон.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) для преобразования. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Результат преобразования этой области к указанной SRS. |


### Method: grow(extent) {#grow_extent_6}


```
 grow(extent) 
```

Увеличивает этот диапазон так, чтобы он включал аргумент.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Другая область. |

### Method: grow(x, y) {#grow_x_y_7}


```
 grow(x, y) 
```

Увеличивает этот диапазон так, чтобы он включал указанную точку.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| x | double | Координата X для включения. |
| y | double | Координата Y для включения. |

### Method: grow_x(value) {#grow_x_value_8}


```
 grow_x(value) 
```

Увеличивает этот диапазон вдоль оси X так, чтобы он включал указанное значение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| value | double | Значение для включения. |

### Method: grow_y(value) {#grow_y_value_9}


```
 grow_y(value) 
```

Увеличивает этот диапазон вдоль оси Y так, чтобы он включал указанное значение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| value | double | Значение для включения. |

### Method: intersects(extent) {#intersects_extent_10}


```
 intersects(extent) 
```

Определяет, пересекается ли этот диапазон с аргументом.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Другой диапазон. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Значение, указывающее, пересекается ли эта область с аргументом. |


### Method: intersects(geometry) {#intersects_geometry_11}


```
 intersects(geometry) 
```

Определяет, пересекается ли этот диапазон с аргументом.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Геометрия для проверки пересечения |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Значение, указывающее, пересекается ли эта область с аргументом. |


### Method: to_polygon() {#to_polygon__12}


```
 to_polygon() 
```

Преобразует этот диапазон в прямоугольный полигон, представляющий его.

**Returns**

| Тип | Описание |
| :- | :- |
| [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Прямоугольный [Polygon](/psd/python-net/aspose.gis.geometries/polygon/), представляющий эту область. Для недопустимых областей<br/>            возвращается пустой полигон. |


