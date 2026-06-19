---
title: "FileDriver.CreateDataset"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة FileDriver. تنشئ مجموعة بيانات"
type: docs
weight: 50
url: /ar/net/aspose.gis/filedriver/createdataset/
---
## CreateDataset(string) {#createdataset_2}

ينشئ مجموعة بيانات.

```csharp
public Dataset CreateDataset(string path)
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
| [GisException](../../gisexception/) | خطأ في إنشاء مجموعة البيانات. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | السائق لا يمكنه فتح مجموعات البيانات (انظر [`CanOpenDatasets`](../canopendatasets/)). |
| InvalidOperationException | مجموعة البيانات موجودة بالفعل. |

### انظر أيضًا

* class [Dataset](../../dataset/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateDataset(AbstractPath) {#createdataset}

ينشئ مجموعة بيانات.

```csharp
public Dataset CreateDataset(AbstractPath path)
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
| [GisException](../../gisexception/) | خطأ في إنشاء مجموعة البيانات. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | السائق لا يمكنه فتح مجموعات البيانات (انظر [`CanOpenDatasets`](../canopendatasets/)). |
| InvalidOperationException | مجموعة البيانات موجودة بالفعل. |

### انظر أيضًا

* class [Dataset](../../dataset/)
* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateDataset(string, DriverOptions) {#createdataset_3}

ينشئ مجموعة بيانات.

```csharp
public Dataset CreateDataset(string path, DriverOptions options)
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
| [GisException](../../gisexception/) | خطأ في إنشاء مجموعة البيانات. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | السائق لا يمكنه فتح مجموعات البيانات (انظر [`CanOpenDatasets`](../canopendatasets/)). |
| InvalidOperationException | مجموعة البيانات موجودة بالفعل. |

### انظر أيضًا

* class [Dataset](../../dataset/)
* class [DriverOptions](../../driveroptions/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateDataset(AbstractPath, DriverOptions) {#createdataset_1}

ينشئ مجموعة بيانات.

```csharp
public virtual Dataset CreateDataset(AbstractPath path, DriverOptions options)
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
| [GisException](../../gisexception/) | خطأ في إنشاء مجموعة البيانات. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | السائق لا يمكنه فتح مجموعات البيانات (انظر [`CanOpenDatasets`](../canopendatasets/)). |
| InvalidOperationException | مجموعة البيانات موجودة بالفعل. |

### انظر أيضًا

* class [Dataset](../../dataset/)
* class [AbstractPath](../../abstractpath/)
* class [DriverOptions](../../driveroptions/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)


