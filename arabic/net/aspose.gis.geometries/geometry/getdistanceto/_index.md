---
title: "Geometry.GetDistanceTo"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. تحسب الحد الأدنى للمسافة بين هذا الشكل الهندسي وشكل هندسي محدد"
type: docs
weight: 240
url: /ar/net/aspose.gis.geometries/geometry/getdistanceto/
---
## Geometry.GetDistanceTo method

يحسب الحد الأدنى للمسافة بين هذه الهندسة وهندسة محددة.

```csharp
public double GetDistanceTo(IGeometry other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | شكل هندسي لإيجاد المسافة إليه. |

### قيمة الإرجاع

إذا لم يكن كلا الشكلين الهندسيين [`IsEmpty`](../isempty/) - تكون المسافة بين أقرب نقطتين من الشكلين. إذا كان أحد الشكلين على الأقل فارغًا يتم إرجاع -1.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) الخاص بالهندسات غير متكافئ. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الهندسات إلى نفس نظام الإشارة المكانية. |

### انظر أيضًا

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


