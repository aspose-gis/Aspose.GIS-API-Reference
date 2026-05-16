---
title: "ProjectedSpatialReferenceSystemParameters Klasse"
type: docs
weight: 160
url: /nl/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/
---

**Summary:** Parameters to create projected SRS. Some of parameters have defaults.<br/>            Some parameters have reasonable defaults, so you don't have to assign only them.<br/>            If you assign <see langword="null" /> to those parameters, a default value will be used.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) and [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) don't have defaults -<br/>            you have to assign some non <see langword="null" /> value to this properties.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.ProjectedSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [ProjectedSpatialReferenceSystemParameters()](#ProjectedSpatialReferenceSystemParameters__1) | Creëert een nieuw exemplaar. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| axises_order | [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder) | r/w | Volgorde van assen. Standaard is [ProjectedAxisesOrder.XY](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/). |
| base | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r/w | Basis geografisch SRS (SRS waarop de projectie wordt toegepast).<br/>            U MOET deze eigenschap instellen op een niet-<see langword=\"null\" /> waarde om een geldig SRS te creëren,<br/>            deze eigenschap heeft geen standaardwaarde. |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | Eenheden die in dit SRS worden gebruikt. Standaard is [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| naam | string | r/w | Naam van het geprojecteerde SRS. Standaard is \"Unnamed\". |
| projection_method_identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r/w | Identificator van de projectiemethode. Er is geen standaardwaarde, u kunt deze parameter instellen op een niet-<see langword=\"null\" /> waarde,<br/>            als u een identificator aan de projectie wilt koppelen. Als u dat doet - het is aan u om ervoor te zorgen dat de identificator in een consistente projectiemethode<br/>            naam blijft (de naam van de projectiemethode verandert niet wanneer u deze eigenschap instelt). |
| projection_method_name | string | r/w | Naam van projectiemethode. Er is geen standaardwaarde en u MOET deze parameter instellen op een niet-<see langword="null" /> waarde, aangezien<br/>            een geprojecteerd SRS zonder projectienaam nutteloos is. |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | As die de X (horizontale) dimensie beschrijft. Standaard is de as met oostelijke richting. |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | As die de Y (verticale) dimensie beschrijft. Standaard is de as met noordelijke richting. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add_projection_parameter(parameter_name, value)](#add_projection_parameter_parameter_name_value_1) | Voegt een projectieparameter toe aan dit SRS. Als een parameter met die naam al is toegevoegd - werk deze bij. |
| [get_projection_parameter(parameter_name)](#get_projection_parameter_parameter_name_2) | Haalt de projectieparameter op met de opgegeven naam. |


### Constructor: ProjectedSpatialReferenceSystemParameters() {#ProjectedSpatialReferenceSystemParameters__1}


```
 ProjectedSpatialReferenceSystemParameters() 
```

Creëert een nieuw exemplaar.

### Method: add_projection_parameter(parameter_name, value) {#add_projection_parameter_parameter_name_value_1}


```
 add_projection_parameter(parameter_name, value) 
```

Voegt een projectieparameter toe aan dit SRS. Als een parameter met die naam al is toegevoegd - werk deze bij.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| parameter_name | string | Naam van projectieparameter. |
| value | double | Waarde van de parameter. Eenheid van de waarde moet zijn in [ProjectedSpatialReferenceSystemParameters.linear_unit](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/)<br/>            of [GeographicSpatialReferenceSystem.angular_unit](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) van [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/). |

### Method: get_projection_parameter(parameter_name) {#get_projection_parameter_parameter_name_2}


```
 get_projection_parameter(parameter_name) 
```

Haalt de projectieparameter op met de opgegeven naam.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| parameter_name | string | Naam van parameter. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| double | Waarde van projectieparameter. |


