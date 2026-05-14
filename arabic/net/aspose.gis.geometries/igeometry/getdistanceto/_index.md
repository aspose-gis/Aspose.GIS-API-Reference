---
title: "IGeometry.GetDistanceTo"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. تحسب الحد الأدنى للمسافة بين هذا الشكل وشكل محدد"
type: docs
weight: 230
url: /ar/net/aspose.gis.geometries/igeometry/getdistanceto/
---
## IGeometry.GetDistanceTo method

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
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) للأشكال غير متكافئة. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الأشكال إلى نفس نظام الإسناد المكاني. |

### انظر أيضًا

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


