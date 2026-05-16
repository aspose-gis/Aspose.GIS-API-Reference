---
title: "Classe ProjectedSpatialReferenceSystemParameters"
type: docs
weight: 160
url: /it/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/
---

**Summary:** Parameters to create projected SRS. Some of parameters have defaults.<br/>            Some parameters have reasonable defaults, so you don't have to assign only them.<br/>            If you assign <see langword="null" /> to those parameters, a default value will be used.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) and [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) don't have defaults -<br/>            you have to assign some non <see langword="null" /> value to this properties.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.ProjectedSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [ProjectedSpatialReferenceSystemParameters()](#ProjectedSpatialReferenceSystemParameters__1) | Crea una nuova istanza. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| axises_order | [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder) | r/w | Ordine degli assi. Predefinito è [ProjectedAxisesOrder.XY](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/). |
| base | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r/w | Base geographic SRS (SRS a cui viene applicata la proiezione).<br/>            È NECESSARIO impostare questa proprietà a un valore diverso da <see langword=\"null\" /> per creare un SRS valido,<br/>            questa proprietà non ha alcun valore predefinito. |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | Unità da utilizzare in questo SRS. Il valore predefinito è [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| nome | string | r/w | Nome del SRS proiettato. Il valore predefinito è \"Unnamed\". |
| projection_method_identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r/w | Identificatore del metodo di proiezione. Non esiste un valore predefinito, è possibile impostare questo parametro a un valore diverso da <see langword=\"null\" />,<br/>            se si desidera associare un identificatore alla proiezione. Se lo si fa, spetta a voi garantire che l'identificatore sia coerente con il nome del metodo di proiezione<br/>            (il nome del metodo di proiezione non cambierà quando impostate questa proprietà). |
| projection_method_name | string | r/w | Nome del metodo di proiezione. Non esiste un valore predefinito e devi impostare questo parametro su un valore diverso da <see langword="null" />, poiché<br/>            un SRS proiettato senza nome di proiezione è inutile. |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Asse che descrive la dimensione X (orizzontale). Per impostazione predefinita è l'asse con direzione est. |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Asse che descrive la dimensione Y (verticale). Per impostazione predefinita è l'asse con direzione nord. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add_projection_parameter(parameter_name, value)](#add_projection_parameter_parameter_name_value_1) | Aggiunge un parametro di proiezione a questo SRS. Se un parametro con lo stesso nome è già stato aggiunto, lo aggiorna. |
| [get_projection_parameter(parameter_name)](#get_projection_parameter_parameter_name_2) | Restituisce il parametro di proiezione con il nome specificato. |


### Constructor: ProjectedSpatialReferenceSystemParameters() {#ProjectedSpatialReferenceSystemParameters__1}


```
 ProjectedSpatialReferenceSystemParameters() 
```

Crea una nuova istanza.

### Method: add_projection_parameter(parameter_name, value) {#add_projection_parameter_parameter_name_value_1}


```
 add_projection_parameter(parameter_name, value) 
```

Aggiunge un parametro di proiezione a questo SRS. Se un parametro con lo stesso nome è già stato aggiunto, lo aggiorna.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| parameter_name | string | Nome del parametro di proiezione. |
| value | double | Valore del parametro. L'unità del valore deve essere in [ProjectedSpatialReferenceSystemParameters.linear_unit](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/)<br/>            o [GeographicSpatialReferenceSystem.angular_unit](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) di [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/). |

### Method: get_projection_parameter(parameter_name) {#get_projection_parameter_parameter_name_2}


```
 get_projection_parameter(parameter_name) 
```

Restituisce il parametro di proiezione con il nome specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| parameter_name | string | Nome del parametro. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| double | Valore del parametro di proiezione. |


