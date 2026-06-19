---
title: "الفئة PrecisionModel"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.PrecisionModel. تحدد PrecisionModel عدد الأرقام ذات الدقة في إحداثية."
type: docs
weight: 3700
url: /ar/net/aspose.gis/precisionmodel/
---
## PrecisionModel class

`PrecisionModel` يحدد عدد الأرقام ذات الدلالة في إحداثي.

```csharp
public abstract class PrecisionModel : IEquatable<PrecisionModel>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Exact](../../aspose.gis/precisionmodel/exact/) { get; } | يعيد نموذج دقة دقيق. وفقًا لنموذج الدقة الدقيق، جميع الأرقام في قيمة مزدوجة ذات دلالة. |
| [IsExact](../../aspose.gis/precisionmodel/isexact/) { get; } | يحصل على قيمة تشير إلى ما إذا كان نموذج الدقة هذا دقيقًا. |
| [IsRounding](../../aspose.gis/precisionmodel/isrounding/) { get; } | يحصل على قيمة تشير إلى ما إذا كان نموذج الدقة هذا يقوم بالتقريب. |
| abstract [SignificantDigits](../../aspose.gis/precisionmodel/significantdigits/) { get; } | يحصل على عدد الأرقام ذات الدلالة في نموذج الدقة إذا كان يقوم بالتقريب. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Rounding](../../aspose.gis/precisionmodel/rounding/)(int) | يعيد نموذج دقة تقريبي. وفقًا لنموذج الدقة التقريبي، عدد محدود فقط من الأرقام ذات دلالة. |
| override [Equals](../../aspose.gis/precisionmodel/equals/#equals_1)(object) | يشير إلى ما إذا كان الكائن الحالي مساويًا لكائن آخر من نفس النوع. |
| [Equals](../../aspose.gis/precisionmodel/equals/#equals)(PrecisionModel) | يشير إلى ما إذا كان الكائن الحالي مساويًا لكائن آخر من نفس النوع. |
| override [GetHashCode](../../aspose.gis/precisionmodel/gethashcode/)() | يعمل كدالة تجزئة افتراضية. |
| [operator ==](../../aspose.gis/precisionmodel/op_equality/) | ينفّذ العامل ==. |
| [operator !=](../../aspose.gis/precisionmodel/op_inequality/) | ينفّذ العامل !=. |

## ملاحظات

هناك نوعان من PrecisionModel: Exact `PrecisionModel` (جميع الأرقام ذات دلالة); Rounded `PrecisionModel` (عدد من الأرقام ذات دلالة). يمكن تعيين `PrecisionModel` إلى [`VectorLayer`](../vectorlayer/) عبر [`DriverOptions`](../driveroptions/) لتقريب الإحداثيات عند كتابة أو قراءة الأشكال الهندسية.

### انظر أيضًا

* property [XYPrecisionModel](../driveroptions/xyprecisionmodel/)
* property [ZPrecisionModel](../driveroptions/zprecisionmodel/)
* property [MPrecisionModel](../driveroptions/mprecisionmodel/)
* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


