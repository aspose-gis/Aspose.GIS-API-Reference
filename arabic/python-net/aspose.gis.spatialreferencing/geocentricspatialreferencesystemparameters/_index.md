---
title: "فئة GeocentricSpatialReferenceSystemParameters"
type: docs
weight: 60
url: /ar/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/
---

**Summary:** Parameters to create geocentric SRS.<br/>            Parameters have reasonable defaults, so you will have to assign only some of them.<br/>            If you assign <see langword="null" /> to any parameter, a default value will be used.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeocentricSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GeocentricSpatialReferenceSystemParameters()](#GeocentricSpatialReferenceSystemParameters__1) | يُنشئ نسخة جديدة من فئة GeocentricSpatialReferenceSystemParameters |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| axises_order | [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder) | r/w | ترتيب المحاور. القيمة الافتراضية هي [GeocentricAxisesOrder.XYZ](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/). |
| datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r/w | المرجع لنظام الإحداثيات الجيوسنترية. القيمة الافتراضية هي [GeographicDatum.wgs84](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/). |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | الوحدات المستخدمة في هذا SRS. القيمة الافتراضية هي [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| الاسم | string | قراءة/كتابة | اسم نظام الإحداثيات الجيوسنترية. القيمة الافتراضية هي "Unnamed". |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r/w | خط الطول الرئيسي لهذا SRS. القيمة الافتراضية هي [PrimeMeridian.greenwich](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/). |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | محور نظام الإحداثيات الجيوسنترية الذي يصف البُعد 'X' (المحور الذي يشير إلى خط الطول الرئيسي). |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | محور نظام الإحداثيات الجيوسنترية الذي يصف البُعد 'Y' (المحور الذي يشير إلى اليسار أو اليمين من محور X على المستوى الاستوائي).<br/>            القيمة الافتراضية هي المحور باتجاه [AxisDirection.EAST](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/). |
| z_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | محور نظام الإحداثيات الجيوسنترية الذي يصف البُعد 'Z' (المحور الذي يشير إلى القطب الشمالي أو الجنوبي).<br/>            القيمة الافتراضية هي المحور باتجاه [AxisDirection.NORTH](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/). |


### Constructor: GeocentricSpatialReferenceSystemParameters() {#GeocentricSpatialReferenceSystemParameters__1}


```
 GeocentricSpatialReferenceSystemParameters() 
```

يُنشئ نسخة جديدة من فئة GeocentricSpatialReferenceSystemParameters

