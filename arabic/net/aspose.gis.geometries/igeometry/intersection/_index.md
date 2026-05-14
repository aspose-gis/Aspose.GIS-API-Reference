---
title: "IGeometry.Intersection"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. تبني تقاطعًا بين هذه الهندسة وهندسة محددة"
type: docs
weight: 260
url: /ar/net/aspose.gis.geometries/igeometry/intersection/
---
## IGeometry.Intersection method

يبني تقاطعًا بين هذه الهندسة وهندسة محددة.

```csharp
public IGeometry Intersection(IGeometry other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | شكل هندسي لحساب التقاطع معه. |

### قيمة الإرجاع

شكل هندسي يمثل تقاطع هذا الشكل الهندسي ومعطى. يحتوي الشكل الهندسي الناتج على مجموعة نقاط موجودة في كل من هذا الشكل الهندسي والمعطى.

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


