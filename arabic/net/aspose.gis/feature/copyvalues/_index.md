---
title: "Feature.CopyValues"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Feature. تنسخ قيم السمات من عنصر آخر"
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
| inputFeature | Feature | العنصر الذي تُنسخ القيم منه. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | السمة بهذا الاسم غير موجودة في هذه الطبقة. |
| InvalidOperationException | السمة غير مقفلة. |
| InvalidOperationException | القيمة المدخلة هي null ولا يمكن أن تكون السمة في هذا العنصر null. |
| [GisException](../../gisexception/) | الخاصية لها نفس الاسم ولكن أنواع بيانات مختلفة في الميزات. |

## ملاحظات

هذه الطريقة تنسخ فقط الخصائص ذات الأسماء المتطابقة.

### انظر أيضًا

* class [Feature](../)
* namespace [Aspose.Gis](../../feature/)
* assembly [Aspose.GIS](../../../)


