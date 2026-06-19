---
title: "الفئة Feature"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.Feature. ميزة جغرافية مكوّنة من شكل وسمات معرفة من قبل المستخدم"
type: docs
weight: 1620
url: /ar/net/aspose.gis/feature/
---
## Feature class

ميزة جغرافية مكوّنة من هندسة وسمات معرفة من قبل المستخدم.

```csharp
public class Feature
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Geometry](../../aspose.gis/feature/geometry/) { get; set; } | يحصل أو يعيّن الشكل للميزة. لا يمكن أن يكون `null`، استخدم [`Null`](../../aspose.gis.geometries/geometry/null/) للإشارة إلى شكل مفقود. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CopyValues](../../aspose.gis/feature/copyvalues/)(Feature) | ينسخ قيم السمات من ميزة أخرى. |
| [GetValue](../../aspose.gis/feature/getvalue/#getvalue)(string) | يحصل على قيمة سمة. |
| [GetValue&lt;T&gt;](../../aspose.gis/feature/getvalue/#getvalue_1)(string) | يحصل على قيمة سمة. |
| [GetValueOrDefault](../../aspose.gis/feature/getvalueordefault/#getvalueordefault)(string, object) | يحصل على قيمة سمة، أو [`DefaultValue`](../featureattribute/defaultvalue/) إذا كانت القيمة غير محددة أو `null`. |
| [GetValueOrDefault&lt;T&gt;](../../aspose.gis/feature/getvalueordefault/#getvalueordefault_1)(string) | يحصل على قيمة سمة، أو [`DefaultValue`](../featureattribute/defaultvalue/) إذا كانت القيمة غير محددة أو `null`. |
| [GetValueOrDefault&lt;T&gt;](../../aspose.gis/feature/getvalueordefault/#getvalueordefault_2)(string, object) | يحصل على قيمة سمة، أو [`DefaultValue`](../featureattribute/defaultvalue/) إذا كانت القيمة غير محددة أو `null`. |
| [GetValues](../../aspose.gis/feature/getvalues/)(object[], object) | يعيد القيم لجميع السمات في مصفوفة. |
| [GetValuesDump](../../aspose.gis/feature/getvaluesdump/)(object) | يعيد القيم لجميع السمات في مصفوفة. يُنصح باستخدام طريقة [`GetValues`](./getvalues/) لتجنب تخصيص ذاكرة إضافي. |
| [GetValuesList&lt;T&gt;](../../aspose.gis/feature/getvalueslist/)(string, string, int) | يحصل على قيم تسلسل السمات كقائمة. |
| [IsValueNull](../../aspose.gis/feature/isvaluenull/)(string) | يحدد ما إذا كانت السمة المحددة قد تم تعيينها صراحةً إلى القيمة `null`. |
| [IsValueSet](../../aspose.gis/feature/isvalueset/)(string) | يتحقق مما إذا كانت قيمة السمة مُعينة في هذه الميزة. |
| [SetValue&lt;T&gt;](../../aspose.gis/feature/setvalue/)(string, T) | يضبط قيمة جديدة لسمة. |
| [SetValueNull](../../aspose.gis/feature/setvaluenull/)(string) | يضبط قيمة السمة إلى `null`. |
| [SetValues](../../aspose.gis/feature/setvalues/)(object[]) | يضبط قيمًا جديدة لجميع السمات. كما يُنصح باستخدام طريقة [`CopyValues`](./copyvalues/) لتبسيط تعيين القيم في استدعاء واحد. |
| [UnsetValue](../../aspose.gis/feature/unsetvalue/)(string) | يزيل قيمة السمة من هذه الميزة. |

### انظر أيضًا

* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


