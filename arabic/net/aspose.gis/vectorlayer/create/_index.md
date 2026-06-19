---
title: "VectorLayer.Create"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة VectorLayer. ينشئ الطبقة ويفتحها لإضافة ميزات جديدة."
type: docs
weight: 10
url: /ar/net/aspose.gis/vectorlayer/create/
---
## Create(string, FileDriver) {#create_4}

ينشئ الطبقة ويفتحها لإضافة ميزات جديدة.

```csharp
public static VectorLayer Create(string path, FileDriver driver)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | String | المسار إلى الملف. |
| المحرك | FileDriver | Driver للاستخدام. |

### قيمة الإرجاع

طبقة للكتابة فقط.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المسار هو `null`. |
| ArgumentException | كائن Options له نوع غير صحيح لهذا السائق. |
| [GisException](../../gisexception/) | خطأ في كتابة الميزة إلى الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |

### انظر أيضًا

* class [FileDriver](../../filedriver/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Create(string, FileDriver, DriverOptions) {#create_5}

ينشئ الطبقة ويفتحها لإضافة ميزات جديدة.

```csharp
public static VectorLayer Create(string path, FileDriver driver, DriverOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | String | المسار إلى الملف. |
| المحرك | FileDriver | Driver للاستخدام. |
| options | DriverOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

طبقة للكتابة فقط.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المسار هو `null`. |
| ArgumentException | كائن Options له نوع غير صحيح لهذا السائق. |
| [GisException](../../gisexception/) | خطأ في كتابة الميزة إلى الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |

### انظر أيضًا

* class [FileDriver](../../filedriver/)
* class [DriverOptions](../../driveroptions/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Create(AbstractPath, FileDriver) {#create}

ينشئ الطبقة ويفتحها لإضافة ميزات جديدة.

```csharp
public static VectorLayer Create(AbstractPath path, FileDriver driver)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | AbstractPath | المسار إلى الملف. |
| المحرك | FileDriver | Driver للاستخدام. |

### قيمة الإرجاع

طبقة للكتابة فقط.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المسار هو `null`. |
| ArgumentException | كائن Options له نوع غير صحيح لهذا السائق. |
| [GisException](../../gisexception/) | خطأ في كتابة الميزة إلى الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |

### انظر أيضًا

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Create(AbstractPath, FileDriver, DriverOptions) {#create_1}

ينشئ الطبقة ويفتحها لإضافة ميزات جديدة.

```csharp
public static VectorLayer Create(AbstractPath path, FileDriver driver, DriverOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | AbstractPath | المسار إلى الملف. |
| المحرك | FileDriver | Driver للاستخدام. |
| options | DriverOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

طبقة للكتابة فقط.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المسار هو `null`. |
| ArgumentException | كائن Options له نوع غير صحيح لهذا السائق. |
| [GisException](../../gisexception/) | خطأ في كتابة الميزة إلى الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |

### انظر أيضًا

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [DriverOptions](../../driveroptions/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Create(string, FileDriver, SpatialReferenceSystem) {#create_7}

ينشئ الطبقة ويفتحها للإلحاق.

```csharp
public static VectorLayer Create(string path, FileDriver driver, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | String | المسار إلى الملف. |
| المحرك | FileDriver | Driver للاستخدام. |
| spatialReferenceSystem | SpatialReferenceSystem | نظام الإسناد المكاني. |

### قيمة الإرجاع

كائن من [`VectorLayer`](../).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المسار هو `null`. |
| [GisException](../../gisexception/) | خطأ في قراءة أو كتابة الميزة من/إلى الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | نظام الإحداثيات المكانية غير مدعوم من قبل السائق. استخدم [`SupportsSpatialReferenceSystem`](../../filedriver/supportsspatialreferencesystem/) للتحقق مما إذا كان نظام الإحداثيات المكانية مدعومًا. |

### انظر أيضًا

* class [FileDriver](../../filedriver/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Create(AbstractPath, FileDriver, SpatialReferenceSystem) {#create_3}

ينشئ الطبقة ويفتحها للإلحاق.

```csharp
public static VectorLayer Create(AbstractPath path, FileDriver driver, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | AbstractPath | المسار إلى الملف. |
| المحرك | FileDriver | Driver للاستخدام. |
| spatialReferenceSystem | SpatialReferenceSystem | نظام الإسناد المكاني. |

### قيمة الإرجاع

كائن من [`VectorLayer`](../).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المسار هو `null`. |
| [GisException](../../gisexception/) | خطأ في قراءة أو كتابة الميزة من/إلى الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | نظام الإحداثيات المكانية غير مدعوم من قبل السائق. استخدم [`SupportsSpatialReferenceSystem`](../../filedriver/supportsspatialreferencesystem/) للتحقق مما إذا كان نظام الإحداثيات المكانية مدعومًا. |

### انظر أيضًا

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Create(string, FileDriver, DriverOptions, SpatialReferenceSystem) {#create_6}

ينشئ الطبقة ويفتحها للإلحاق.

```csharp
public static VectorLayer Create(string path, FileDriver driver, DriverOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | String | المسار إلى الملف. |
| المحرك | FileDriver | Driver للاستخدام. |
| options | DriverOptions | خيارات خاصة بالسائق. |
| spatialReferenceSystem | SpatialReferenceSystem | نظام الإسناد المكاني. |

### قيمة الإرجاع

كائن من [`VectorLayer`](../).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المسار هو `null`. |
| ArgumentException | كائن Options له نوع غير صحيح لهذا السائق. |
| [GisException](../../gisexception/) | خطأ في قراءة أو كتابة الميزة من/إلى الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | نظام الإحداثيات المكانية غير مدعوم من قبل السائق. استخدم [`SupportsSpatialReferenceSystem`](../../filedriver/supportsspatialreferencesystem/) للتحقق مما إذا كان نظام الإحداثيات المكانية مدعومًا. |

### انظر أيضًا

* class [FileDriver](../../filedriver/)
* class [DriverOptions](../../driveroptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Create(AbstractPath, FileDriver, DriverOptions, SpatialReferenceSystem) {#create_2}

ينشئ الطبقة ويفتحها للإلحاق.

```csharp
public static VectorLayer Create(AbstractPath path, FileDriver driver, DriverOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | AbstractPath | المسار إلى الملف. |
| المحرك | FileDriver | Driver للاستخدام. |
| options | DriverOptions | خيارات خاصة بالسائق. |
| spatialReferenceSystem | SpatialReferenceSystem | نظام الإسناد المكاني. |

### قيمة الإرجاع

كائن من [`VectorLayer`](../).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المسار هو `null`. |
| ArgumentException | كائن Options له نوع غير صحيح لهذا السائق. |
| [GisException](../../gisexception/) | خطأ في قراءة أو كتابة الميزة من/إلى الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | نظام الإحداثيات المكانية غير مدعوم من قبل السائق. استخدم [`SupportsSpatialReferenceSystem`](../../filedriver/supportsspatialreferencesystem/) للتحقق مما إذا كان نظام الإحداثيات المكانية مدعومًا. |

### انظر أيضًا

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [DriverOptions](../../driveroptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)


