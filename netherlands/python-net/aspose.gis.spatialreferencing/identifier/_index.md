---
title: "Identifier Klasse"
type: docs
weight: 110
url: /nl/python-net/aspose.gis.spatialreferencing/identifier/
---

**Summary:** Represents an identifier - a reference to external description of an object.<br/>            If you create a SRS from WKT, [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) corresponds to "AUTHORITY" keyword.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Identifier

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [Identifier(authority_name, authority_unique_identifier)](#Identifier_authority_name_authority_unique_identifier_1) | Maak een nieuw exemplaar. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| authority_name | string | r | Een naam van de autoriteit die een [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) heeft gegeven. |
| authority_unique_identifier | string | r | Een unieke manier om een object binnen een [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/) te representeren. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [epsg(epsg_code)](#epsg_epsg_code_1) | Maakt een nieuwe Identifier die een EPSG-identificatie vertegenwoordigt met code <paramref name="epsgCode" />. |
| [get_epsg_code()](#get_epsg_code__2) | Als dit object een geldige EPSG-identificatie vertegenwoordigt (bijv. - autoriteitsnaam is "EPSG" en autoriteit unieke identificatie is een geheel getal) -<br/>            retourneer het. Anders - retourneer -1. |


### Constructor: Identifier(authority_name, authority_unique_identifier) {#Identifier_authority_name_authority_unique_identifier_1}


```
 Identifier(authority_name, authority_unique_identifier) 
```

Maak een nieuw exemplaar.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| authority_name | string | [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
| authority_unique_identifier | string | [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |

### Method: epsg(epsg_code)  [static] {#epsg_epsg_code_1}


```
 epsg(epsg_code) 
```

Maakt een nieuwe Identifier die een EPSG-identificatie vertegenwoordigt met code <paramref name="epsgCode" />.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| epsg_code | int | Epsg-code. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Nieuwe identifier met [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/) "EPSG" en [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) <paramref name="epsgCode" />.<br/>            Als <paramref name="epsgCode" /> kleiner is dan 0 - retourneer <see langword="null" />; |


### Method: get_epsg_code() {#get_epsg_code__2}


```
 get_epsg_code() 
```

Als dit object een geldige EPSG-identificatie vertegenwoordigt (bijv. - autoriteitsnaam is "EPSG" en autoriteit unieke identificatie is een geheel getal) -<br/>            retourneer het. Anders - retourneer -1.

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | EPSG-identifier weergegeven door dit object. Als dit object geen EPSG-identifier vertegenwoordigt - retourneer -1. |


