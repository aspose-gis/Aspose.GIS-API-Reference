---
title: "Classe Identifier"
type: docs
weight: 110
url: /it/python-net/aspose.gis.spatialreferencing/identifier/
---

**Summary:** Represents an identifier - a reference to external description of an object.<br/>            If you create a SRS from WKT, [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) corresponds to "AUTHORITY" keyword.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Identifier

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [Identifier(authority_name, authority_unique_identifier)](#Identifier_authority_name_authority_unique_identifier_1) | Crea una nuova istanza. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| authority_name | string | r | Un nome dell'autorità, che ha fornito un [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
| authority_unique_identifier | string | r | Un modo unico per rappresentare un oggetto all'interno di un [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [epsg(epsg_code)](#epsg_epsg_code_1) | Crea un nuovo Identifier che rappresenta l'identificatore EPSG con codice <paramref name="epsgCode" />. |
| [get_epsg_code()](#get_epsg_code__2) | Se questo oggetto rappresenta un identificatore EPSG valido (ad es. - il nome dell'autorità è "EPSG" e l'identificatore unico dell'autorità è un intero) -<br/>            restituiscilo. Altrimenti - restituisci -1. |


### Constructor: Identifier(authority_name, authority_unique_identifier) {#Identifier_authority_name_authority_unique_identifier_1}


```
 Identifier(authority_name, authority_unique_identifier) 
```

Crea una nuova istanza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| authority_name | string | [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
| authority_unique_identifier | string | [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |

### Method: epsg(epsg_code)  [static] {#epsg_epsg_code_1}


```
 epsg(epsg_code) 
```

Crea un nuovo Identifier che rappresenta l'identificatore EPSG con codice <paramref name="epsgCode" />.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| epsg_code | int | Codice EPSG. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Nuovo identificatore con [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/) \"EPSG\" e [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) <paramref name=\"epsgCode\" />.<br/> Se <paramref name=\"epsgCode\" /> è inferiore a 0 - restituisce <see langword=\"null\" />; |


### Method: get_epsg_code() {#get_epsg_code__2}


```
 get_epsg_code() 
```

Se questo oggetto rappresenta un identificatore EPSG valido (ad es. - il nome dell'autorità è "EPSG" e l'identificatore unico dell'autorità è un intero) -<br/>            restituiscilo. Altrimenti - restituisci -1.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Identificatore EPSG rappresentato da questo oggetto. Se questo oggetto non rappresenta un identificatore EPSG - restituisce -1. |


