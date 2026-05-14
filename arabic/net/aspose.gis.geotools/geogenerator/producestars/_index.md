---
title: "GeoGenerator.ProduceStars"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة GeoGenerator. تنشئ مصفوفة من النجوم جميعها داخل نطاق محدد"
type: docs
weight: 40
url: /ar/net/aspose.gis.geotools/geogenerator/producestars/
---
## GeoGenerator.ProduceStars method

إنشاء مصفوفة من النجوم، جميعها ضمن نطاق معين.

```csharp
public static IEnumerable<IPolygon> ProduceStars(Extent rect, StarGeneratorOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | Extent | المنطقة المحددة (انظر [`Extent`](../../../aspose.gis/extent/)) |
| options | StarGeneratorOptions | خيارات إنشاء المضلع (انظر [`StarGeneratorOptions`](../../stargeneratoroptions/)) |

### قيمة الإرجاع

مصفوفة من النجوم (انظر تعداد [`IPolygon`](../../../aspose.gis.geometries/ipolygon/))

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | يجب أن يكون عدد النجوم أكبر من واحد |
| NullReferenceException | يجب أن يكون للنطاق قيمة (لا يكون NULL) |
| ArgumentException | يجب أن يكون الحد الأدنى والحد الأقصى غير متساويين وأكبر من 3 |
| ArgumentException | يجب أن يكون الحد الأقصى أكبر من الحد الأدنى |

### انظر أيضًا

* interface [IPolygon](../../../aspose.gis.geometries/ipolygon/)
* class [Extent](../../../aspose.gis/extent/)
* class [StarGeneratorOptions](../../stargeneratoroptions/)
* class [GeoGenerator](../)
* namespace [Aspose.Gis.GeoTools](../../geogenerator/)
* assembly [Aspose.GIS](../../../)


