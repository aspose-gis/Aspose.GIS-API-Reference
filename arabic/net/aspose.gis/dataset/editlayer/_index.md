---
title: "Dataset.EditLayer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Dataset. تفتح الطبقة بالاسم المحدد للتحرير"
type: docs
weight: 90
url: /ar/net/aspose.gis/dataset/editlayer/
---
## Dataset.EditLayer method

يفتح الطبقة بالاسم المحدد للتحرير.

```csharp
public abstract VectorLayer EditLayer(string name, DriverOptions options = null, 
    SpatialReferenceSystem spatialReferenceSystem = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | String | اسم الطبقة للتحرير. |
| options | DriverOptions | خيارات الفتح. |
| spatialReferenceSystem | SpatialReferenceSystem | نظام الإحداثيات المكانية للأشكال الهندسية الجديدة. |

### قيمة الإرجاع

تم فتح الطبقة للتحرير.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | الطبقة بالاسم المحدد غير موجودة؛ كائن Options له نوع غير صحيح لهذا مجموعة البيانات. |
| ArgumentException | كائن Options له نوع غير صحيح لهذا مجموعة البيانات. |
| ArgumentNullException | الاسم هو `null`. |
| [GisException](../../gisexception/) | خطأ في قراءة الميزة من الطبقة. |
| IOException | حدث خطأ في الإدخال/الإخراج. |

### انظر أيضًا

* class [VectorLayer](../../vectorlayer/)
* class [DriverOptions](../../driveroptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)


