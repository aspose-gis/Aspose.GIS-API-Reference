---
title: "Класс GeographicDatum"
type: docs
weight: 70
url: /ru/python-net/aspose.gis.spatialreferencing/geographicdatum/
---

**Summary:** Geographic datum relates longitude and latitude to particular place on earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicDatum

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier)](#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1) | Создаёт новый экземпляр. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Эллипсоид, используемый в этом датуме для приближения формы Земли. |
| epsg_code | int | r | Если идентификатор этого объекта является EPSG‑идентификатором — вернуть его код. В противном случае — вернуть -1. |
| etrs89 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Датум ETRS 89. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Идентификатор этого идентифицируемого объекта. |
| nad83 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Датум NAD 83. |
| имя | string | r | Имя этого объекта. |
| osgb36 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Датум OSGB 1936. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | r | BursaWolfParamters, которые можно использовать для преобразования координат в этом датуме в координаты датума WGS84. |
| wgs72 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Датум WGS 72. |
| wgs84 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Датум WGS 84. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [is_equivalent(datum1, datum2)](#is_equivalent_datum1_datum2_1) | Определяет, являются ли два датума эквивалентными.<br/>            Одни и те же координаты эквивалентных датумов соответствуют одному и тому же месту на Земле.<br/>            Некоторые параметры эквивалентных датумов могут различаться, например [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [is_equivalent(other)](#is_equivalent_other_2) | Определяет, являются ли два датума эквивалентными.<br/>            Одни и те же координаты эквивалентных датумов соответствуют одному и тому же месту на Земле.<br/>            Некоторые параметры эквивалентных датумов могут различаться, например [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |


### Constructor: GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) {#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1}


```
 GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) 
```

Создаёт новый экземпляр.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя этого датума. |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Эллипсоид этого датума. Не может быть null. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | Параметры, которые могут быть переданы формуле bursa wolf для преобразования координат в этом датуме в координаты датума WGS84.<br/>            Если этот датум близок к WGS84 и преобразование не требуется, передайте параметры bursa wolf со всеми значениями, установленными в 0.<br/>            Если null, ToWgs84 будет установлен в параметры [BursaWolfParameters.is_null](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/). |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Идентификатор этого датума. |

### Method: is_equivalent(datum1, datum2)  [static] {#is_equivalent_datum1_datum2_1}


```
 is_equivalent(datum1, datum2) 
```

Определяет, являются ли два датума эквивалентными.<br/>            Одни и те же координаты эквивалентных датумов соответствуют одному и тому же месту на Земле.<br/>            Некоторые параметры эквивалентных датумов могут различаться, например [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| datum1 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Первый датум. |
| datum2 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Второй датум. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | bool значение, указывающее, являются ли два датума эквивалентными. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

Определяет, являются ли два датума эквивалентными.<br/>            Одни и те же координаты эквивалентных датумов соответствуют одному и тому же месту на Земле.<br/>            Некоторые параметры эквивалентных датумов могут различаться, например [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Другой датум. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | bool значение, указывающее, являются ли два датума эквивалентными. |


