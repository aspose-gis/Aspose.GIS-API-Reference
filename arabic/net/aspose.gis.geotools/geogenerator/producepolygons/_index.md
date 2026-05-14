---
title: "GeoGenerator.ProducePolygons"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة GeoGenerator. تنشئ مُعدد IPolygon جديد بعدد محدد من العناصر العشوائية جميعها داخل نطاق محدد"
type: docs
weight: 30
url: /ar/net/aspose.gis.geotools/geogenerator/producepolygons/
---
## GeoGenerator.ProducePolygons method

إنشاء عداد IPolygon جديد بعدد معين من العناصر العشوائية، جميعها ضمن نطاق معين.

```csharp
public static IEnumerable<IPolygon> ProducePolygons(Extent rect, PolygonGeneratorOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | Extent | المنطقة المحددة (انظر [`Extent`](../../../aspose.gis/extent/)) |
| options | PolygonGeneratorOptions | خيارات إنشاء المضلع (انظر [`PolygonGeneratorOptions`](../../polygongeneratoroptions/)) |

### قيمة الإرجاع

مصفوفة من المضلع (انظر تعداد [`IPolygon`](../../../aspose.gis.geometries/ipolygon/))

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | يجب أن يكون عدد المضلعات أكبر من واحد. |
| NullReferenceException | يجب أن يكون للنطاق قيمة (لا يكون NULL) |
| ArgumentException | يجب أن تكون الأطوال الدنيا والقصوى غير متساوية وأكبر من 0 |
| ArgumentException | يجب أن يكون الحد الأقصى أكبر من الحد الأدنى |

### انظر أيضًا

* interface [IPolygon](../../../aspose.gis.geometries/ipolygon/)
* class [Extent](../../../aspose.gis/extent/)
* class [PolygonGeneratorOptions](../../polygongeneratoroptions/)
* class [GeoGenerator](../)
* namespace [Aspose.Gis.GeoTools](../../geogenerator/)
* assembly [Aspose.GIS](../../../)


