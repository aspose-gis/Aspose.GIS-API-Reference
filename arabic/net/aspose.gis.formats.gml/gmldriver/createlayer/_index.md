---
title: "GmlDriver.CreateLayer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة GmlDriver. تنشئ طبقة وتفتحها لإضافة ميزات جديدة"
type: docs
weight: 40
url: /ar/net/aspose.gis.formats.gml/gmldriver/createlayer/
---
## CreateLayer(string, GmlOptions) {#createlayer_7}

ينشئ طبقة ويفتحها لإضافة ميزات جديدة.

```csharp
public VectorLayer CreateLayer(string path, GmlOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | String | المسار إلى الملف. |
| options | GmlOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

كائن من [`VectorLayer`](../../../aspose.gis/vectorlayer/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | الطبقة موجودة بالفعل. |

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [GmlOptions](../../gmloptions/)
* class [GmlDriver](../)
* namespace [Aspose.Gis.Formats.Gml](../../gmldriver/)
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
* class [GmlDriver](../)
* namespace [Aspose.Gis.Formats.Gml](../../gmldriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(string, GmlOptions, SpatialReferenceSystem) {#createlayer_8}

ينشئ طبقة ويفتحها لإضافة ميزات جديدة.

```csharp
public VectorLayer CreateLayer(string path, GmlOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | String | المسار إلى الملف. |
| options | GmlOptions | خيارات خاصة بالسائق. |
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
* class [GmlOptions](../../gmloptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [GmlDriver](../)
* namespace [Aspose.Gis.Formats.Gml](../../gmldriver/)
* assembly [Aspose.GIS](../../../)


