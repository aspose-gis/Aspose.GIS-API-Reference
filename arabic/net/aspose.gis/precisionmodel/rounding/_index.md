---
title: "PrecisionModel.Rounding"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة PrecisionModel. تُرجع نموذج دقة تقريبي. وفقًا لنموذج الدقة التقريبي، عدد محدود فقط من الأرقام يكون مهمًا"
type: docs
weight: 20
url: /ar/net/aspose.gis/precisionmodel/rounding/
---
## PrecisionModel.Rounding method

يعيد نموذج دقة تقريبي. وفقًا لنموذج الدقة التقريبي، عدد محدود فقط من الأرقام ذات دلالة.

```csharp
public static PrecisionModel Rounding(int significantDigits)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| significantDigits | Int32 | عدد الأرقام المهمة. |

### قيمة الإرجاع

نموذج دقة التقريب.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | عدد الأرقام المهمة أقل من 0 أو أكثر من 15. |

## ملاحظات

عند تطبيقه على إحداثي، يُستخدم الشيفرة التالية لتقليل الدقة:

```csharp
double rounded = Math.Round(value, significantDigits);
```

### انظر أيضًا

* class [PrecisionModel](../)
* namespace [Aspose.Gis](../../precisionmodel/)
* assembly [Aspose.GIS](../../../)


