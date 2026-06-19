---
title: "GpxDriver.CreateLayer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة GpxDriver. تنشئ طبقة وتفتحها لإضافة ميزات جديدة"
type: docs
weight: 40
url: /ar/net/aspose.gis.formats.gpx/gpxdriver/createlayer/
---
## CreateLayer(string, GpxOptions) {#createlayer_9}

ينشئ طبقة ويفتحها لإضافة ميزات جديدة.

```csharp
public VectorLayer CreateLayer(string path, GpxOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | String | المسار إلى الملف. |
| options | GpxOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

كائن من [`VectorLayer`](../../../aspose.gis/vectorlayer/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | الطبقة موجودة بالفعل. |

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [GpxOptions](../../gpxoptions/)
* class [GpxDriver](../)
* namespace [Aspose.Gis.Formats.Gpx](../../gpxdriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath, GpxOptions) {#createlayer_3}

ينشئ طبقة ويفتحها لإضافة ميزات جديدة.

```csharp
public VectorLayer CreateLayer(AbstractPath path, GpxOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | AbstractPath | المسار إلى الملف. |
| options | GpxOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

كائن من [`VectorLayer`](../../../aspose.gis/vectorlayer/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | الطبقة موجودة بالفعل. |

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [GpxOptions](../../gpxoptions/)
* class [GpxDriver](../)
* namespace [Aspose.Gis.Formats.Gpx](../../gpxdriver/)
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
| path | AbstractPath | المسار إلى الملف. |
| options | DriverOptions | خيارات خاصة بالسائق. |
| spatialReferenceSystem | SpatialReferenceSystem | نظام الإسناد المكاني. |

### قيمة الإرجاع

كائن من [`VectorLayer`](../../../aspose.gis/vectorlayer/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | الطبقة موجودة بالفعل. |

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [DriverOptions](../../../aspose.gis/driveroptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [GpxDriver](../)
* namespace [Aspose.Gis.Formats.Gpx](../../gpxdriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath, GpxOptions, SpatialReferenceSystem) {#createlayer_4}

ينشئ طبقة ويفتحها لإضافة ميزات جديدة.

```csharp
public VectorLayer CreateLayer(AbstractPath path, GpxOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | AbstractPath | المسار إلى الملف. |
| options | GpxOptions | خيارات خاصة بالسائق. |
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
* class [GpxOptions](../../gpxoptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [GpxDriver](../)
* namespace [Aspose.Gis.Formats.Gpx](../../gpxdriver/)
* assembly [Aspose.GIS](../../../)


