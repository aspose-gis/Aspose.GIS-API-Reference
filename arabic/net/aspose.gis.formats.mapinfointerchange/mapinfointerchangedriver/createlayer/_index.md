---
title: "MapInfoInterchangeDriver.CreateLayer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة MapInfoInterchangeDriver. تنشئ طبقة وتفتحها لإضافة ميزات جديدة"
type: docs
weight: 40
url: /ar/net/aspose.gis.formats.mapinfointerchange/mapinfointerchangedriver/createlayer/
---
## CreateLayer(string, MapInfoInterchangeOptions) {#createlayer_7}

ينشئ طبقة ويفتحها لإضافة ميزات جديدة.

```csharp
public VectorLayer CreateLayer(string path, MapInfoInterchangeOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار إلى الملف. |
| الخيارات | MapInfoInterchangeOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

مثيل من [`VectorLayer`](../../../aspose.gis/vectorlayer/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | الطبقة موجودة بالفعل. |

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [MapInfoInterchangeOptions](../../mapinfointerchangeoptions/)
* class [MapInfoInterchangeDriver](../)
* namespace [Aspose.Gis.Formats.MapInfoInterchange](../../mapinfointerchangedriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath, DriverOptions, SpatialReferenceSystem) {#createlayer_2}

ينشئ طبقة ويفتحها لإضافة ميزات جديدة.

```csharp
public override VectorLayer CreateLayer(AbstractPath path, DriverOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | AbstractPath | المسار إلى الملف. |
| الخيارات | DriverOptions | خيارات خاصة بالسائق. |
| spatialReferenceSystem | SpatialReferenceSystem | نظام الإحداثيات المكانية. |

### قيمة الإرجاع

مثيل من [`VectorLayer`](../../../aspose.gis/vectorlayer/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | الطبقة موجودة بالفعل. |

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [DriverOptions](../../../aspose.gis/driveroptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [MapInfoInterchangeDriver](../)
* namespace [Aspose.Gis.Formats.MapInfoInterchange](../../mapinfointerchangedriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(string, MapInfoInterchangeOptions, SpatialReferenceSystem) {#createlayer_8}

ينشئ طبقة ويفتحها لإضافة ميزات جديدة.

```csharp
public VectorLayer CreateLayer(string path, MapInfoInterchangeOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار إلى الملف. |
| الخيارات | MapInfoInterchangeOptions | خيارات خاصة بالسائق. |
| spatialReferenceSystem | SpatialReferenceSystem | نظام الإحداثيات المكانية. |

### قيمة الإرجاع

مثيل من [`VectorLayer`](../../../aspose.gis/vectorlayer/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | الطبقة موجودة بالفعل. |
| NotSupportedException | نظام الإحداثيات المكانية غير مدعوم من قبل السائق. |

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [MapInfoInterchangeOptions](../../mapinfointerchangeoptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [MapInfoInterchangeDriver](../)
* namespace [Aspose.Gis.Formats.MapInfoInterchange](../../mapinfointerchangedriver/)
* assembly [Aspose.GIS](../../../)


