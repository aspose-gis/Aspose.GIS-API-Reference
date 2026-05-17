---
title: "Класс PrimeMeridian"
type: docs
weight: 140
url: /ru/python-net/aspose.gis.spatialreferencing/primemeridian/
---

**Summary:** PrimeMeridian represents a meridian at which longitude is defined to be 0.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.PrimeMeridian

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [PrimeMeridian(name, longitude, identifier)](#PrimeMeridian_name_longitude_identifier_1) | Создаёт новый экземпляр. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| epsg_code | int | r | Если идентификатор этого объекта является EPSG‑идентификатором — вернуть его код. В противном случае — вернуть -1. |
| greenwich [static] | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r | Гринвичский меридиан. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Идентификатор этого идентифицируемого объекта. |
| долгота | double | r | Расстояние от гринвичского меридиана до главного меридиана в градусах. |
| имя | string | r | Имя этого объекта. |


### Constructor: PrimeMeridian(name, longitude, identifier) {#PrimeMeridian_name_longitude_identifier_1}


```
 PrimeMeridian(name, longitude, identifier) 
```

Создаёт новый экземпляр.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя этого главного меридиана. |
| долгота | double | Долгота главного меридиана относительно Гринвича в градусах. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Идентификатор главного меридиана. |

