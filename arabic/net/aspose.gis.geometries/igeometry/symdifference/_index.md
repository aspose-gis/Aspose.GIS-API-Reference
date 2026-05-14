---
title: "IGeometry.SymDifference"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "IGeometry طريقة. يبني فرقًا متماثلًا بين هذه الهندسة وهندسة محددة"
type: docs
weight: 330
url: /ar/net/aspose.gis.geometries/igeometry/symdifference/
---
## IGeometry.SymDifference method

يبني فرقًا متماثلًا بين هذه الهندسة وهندسة محددة.

```csharp
public IGeometry SymDifference(IGeometry other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | شكل لحساب الفرق المتماثل معه. |

### قيمة الإرجاع

شكل يمثل فرقًا متماثلًا بين هذا الشكل ووسيط. يحتوي الشكل الناتج على مجموعة نقاط موجودة في أحد الشكلين ولكن ليست موجودة في كليهما.

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


