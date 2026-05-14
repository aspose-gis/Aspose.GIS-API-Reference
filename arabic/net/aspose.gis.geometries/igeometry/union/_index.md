---
title: "IGeometry.Union"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. يوحد هذا الشكل مع شكل محدد"
type: docs
weight: 370
url: /ar/net/aspose.gis.geometries/igeometry/union/
---
## IGeometry.Union method

يوحد هذا الشكل وشكلًا محددًا.

```csharp
public IGeometry Union(IGeometry other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | شكل للاتحاد معه. |

### قيمة الإرجاع

شكل يمثل اتحاد هذا الشكل مع وسيط. يحتوي الشكل الناتج على مجموعة نقاط موجودة في هذا الشكل أو في الوسيط.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *other* هو `null`. |
| ArgumentException | إحدى الهندسات غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) للأشكال غير متكافئة. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الأشكال إلى نفس نظام الإسناد المكاني. |

### انظر أيضًا

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


