---
title: "ProjectedSpatialReferenceSystemParameters klass"
type: docs
weight: 160
url: /sv/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/
---

**Summary:** Parameters to create projected SRS. Some of parameters have defaults.<br/>            Some parameters have reasonable defaults, so you don't have to assign only them.<br/>            If you assign <see langword="null" /> to those parameters, a default value will be used.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) and [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) don't have defaults -<br/>            you have to assign some non <see langword="null" /> value to this properties.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.ProjectedSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [ProjectedSpatialReferenceSystemParameters()](#ProjectedSpatialReferenceSystemParameters__1) | Skapar ny instans. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| axises_order | [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder) | r/w | Ordning av axlar. Standard är [ProjectedAxisesOrder.XY](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/). |
| base | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r/w | Basgeografisk SRS (SRS som projektionen tillämpas på).<br/>            Du MÅSTE sätta detta egenskap till ett icke-<see langword=\"null\" /> värde för att skapa en giltig SRS,<br/>            denna egenskap har inget standardvärde. |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | Enheter som ska användas i denna SRS. Standard är [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| namn | string | läs/skriv | Namn på projicerad SRS. Standard är \"Unnamed\". |
| projection_method_identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r/w | Identifierare för projektionmetod. Det finns inget standardvärde, du kan sätta denna parameter till ett icke-<see langword=\"null\" /> värde,<br/>            om du vill bifoga identifierare till projektionen. Om du gör det är det upp till dig att säkerställa att identifieraren är i en konsekvent projektionmetod<br/>            namn (projektionmetodens namn kommer inte att ändras när du sätter denna egenskap). |
| projection_method_name | string | läs/skriv | Namn på projektionmetod. Det finns inget standardvärde och du MÅSTE sätta detta parameter till ett icke <see langword="null" /> värde, eftersom<br/>            projicerat SRS utan projektionnamn är värdelöst. |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Axel som beskriver X‑dimensionen (horisontell). Standard är axel med östlig riktning. |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Axel som beskriver Y‑dimensionen (vertikal). Standard är axel med nordlig riktning. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add_projection_parameter(parameter_name, value)](#add_projection_parameter_parameter_name_value_1) | Lägger till projektionparameter till detta SRS. Om en parameter med samma namn redan har lagts till – uppdatera den. |
| [get_projection_parameter(parameter_name)](#get_projection_parameter_parameter_name_2) | Hämtar projektionparameter med angivet namn. |


### Constructor: ProjectedSpatialReferenceSystemParameters() {#ProjectedSpatialReferenceSystemParameters__1}


```
 ProjectedSpatialReferenceSystemParameters() 
```

Skapar ny instans.

### Method: add_projection_parameter(parameter_name, value) {#add_projection_parameter_parameter_name_value_1}


```
 add_projection_parameter(parameter_name, value) 
```

Lägger till projektionparameter till detta SRS. Om en parameter med samma namn redan har lagts till – uppdatera den.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| parameter_name | string | Namn på projektionparameter. |
| value | double | Värde på parametern. Enheten för värdet bör vara i [ProjectedSpatialReferenceSystemParameters.linear_unit](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/)<br/>            eller [GeographicSpatialReferenceSystem.angular_unit](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) av [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/). |

### Method: get_projection_parameter(parameter_name) {#get_projection_parameter_parameter_name_2}


```
 get_projection_parameter(parameter_name) 
```

Hämtar projektionparameter med angivet namn.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| parameter_name | string | Namn på parameter. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| double | Värde på projektionparameter. |


