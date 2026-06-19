---
title: "IGeometry.CoveredBy"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. تحدد ما إذا كانت هذه الهندسة مغطاة بواسطة هندسة محددة"
type: docs
weight: 140
url: /ar/net/aspose.gis.geometries/igeometry/coveredby/
---
## IGeometry.CoveredBy method

يحدد ما إذا كانت هذه الـ geometry مغطاة بواسطة هندسة محددة.

```csharp
public bool CoveredBy(IGeometry other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | هندسة. |

### قيمة الإرجاع

`true` إذا كان هذا الشكل الهندسي "مغطى مكانيًا" بواسطة شكل هندسي آخر. `false` خلاف ذلك.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | إحدى الهندسات غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) للهندسات غير متكافئة. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الهندسات إلى نظام إسناد مكاني موحد. |

## ملاحظات

تختبر هذه الطريقة ما إذا كان شكل هندسي مغطى بآخر وفقًا لمصفوفة تقاطع DE-9IM. هذه الطريقة مكافئة لـ:

```csharp
other.Covers(this);
```

### انظر أيضًا

* method [SpatiallyContains](../spatiallycontains/)
* method [Covers](../covers/)
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


