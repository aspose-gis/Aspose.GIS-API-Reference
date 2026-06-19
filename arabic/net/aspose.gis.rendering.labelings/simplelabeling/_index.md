---
title: "فئة SimpleLabeling"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "فئة Aspose.Gis.Rendering.Labelings.SimpleLabeling. وضع بسيط للتسمية يضع تسمية على كل ميزة"
type: docs
weight: 4150
url: /ar/net/aspose.gis.rendering.labelings/simplelabeling/
---
## SimpleLabeling class

تسمية بسيطة تضع التسمية على كل ميزة.

```csharp
public class SimpleLabeling : Labeling
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [SimpleLabeling](simplelabeling/#constructor)() | ينشئ مثيلاً جديداً من الفئة `SimpleLabeling`. |
| [SimpleLabeling](simplelabeling/#constructor_1)(SimpleLabeling) | ينشئ مثيلاً جديداً من الفئة `SimpleLabeling`. |
| [SimpleLabeling](simplelabeling/#constructor_2)(string) | ينشئ مثيلاً جديداً من الفئة `SimpleLabeling`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [FeatureBasedConfiguration](../../aspose.gis.rendering.labelings/simplelabeling/featurebasedconfiguration/) { get; set; } | دالة رد نداء تُستخدم لتكوين هذه التسمية قبل معالجة ميزة. |
| [FontColor](../../aspose.gis.rendering.labelings/simplelabeling/fontcolor/) { get; set; } | يحدد لون النص. |
| [FontFamily](../../aspose.gis.rendering.labelings/simplelabeling/fontfamily/) { get; set; } | عائلة الخط المستخدمة لعرض النص. القيمة الافتراضية تعتمد على النظام. |
| [FontSize](../../aspose.gis.rendering.labelings/simplelabeling/fontsize/) { get; set; } | حجم النص. |
| [FontStyle](../../aspose.gis.rendering.labelings/simplelabeling/fontstyle/) { get; set; } | النمط المطبق على النص. |
| [GeometryExpression](../../aspose.gis.rendering.labelings/simplelabeling/geometryexpression/) { get; set; } | يوفر طريقة لاستبدال هندسة الميزة بأخرى معدلة للتسمية. يتم استدعاء هذه الدالة أولاً بعد [`FeatureBasedConfiguration`](./featurebasedconfiguration/). القيمة الافتراضية هي `null` (استخدام هندسة الميزة كما هي). |
| [HaloColor](../../aspose.gis.rendering.labelings/simplelabeling/halocolor/) { get; set; } | لون الهالة (الخط) حول النص. |
| [HaloSize](../../aspose.gis.rendering.labelings/simplelabeling/halosize/) { get; set; } | حجم الهالة (الخط) حول النص. |
| [LabelAttribute](../../aspose.gis.rendering.labelings/simplelabeling/labelattribute/) { get; set; } | اسم السمة المستخدم كمصدر للتسميات. يتم تجاهله إذا تم تعيين [`LabelExpression`](./labelexpression/). يجب تعيين إما [`LabelAttribute`](./labelattribute/) أو [`LabelExpression`](./labelexpression/) قبل العرض؛ وإلا يتم رمي استثناء InvalidOperationException. |
| [LabelExpression](../../aspose.gis.rendering.labelings/simplelabeling/labelexpression/) { get; set; } | يوفر طريقة لتخصيص وتنسيق نص التسمية. إذا تم تعيينه، يتجاوز [`LabelAttribute`](./labelattribute/). يجب تعيين إما [`LabelAttribute`](./labelattribute/) أو [`LabelExpression`](./labelexpression/) قبل العرض؛ وإلا يتم رمي استثناء InvalidOperationException. |
| [MultipartMode](../../aspose.gis.rendering.labelings/simplelabeling/multipartmode/) { get; set; } | يحدد سلوك العرض للأشكال المتعددة الأجزاء. القيمة الافتراضية هي All. |
| [Placement](../../aspose.gis.rendering.labelings/simplelabeling/placement/) { get; set; } | تحديد موضع التسمية يوضح كيفية وضع التسميات بالنسبة إلى هندسة الميزة. |
| [Priority](../../aspose.gis.rendering.labelings/simplelabeling/priority/) { get; set; } | يشير إلى أولوية هذه التسمية في حال تداخلها مع تسمية أخرى. التسمية ذات الأولوية الأقل لا تُعرض. القيمة الافتراضية هي 1000. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Clone](../../aspose.gis.rendering.labelings/simplelabeling/clone/)() | ينسخ هذا الكائن. |

### انظر أيضًا

* class [Labeling](../labeling/)
* namespace [Aspose.Gis.Rendering.Labelings](../../aspose.gis.rendering.labelings/)
* assembly [Aspose.GIS](../../)


