---
title: "SpatialReferenceSystemTransformation.Transform"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة SpatialReferenceSystemTransformation. تحول الهندسة من نظام الإحداثيات المصدري إلى نظام الإحداثيات الهدف"
type: docs
weight: 40
url: /ar/net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation/transform/
---
## SpatialReferenceSystemTransformation.Transform method

يحول الهندسة من نظام الإسناد المكاني المصدر إلى نظام الإسناد المكاني الهدف.

```csharp
public Geometry Transform(IGeometry geometry)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| هندسة | IGeometry | الهندسة للتحويل. |

### قيمة الإرجاع

هندسة جديدة في نظام الإحداثيات الهدف.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الهندسة هي `null`. |
| ArgumentException | الهندسات [`SpatialReferenceSystem`](../../../aspose.gis.geometries/igeometry/spatialreferencesystem/) ليست `null` ولا تعادل [`Source`](../source/) |
| [TransformationException](../../transformationexception/) | فشل التحويل. |

### انظر أيضًا

* class [Geometry](../../../aspose.gis.geometries/geometry/)
* interface [IGeometry](../../../aspose.gis.geometries/igeometry/)
* class [SpatialReferenceSystemTransformation](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystemtransformation/)
* assembly [Aspose.GIS](../../../)


