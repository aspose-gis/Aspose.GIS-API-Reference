---
title: "IGeometry.SpatiallyContains"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. تحدد ما إذا كان هذا الشكل الهندسي يحتوي مكانيًا على شكل هندسي محدد"
type: docs
weight: 310
url: /ar/net/aspose.gis.geometries/igeometry/spatiallycontains/
---
## IGeometry.SpatiallyContains method

يحدد ما إذا كانت هذه الهندسة تحتوي مكانيًا على هندسة محددة.

```csharp
public bool SpatiallyContains(IGeometry other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | هندسة. |

### قيمة الإرجاع

`true` إذا كان هذا الشكل الهندسي "يحتوي مكانيًا" على شكل هندسي آخر. `false` غير ذلك.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | إحدى الهندسات غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) للهندسات غير متكافئة. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الهندسات إلى نظام إسناد مكاني موحد. |

## ملاحظات

تختبر هذه الطريقة ما إذا كان شكل هندسي يحتوي على آخر وفقًا لمصفوفة تقاطع DE-9IM. هذه الطريقة تعادل:

```csharp
other.Within(this);
```

### انظر أيضًا

* method [Within](../within/)
* method [Covers](../covers/)
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


