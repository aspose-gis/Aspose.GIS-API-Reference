---
title: "Identifier Classe"
type: docs
weight: 110
url: /fr/python-net/aspose.gis.spatialreferencing/identifier/
---

**Summary:** Represents an identifier - a reference to external description of an object.<br/>            If you create a SRS from WKT, [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) corresponds to "AUTHORITY" keyword.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Identifier

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Identifier(authority_name, authority_unique_identifier)](#Identifier_authority_name_authority_unique_identifier_1) | Créer une nouvelle instance. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| authority_name | string | r | Un nom d'autorité, qui a fourni un [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
| authority_unique_identifier | string | r | Une façon unique de représenter un objet au sein d'un [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [epsg(epsg_code)](#epsg_epsg_code_1) | Crée un nouvel Identifier qui représente l'identifiant EPSG avec le code <paramref name="epsgCode" />. |
| [get_epsg_code()](#get_epsg_code__2) | Si cet objet représente un identifiant EPSG valide (par ex. - le nom de l'autorité est "EPSG" et l'identifiant unique de l'autorité est un entier) -<br/>            le retourner. Sinon - retourner -1. |


### Constructor: Identifier(authority_name, authority_unique_identifier) {#Identifier_authority_name_authority_unique_identifier_1}


```
 Identifier(authority_name, authority_unique_identifier) 
```

Créer une nouvelle instance.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| authority_name | string | [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
| authority_unique_identifier | string | [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |

### Method: epsg(epsg_code)  [static] {#epsg_epsg_code_1}


```
 epsg(epsg_code) 
```

Crée un nouvel Identifier qui représente l'identifiant EPSG avec le code <paramref name="epsgCode" />.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| epsg_code | int | Code EPSG. |

**Returns**

| Type | Description |
| :- | :- |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Nouvel identifiant avec [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/) "EPSG" et [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) <paramref name=\"epsgCode\" />.<br/>            Si <paramref name=\"epsgCode\" /> est inférieur à 0 - renvoie <see langword=\"null\" />; |


### Method: get_epsg_code() {#get_epsg_code__2}


```
 get_epsg_code() 
```

Si cet objet représente un identifiant EPSG valide (par ex. - le nom de l'autorité est "EPSG" et l'identifiant unique de l'autorité est un entier) -<br/>            le retourner. Sinon - retourner -1.

**Returns**

| Type | Description |
| :- | :- |
| int | Identifiant EPSG représenté par cet objet. Si cet objet ne représente pas un identifiant EPSG - renvoie -1. |


