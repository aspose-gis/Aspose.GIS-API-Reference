---
title: "SpatialReferenceSystemTransformation.Transform"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة SpatialReferenceSystemTransformation. تحول الشكل الهندسي من نظام الإسناد المكاني المصدر إلى نظام الإسناد المكاني الهدف"
type: docs
weight: 40
url: /ar/net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation/transform/
---
## SpatialReferenceSystemTransformation.Transform method

يحول الشكل الهندسي من نظام الإسناد المكاني المصدر إلى نظام الإسناد المكاني الهدف.

```csharp
public Geometry Transform(IGeometry geometry)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| هندسة | IGeometry | الشكل الهندسي للتحويل. |

### قيمة الإرجاع

شكل هندسي جديد في نظام الإسناد المكاني الهدف.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الشكل الهندسي هو `null`. |
| ArgumentException | الأشكال الهندسية [`SpatialReferenceSystem`](../../../aspose.gis.geometries/igeometry/spatialreferencesystem/) ليست `null` ولا تعادل [`Source`](../source/) |
| [TransformationException](../../transformationexception/) | فشل التحويل. |

### انظر أيضًا

* class [Geometry](../../../aspose.gis.geometries/geometry/)
* interface [IGeometry](../../../aspose.gis.geometries/igeometry/)
* class [SpatialReferenceSystemTransformation](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystemtransformation/)
* assembly [Aspose.GIS](../../../)


