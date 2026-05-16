---
title: "Projection Klasse"
type: docs
weight: 170
url: /nl/python-net/aspose.gis.spatialreferencing/projection/
---

**Summary:** Represents a projection method with parameters, that transforms (longitude, latitude) to (x, y).

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Projection

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| angular_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Eenheid die wordt gebruikt voor hoekparameters. |
| epsg_code | int | r | Als de identifier van dit object een EPSG-identificatie is - retourneer de code. Anders - retourneer -1. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Identifier van dit identificeerbare object. |
| linear_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Eenheid die wordt gebruikt voor lineaire parameters. |
| naam | string | r | Naam van dit object. |
| parameters_names | System.Collections.Generic.IList<string> | r | Haalt een enumerabele collectie van namen van parameters op die aan deze projectie zijn gegeven. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_parameter_value(name, type)](#get_parameter_value_name_type_1) | Haalt parameter met opgegeven naam van deze projectie op. |
| [is_equivalent(other)](#is_equivalent_other_2) | Bepaalt of twee projecties equivalent zijn. Equivalente projecties mappen (longitude, latitude) naar (x, y) in de<br/>            dezelfde manier. |
| [try_get_parameter_value(name, type)](#try_get_parameter_value_name_type_3) | Haalt parameter met opgegeven naam van deze projectie op. Als er geen dergelijke parameter bestaat - retourneert <see langword="null" />. |


### Method: get_parameter_value(name, type) {#get_parameter_value_name_type_1}


```
 get_parameter_value(name, type) 
```

Haalt parameter met opgegeven naam van deze projectie op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| naam | string | Naam van parameter. |
