---
title: "GeocentricSpatialReferenceSystemParameters-klass"
type: docs
weight: 60
url: /sv/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/
---

**Summary:** Parameters to create geocentric SRS.<br/>            Parameters have reasonable defaults, so you will have to assign only some of them.<br/>            If you assign <see langword="null" /> to any parameter, a default value will be used.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeocentricSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [GeocentricSpatialReferenceSystemParameters()](#GeocentricSpatialReferenceSystemParameters__1) | Initierar en ny instans av klassen GeocentricSpatialReferenceSystemParameters |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| axises_order | [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder) | r/w | Ordning av axlar. Standard är [GeocentricAxisesOrder.XYZ](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/). |
| datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r/w | Datum för geocentriskt SRS. Standard är [GeographicDatum.wgs84](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/). |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | Enheter som ska användas i detta SRS. Standard är [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| namn | string | läs/skriv | Namn på geocentriskt SRS. Standard är "Unnamed". |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r/w | Primärmeridian för detta SRS. Standard är [PrimeMeridian.greenwich](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/). |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Axel för geocentriskt SRS som beskriver 'X'-dimensionen (axel som pekar mot primärmeridianen). |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Axel för geocentriskt SRS som beskriver 'Y'-dimensionen (axel som pekar åt vänster eller höger om X-axeln på ekvatorialplanet).<br/>            Standard är axel med [AxisDirection.EAST](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) riktning. |
| z_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Axel för geocentriskt SRS som beskriver 'Z'-dimensionen (axel som pekar mot norra eller södra polen).<br/>            Standard är axel med [AxisDirection.NORTH](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) riktning. |


### Constructor: GeocentricSpatialReferenceSystemParameters() {#GeocentricSpatialReferenceSystemParameters__1}


```
 GeocentricSpatialReferenceSystemParameters() 
```

Initierar en ny instans av klassen GeocentricSpatialReferenceSystemParameters

