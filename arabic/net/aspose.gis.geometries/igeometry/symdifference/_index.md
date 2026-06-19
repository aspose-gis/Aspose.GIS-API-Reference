---
title: "IGeometry.SymDifference"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. تُنشئ فرقًا متماثلًا بين هذه الهندسة وهندسة محددة"
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
| آخر | IGeometry | شكل هندسي لحساب الفرق المتماثل معه. |

### قيمة الإرجاع

شكل هندسي يمثل فرقًا متماثلًا بين هذا الشكل الهندسي ومعامل. يحتوي الشكل الهندسي الناتج على مجموعة نقاط موجودة في أحد الشكلين ولكن ليست موجودة في كليهما.

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


