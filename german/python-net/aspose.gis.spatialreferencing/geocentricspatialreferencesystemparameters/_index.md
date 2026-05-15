---
title: "GeocentricSpatialReferenceSystemParameters Klasse"
type: docs
weight: 60
url: /de/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/
---

**Summary:** Parameters to create geocentric SRS.<br/>            Parameters have reasonable defaults, so you will have to assign only some of them.<br/>            If you assign <see langword="null" /> to any parameter, a default value will be used.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeocentricSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [GeocentricSpatialReferenceSystemParameters()](#GeocentricSpatialReferenceSystemParameters__1) | Initialisiert eine neue Instanz der GeocentricSpatialReferenceSystemParameters Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| axises_order | [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder) | r/w | Reihenfolge der Achsen. Standardwert ist [GeocentricAxisesOrder.XYZ](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/). |
| datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r/w | Datum des geozentrischen SRS. Standardwert ist [GeographicDatum.wgs84](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/). |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | Einheiten, die in diesem SRS verwendet werden sollen. Standardwert ist [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| Name | string | r/w | Name des geozentrischen SRS. Standardwert ist "Unnamed". |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r/w | Nullmeridian dieses SRS. Standardwert ist [PrimeMeridian.greenwich](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/). |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Achse des geozentrischen SRS, die die 'X'-Dimension beschreibt (Achse, die zum Nullmeridian zeigt). |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Achse des geozentrischen SRS, die die 'Y'-Dimension beschreibt (Achse, die links oder rechts von der X-Achse in der Äquatorebene zeigt).<br/>            Standardwert ist die Achse mit Richtung [AxisDirection.EAST](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/). |
| z_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Achse des geozentrischen SRS, die die 'Z'-Dimension beschreibt (Achse, die zum Nord- oder Südpol zeigt).<br/>            Standardwert ist die Achse mit Richtung [AxisDirection.NORTH](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/). |


### Constructor: GeocentricSpatialReferenceSystemParameters() {#GeocentricSpatialReferenceSystemParameters__1}


```
 GeocentricSpatialReferenceSystemParameters() 
```

Initialisiert eine neue Instanz der GeocentricSpatialReferenceSystemParameters Klasse

