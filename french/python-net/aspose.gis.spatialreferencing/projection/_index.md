---
title: "Classe Projection"
type: docs
weight: 170
url: /fr/python-net/aspose.gis.spatialreferencing/projection/
---

**Summary:** Represents a projection method with parameters, that transforms (longitude, latitude) to (x, y).

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Projection

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| angular_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Unité utilisée pour les paramètres angulaires. |
| epsg_code | int | r | Si l’identifiant de cet objet est un identifiant EPSG, renvoie son code. Sinon, renvoie -1. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Identifiant de cet objet identifiable. |
| linear_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Unité utilisée pour les paramètres linéaires. |
| nom | string | r | Nom de cet objet. |
| parameters_names | System.Collections.Generic.IList<string> | r | Obtient une collection énumérable des noms des paramètres fournis à cette projection |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_parameter_value(name, type)](#get_parameter_value_name_type_1) | Obtient le paramètre avec le nom spécifié de cette projection. |
| [is_equivalent(other)](#is_equivalent_other_2) | Détermine si deux projections sont équivalentes. Les projections équivalentes cartographient (longitude, latitude) vers (x, y) de la même façon<br/>             |
| [try_get_parameter_value(name, type)](#try_get_parameter_value_name_type_3) | Obtient le paramètre avec le nom spécifié de cette projection. S'il n'existe aucun paramètre de ce type - renvoie <see langword=\"null\" />. |


### Method: get_parameter_value(name, type) {#get_parameter_value_name_type_1}


```
 get_parameter_value(name, type) 
```

Obtient le paramètre avec le nom spécifié de cette projection.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| nom | string | Nom du paramètre. |
