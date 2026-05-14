---
title: "Geometry.Difference"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. تطرح شكلًا هندسيًا محددًا من هذا الشكل الهندسي"
type: docs
weight: 180
url: /ar/net/aspose.gis.geometries/geometry/difference/
---
## Geometry.Difference method

يطرح هندسة محددة من هذه الهندسة.

```csharp
public IGeometry Difference(IGeometry other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | شكل هندسي للطرح. |

### قيمة الإرجاع

شكل هندسي يمثل الفرق بين هذا الشكل الهندسي ومعامل. يحتوي الشكل الهندسي الناتج على مجموعة نقاط موجودة في هذا الشكل الهندسي ولكن غير موجودة في المعامل.

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


