---
title: "Projektionsklasse"
type: docs
weight: 170
url: /de/python-net/aspose.gis.spatialreferencing/projection/
---

**Summary:** Represents a projection method with parameters, that transforms (longitude, latitude) to (x, y).

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Projection

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| angular_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Einheit, die für Winkelparameter verwendet wird. |
| epsg_code | int | r | Wenn der Bezeichner dieses Objekts ein EPSG‑Bezeichner ist – geben Sie dessen Code zurück. Andernfalls - geben Sie -1 zurück. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Bezeichner dieses identifizierbaren Objekts. |
| linear_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Einheit, die für lineare Parameter verwendet wird. |
| Name | string | r | Name dieses Objekts. |
| parameters_names | System.Collections.Generic.IList<string> | r | Gibt eine aufzählbare Sammlung von Parameternamen zurück, die dieser Projektion übergeben wurden. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_parameter_value(name, type)](#get_parameter_value_name_type_1) | Gibt den Parameter mit dem angegebenen Namen dieser Projektion zurück. |
| [is_equivalent(other)](#is_equivalent_other_2) | Bestimmt, ob zwei Projektionen äquivalent sind. Äquivalente Projektionen bilden (Länge, Breite) zu (x, y) auf die<br/>            gleiche Weise ab. |
| [try_get_parameter_value(name, type)](#try_get_parameter_value_name_type_3) | Gibt den Parameter mit dem angegebenen Namen dieser Projektion zurück. Wenn ein solcher Parameter nicht existiert – wird <see langword="null" /> zurückgegeben. |


### Method: get_parameter_value(name, type) {#get_parameter_value_name_type_1}


```
 get_parameter_value(name, type) 
```

Gibt den Parameter mit dem angegebenen Namen dieser Projektion zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Name des Parameters. |
