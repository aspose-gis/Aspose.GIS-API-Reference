---
title: "FileDriver.OpenLayer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة FileDriver. تفتح الطبقة للقراءة"
type: docs
weight: 90
url: /ar/net/aspose.gis/filedriver/openlayer/
---
## OpenLayer(string) {#openlayer_2}

يفتح الطبقة للقراءة.

```csharp
public VectorLayer OpenLayer(string path)
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
| [GisException](../../gisexception/) | خطأ في قراءة العنصر من الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | السائق لا يمكنه فتح طبقات المتجهات (انظر [`CanOpenLayers`](../canopenlayers/)). |

### انظر أيضًا

* class [VectorLayer](../../vectorlayer/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## OpenLayer(AbstractPath) {#openlayer}

يفتح الطبقة للقراءة.

```csharp
public VectorLayer OpenLayer(AbstractPath path)
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
| [GisException](../../gisexception/) | خطأ في قراءة العنصر من الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | السائق لا يمكنه فتح طبقات المتجهات (انظر [`CanOpenLayers`](../canopenlayers/)). |

### انظر أيضًا

* class [VectorLayer](../../vectorlayer/)
* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## OpenLayer(string, DriverOptions) {#openlayer_3}

يفتح الطبقة للقراءة.

```csharp
public VectorLayer OpenLayer(string path, DriverOptions options)
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
| ArgumentException | كائن Options له نوع غير صحيح لهذا السائق. |
| ArgumentNullException | المسار هو `null`. |
| [GisException](../../gisexception/) | خطأ في قراءة العنصر من الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | السائق لا يمكنه فتح طبقات المتجهات (انظر [`CanOpenLayers`](../canopenlayers/)). |

### انظر أيضًا

* class [VectorLayer](../../vectorlayer/)
* class [DriverOptions](../../driveroptions/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## OpenLayer(AbstractPath, DriverOptions) {#openlayer_1}

يفتح الطبقة للقراءة.

```csharp
public abstract VectorLayer OpenLayer(AbstractPath path, DriverOptions options)
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
| ArgumentException | كائن Options له نوع غير صحيح لهذا السائق. |
| ArgumentNullException | المسار هو `null`. |
| [GisException](../../gisexception/) | خطأ في قراءة العنصر من الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | السائق لا يمكنه فتح طبقات المتجهات (انظر [`CanOpenLayers`](../canopenlayers/)). |

### انظر أيضًا

* class [VectorLayer](../../vectorlayer/)
* class [AbstractPath](../../abstractpath/)
* class [DriverOptions](../../driveroptions/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)


