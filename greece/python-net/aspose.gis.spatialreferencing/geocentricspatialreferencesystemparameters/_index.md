---
title: "GeocentricSpatialReferenceSystemParameters Κλάση"
type: docs
weight: 60
url: /el/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/
---

**Summary:** Parameters to create geocentric SRS.<br/>            Parameters have reasonable defaults, so you will have to assign only some of them.<br/>            If you assign <see langword="null" /> to any parameter, a default value will be used.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeocentricSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GeocentricSpatialReferenceSystemParameters()](#GeocentricSpatialReferenceSystemParameters__1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης GeocentricSpatialReferenceSystemParameters |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| axises_order | [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder) | r/w | Σειρά των αξόνων. Προεπιλογή είναι [GeocentricAxisesOrder.XYZ](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/). |
| datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r/w | Datum του γεωκεντρικού SRS. Προεπιλογή είναι [GeographicDatum.wgs84](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/). |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | Μονάδες που θα χρησιμοποιηθούν σε αυτό το SRS. Προεπιλογή είναι [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| όνομα | string | r/w | Όνομα του γεωκεντρικού SRS. Προεπιλογή είναι "Unnamed". |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r/w | Πρωτεύων μεσημβρινός αυτού του SRS. Προεπιλογή είναι [PrimeMeridian.greenwich](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/). |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Άξονας του γεωκεντρικού SRS που περιγράφει τη διάσταση 'X' (άξονας που δείχνει προς τον πρωτεύοντα μεσημβρινό). |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Άξονας του γεωκεντρικού SRS που περιγράφει τη διάσταση 'Y' (άξονας που δείχνει προς τα αριστερά ή δεξιά του άξονα X στο ισημερινό επίπεδο).<br/>            Προεπιλογή είναι ο άξονας με κατεύθυνση [AxisDirection.EAST](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/). |
| z_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Άξονας του γεωκεντρικού SRS που περιγράφει τη διάσταση 'Z' (άξονας που δείχνει προς το βόρειο ή νότιο πόλο).<br/>            Προεπιλογή είναι ο άξονας με κατεύθυνση [AxisDirection.NORTH](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/). |


### Constructor: GeocentricSpatialReferenceSystemParameters() {#GeocentricSpatialReferenceSystemParameters__1}


```
 GeocentricSpatialReferenceSystemParameters() 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης GeocentricSpatialReferenceSystemParameters

