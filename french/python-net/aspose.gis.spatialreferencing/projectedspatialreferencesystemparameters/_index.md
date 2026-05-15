---
title: "Classe ProjectedSpatialReferenceSystemParameters"
type: docs
weight: 160
url: /fr/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/
---

**Summary:** Parameters to create projected SRS. Some of parameters have defaults.<br/>            Some parameters have reasonable defaults, so you don't have to assign only them.<br/>            If you assign <see langword="null" /> to those parameters, a default value will be used.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) and [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) don't have defaults -<br/>            you have to assign some non <see langword="null" /> value to this properties.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.ProjectedSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ProjectedSpatialReferenceSystemParameters()](#ProjectedSpatialReferenceSystemParameters__1) | Crée une nouvelle instance. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| axises_order | [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder) | r/w | Ordre des axes. Par défaut, [ProjectedAxisesOrder.XY](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/). |
| base | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r/w | SRS géographique de base (SRS auquel la projection est appliquée).<br/>            Vous DEVEZ définir cette propriété à une valeur différente de <see langword=\"null\" /> afin de créer un SRS valide,<br/>            cette propriété n'a aucune valeur par défaut. |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | Unités à utiliser dans ce SRS. Par défaut, [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| nom | string | r/w | Nom du SRS projeté. Par défaut, \"Unnamed\". |
| projection_method_identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r/w | Identifiant de la méthode de projection. Il n'existe aucune valeur par défaut, vous pouvez définir ce paramètre à une valeur différente de <see langword=\"null\" />,<br/>            si vous souhaitez associer un identifiant à la projection. Si vous le faites, il vous incombe de vous assurer que l'identifiant est cohérent avec le nom de la méthode de projection<br/>            (le nom de la méthode de projection ne changera pas lorsque vous définirez cette propriété). |
| projection_method_name | string | r/w | Nom de la méthode de projection. Il n’y a pas de valeur par défaut et vous DEVEZ définir ce paramètre sur une valeur différente de <see langword="null" />, car<br/>            le SRS projeté sans nom de projection est inutile. |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Axe décrivant la dimension X (horizontale). Par défaut, l’axe pointe vers l’est. |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Axe décrivant la dimension Y (verticale). Par défaut, l’axe pointe vers le nord. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_projection_parameter(parameter_name, value)](#add_projection_parameter_parameter_name_value_1) | Ajoute un paramètre de projection à ce SRS. Si un paramètre portant ce nom a déjà été ajouté, mettez-le à jour. |
| [get_projection_parameter(parameter_name)](#get_projection_parameter_parameter_name_2) | Obtient le paramètre de projection avec le nom spécifié. |


### Constructor: ProjectedSpatialReferenceSystemParameters() {#ProjectedSpatialReferenceSystemParameters__1}


```
 ProjectedSpatialReferenceSystemParameters() 
```

Crée une nouvelle instance.

### Method: add_projection_parameter(parameter_name, value) {#add_projection_parameter_parameter_name_value_1}


```
 add_projection_parameter(parameter_name, value) 
```

Ajoute un paramètre de projection à ce SRS. Si un paramètre portant ce nom a déjà été ajouté, mettez-le à jour.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| parameter_name | string | Nom du paramètre de projection. |
| value | double | Valeur du paramètre. L’unité de la valeur doit être dans [ProjectedSpatialReferenceSystemParameters.linear_unit](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/)<br/>            ou [GeographicSpatialReferenceSystem.angular_unit](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) de [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/). |

### Method: get_projection_parameter(parameter_name) {#get_projection_parameter_parameter_name_2}


```
 get_projection_parameter(parameter_name) 
```

Obtient le paramètre de projection avec le nom spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| parameter_name | string | Nom du paramètre. |

**Returns**

| Type | Description |
| :- | :- |
| double | Valeur du paramètre de projection. |


