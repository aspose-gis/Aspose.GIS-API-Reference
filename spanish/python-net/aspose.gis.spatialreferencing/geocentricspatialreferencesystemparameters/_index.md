---
title: "Clase GeocentricSpatialReferenceSystemParameters"
type: docs
weight: 60
url: /es/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/
---

**Summary:** Parameters to create geocentric SRS.<br/>            Parameters have reasonable defaults, so you will have to assign only some of them.<br/>            If you assign <see langword="null" /> to any parameter, a default value will be used.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeocentricSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [GeocentricSpatialReferenceSystemParameters()](#GeocentricSpatialReferenceSystemParameters__1) | Inicializa una nueva instancia de la clase GeocentricSpatialReferenceSystemParameters |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| axises_order | [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder) | r/w | Orden de ejes. Por defecto es [GeocentricAxisesOrder.XYZ](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/). |
| datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r/w | Datum del SRS geocéntrico. Por defecto es [GeographicDatum.wgs84](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/). |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | Unidades a usar en este SRS. Por defecto es [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| nombre | string | r/w | Nombre del SRS geocéntrico. Por defecto es "Unnamed". |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r/w | Meridiano principal de este SRS. Por defecto es [PrimeMeridian.greenwich](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/). |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Eje del SRS geocéntrico que describe la dimensión 'X' (eje que apunta al meridiano principal). |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Eje del SRS geocéntrico que describe la dimensión 'Y' (eje que apunta a la izquierda o a la derecha del eje X en el plano ecuatorial).<br/>            Por defecto es el eje con dirección [AxisDirection.EAST](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/). |
| z_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Eje del SRS geocéntrico que describe la dimensión 'Z' (eje que apunta al polo norte o sur).<br/>            Por defecto es el eje con dirección [AxisDirection.NORTH](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/). |


### Constructor: GeocentricSpatialReferenceSystemParameters() {#GeocentricSpatialReferenceSystemParameters__1}


```
 GeocentricSpatialReferenceSystemParameters() 
```

Inicializa una nueva instancia de la clase GeocentricSpatialReferenceSystemParameters

