---
title: "Geometry.CoveredBy"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. تحدد ما إذا كان هذا الشكل مغطىً بواسطة شكل محدد"
type: docs
weight: 150
url: /ar/net/aspose.gis.geometries/geometry/coveredby/
---
## Geometry.CoveredBy method

يحدد ما إذا كانت هذه الهندسة مغطاة بواسطة هندسة محددة.

```csharp
public bool CoveredBy(IGeometry other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | هندسة. |

### قيمة الإرجاع

`true` إذا كان هذا الشكل "مغطى مكانيًا" بواسطة شكل آخر. `false` خلاف ذلك.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | إحدى الهندسات غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) الخاص بالهندسات غير متكافئ. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الهندسات إلى نفس نظام الإشارة المكانية. |

## ملاحظات

تختبر هذه الطريقة ما إذا كان شكل ما مغطىً بآخر وفقًا لمصفوفة تقاطع DE-9IM. هذه الطريقة مكافئة لـ:

```csharp
other.Covers(this);
```

### انظر أيضًا

* method [SpatiallyContains](../../igeometry/spatiallycontains/)
* method [Covers](../../igeometry/covers/)
* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


