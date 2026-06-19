---
title: "FileGdbDriver.CreateLayer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة FileGdbDriver. تنشئ طبقة وتفتحها لإضافة ميزات جديدة"
type: docs
weight: 60
url: /ar/net/aspose.gis.formats.filegdb/filegdbdriver/createlayer/
---
## CreateLayer(string, FileGdbOptions) {#createlayer_8}

ينشئ طبقة ويفتحها لإضافة ميزات جديدة.

```csharp
public VectorLayer CreateLayer(string path, FileGdbOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | String | المسار إلى الملف. |
| options | FileGdbOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

كائن من [`VectorLayer`](../../../aspose.gis/vectorlayer/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | الطبقة موجودة بالفعل. |

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [FileGdbOptions](../../filegdboptions/)
* class [FileGdbDriver](../)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdbdriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(string, FileGdbOptions, SpatialReferenceSystem) {#createlayer_9}

ينشئ طبقة ويفتحها للإلحاق.

```csharp
public VectorLayer CreateLayer(string path, FileGdbOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | String | المسار إلى الملف. |
| options | FileGdbOptions | خيارات خاصة بالسائق. |
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
* class [FileGdbOptions](../../filegdboptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [FileGdbDriver](../)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdbdriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath, DriverOptions, SpatialReferenceSystem) {#createlayer_2}

ينشئ طبقة ويفتحها للإلحاق.

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
* class [FileGdbDriver](../)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdbdriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath, FileGdbOptions, SpatialReferenceSystem) {#createlayer_3}

ينشئ طبقة ويفتحها للإلحاق.

```csharp
public VectorLayer CreateLayer(AbstractPath path, FileGdbOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | AbstractPath | المسار إلى الملف. |
| options | FileGdbOptions | خيارات خاصة بالسائق. |
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
* class [FileGdbOptions](../../filegdboptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [FileGdbDriver](../)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdbdriver/)
* assembly [Aspose.GIS](../../../)


