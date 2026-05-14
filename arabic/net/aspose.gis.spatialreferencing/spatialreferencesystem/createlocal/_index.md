---
title: "SpatialReferenceSystem.CreateLocal"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة SpatialReferenceSystem. إنشاء نظام إحداثيات محلي."
type: docs
weight: 370
url: /ar/net/aspose.gis.spatialreferencing/spatialreferencesystem/createlocal/
---
## SpatialReferenceSystem.CreateLocal method

إنشاء نظام إسناد مكاني محلي.

```csharp
public static LocalSpatialReferenceSystem CreateLocal(string name, LocalDatum datum, Unit unit, 
    ICollection<Axis> axises, Identifier identifier = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | String | اسم نظام الإسناد المكاني. |
| نقطة إسناد | نقطة إسناد محلية | الـ Datum لاستخدامه في SRS. |
| وحدة | وحدة | الوحدة المستخدمة في نظام الإسناد المكاني. |
| محاور | ICollection`1 | المحاور المستخدمة في نظام الإسناد المكاني. يجب ألا تكون فارغة |
| معرّف | معرّف | Identifier، الذي سيُرفق بـ SRS. إرفاق Identifier لن يغيّر معلمات SRS الأخرى. الأمر متروك لك لضمان اتساق Identifier ومعلمات SRS. |

### قيمة الإرجاع

نظام إسناد مكاني محلي جديد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | يجب أن يكون هناك محور واحد على الأقل. |
| InvalidOperationException | *محاور* فارغة. |
| ArgumentNullException | أي وسيط، باستثناء *identifier* هو null. |

### انظر أيضًا

* class [LocalSpatialReferenceSystem](../../localspatialreferencesystem/)
* class [LocalDatum](../../localdatum/)
* class [Unit](../../unit/)
* class [Axis](../../axis/)
* class [Identifier](../../identifier/)
* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


