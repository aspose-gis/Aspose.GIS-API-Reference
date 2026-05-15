---
title: "Identifier Klasse"
type: docs
weight: 110
url: /de/python-net/aspose.gis.spatialreferencing/identifier/
---

**Summary:** Represents an identifier - a reference to external description of an object.<br/>            If you create a SRS from WKT, [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) corresponds to "AUTHORITY" keyword.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Identifier

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Identifier(authority_name, authority_unique_identifier)](#Identifier_authority_name_authority_unique_identifier_1) | Neue Instanz erstellen. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| authority_name | string | r | Ein Name der Behörde, die eine [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) bereitstellt. |
| authority_unique_identifier | string | r | Eine eindeutige Möglichkeit, ein Objekt innerhalb eines [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/) darzustellen. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [epsg(epsg_code)](#epsg_epsg_code_1) | Erstellt einen neuen Identifier, der den EPSG-Identifikator mit dem Code <paramref name="epsgCode" /> repräsentiert. |
| [get_epsg_code()](#get_epsg_code__2) | Wenn dieses Objekt einen gültigen EPSG-Identifikator darstellt (z. B. - Behördenname ist "EPSG" und eindeutige Behördenkennung ist eine ganze Zahl) -<br/>            gib ihn zurück. Andernfalls - gib -1 zurück. |


### Constructor: Identifier(authority_name, authority_unique_identifier) {#Identifier_authority_name_authority_unique_identifier_1}


```
 Identifier(authority_name, authority_unique_identifier) 
```

Neue Instanz erstellen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| authority_name | string | [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
| authority_unique_identifier | string | [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |

### Method: epsg(epsg_code)  [static] {#epsg_epsg_code_1}


```
 epsg(epsg_code) 
```

Erstellt einen neuen Identifier, der den EPSG-Identifikator mit dem Code <paramref name="epsgCode" /> repräsentiert.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| epsg_code | int | EPSG-Code. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Neuer Bezeichner mit [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/) "EPSG" und [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) <paramref name="epsgCode" />.<br/>            Wenn <paramref name="epsgCode" /> kleiner als 0 ist - gibt <see langword="null" /> zurück; |


### Method: get_epsg_code() {#get_epsg_code__2}


```
 get_epsg_code() 
```

Wenn dieses Objekt einen gültigen EPSG-Identifikator darstellt (z. B. - Behördenname ist "EPSG" und eindeutige Behördenkennung ist eine ganze Zahl) -<br/>            gib ihn zurück. Andernfalls - gib -1 zurück.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int | EPSG-Bezeichner, der von diesem Objekt repräsentiert wird. Wenn dieses Objekt keinen EPSG-Bezeichner repräsentiert - gibt -1 zurück. |


