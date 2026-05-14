---
title: "FileDriver.EditLayer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة FileDriver. تفتح طبقة للتحرير"
type: docs
weight: 70
url: /ar/net/aspose.gis/filedriver/editlayer/
---
## EditLayer(string, DriverOptions) {#editlayer_1}

يفتح طبقة للتحرير.

```csharp
public VectorLayer EditLayer(string path, DriverOptions options = null)
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

### انظر أيضًا

* class [VectorLayer](../../vectorlayer/)
* class [DriverOptions](../../driveroptions/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## EditLayer(AbstractPath, DriverOptions) {#editlayer}

يفتح طبقة للتحرير.

```csharp
public virtual VectorLayer EditLayer(AbstractPath path, DriverOptions options = null)
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
| NotSupportedException | السائق لا يمكنه تحرير الطبقات. |
| IOException | حدث خطأ في الإدخال/الإخراج. |

## ملاحظات

السائق ينشئ طبقة داخلية تحتوي على جميع العناصر. لكن لدينا خيار استخدام مساحة القرص بدلاً من الذاكرة العشوائية. هناك سائقون لاستخدام أكثر كفاءة للموارد (انظر وثائق السائق المحددة). كما يمكن للسائق تحرير طبقة إذا كان يستطيع إنشاء وفتح الطبقات.

### انظر أيضًا

* class [VectorLayer](../../vectorlayer/)
* class [AbstractPath](../../abstractpath/)
* class [DriverOptions](../../driveroptions/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)


