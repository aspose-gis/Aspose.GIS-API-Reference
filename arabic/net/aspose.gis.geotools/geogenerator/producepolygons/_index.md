---
title: "GeoGenerator.ProducePolygons"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة GeoGenerator. تنشئ عدّاد IPolygon جديد بعدد معين من العناصر العشوائية جميعها داخل مدى محدد"
type: docs
weight: 30
url: /ar/net/aspose.gis.geotools/geogenerator/producepolygons/
---
## GeoGenerator.ProducePolygons method

إنشاء IPolygon Enumerator جديد بعدد محدد من العناصر العشوائية، جميعها ضمن نطاق محدد.

```csharp
public static IEnumerable<IPolygon> ProducePolygons(Extent rect, PolygonGeneratorOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | Extent | المنطقة المحددة (انظر [`Extent`](../../../aspose.gis/extent/)) |
| options | PolygonGeneratorOptions | خيارات إنشاء المضلع (انظر [`PolygonGeneratorOptions`](../../polygongeneratoroptions/)) |

### قيمة الإرجاع

مصفوفة من المضلعات (انظر تعداد [`IPolygon`](../../../aspose.gis.geometries/ipolygon/))

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | يجب أن يكون عدد المضلعات أكبر من واحد. |
| NullReferenceException | يجب أن يكون للمدى قيمة (ليس NULL) |
| ArgumentException | يجب أن تكون الأطوال الدنيا والقصوى غير متساوية وأكبر من 0 |
| ArgumentException | يجب أن يكون الطول الأقصى أكبر من الحد الأدنى |

### انظر أيضًا

* interface [IPolygon](../../../aspose.gis.geometries/ipolygon/)
* class [Extent](../../../aspose.gis/extent/)
* class [PolygonGeneratorOptions](../../polygongeneratoroptions/)
* class [GeoGenerator](../)
* namespace [Aspose.Gis.GeoTools](../../geogenerator/)
* assembly [Aspose.GIS](../../../)


