---
title: "IGeometry.Union"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. توحّد هذه الهندسة مع هندسة محددة"
type: docs
weight: 370
url: /ar/net/aspose.gis.geometries/igeometry/union/
---
## IGeometry.Union method

يوحد هذه الهندسة وهندسة محددة.

```csharp
public IGeometry Union(IGeometry other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | شكل هندسي للاتحاد معه. |

### قيمة الإرجاع

شكل هندسي يمثل اتحاد هذا الشكل الهندسي ومعامل. يحتوي الشكل الهندسي الناتج على مجموعة نقاط موجودة في هذا الشكل الهندسي أو في المعامل.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *other* هو `null`. |
| ArgumentException | إحدى الهندسات غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) للهندسات غير متكافئة. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الهندسات إلى نظام إسناد مكاني موحد. |

### انظر أيضًا

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


