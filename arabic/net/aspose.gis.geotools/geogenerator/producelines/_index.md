---
title: "GeoGenerator.ProduceLines"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة GeoGenerator. تنشئ عدّاد ILineString جديد بعدد معين من العناصر العشوائية جميعها داخل مدى محدد"
type: docs
weight: 10
url: /ar/net/aspose.gis.geotools/geogenerator/producelines/
---
## GeoGenerator.ProduceLines method

إنشاء ILineString Enumerator جديد بعدد محدد من العناصر العشوائية، جميعها ضمن نطاق محدد.

```csharp
public static IEnumerable<ILineString> ProduceLines(Extent rect, LineGeneratorOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| rect | Extent | المنطقة المحددة (انظر [`Extent`](../../../aspose.gis/extent/)) |
| options | LineGeneratorOptions | خيارات إنشاء الخط (انظر [`LineGeneratorOptions`](../../linegeneratoroptions/)) |

### قيمة الإرجاع

مصفوفة من الخطوط (انظر تعداد [`ILineString`](../../../aspose.gis.geometries/ilinestring/))

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | يجب أن يكون عدد الخطوط أكبر من واحد. |
| NullReferenceException | يجب أن يكون للمدى قيمة (ليس NULL) |

### انظر أيضًا

* interface [ILineString](../../../aspose.gis.geometries/ilinestring/)
* class [Extent](../../../aspose.gis/extent/)
* class [LineGeneratorOptions](../../linegeneratoroptions/)
* class [GeoGenerator](../)
* namespace [Aspose.Gis.GeoTools](../../geogenerator/)
* assembly [Aspose.GIS](../../../)


