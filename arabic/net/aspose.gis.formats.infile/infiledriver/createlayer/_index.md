---
title: "InFileDriver.CreateLayer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة InFileDriver. تنشئ طبقة وتفتحها لإضافة ميزات جديدة"
type: docs
weight: 40
url: /ar/net/aspose.gis.formats.infile/infiledriver/createlayer/
---
## CreateLayer(string, InFileOptions) {#createlayer_9}

ينشئ طبقة ويفتحها لإضافة ميزات جديدة.

```csharp
public VectorLayer CreateLayer(string path, InFileOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | String | المسار إلى الملف. |
| options | InFileOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

كائن من [`VectorLayer`](../../../aspose.gis/vectorlayer/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | الطبقة موجودة بالفعل. |

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [InFileOptions](../../infileoptions/)
* class [InFileDriver](../)
* namespace [Aspose.Gis.Formats.InFile](../../infiledriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath, InFileOptions) {#createlayer_3}

ينشئ طبقة ويفتحها لإضافة ميزات جديدة.

```csharp
public VectorLayer CreateLayer(AbstractPath path, InFileOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | AbstractPath | المسار إلى الملف. |
| options | InFileOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

كائن من [`VectorLayer`](../../../aspose.gis/vectorlayer/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | الطبقة موجودة بالفعل. |

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [InFileOptions](../../infileoptions/)
* class [InFileDriver](../)
* namespace [Aspose.Gis.Formats.InFile](../../infiledriver/)
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
* class [InFileDriver](../)
* namespace [Aspose.Gis.Formats.InFile](../../infiledriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath, InFileOptions, SpatialReferenceSystem) {#createlayer_4}

ينشئ طبقة ويفتحها لإضافة ميزات جديدة.

```csharp
public VectorLayer CreateLayer(AbstractPath path, InFileOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | AbstractPath | المسار إلى الملف. |
| options | InFileOptions | خيارات خاصة بالسائق. |
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
* class [InFileOptions](../../infileoptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [InFileDriver](../)
* namespace [Aspose.Gis.Formats.InFile](../../infiledriver/)
* assembly [Aspose.GIS](../../../)


