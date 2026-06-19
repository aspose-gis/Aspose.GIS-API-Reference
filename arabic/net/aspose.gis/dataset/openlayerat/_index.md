---
title: "Dataset.OpenLayerAt"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Dataset. تفتح الطبقة في الفهرس المحدد للقراءة"
type: docs
weight: 140
url: /ar/net/aspose.gis/dataset/openlayerat/
---
## Dataset.OpenLayerAt method

يفتح الطبقة في الفهرس المحدد للقراءة.

```csharp
public abstract VectorLayer OpenLayerAt(int index, DriverOptions options = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| فهرس | Int32 | فهرس الطبقة للفتح. |
| options | DriverOptions | خيارات الفتح. |

### قيمة الإرجاع

تم فتح الطبقة للقراءة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | كائن Options له نوع غير صحيح لهذا مجموعة البيانات. |
| ArgumentOutOfRangeException | الفهرس خارج النطاق |
| ArgumentException | كائن Options له نوع غير صحيح لهذا مجموعة البيانات. |
| [GisException](../../gisexception/) | خطأ في قراءة الميزة من الطبقة. |
| IOException | حدث خطأ في الإدخال/الإخراج. |

### انظر أيضًا

* class [VectorLayer](../../vectorlayer/)
* class [DriverOptions](../../driveroptions/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)


