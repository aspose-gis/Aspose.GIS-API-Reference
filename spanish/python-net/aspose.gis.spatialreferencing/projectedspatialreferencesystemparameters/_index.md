---
title: "Clase ProjectedSpatialReferenceSystemParameters"
type: docs
weight: 160
url: /es/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/
---

**Summary:** Parameters to create projected SRS. Some of parameters have defaults.<br/>            Some parameters have reasonable defaults, so you don't have to assign only them.<br/>            If you assign <see langword="null" /> to those parameters, a default value will be used.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) and [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) don't have defaults -<br/>            you have to assign some non <see langword="null" /> value to this properties.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.ProjectedSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [ProjectedSpatialReferenceSystemParameters()](#ProjectedSpatialReferenceSystemParameters__1) | Crea una nueva instancia. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| axises_order | [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder) | r/w | Orden de ejes. Por defecto es [ProjectedAxisesOrder.XY](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/). |
| base | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r/w | Base geographic SRS (SRS al que se aplica la proyección).<br/>            DEBE establecer esta propiedad a un valor distinto de <see langword=\"null\" /> para crear un SRS válido,<br/>            esta propiedad no tiene ningún valor predeterminado. |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | Unidades a usar en este SRS. Por defecto es [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| nombre | string | r/w | Nombre del SRS proyectado. Por defecto es \"Unnamed\". |
| projection_method_identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r/w | Identificador del método de proyección. No hay un valor predeterminado, puede establecer este parámetro a un valor distinto de <see langword=\"null\" />,<br/>            si desea adjuntar un identificador a la proyección. Si lo hace, depende de usted garantizar que el identificador sea coherente con el método de proyección<br/>            nombre (el nombre del método de proyección no cambiará cuando establezca esta propiedad). |
| projection_method_name | string | r/w | Nombre del método de proyección. No hay un valor predeterminado y DEBE establecer este parámetro a un valor distinto de <see langword=\"null\" />, ya que<br/>            el SRS proyectado sin nombre de proyección es inútil. |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Eje que describe la dimensión X (horizontal). Por defecto es el eje con dirección este. |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Eje que describe la dimensión Y (vertical). Por defecto es el eje con dirección norte. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [add_projection_parameter(parameter_name, value)](#add_projection_parameter_parameter_name_value_1) | Agrega un parámetro de proyección a este SRS. Si ya se había añadido un parámetro con ese nombre, actualícelo. |
| [get_projection_parameter(parameter_name)](#get_projection_parameter_parameter_name_2) | Obtiene el parámetro de proyección con el nombre especificado. |


### Constructor: ProjectedSpatialReferenceSystemParameters() {#ProjectedSpatialReferenceSystemParameters__1}


```
 ProjectedSpatialReferenceSystemParameters() 
```

Crea una nueva instancia.

### Method: add_projection_parameter(parameter_name, value) {#add_projection_parameter_parameter_name_value_1}


```
 add_projection_parameter(parameter_name, value) 
```

Agrega un parámetro de proyección a este SRS. Si ya se había añadido un parámetro con ese nombre, actualícelo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| parameter_name | string | Nombre del parámetro de proyección. |
| value | double | Valor del parámetro. La unidad del valor debe estar en [ProjectedSpatialReferenceSystemParameters.linear_unit](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/)<br/>            o [GeographicSpatialReferenceSystem.angular_unit](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) de [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/). |

### Method: get_projection_parameter(parameter_name) {#get_projection_parameter_parameter_name_2}


```
 get_projection_parameter(parameter_name) 
```

Obtiene el parámetro de proyección con el nombre especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| parameter_name | string | Nombre del parámetro. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| double | Valor del parámetro de proyección. |


