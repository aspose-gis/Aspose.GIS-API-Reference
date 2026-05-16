---
title: "Projection Classe"
type: docs
weight: 170
url: /it/python-net/aspose.gis.spatialreferencing/projection/
---

**Summary:** Represents a projection method with parameters, that transforms (longitude, latitude) to (x, y).

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Projection

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| angular_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Unità utilizzata per i parametri angolari. |
| epsg_code | int | r | Se l'identificatore di questo oggetto è un identificatore EPSG, restituisce il suo codice. Altrimenti restituisce -1. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Identificatore di questo oggetto identificabile. |
| linear_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Unità utilizzata per i parametri lineari. |
| nome | string | r | Nome di questo oggetto. |
| parameters_names | System.Collections.Generic.IList<string> | r | Ottiene una collezione enumerabile dei nomi dei parametri forniti a questa proiezione |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [get_parameter_value(name, type)](#get_parameter_value_name_type_1) | Ottiene il parametro con il nome specificato di questa proiezione. |
| [is_equivalent(other)](#is_equivalent_other_2) | Determina se due proiezioni sono equivalenti. Le proiezioni equivalenti mappano (longitude, latitude) a (x, y) nello stesso modo.<br/>             |
| [try_get_parameter_value(name, type)](#try_get_parameter_value_name_type_3) | Ottiene il parametro con il nome specificato di questa proiezione. Se non esiste tale parametro - restituisce <see langword="null" />. |


### Method: get_parameter_value(name, type) {#get_parameter_value_name_type_1}


```
 get_parameter_value(name, type) 
```

Ottiene il parametro con il nome specificato di questa proiezione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| nome | string | Nome del parametro. |
