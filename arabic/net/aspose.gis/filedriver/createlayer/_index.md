---
title: "FileDriver.CreateLayer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة FileDriver. ينشئ الطبقة ويفتحها للإلحاق"
type: docs
weight: 60
url: /ar/net/aspose.gis/filedriver/createlayer/
---
## CreateLayer(string) {#createlayer_4}

ينشئ الطبقة ويفتحها للإلحاق.

```csharp
public VectorLayer CreateLayer(string path)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار إلى الملف. |

### قيمة الإرجاع

مثال من [`VectorLayer`](../../vectorlayer/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المسار هو `null`. |
| [GisException](../../gisexception/) | خطأ في كتابة الميزة إلى الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | السائق لا يمكنه إنشاء طبقات المتجه (انظر [`CanCreateLayers`](../cancreatelayers/)). |

### انظر أيضًا

* class [VectorLayer](../../vectorlayer/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath) {#createlayer}

ينشئ الطبقة ويفتحها للإلحاق.

```csharp
public VectorLayer CreateLayer(AbstractPath path)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | AbstractPath | المسار إلى الملف. |

### قيمة الإرجاع

مثال من [`VectorLayer`](../../vectorlayer/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المسار هو `null`. |
| [GisException](../../gisexception/) | خطأ في كتابة الميزة إلى الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | السائق لا يمكنه إنشاء طبقات المتجه (انظر [`CanCreateLayers`](../cancreatelayers/)). |

### انظر أيضًا

* class [VectorLayer](../../vectorlayer/)
* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(string, DriverOptions) {#createlayer_5}

ينشئ الطبقة ويفتحها للإلحاق.

```csharp
public VectorLayer CreateLayer(string path, DriverOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار إلى الملف. |
| الخيارات | DriverOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

مثال من [`VectorLayer`](../../vectorlayer/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المسار هو `null`. |
| ArgumentException | كائن Options له نوع غير صحيح لهذا السائق. |
| [GisException](../../gisexception/) | خطأ في كتابة الميزة إلى الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | السائق لا يمكنه إنشاء طبقات المتجه (انظر [`CanCreateLayers`](../cancreatelayers/)). |

### انظر أيضًا

* class [VectorLayer](../../vectorlayer/)
* class [DriverOptions](../../driveroptions/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath, DriverOptions) {#createlayer_1}

ينشئ الطبقة ويفتحها للإلحاق.

```csharp
public VectorLayer CreateLayer(AbstractPath path, DriverOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | AbstractPath | المسار إلى الملف. |
| الخيارات | DriverOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

مثال من [`VectorLayer`](../../vectorlayer/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المسار هو `null`. |
| ArgumentException | كائن Options له نوع غير صحيح لهذا السائق. |
| [GisException](../../gisexception/) | خطأ في كتابة الميزة إلى الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | السائق لا يمكنه إنشاء طبقات المتجه (انظر [`CanCreateLayers`](../cancreatelayers/)). |

### انظر أيضًا

* class [VectorLayer](../../vectorlayer/)
* class [AbstractPath](../../abstractpath/)
* class [DriverOptions](../../driveroptions/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(string, SpatialReferenceSystem) {#createlayer_7}

ينشئ الطبقة ويفتحها للإلحاق.

```csharp
public VectorLayer CreateLayer(string path, SpatialReferenceSystem spatialReferenceSystem)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار إلى الملف. |
| spatialReferenceSystem | SpatialReferenceSystem | نظام الإحداثيات المكانية. |

### قيمة الإرجاع

مثال من [`VectorLayer`](../../vectorlayer/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المسار هو `null`. |
| [GisException](../../gisexception/) | خطأ في كتابة الميزة إلى الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | نظام الإحداثيات المكانية غير مدعوم من قبل السائق. استخدم [`SupportsSpatialReferenceSystem`](../supportsspatialreferencesystem/) للتحقق مما إذا كان نظام الإحداثيات المكانية مدعومًا. |

### انظر أيضًا

* class [VectorLayer](../../vectorlayer/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath, SpatialReferenceSystem) {#createlayer_3}

ينشئ الطبقة ويفتحها للإلحاق.

```csharp
public VectorLayer CreateLayer(AbstractPath path, SpatialReferenceSystem spatialReferenceSystem)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | AbstractPath | المسار إلى الملف. |
| spatialReferenceSystem | SpatialReferenceSystem | نظام الإحداثيات المكانية. |

### قيمة الإرجاع

مثال من [`VectorLayer`](../../vectorlayer/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المسار هو `null`. |
| [GisException](../../gisexception/) | خطأ في كتابة الميزة إلى الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | نظام الإحداثيات المكانية غير مدعوم من قبل السائق. استخدم [`SupportsSpatialReferenceSystem`](../supportsspatialreferencesystem/) للتحقق مما إذا كان نظام الإحداثيات المكانية مدعومًا. |

### انظر أيضًا

* class [VectorLayer](../../vectorlayer/)
* class [AbstractPath](../../abstractpath/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(string, DriverOptions, SpatialReferenceSystem) {#createlayer_6}

ينشئ الطبقة ويفتحها للإلحاق.

```csharp
public VectorLayer CreateLayer(string path, DriverOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار إلى الملف. |
| الخيارات | DriverOptions | خيارات خاصة بالسائق. |
| spatialReferenceSystem | SpatialReferenceSystem | نظام الإحداثيات المكانية. |

### قيمة الإرجاع

مثال من [`VectorLayer`](../../vectorlayer/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المسار هو `null`. |
| ArgumentException | كائن Options له نوع غير صحيح لهذا السائق. |
| [GisException](../../gisexception/) | خطأ في كتابة الميزة إلى الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | نظام الإحداثيات المكانية غير مدعوم من قبل السائق. استخدم [`SupportsSpatialReferenceSystem`](../supportsspatialreferencesystem/) للتحقق مما إذا كان نظام الإحداثيات المكانية مدعومًا. |
| NotSupportedException | السائق لا يمكنه إنشاء طبقات المتجه (انظر [`CanCreateLayers`](../cancreatelayers/)). |

### انظر أيضًا

* class [VectorLayer](../../vectorlayer/)
* class [DriverOptions](../../driveroptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath, DriverOptions, SpatialReferenceSystem) {#createlayer_2}

ينشئ الطبقة ويفتحها للإلحاق.

```csharp
public abstract VectorLayer CreateLayer(AbstractPath path, DriverOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | AbstractPath | المسار إلى الملف. |
| الخيارات | DriverOptions | خيارات خاصة بالسائق. |
| spatialReferenceSystem | SpatialReferenceSystem | نظام الإحداثيات المكانية. |

### قيمة الإرجاع

مثال من [`VectorLayer`](../../vectorlayer/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المسار هو `null`. |
| ArgumentException | كائن Options له نوع غير صحيح لهذا السائق. |
| [GisException](../../gisexception/) | خطأ في كتابة الميزة إلى الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | نظام الإحداثيات المكانية غير مدعوم من قبل السائق. استخدم [`SupportsSpatialReferenceSystem`](../supportsspatialreferencesystem/) للتحقق مما إذا كان نظام الإحداثيات المكانية مدعومًا. |
| NotSupportedException | السائق لا يمكنه إنشاء طبقات المتجه (انظر [`CanCreateLayers`](../cancreatelayers/)). |

### انظر أيضًا

* class [VectorLayer](../../vectorlayer/)
* class [AbstractPath](../../abstractpath/)
* class [DriverOptions](../../driveroptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)


