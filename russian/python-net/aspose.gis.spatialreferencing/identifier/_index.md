---
title: "Identifier Класс"
type: docs
weight: 110
url: /ru/python-net/aspose.gis.spatialreferencing/identifier/
---

**Summary:** Represents an identifier - a reference to external description of an object.<br/>            If you create a SRS from WKT, [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) corresponds to "AUTHORITY" keyword.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Identifier

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [Identifier(authority_name, authority_unique_identifier)](#Identifier_authority_name_authority_unique_identifier_1) | Создать новый экземпляр. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| authority_name | string | r | Имя органа, который дал [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
| authority_unique_identifier | string | r | Уникальный способ представления объекта в рамках [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [epsg(epsg_code)](#epsg_epsg_code_1) | Создаёт новый Identifier, представляющий EPSG‑идентификатор с кодом <paramref name="epsgCode" />. |
| [get_epsg_code()](#get_epsg_code__2) | Если этот объект представляет действительный EPSG‑идентификатор (например, имя органа — "EPSG" и уникальный идентификатор органа — целое число) -<br/>            вернуть его. В противном случае - вернуть -1. |


### Constructor: Identifier(authority_name, authority_unique_identifier) {#Identifier_authority_name_authority_unique_identifier_1}


```
 Identifier(authority_name, authority_unique_identifier) 
```

Создать новый экземпляр.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| authority_name | string | [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
| authority_unique_identifier | string | [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |

### Method: epsg(epsg_code)  [static] {#epsg_epsg_code_1}


```
 epsg(epsg_code) 
```

Создаёт новый Identifier, представляющий EPSG‑идентификатор с кодом <paramref name="epsgCode" />.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| epsg_code | int | Код EPSG. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Новый идентификатор с [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/) "EPSG" и [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) <paramref name=\"epsgCode\" />.<br/>            Если <paramref name=\"epsgCode\" /> меньше 0 — возвращает <see langword=\"null\" />; |


### Method: get_epsg_code() {#get_epsg_code__2}


```
 get_epsg_code() 
```

Если этот объект представляет действительный EPSG‑идентификатор (например, имя органа — "EPSG" и уникальный идентификатор органа — целое число) -<br/>            вернуть его. В противном случае - вернуть -1.

**Returns**

| Тип | Описание |
| :- | :- |
| int | Идентификатор EPSG, представленный этим объектом. Если этот объект не представляет идентификатор EPSG, возвращает -1. |


