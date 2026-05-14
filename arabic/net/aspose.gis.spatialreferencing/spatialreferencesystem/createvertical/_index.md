---
title: "SpatialReferenceSystem.CreateVertical"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة SpatialReferenceSystem. إنشاء SRS عمودي"
type: docs
weight: 390
url: /ar/net/aspose.gis.spatialreferencing/spatialreferencesystem/createvertical/
---
## SpatialReferenceSystem.CreateVertical method

إنشاء نظام إسناد عمودي.

```csharp
public static VerticalSpatialReferenceSystem CreateVertical(string name, 
    VerticalDatum verticalDatum, Unit verticalUnit = null, Axis verticalAxis = null, 
    Identifier identifier = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | String | اسم SRS. إذا كان `null`. |
| verticalDatum | VerticalDatum | الـ Datum لاستخدامه في SRS. |
| verticalUnit | Unit | الوحدة لاستخدامها في SRS. إذا كان `null`، سيتم استخدام [`Meter`](../../unit/meter/). |
| verticalAxis | محور | محور باتجاه "أعلى" أو "أسفل"، لاستخدامه في SRS. إذا كان `null`، سيُستخدم محور باتجاه الأعلى. |
| معرّف | معرّف | Identifier، الذي سيُرفق بـ SRS. إرفاق Identifier لن يغيّر معلمات SRS الأخرى. الأمر متروك لك لضمان اتساق Identifier ومعلمات SRS. |

### قيمة الإرجاع

SRS عمودي جديد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | اتجاه *verticalAxis* ليس أعلى أو أسفل. |
| ArgumentNullException | بعض المعلمات المطلوبة قيمتها null. |

### انظر أيضًا

* class [VerticalSpatialReferenceSystem](../../verticalspatialreferencesystem/)
* class [VerticalDatum](../../verticaldatum/)
* class [Unit](../../unit/)
* class [Axis](../../axis/)
* class [Identifier](../../identifier/)
* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


