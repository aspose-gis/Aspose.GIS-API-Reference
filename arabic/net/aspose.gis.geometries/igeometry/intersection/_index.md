---
title: "IGeometry.Intersection"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. تُنشئ تقاطعًا بين هذا الشكل الهندسي وشكل هندسي محدد"
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

شكل هندسي يمثل تقاطع هذا الشكل الهندسي ومعطى. يحتوي الشكل الناتج على مجموعة نقاط موجودة في كل من هذا الشكل الهندسي والمعطى.

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


