---
title: "Projection Klass"
type: docs
weight: 170
url: /sv/python-net/aspose.gis.spatialreferencing/projection/
---

**Summary:** Represents a projection method with parameters, that transforms (longitude, latitude) to (x, y).

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Projection

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| angular_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Enhet som används för vinkelparametrar. |
| epsg_code | int | r | Om detta objekts identifierare är en EPSG‑identifierare – returnera dess kod. Annars – returnera -1. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Identifierare för detta identifierbara objekt. |
| linear_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Enhet som används för linjära parametrar. |
| namn | string | r | Namn på detta objekt. |
| parameters_names | System.Collections.Generic.IList<string> | r | Hämtar en enumererbar samling av namn på parametrar som ges till denna projektion |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_parameter_value(name, type)](#get_parameter_value_name_type_1) | Hämtar parameter med angivet namn för denna projektion. |
| [is_equivalent(other)](#is_equivalent_other_2) | Bestämmer om två projektioner är ekvivalenta. Ekvivalenta projektioner avbildar (longitude, latitude) till (x, y) på samma sätt.<br/>             |
| [try_get_parameter_value(name, type)](#try_get_parameter_value_name_type_3) | Hämtar parameter med angivet namn för denna projektion. Om det inte finns någon sådan parameter - returnerar <see langword="null" />. |


### Method: get_parameter_value(name, type) {#get_parameter_value_name_type_1}


```
 get_parameter_value(name, type) 
```

Hämtar parameter med angivet namn för denna projektion.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| namn | string | Namn på parameter. |
