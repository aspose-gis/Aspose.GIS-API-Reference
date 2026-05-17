---
title: "Класс Ellipsoid"
type: docs
weight: 40
url: /ru/python-net/aspose.gis.spatialreferencing/ellipsoid/
---

**Summary:** Ellipsoid represents an ellipsoid, which approximates earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Ellipsoid

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [Ellipsoid(name, semi_major_axis, inverse_flattening, identifier)](#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1) | Создаёт новый Ellipsoid. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| airy [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Эллипсоид Airy. |
| epsg_code | int | r | Если идентификатор этого объекта является EPSG‑идентификатором — вернуть его код. В противном случае — вернуть -1. |
| grs80 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Эллипсоид GRS 1980. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Идентификатор этого идентифицируемого объекта. |
| inverse_flattening | double | r | Обратное сплющивание эллипсоида. 0, если это сфера. |
| is_sphere | bool | r | Определяет, является ли данный эллипсоид сферой. |
| is_valid | bool | r | Определяет, является ли эллипсоид корректным: его большая полуось больше 0, а обратное сплющивание положительно или равно 0. |
| имя | string | r | Имя этого объекта. |
| semi_major_axis | double | r | Большая полуось эллипсоида. |
| semi_minor_axis | double | r | Малая полуось эллипсоида. Совпадает с большой полуосью, если это сфера. |
| wgs72 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Эллипсоид WGS 72. |
| wgs84 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Эллипсоид WGS 84. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [is_equivalent(ellipsoid1, ellipsoid2)](#is_equivalent_ellipsoid1_ellipsoid2_1) | Определяет, эквивалентны ли два эллипсоида.<br/>            Если эллипсоид A эквивалентен эллипсоиду B, то у них одинаковая большая полуось и обратное сплющивание. |
| [is_equivalent(other)](#is_equivalent_other_2) | Определяет, эквивалентны ли два эллипсоида.<br/>            Если эллипсоид A эквивалентен эллипсоиду B, то у них одинаковая большая полуось и обратное сплющивание. |


### Constructor: Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) {#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1}


```
 Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) 
```

Создаёт новый Ellipsoid.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Название эллипсоида. |
| semi_major_axis | double | Большая полуось эллипсоида. |
| inverse_flattening | double | Обратное сплющивание эллипсоида. Должно быть 0 для создания сфероида. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Идентификатор эллипсоида. |

### Method: is_equivalent(ellipsoid1, ellipsoid2)  [static] {#is_equivalent_ellipsoid1_ellipsoid2_1}


```
 is_equivalent(ellipsoid1, ellipsoid2) 
```

Определяет, эквивалентны ли два эллипсоида.<br/>            Если эллипсоид A эквивалентен эллипсоиду B, то у них одинаковая большая полуось и обратное сплющивание.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| ellipsoid1 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Первый эллипсоид. |
| ellipsoid2 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Второй эллипсоид. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | логическое значение, указывающее, эквивалентны ли два эллипсоида. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

Определяет, эквивалентны ли два эллипсоида.<br/>            Если эллипсоид A эквивалентен эллипсоиду B, то у них одинаковая большая полуось и обратное сплющивание.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Другой эллипсоид. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | логическое значение, указывающее, эквивалентны ли два эллипсоида. |


