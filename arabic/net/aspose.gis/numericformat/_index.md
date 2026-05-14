---
title: "الفئة NumericFormat"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.NumericFormat. تُستخدم NumericFormat لتنسيق الأنواع الرقمية الشائعة في النص"
type: docs
weight: 3440
url: /ar/net/aspose.gis/numericformat/
---
## NumericFormat class

`NumericFormat` تُستخدم لتنسيق الأنواع الرقمية الشائعة في النص.

```csharp
public abstract class NumericFormat
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [RoundTrip](../../aspose.gis/numericformat/roundtrip/) { get; } | يحول ويحاول التأكد من أن القيمة الرقمية التي تم تحويلها إلى سلسلة يتم تحليلها مرة أخرى إلى نفس القيمة الرقمية. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Flat](../../aspose.gis/numericformat/flat/)(int) | يحول عددًا إلى نص ثابت النقطة دون استخدام الصيغة العلمية. |
| static [General](../../aspose.gis/numericformat/general/)(int) | يحول عددًا إلى الشكل الأكثر اختصارًا إما ثابت النقطة أو الصيغة العلمية، اعتمادًا على نوع العدد وما إذا كان محدد الدقة موجودًا. يُنصح باستخدامه. |

## ملاحظات

هناك ثلاثة أنواع من `NumericFormat`: عام - ثابت النقطة أو الصيغة العلمية. بعض الأرقام ذات أهمية. RoundTrip - ثابت النقطة أو الصيغة العلمية. الحد الأقصى للأرقام ذات أهمية. Flat - صيغة ثابت النقطة. بعض الأرقام ذات أهمية. يمكن تعيين `NumericFormat` إلى [`IGeometry`](../../aspose.gis.geometries/igeometry/) عبر [`AsText`](../../aspose.gis.geometries/igeometry/astext/) لتحديد تنسيق الأرقام عند تحويل الشكل إلى تمثيله النصي المعروف (WKT).

### انظر أيضًا

* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


