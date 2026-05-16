---
title: "GeocentricSpatialReferenceSystemParameters Klasse"
type: docs
weight: 60
url: /nl/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/
---

**Summary:** Parameters to create geocentric SRS.<br/>            Parameters have reasonable defaults, so you will have to assign only some of them.<br/>            If you assign <see langword="null" /> to any parameter, a default value will be used.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeocentricSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [GeocentricSpatialReferenceSystemParameters()](#GeocentricSpatialReferenceSystemParameters__1) | Initialiseert een nieuw exemplaar van de GeocentricSpatialReferenceSystemParameters klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| axises_order | [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder) | r/w | Volgorde van assen. Standaard is [GeocentricAxisesOrder.XYZ](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/). |
| datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r/w | Datum van geocentrisch SRS. Standaard is [GeographicDatum.wgs84](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/). |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | Eenheden die in dit SRS gebruikt worden. Standaard is [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| naam | string | r/w | Naam van geocentrisch SRS. Standaard is "Unnamed". |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r/w | Primaire meridiaan van dit SRS. Standaard is [PrimeMeridian.greenwich](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/). |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | As van geocentrisch SRS die de 'X'-dimensie beschrijft (as die naar de primaire meridiaan wijst). |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | As van geocentrisch SRS die de 'Y'-dimensie beschrijft (as die naar links of rechts van de X-as wijst op het equatoriale vlak).<br/>            Standaard is as met [AxisDirection.EAST](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) richting. |
| z_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | As van geocentrisch SRS die de 'Z'-dimensie beschrijft (as die naar de noord- of zuidpool wijst).<br/>            Standaard is as met [AxisDirection.NORTH](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) richting. |


### Constructor: GeocentricSpatialReferenceSystemParameters() {#GeocentricSpatialReferenceSystemParameters__1}


```
 GeocentricSpatialReferenceSystemParameters() 
```

Initialiseert een nieuw exemplaar van de GeocentricSpatialReferenceSystemParameters klasse

