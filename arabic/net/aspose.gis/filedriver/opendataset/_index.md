---
title: "FileDriver.OpenDataset"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "FileDriver الطريقة. يفتح مجموعة البيانات"
type: docs
weight: 80
url: /ar/net/aspose.gis/filedriver/opendataset/
---
## OpenDataset(string) {#opendataset_2}

يفتح مجموعة البيانات.

```csharp
public Dataset OpenDataset(string path)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | String | مسار مجموعة البيانات. |

### قيمة الإرجاع

كائن من [`Dataset`](../../dataset/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المسار هو `null`. |
| [GisException](../../gisexception/) | خطأ في قراءة مجموعة البيانات. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | السائق لا يمكنه فتح مجموعات البيانات (انظر [`CanOpenDatasets`](../canopendatasets/)). |

### انظر أيضًا

* class [Dataset](../../dataset/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## OpenDataset(AbstractPath) {#opendataset}

يفتح مجموعة البيانات.

```csharp
public Dataset OpenDataset(AbstractPath path)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | AbstractPath | مسار مجموعة البيانات. |

### قيمة الإرجاع

كائن من [`Dataset`](../../dataset/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المسار هو `null`. |
| [GisException](../../gisexception/) | خطأ في قراءة مجموعة البيانات. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | السائق لا يمكنه فتح مجموعات البيانات (انظر [`CanOpenDatasets`](../canopendatasets/)). |

### انظر أيضًا

* class [Dataset](../../dataset/)
* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## OpenDataset(string, DriverOptions) {#opendataset_3}

يفتح مجموعة البيانات.

```csharp
public Dataset OpenDataset(string path, DriverOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | String | مسار مجموعة البيانات. |
| options | DriverOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

كائن من [`Dataset`](../../dataset/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | كائن Options له نوع غير صحيح لهذا السائق. |
| ArgumentNullException | المسار هو `null`. |
| [GisException](../../gisexception/) | خطأ في قراءة مجموعة البيانات. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | السائق لا يمكنه فتح مجموعات البيانات (انظر [`CanOpenDatasets`](../canopendatasets/)). |

### انظر أيضًا

* class [Dataset](../../dataset/)
* class [DriverOptions](../../driveroptions/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## OpenDataset(AbstractPath, DriverOptions) {#opendataset_1}

يفتح مجموعة البيانات.

```csharp
public virtual Dataset OpenDataset(AbstractPath path, DriverOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | AbstractPath | مسار مجموعة البيانات. |
| options | DriverOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

كائن من [`Dataset`](../../dataset/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | كائن Options له نوع غير صحيح لهذا السائق. |
| ArgumentNullException | المسار هو `null`. |
| [GisException](../../gisexception/) | خطأ في قراءة مجموعة البيانات. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | السائق لا يمكنه فتح مجموعات البيانات (انظر [`CanOpenDatasets`](../canopendatasets/)). |

### انظر أيضًا

* class [Dataset](../../dataset/)
* class [AbstractPath](../../abstractpath/)
* class [DriverOptions](../../driveroptions/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)


