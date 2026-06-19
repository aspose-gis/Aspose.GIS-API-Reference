---
title: "Geometry.Union"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. توحد هذا الشكل الهندسي وشكل هندسي محدد"
type: docs
weight: 440
url: /ar/net/aspose.gis.geometries/geometry/union/
---
## Geometry.Union method

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
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) للهندسات غير متكافئة. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الهندسات إلى نفس نظام الإسناد المكاني. |

### انظر أيضًا

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


