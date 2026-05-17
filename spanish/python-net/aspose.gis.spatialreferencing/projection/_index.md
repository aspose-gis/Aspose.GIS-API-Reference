---
title: "Clase Projection"
type: docs
weight: 170
url: /es/python-net/aspose.gis.spatialreferencing/projection/
---

**Summary:** Represents a projection method with parameters, that transforms (longitude, latitude) to (x, y).

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Projection

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| angular_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Unidad que se utiliza para parámetros angulares. |
| epsg_code | int | r | Si el identificador de este objeto es un identificador EPSG, devuelva su código. De lo contrario, devuelva -1. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Identificador de este objeto identificable. |
| linear_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Unidad que se utiliza para parámetros lineales. |
| nombre | string | r | Nombre de este objeto. |
| parameters_names | System.Collections.Generic.IList<string> | r | Obtiene una colección enumerable de nombres de parámetros dados a esta proyección |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_parameter_value(name, type)](#get_parameter_value_name_type_1) | Obtiene el parámetro con el nombre especificado de esta proyección. |
| [is_equivalent(other)](#is_equivalent_other_2) | Determina si dos proyecciones son equivalentes. Proyecciones equivalentes mapean (longitude, latitude) a (x, y) en la<br/>            misma forma. |
| [try_get_parameter_value(name, type)](#try_get_parameter_value_name_type_3) | Obtiene el parámetro con el nombre especificado de esta proyección. Si no existe tal parámetro, devuelve <see langword="null" />. |


### Method: get_parameter_value(name, type) {#get_parameter_value_name_type_1}


```
 get_parameter_value(name, type) 
```

Obtiene el parámetro con el nombre especificado de esta proyección.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| nombre | string | Nombre del parámetro. |
