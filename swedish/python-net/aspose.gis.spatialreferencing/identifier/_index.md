---
title: "Identifier-klass"
type: docs
weight: 110
url: /sv/python-net/aspose.gis.spatialreferencing/identifier/
---

**Summary:** Represents an identifier - a reference to external description of an object.<br/>            If you create a SRS from WKT, [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) corresponds to "AUTHORITY" keyword.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Identifier

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [Identifier(authority_name, authority_unique_identifier)](#Identifier_authority_name_authority_unique_identifier_1) | Skapa ny instans. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| authority_name | string | r | Ett namn på myndighet som gav ett [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
| authority_unique_identifier | string | r | Ett unikt sätt att representera ett objekt inom en [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [epsg(epsg_code)](#epsg_epsg_code_1) | Skapar en ny Identifier som representerar EPSG-identifierare med kod <paramref name="epsgCode" />. |
| [get_epsg_code()](#get_epsg_code__2) | Om detta objekt representerar en giltig EPSG-identifierare (t.ex. - myndighetsnamn är "EPSG" och myndighets unika identifierare är ett heltal) -<br/>            returnera den. Annars - returnera -1. |


### Constructor: Identifier(authority_name, authority_unique_identifier) {#Identifier_authority_name_authority_unique_identifier_1}


```
 Identifier(authority_name, authority_unique_identifier) 
```

Skapa ny instans.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| authority_name | string | [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
| authority_unique_identifier | string | [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |

### Method: epsg(epsg_code)  [static] {#epsg_epsg_code_1}


```
 epsg(epsg_code) 
```

Skapar en ny Identifier som representerar EPSG-identifierare med kod <paramref name="epsgCode" />.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| epsg_code | int | Epsg-kod. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Ny identifierare med [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/) "EPSG" och [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) <paramref name=\"epsgCode\" />.<br/>            Om <paramref name=\"epsgCode\" /> är mindre än 0 - returnerar <see langword=\"null\" />; |


### Method: get_epsg_code() {#get_epsg_code__2}


```
 get_epsg_code() 
```

Om detta objekt representerar en giltig EPSG-identifierare (t.ex. - myndighetsnamn är "EPSG" och myndighets unika identifierare är ett heltal) -<br/>            returnera den. Annars - returnera -1.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | EPSG-identifikator som representeras av detta objekt. Om detta objekt inte representerar en EPSG-identifikator - returnerar -1. |


