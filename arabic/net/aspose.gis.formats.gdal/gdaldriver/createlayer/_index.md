---
title: "GdalDriver.CreateLayer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة GdalDriver. تنشئ طبقة وتفتحها لإضافة ميزات جديدة"
type: docs
weight: 40
url: /ar/net/aspose.gis.formats.gdal/gdaldriver/createlayer/
---
## GdalDriver.CreateLayer method

ينشئ طبقة ويفتحها لإضافة ميزات جديدة.

```csharp
public override VectorLayer CreateLayer(AbstractPath path, DriverOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | AbstractPath | المسار إلى الملف. |
| options | DriverOptions | خيارات خاصة بالسائق. |
| spatialReferenceSystem | SpatialReferenceSystem | نظام الإسناد المكاني. |

### قيمة الإرجاع

كائن من [`VectorLayer`](../../../aspose.gis/vectorlayer/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | الطبقة موجودة بالفعل. |
| NotSupportedException | نظام الإسناد المكاني غير مدعوم من قبل السائق. |

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [DriverOptions](../../../aspose.gis/driveroptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [GdalDriver](../)
* namespace [Aspose.Gis.Formats.GDAL](../../gdaldriver/)
* assembly [Aspose.GIS](../../../)


