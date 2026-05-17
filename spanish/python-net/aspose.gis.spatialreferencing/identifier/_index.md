---
title: "Clase Identifier"
type: docs
weight: 110
url: /es/python-net/aspose.gis.spatialreferencing/identifier/
---

**Summary:** Represents an identifier - a reference to external description of an object.<br/>            If you create a SRS from WKT, [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) corresponds to "AUTHORITY" keyword.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Identifier

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [Identifier(authority_name, authority_unique_identifier)](#Identifier_authority_name_authority_unique_identifier_1) | Crear una nueva instancia. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| authority_name | string | r | Un nombre de autoridad, que proporcionó un [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
| authority_unique_identifier | string | r | Una forma única de representar un objeto dentro de un [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [epsg(epsg_code)](#epsg_epsg_code_1) | Crea un nuevo Identifier que representa un identificador EPSG con el código <paramref name="epsgCode" />. |
| [get_epsg_code()](#get_epsg_code__2) | Si este objeto representa un identificador EPSG válido (p. ej., el nombre de autoridad es "EPSG" y el identificador único de autoridad es un entero) -<br/>            devuélvelo. De lo contrario, devuelve -1. |


### Constructor: Identifier(authority_name, authority_unique_identifier) {#Identifier_authority_name_authority_unique_identifier_1}


```
 Identifier(authority_name, authority_unique_identifier) 
```

Crear una nueva instancia.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| authority_name | string | [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
| authority_unique_identifier | string | [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |

### Method: epsg(epsg_code)  [static] {#epsg_epsg_code_1}


```
 epsg(epsg_code) 
```

Crea un nuevo Identifier que representa un identificador EPSG con el código <paramref name="epsgCode" />.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| epsg_code | int | Código EPSG. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Nuevo identificador con [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/) \"EPSG\" y [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) <paramref name=\"epsgCode\" />.<br/>            Si <paramref name=\"epsgCode\" /> es menor que 0 - devuelve <see langword=\"null\" />; |


### Method: get_epsg_code() {#get_epsg_code__2}


```
 get_epsg_code() 
```

Si este objeto representa un identificador EPSG válido (p. ej., el nombre de autoridad es "EPSG" y el identificador único de autoridad es un entero) -<br/>            devuélvelo. De lo contrario, devuelve -1.

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Identificador EPSG representado por este objeto. Si este objeto no representa un identificador EPSG - devuelve -1. |


