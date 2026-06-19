---
title: "ShapefileDriver.CreateLayer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة ShapefileDriver. تنشئ طبقة وتفتحها لإضافة ميزات جديدة"
type: docs
weight: 40
url: /ar/net/aspose.gis.formats.shapefile/shapefiledriver/createlayer/
---
## CreateLayer(string, ShapefileOptions) {#createlayer_9}

ينشئ طبقة ويفتحها لإضافة ميزات جديدة.

```csharp
public VectorLayer CreateLayer(string path, ShapefileOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | String | المسار إلى الملف. |
| options | ShapefileOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

كائن من [`VectorLayer`](../../../aspose.gis/vectorlayer/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | الطبقة موجودة بالفعل. |

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [ShapefileOptions](../../shapefileoptions/)
* class [ShapefileDriver](../)
* namespace [Aspose.Gis.Formats.Shapefile](../../shapefiledriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath, ShapefileOptions) {#createlayer_3}

ينشئ طبقة ويفتحها لإضافة ميزات جديدة.

```csharp
public VectorLayer CreateLayer(AbstractPath path, ShapefileOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | AbstractPath | المسار إلى الملف. |
| options | ShapefileOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

كائن من [`VectorLayer`](../../../aspose.gis/vectorlayer/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | الطبقة موجودة بالفعل. |

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [ShapefileOptions](../../shapefileoptions/)
* class [ShapefileDriver](../)
* namespace [Aspose.Gis.Formats.Shapefile](../../shapefiledriver/)
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
* class [ShapefileDriver](../)
* namespace [Aspose.Gis.Formats.Shapefile](../../shapefiledriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath, ShapefileOptions, SpatialReferenceSystem) {#createlayer_4}

ينشئ طبقة ويفتحها لإضافة ميزات جديدة.

```csharp
public VectorLayer CreateLayer(AbstractPath path, ShapefileOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | AbstractPath | المسار إلى الملف. |
| options | ShapefileOptions | خيارات خاصة بالسائق. |
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
* class [ShapefileOptions](../../shapefileoptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [ShapefileDriver](../)
* namespace [Aspose.Gis.Formats.Shapefile](../../shapefiledriver/)
* assembly [Aspose.GIS](../../../)


