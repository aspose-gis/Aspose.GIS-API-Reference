---
title: "Extent.GetTransformed"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Extent. تُرجع نطاقًا جديدًا في نظام الإسناد المكاني المحدد الذي يحتوي على هذا النطاق"
type: docs
weight: 150
url: /ar/net/aspose.gis/extent/gettransformed/
---
## Extent.GetTransformed method

تُرجع نطاقًا جديدًا في [`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem/) المحدد الذي يحتوي على هذا النطاق.

```csharp
public Extent GetTransformed(SpatialReferenceSystem targetSrs)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| targetSrs | SpatialReferenceSystem | [`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem/) للتحويل إليه. |

### قيمة الإرجاع

نتيجة تحويل هذا النطاق إلى نظام الإسناد المكاني (SRS) المحدد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| NotSupportedException | التحويل إلى نظام الإسناد المكاني (SRS) المقدم غير مدعوم. |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception/) | فشل التحويل. |
| InvalidOperationException | [`SpatialReferenceSystem`](../spatialreferencesystem/) لهذا النطاق هو `null`. |

### انظر أيضًا

* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [Extent](../)
* namespace [Aspose.Gis](../../extent/)
* assembly [Aspose.GIS](../../../)


