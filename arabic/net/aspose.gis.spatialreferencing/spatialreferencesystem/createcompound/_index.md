---
title: "SpatialReferenceSystem.CreateCompound"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة SpatialReferenceSystem. إنشاء نظام إسناد مكاني مركب"
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
| head | SpatialReferenceSystem | نظام الإسناد المكاني الرئيسي للنظام الجديد. |
| tail | SpatialReferenceSystem | نظام الإسناد المكاني الفرعي للنظام الجديد. |
| معرّف | معرّف | المعرّف الذي سيُرفق بـ SRS. إرفاق معرّف لن يغيّر معلمات SRS الأخرى. الأمر متروك لك لضمان اتساق المعرف ومعلمات SRS. |

### قيمة الإرجاع

نظام إسناد مكاني مركب جديد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | أي وسيط باستثناء *identifier* هو `null`. |
| InvalidOperationException | *head* أو *tail* هما نظام إسناد مكاني مركب بحد ذاتهما. |

### انظر أيضًا

* class [CompoundSpatialReferenceSystem](../../compoundspatialreferencesystem/)
* class [Identifier](../../identifier/)
* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


