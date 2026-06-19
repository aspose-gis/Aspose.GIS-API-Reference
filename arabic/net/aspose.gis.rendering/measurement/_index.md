---
title: "بنية Measurement"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "بنية Aspose.Gis.Rendering.Measurement. رقم يشير إلى قياس العرض."
type: docs
weight: 4190
url: /ar/net/aspose.gis.rendering/measurement/
---
## Measurement structure

رقم يشير إلى قياس التصيير.

```csharp
public struct Measurement
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Measurement](measurement/)(double, Unit) | ينشئ نسخة جديدة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Zero](../../aspose.gis.rendering/measurement/zero/) { get; } | قياس بطول صفر. |
| [Unit](../../aspose.gis.rendering/measurement/unit/) { get; } | وحدة قياس. |
| [Value](../../aspose.gis.rendering/measurement/value/) { get; } | رقم يشير إلى طول القياس. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Inches](../../aspose.gis.rendering/measurement/inches/)(double) | يعيد نسخة جديدة من `Measurement` تمثل الطول بالبوصة. |
| static [MapUnits](../../aspose.gis.rendering/measurement/mapunits/)(double) | يعيد نسخة جديدة من `Measurement` تمثل الطول بوحدات الإشارة المكانية للخرائط. |
| static [MetersOnEarth](../../aspose.gis.rendering/measurement/metersonearth/)(double) | يعيد نسخة جديدة من `Measurement` تمثل الطول بالأمتار على الأرض. |
| static [Millimeters](../../aspose.gis.rendering/measurement/millimeters/)(double) | يعيد نسخة جديدة من `Measurement` تمثل الطول بالمليمتر. |
| static [Pixels](../../aspose.gis.rendering/measurement/pixels/)(double) | يعيد نسخة جديدة من `Measurement` تمثل الطول بالبكسل. |
| static [Points](../../aspose.gis.rendering/measurement/points/)(double) | إرجاع كائن جديد من `Measurement` يمثل الطول بالنقاط. |
| override [ToString](../../aspose.gis.rendering/measurement/tostring/)() | إرجاع هذه النسخة محوَّلة إلى سلسلة. |
| [operator /](../../aspose.gis.rendering/measurement/op_division/) | قسّم القياس على العامل. |
| [implicit operator](../../aspose.gis.rendering/measurement/op_implicit/) | يعيد نسخة جديدة من `Measurement` تمثل الطول بالبكسل. |
| [operator *](../../aspose.gis.rendering/measurement/op_multiply/) | يضرب القياس في العامل. |

### انظر أيضًا

* namespace [Aspose.Gis.Rendering](../../aspose.gis.rendering/)
* assembly [Aspose.GIS](../../)


