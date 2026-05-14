---
title: "Geometry.Union"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. توحد هذا الشكل مع شكل محدد"
type: docs
weight: 440
url: /ar/net/aspose.gis.geometries/geometry/union/
---
## Geometry.Union method

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
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) الخاص بالهندسات غير متكافئ. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الهندسات إلى نفس نظام الإشارة المكانية. |

### انظر أيضًا

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


