---
title: "Dataset.OpenLayer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Dataset. تفتح الطبقة بالاسم المحدد للقراءة"
type: docs
weight: 130
url: /ar/net/aspose.gis/dataset/openlayer/
---
## Dataset.OpenLayer method

يفتح الطبقة بالاسم المحدد للقراءة.

```csharp
public abstract VectorLayer OpenLayer(string name, DriverOptions options = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | String | اسم الطبقة للفتح. |
| الخيارات | DriverOptions | خيارات الفتح. |

### قيمة الإرجاع

تم فتح الطبقة للقراءة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | الطبقة بالاسم المحدد غير موجودة؛ كائن Options له نوع غير صحيح لهذه مجموعة البيانات. |
| ArgumentException | كائن Options له نوع غير صحيح لهذه مجموعة البيانات. |
| ArgumentNullException | الاسم هو `null`. |
| [GisException](../../gisexception/) | خطأ في قراءة العنصر من الطبقة. |
| IOException | حدث خطأ في الإدخال/الإخراج. |

### انظر أيضًا

* class [VectorLayer](../../vectorlayer/)
* class [DriverOptions](../../driveroptions/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)


