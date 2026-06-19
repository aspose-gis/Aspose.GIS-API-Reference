---
title: "Geometry.Intersection"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. تبني تقاطعاً بين هذا الشكل الهندسي وشكل هندسي محدد."
type: docs
weight: 270
url: /ar/net/aspose.gis.geometries/geometry/intersection/
---
## Geometry.Intersection method

يبني تقاطعًا بين هذه الهندسة وهندسة محددة.

```csharp
public IGeometry Intersection(IGeometry other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | شكل هندسي لحساب التقاطع معه. |

### قيمة الإرجاع

شكل هندسي يمثل تقاطع هذا الشكل الهندسي ومعطى. يحتوي الشكل الناتج على مجموعة نقاط موجودة في كل من هذا الشكل الهندسي والمعطى.

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


