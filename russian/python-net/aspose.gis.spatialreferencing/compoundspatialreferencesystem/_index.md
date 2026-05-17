---
title: "Класс CompoundSpatialReferenceSystem"
type: docs
weight: 30
url: /ru/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/
---

**Summary:** Compound SRS unites two underlying SRS, none of which can be compound.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.CompoundSpatialReferenceSystem

**Inheritance:** SpatialReferenceSystem

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| as_compound | [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | r | Вернуть это. |
| as_geocentric | [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | r | Возвращает эту СРС, преобразованную в [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/).<br/>            Используйте [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) чтобы узнать, возможна ли конверсия. |
| as_geographic | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Возвращает географическое представление этой СРС. Если эта составная СРС действительно представляет географическую СРС, результат будет<br/>            трёхмерной географической СРС (с измерениями долготы, широты, высоты). В противном случае будет выброшено исключение. |
| as_local | [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | r | Возвращает эту СРС, преобразованную в [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/).<br/>            Используйте [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) чтобы узнать, возможна ли конверсия. |
| as_projected | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Возвращает проекционное представление этой СРС. Если эта составная СРС действительно представляет проекционную СРС, результат будет<br/>            трёхмерной проекционной СРС (с измерениями X, Y, высоты). В противном случае будет выброшено исключение. |
| as_vertical | [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | r | Возвращает эту СРС, преобразованную в [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/).<br/>            Используйте [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) чтобы узнать, возможна ли конверсия. |
| dimensions_count | int | r | Количество измерений. Для составной SRS это сумма количества измерений базовой SRS. |
| epsg_code | int | r | Если идентификатор этого объекта является EPSG‑идентификатором — вернуть его код. В противном случае — вернуть -1. |
| etrs89 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | ETRS 89 (EPSG:4258) система пространственных координат. |
| etrs_89_lambert_azimuthal_equal_area [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / ETRS Lambert Azimuthal Equal Area (EPSG:3035) система пространственных координат. |
| etrs_89_lambert_conformal_conic [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / Lambert Conformal Conic (EPSG:3034) система пространственных координат. |
| geographic_datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Возвращает географический датум этой SRS.<br/>            Если и [CompoundSpatialReferenceSystem.head](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) и [CompoundSpatialReferenceSystem.tail](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) имеют географический датум - возвращает географический датум головы. |
| has_geographic_datum | bool | r | Составная SRS имеет географический датум, если любой из базовых SRS имеет географический датум. |
| has_prime_meridian | bool | r | Составная SRS имеет главный меридиан, если любой из базовых SRS имеет главный меридиан. |
| head | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | r | Первый базовый SRS. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Идентификатор этого идентифицируемого объекта. |
| is_compound | bool | r | Возвращает <see langword="true" />. |
| is_single | bool | r | Возвращает, является ли эта СРС одиночной (не объединением двух СРС). |
| is_valid | bool | r | То же, что и <see cref="M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)" />, но не возвращает сообщение об ошибке. |
| nad83 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | NAD 83 (EPSG:4269) система пространственных координат. |
| имя | string | r | Имя этого объекта. |
| osgb36 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | OSGB 36 (EPSG:4277) система пространственных координат. |
| osgb_36_british_national_grid [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | OSGB 36 / British National Grid (EPSG:27700) система пространственных координат. |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r | Возвращает главный меридиан этой SRS.<br/>            Если и [CompoundSpatialReferenceSystem.head](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) и [CompoundSpatialReferenceSystem.tail](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) имеют главный меридиан - возвращает главный меридиан головы. |
| tail | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | r | Второй базовый SRS. |
| type | [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype) | r | Тип этой составной SRS. Может быть [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) если<br/>            эта составная SRS является комбинацией географической и вертикальной SRS, или [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) если<br/>            эта составная SRS является комбинацией проекционной и вертикальной SRS. |
| web_mercator [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Пространственная система координат Web Mercator (EPSG:3857). |
| wgs72 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Пространственная система координат WGS 72 (EPSG:4322). |
| wgs84 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Пространственная система координат WGS 84 (EPSG:4326). |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [create_compound(name, head, tail, identifier)](#create_compound_name_head_tail_identifier_1) | Создать составную SRS. |
| [create_from_epsg(epsg)](#create_from_epsg_epsg_2) | Создать систему координат, основанную на указанном коде EPSG. |
| [create_from_wkt(wkt)](#create_from_wkt_wkt_3) | Создаёт новый <c>SpatialReferenceSystem</c>, основанный на строке WKT (Well-Known Text). |
| [create_geocentric(parameters, identifier)](#create_geocentric_parameters_identifier_4) | Создать геоцентрическую SRS из пользовательских параметров. |
| [create_geographic(parameters, identifier)](#create_geographic_parameters_identifier_5) | Создать географическую SRS из пользовательских параметров. |
| [create_local(name, datum, unit, axises, identifier)](#create_local_name_datum_unit_axises_identifier_6) | Создать локальную систему координат. |
| [create_projected(parameters, identifier)](#create_projected_parameters_identifier_7) | Создать проекционную SRS из пользовательских параметров. |
| [create_transformation_to(target_srs)](#create_transformation_to_target_srs_8) | Создаёт преобразование из этого <c>SpatialReferenceSystem</c> в другой <c>SpatialReferenceSystem</c>. |
| [create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)](#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9) | Создать вертикальную SRS. |
| [export_to_wkt()](#export_to_wkt__10) | Возвращает представление этой SRS в виде строки WKT.<br/>            Полученная строка WKT будет соответствовать спецификации OGC 01-009, обычно именуемой "WKT1". |
| [get_axis(dimension)](#get_axis_dimension_11) | Получить [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/), описывающий измерение. |
| [get_unit(dimension)](#get_unit_dimension_12) | Получить [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) измерения. |
| [is_equivalent(other)](#is_equivalent_other_13) | Определяет, эквивалентна ли эта SRS другой SRS. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/). |
| [is_equivalent(srs1, srs2)](#is_equivalent_srs1_srs2_14) | Определяет, эквивалентны ли две SRS.<br/>            Одни и те же координаты эквивалентных SRS соответствуют одному и тому же месту на Земле.<br/>            Некоторые параметры эквивалентных SRS могут различаться, например [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [try_create_from_epsg(epsg, value)](#try_create_from_epsg_epsg_value_15) | Создать систему координат, основанную на указанном коде EPSG. |
| [try_create_from_wkt(wkt, value)](#try_create_from_wkt_wkt_value_16) | Создаёт новый <c>SpatialReferenceSystem</c>, основанный на строке WKT (Well-Known Text). |
| [try_create_transformation_to(target_srs, value)](#try_create_transformation_to_target_srs_value_17) | Создаёт преобразование из этого <c>SpatialReferenceSystem</c> в другой <c>SpatialReferenceSystem</c>. |
| [validate(error_message)](#validate_error_message_18) | Определить, является ли этот SRS действительным. Смотрите <see cref=\"M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)\" /> для описания валидности. |


### Method: create_compound(name, head, tail, identifier)  [static] {#create_compound_name_head_tail_identifier_1}


```
 create_compound(name, head, tail, identifier) 
```

Создать составную SRS.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя новой SRS. |
| head | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Главная SRS новой SRS. |
| tail | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Конечная SRS новой SRS. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Идентификатор, который будет прикреплён к SRS. Прикрепление идентификатора не изменит другие параметры SRS.<br/>            От вас зависит обеспечить согласованность идентификатора и параметров SRS. |

**Returns**

| Тип | Описание |
| :- | :- |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | Новая составная SRS. |


### Method: create_from_epsg(epsg)  [static] {#create_from_epsg_epsg_2}


```
 create_from_epsg(epsg) 
```

Создать систему координат, основанную на указанном коде EPSG.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| epsg | int | Код EPSG системы пространственных ссылок. |

**Returns**

| Тип | Описание |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Новая система пространственных ссылок с указанным кодом EPSG. |


### Method: create_from_wkt(wkt)  [static] {#create_from_wkt_wkt_3}


```
 create_from_wkt(wkt) 
```

Создаёт новый <c>SpatialReferenceSystem</c>, основанный на строке WKT (Well-Known Text).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| wkt | string | Строка WKT. |

**Returns**

| Тип | Описание |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Новый <c>SpatialReferenceSystem</c>. |


### Method: create_geocentric(parameters, identifier)  [static] {#create_geocentric_parameters_identifier_4}


```
 create_geocentric(parameters, identifier) 
```

Создать геоцентрическую SRS из пользовательских параметров.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| parameters | [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters) | Параметры для создания. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Идентификатор, который будет прикреплён к SRS. Прикрепление идентификатора не изменит другие параметры SRS.<br/>            От вас зависит обеспечить согласованность идентификатора и параметров SRS. |

**Returns**

| Тип | Описание |
| :- | :- |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | Новая геоцентрическая SRS. |


### Method: create_geographic(parameters, identifier)  [static] {#create_geographic_parameters_identifier_5}


```
 create_geographic(parameters, identifier) 
```

Создать географическую SRS из пользовательских параметров.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| parameters | [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters) | Параметры для создания. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Идентификатор, который будет прикреплён к SRS. Прикрепление идентификатора не изменит другие параметры SRS.<br/>            От вас зависит обеспечить согласованность идентификатора и параметров SRS. |

**Returns**

| Тип | Описание |
| :- | :- |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | Новая географическая SRS. |


### Method: create_local(name, datum, unit, axises, identifier)  [static] {#create_local_name_datum_unit_axises_identifier_6}


```
 create_local(name, datum, unit, axises, identifier) 
```

Создать локальную систему координат.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя системы пространственных ссылок. |
| datum | [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum) | Датум, используемый в SRS. |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Единица измерения, используемая в SRS. |
| оси | System.Collections.Generic.ICollection<Axis> | Оси, используемые в SRS. Должны быть непустыми. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Идентификатор, который будет прикреплён к SRS. Прикрепление идентификатора не изменит другие параметры SRS.<br/>            От вас зависит обеспечить согласованность идентификатора и параметров SRS. |

**Returns**

| Тип | Описание |
| :- | :- |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | Новая локальная система пространственных ссылок. |


### Method: create_projected(parameters, identifier)  [static] {#create_projected_parameters_identifier_7}


```
 create_projected(parameters, identifier) 
```

Создать проекционную SRS из пользовательских параметров.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| parameters | [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters) | Параметры для создания. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Идентификатор, который будет прикреплён к SRS. Прикрепление идентификатора не изменит другие параметры SRS.<br/>            От вас зависит обеспечить согласованность идентификатора и параметров SRS. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | Новая проецируемая SRS. |


### Method: create_transformation_to(target_srs) {#create_transformation_to_target_srs_8}


```
 create_transformation_to(target_srs) 
```

Создаёт преобразование из этого <c>SpatialReferenceSystem</c> в другой <c>SpatialReferenceSystem</c>.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Другая <c>SpatialReferenceSystem</c>. |

**Returns**

| Тип | Описание |
| :- | :- |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | Преобразование из этой <c>SpatialReferenceSystem</c> в другую <c>SpatialReferenceSystem</c>. |


### Method: create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)  [static] {#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9}


```
 create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier) 
```

Создать вертикальную SRS.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя SRS. Если <see langword=\"null\" />. |
| vertical_datum | [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum) | Датум, используемый в SRS. |
| vertical_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Единица измерения, используемая в SRS. Если <see langword=\"null\" />, будет использована [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| vertical_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | Ось с направлением \"up\" или \"down\", используемая в SRS. Если <see langword=\"null\" />, будет использована ось с направлением up. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Идентификатор, который будет прикреплён к SRS. Прикрепление идентификатора не изменит другие параметры SRS.<br/>            От вас зависит обеспечить согласованность идентификатора и параметров SRS. |

**Returns**

| Тип | Описание |
| :- | :- |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | Новая вертикальная SRS. |


### Method: export_to_wkt() {#export_to_wkt__10}


```
 export_to_wkt() 
```

Возвращает представление этой SRS в виде строки WKT.<br/>            Полученная строка WKT будет соответствовать спецификации OGC 01-009, обычно именуемой "WKT1".

**Returns**

| Тип | Описание |
| :- | :- |
| string | Представление WKT этой SRS. |


### Method: get_axis(dimension) {#get_axis_dimension_11}


```
 get_axis(dimension) 
```

Получить [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/), описывающий измерение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| измерение | int | Количество измерений. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | Ось, описывающая измерение. |


### Method: get_unit(dimension) {#get_unit_dimension_12}


```
 get_unit(dimension) 
```

Получить [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) измерения.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| измерение | int | Количество измерений. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Единица измерения. |


### Method: is_equivalent(other) {#is_equivalent_other_13}


```
 is_equivalent(other) 
```

Определяет, эквивалентна ли эта SRS другой SRS. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Другой SRS. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | логическое значение, указывающее, эквивалентен ли этот SRS другому SRS. |


### Method: is_equivalent(srs1, srs2)  [static] {#is_equivalent_srs1_srs2_14}


```
 is_equivalent(srs1, srs2) 
```

Определяет, эквивалентны ли две SRS.<br/>            Одни и те же координаты эквивалентных SRS соответствуют одному и тому же месту на Земле.<br/>            Некоторые параметры эквивалентных SRS могут различаться, например [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| srs1 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Первый SRS. |
| srs2 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Второй SRS. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | логическое значение, указывающее, эквивалентны ли два SRS. |


### Method: try_create_from_epsg(epsg, value)  [static] {#try_create_from_epsg_epsg_value_15}


```
 try_create_from_epsg(epsg, value) 
```

Создать систему координат, основанную на указанном коде EPSG.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| epsg | int | Код EPSG системы пространственных ссылок. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Когда этот метод возвращает <see langword=\"true\" />, содержит SRS с указанным кодом EPSG; в противном случае,<br/>            содержит <see langword=\"null\" />. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <see langword=\"true\" /> если указанный код EPSG известен и SRS был создан; <see langword=\"false\" /> в противном случае. |


### Method: try_create_from_wkt(wkt, value)  [static] {#try_create_from_wkt_wkt_value_16}


```
 try_create_from_wkt(wkt, value) 
```

Создаёт новый <c>SpatialReferenceSystem</c>, основанный на строке WKT (Well-Known Text).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| wkt | string | Строка WKT. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Когда этот метод возвращает <see langword=\"true\" />, содержит SRS, созданный из WKT; в противном случае,<br/>            содержит <see langword=\"null\" />. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <see langword=\"true\" /> если SRS был успешно создан; <see langword=\"false\" /> в противном случае. |


### Method: try_create_transformation_to(target_srs, value) {#try_create_transformation_to_target_srs_value_17}


```
 try_create_transformation_to(target_srs, value) 
```

Создаёт преобразование из этого <c>SpatialReferenceSystem</c> в другой <c>SpatialReferenceSystem</c>.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Другая <c>SpatialReferenceSystem</c>. |
| value | [SpatialReferenceSystemTransformation[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | Когда этот метод возвращает <see langword=\"true\" />, содержит преобразование; в противном случае содержит <see langword=\"null\" />. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Преобразование из этой <c>SpatialReferenceSystem</c> в другую <c>SpatialReferenceSystem</c>. |


### Method: validate(error_message) {#validate_error_message_18}


```
 validate(error_message) 
```

Определить, является ли этот SRS действительным. Смотрите <see cref=\"M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)\" /> для описания валидности.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| error_message | Строка | Описание недействительности (если результат <see langword="false" />) |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Если эта SRS действительна - <see langword="true" />, иначе - <see langword="false" />. |


