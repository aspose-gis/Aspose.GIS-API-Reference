---
title: "ProjectedSpatialReferenceSystemParameters-Klasse"
type: docs
weight: 160
url: /de/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/
---

**Summary:** Parameters to create projected SRS. Some of parameters have defaults.<br/>            Some parameters have reasonable defaults, so you don't have to assign only them.<br/>            If you assign <see langword="null" /> to those parameters, a default value will be used.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) and [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) don't have defaults -<br/>            you have to assign some non <see langword="null" /> value to this properties.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.ProjectedSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [ProjectedSpatialReferenceSystemParameters()](#ProjectedSpatialReferenceSystemParameters__1) | Erstellt eine neue Instanz. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| axises_order | [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder) | r/w | Reihenfolge der Achsen. Standard ist [ProjectedAxisesOrder.XY](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/). |
| base | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r/w | Basis-geografisches SRS (SRS, auf das die Projektion angewendet wird).<br/>            Sie MÜSSEN diese Eigenschaft auf einen Wert ungleich <see langword="null" /> setzen, um ein gültiges SRS zu erstellen,<br/>            diese Eigenschaft hat keinen Standardwert. |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | Einheiten, die in diesem SRS verwendet werden. Standard ist [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| Name | string | r/w | Name des projizierten SRS. Standard ist "Unnamed". |
| projection_method_identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r/w | Bezeichner der Projektionsmethode. Es gibt keinen Standardwert, Sie können diesen Parameter auf einen Wert ungleich <see langword="null" /> setzen,<br/>            wenn Sie der Projektion einen Bezeichner zuweisen möchten. Wenn Sie dies tun – liegt es an Ihnen, sicherzustellen, dass der Bezeichner in einer konsistenten Projektionsmethode<br/>            bleibt (der Name der Projektionsmethode ändert sich nicht, wenn Sie diese Eigenschaft setzen). |
| projection_method_name | string | r/w | Name der Projektionsmethode. Es gibt keinen Standardwert und Sie MÜSSEN diesen Parameter auf einen Wert ungleich <see langword="null" /> setzen, da<br/>            ein projiziertes SRS ohne Projektionsnamen nutzlos ist. |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Achse, die die X (horizontal) Dimension beschreibt. Standardmäßig die Achse mit Ost‑Richtung. |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Achse, die die Y (vertical) Dimension beschreibt. Standardmäßig die Achse mit Nord‑Richtung. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_projection_parameter(parameter_name, value)](#add_projection_parameter_parameter_name_value_1) | Fügt dem SRS einen Projektionsparameter hinzu. Wenn ein Parameter mit diesem Namen bereits hinzugefügt wurde – aktualisieren Sie ihn. |
| [get_projection_parameter(parameter_name)](#get_projection_parameter_parameter_name_2) | Ruft den Projektionsparameter mit dem angegebenen Namen ab. |


### Constructor: ProjectedSpatialReferenceSystemParameters() {#ProjectedSpatialReferenceSystemParameters__1}


```
 ProjectedSpatialReferenceSystemParameters() 
```

Erstellt eine neue Instanz.

### Method: add_projection_parameter(parameter_name, value) {#add_projection_parameter_parameter_name_value_1}


```
 add_projection_parameter(parameter_name, value) 
```

Fügt dem SRS einen Projektionsparameter hinzu. Wenn ein Parameter mit diesem Namen bereits hinzugefügt wurde – aktualisieren Sie ihn.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| parameter_name | string | Name des Projektionsparameters. |
| value | double | Wert des Parameters. Die Einheit des Wertes sollte in [ProjectedSpatialReferenceSystemParameters.linear_unit](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/)<br/>            oder [GeographicSpatialReferenceSystem.angular_unit](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) von [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) liegen. |

### Method: get_projection_parameter(parameter_name) {#get_projection_parameter_parameter_name_2}


```
 get_projection_parameter(parameter_name) 
```

Ruft den Projektionsparameter mit dem angegebenen Namen ab.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| parameter_name | string | Name des Parameters. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| double | Wert des Projektionsparameters. |


