---
title: "Dataset.EditLayerAt"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Dataset. تفتح الطبقة بالاسم المحدد للتحرير"
type: docs
weight: 100
url: /ar/net/aspose.gis/dataset/editlayerat/
---
## Dataset.EditLayerAt method

يفتح الطبقة بالاسم المحدد للتحرير.

```csharp
public abstract VectorLayer EditLayerAt(int index, DriverOptions options = null, 
    SpatialReferenceSystem spatialReferenceSystem = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الفهرس | Int32 | فهرس الطبقة التي سيتم تعديلها. |
| الخيارات | DriverOptions | خيارات الفتح. |
| spatialReferenceSystem | SpatialReferenceSystem | نظام الإحداثيات المكانية للأشكال الجديدة. |

### قيمة الإرجاع

تم فتح الطبقة للتحرير.

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
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)


