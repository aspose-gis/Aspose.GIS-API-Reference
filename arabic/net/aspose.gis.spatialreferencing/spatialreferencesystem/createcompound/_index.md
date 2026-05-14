---
title: "SpatialReferenceSystem.CreateCompound"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة SpatialReferenceSystem. إنشاء نظام إسناد مركب"
type: docs
weight: 340
url: /ar/net/aspose.gis.spatialreferencing/spatialreferencesystem/createcompound/
---
## SpatialReferenceSystem.CreateCompound method

إنشاء نظام إسناد مركب.

```csharp
public static CompoundSpatialReferenceSystem CreateCompound(string name, 
    SpatialReferenceSystem head, SpatialReferenceSystem tail, Identifier identifier = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | String | اسم نظام الإسناد المكاني الجديد. |
| الرأس | SpatialReferenceSystem | نظام الإسناد المكاني الرأس لنظام الإسناد المكاني الجديد. |
| الذيل | SpatialReferenceSystem | نظام الإسناد المكاني الذيل لنظام الإسناد المكاني الجديد. |
| معرّف | معرّف | Identifier، الذي سيُرفق بـ SRS. إرفاق Identifier لن يغيّر معلمات SRS الأخرى. الأمر متروك لك لضمان اتساق Identifier ومعلمات SRS. |

### قيمة الإرجاع

نظام إسناد مركب جديد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | أي وسيط باستثناء *identifier* هو `null`. |
| InvalidOperationException | *head* أو *tail* هي أنظمة إحداثيات مركبة بحد ذاتها. |

### انظر أيضًا

* class [CompoundSpatialReferenceSystem](../../compoundspatialreferencesystem/)
* class [Identifier](../../identifier/)
* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


