---
title: "Geometry.SymDifference"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. تبني فرقًا متماثلًا بين هذا الشكل الهندسي وشكل هندسي محدد"
type: docs
weight: 380
url: /ar/net/aspose.gis.geometries/geometry/symdifference/
---
## Geometry.SymDifference method

يبني فرقًا متماثلًا بين هذه الهندسة وهندسة محددة.

```csharp
public IGeometry SymDifference(IGeometry other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | شكل هندسي لحساب الفرق المتماثل معه. |

### قيمة الإرجاع

شكل هندسي يمثل فرقًا متماثلًا بين هذا الشكل الهندسي ومعامل. يحتوي الشكل الهندسي الناتج على مجموعة نقاط موجودة في أحد الشكلين ولكن ليست موجودة في كليهما.

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


