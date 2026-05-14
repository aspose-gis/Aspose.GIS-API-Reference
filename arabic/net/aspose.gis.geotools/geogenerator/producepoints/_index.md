---
title: "GeoGenerator.ProducePoints"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة GeoGenerator. تنشئ مصفوفة من النقاط التابعة للمنطقة المحددة"
type: docs
weight: 20
url: /ar/net/aspose.gis.geotools/geogenerator/producepoints/
---
## GeoGenerator.ProducePoints method

إنشاء مصفوفة من النقاط التي تنتمي إلى المنطقة المحددة.

```csharp
public static IEnumerable<IGeometry> ProducePoints(Extent rect, PointGeneratorOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | Extent | المنطقة المحددة (انظر [`Extent`](../../../aspose.gis/extent/)). |
| options | PointGeneratorOptions | خيارات إنشاء النقاط (انظر [`PointGeneratorOptions`](../../pointgeneratoroptions/)). |

### قيمة الإرجاع

مصفوفة من النقاط (انظر تعداد [`IGeometry`](../../../aspose.gis.geometries/igeometry/)).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | يجب أن يكون عدد النقاط أكبر من واحد |
| NullReferenceException | يجب أن يكون للنطاق قيمة (لا يكون NULL). |

### انظر أيضًا

* interface [IGeometry](../../../aspose.gis.geometries/igeometry/)
* class [Extent](../../../aspose.gis/extent/)
* class [PointGeneratorOptions](../../pointgeneratoroptions/)
* class [GeoGenerator](../)
* namespace [Aspose.Gis.GeoTools](../../geogenerator/)
* assembly [Aspose.GIS](../../../)


