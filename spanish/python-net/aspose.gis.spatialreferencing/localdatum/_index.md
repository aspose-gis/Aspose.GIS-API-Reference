---
title: "Clase LocalDatum"
type: docs
weight: 120
url: /es/python-net/aspose.gis.spatialreferencing/localdatum/
---

**Summary:** Indicates method used for measurements in local spatial reference system.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.LocalDatum

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [LocalDatum(name, datum_type, identifier)](#LocalDatum_name_datum_type_identifier_1) | Crear una nueva instancia. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| datum_type | int | r | Un número entero, que indica el método de medición que se había utilizado. |
| epsg_code | int | r | Si el identificador de este objeto es un identificador EPSG, devuelva su código. De lo contrario, devuelva -1. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Identificador de este objeto identificable. |
| nombre | string | r | Nombre de este objeto. |


### Constructor: LocalDatum(name, datum_type, identifier) {#LocalDatum_name_datum_type_identifier_1}


```
 LocalDatum(name, datum_type, identifier) 
```

Crear una nueva instancia.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | nombre del datum. |
| datum_type | int | número entero, que representa el tipo de datum. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | identificador del datum. |

