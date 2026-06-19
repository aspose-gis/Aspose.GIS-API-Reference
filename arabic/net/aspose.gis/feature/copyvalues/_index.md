---
title: "Feature.CopyValues"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Feature. تنسخ قيم السمات من ميزة أخرى."
type: docs
weight: 20
url: /ar/net/aspose.gis/feature/copyvalues/
---
## Feature.CopyValues method

ينسخ قيم السمات من ميزة أخرى.

```csharp
public void CopyValues(Feature inputFeature)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| inputFeature | Feature | الميزة التي تُنسخ القيم منها. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | السمة بهذا الاسم غير موجودة في هذه الطبقة. |
| InvalidOperationException | السمة غير مقفلة. |
| InvalidOperationException | قيمة الإدخال هي null ولا يمكن أن تكون السمة في هذه الميزة null. |
| [GisException](../../gisexception/) | الخاصية لها نفس الاسم ولكن أنواع بيانات مختلفة في المميزات. |

## ملاحظات

هذه الطريقة تنسخ فقط الخصائص التي لها أسماء مطابقة.

### انظر أيضًا

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)


