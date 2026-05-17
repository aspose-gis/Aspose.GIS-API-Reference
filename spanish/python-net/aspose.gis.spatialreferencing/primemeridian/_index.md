---
title: "Clase PrimeMeridian"
type: docs
weight: 140
url: /es/python-net/aspose.gis.spatialreferencing/primemeridian/
---

**Summary:** PrimeMeridian represents a meridian at which longitude is defined to be 0.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.PrimeMeridian

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [PrimeMeridian(name, longitude, identifier)](#PrimeMeridian_name_longitude_identifier_1) | Crea una nueva instancia. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| epsg_code | int | r | Si el identificador de este objeto es un identificador EPSG, devuelva su código. De lo contrario, devuelva -1. |
| greenwich [static] | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r | Meridiano de Greenwich. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Identificador de este objeto identificable. |
| longitud | double | r | Distancia del meridiano de Greenwich al meridiano principal en grados. |
| nombre | string | r | Nombre de este objeto. |


### Constructor: PrimeMeridian(name, longitude, identifier) {#PrimeMeridian_name_longitude_identifier_1}


```
 PrimeMeridian(name, longitude, identifier) 
```

Crea una nueva instancia.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | Nombre de este meridiano principal. |
| longitud | double | Longitud del meridiano principal respecto a Greenwich en grados. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Identificador del meridiano principal. |

