---
title: "GeographicSpatialReferenceSystemParameters Klasse"
type: docs
weight: 90
url: /de/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters/
---

**Summary:** Parameters to create geographic SRS.<br/>            Parameters have reasonable defaults, so you will have to assign only some of them.<br/>            If you assign <see langword="null" /> to any parameter, a default value will be used.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [GeographicSpatialReferenceSystemParameters()](#GeographicSpatialReferenceSystemParameters__1) | Initialisiert eine neue Instanz der GeographicSpatialReferenceSystemParameters Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| angular_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | Einheiten, die in diesem SRS verwendet werden. Standard ist [Unit.degree](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| axises_order | [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder) | r/w | Reihenfolge der Achsen. Standard ist [GeographicAxisesOrder.LONGITUDE_LATITUDE](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/). |
| datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r/w | Datum des geografischen SRS. Standard ist [GeographicDatum.wgs84](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/). |
| latitude_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Achse, die die Breite beschreibt. Standard ist die Achse mit Nordrichtung. |
| longitude_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Achse, die die Länge beschreibt. Standard ist die Achse mit Ostrichtung. |
| Name | string | r/w | Name des geografischen SRS. Standard ist "Unnamed". |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r/w | Nullmeridian dieses SRS. Standardwert ist [PrimeMeridian.greenwich](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/). |


### Constructor: GeographicSpatialReferenceSystemParameters() {#GeographicSpatialReferenceSystemParameters__1}


```
 GeographicSpatialReferenceSystemParameters() 
```

Initialisiert eine neue Instanz der GeographicSpatialReferenceSystemParameters Klasse

