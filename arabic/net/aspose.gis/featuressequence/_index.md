---
title: "الفئة FeaturesSequence"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "Aspose.Gis.FeaturesSequence الفئة. FeaturesSequence تمثل مجموعة من المعالم المتجهية"
type: docs
weight: 1660
url: /ar/net/aspose.gis/featuressequence/
---
## FeaturesSequence class

`FeaturesSequence` تمثل مجموعة من المعالم المتجهية.

```csharp
public abstract class FeaturesSequence : IEnumerable<Feature>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| abstract [Attributes](../../aspose.gis/featuressequence/attributes/) { get; } | يحصل على مجموعة السمات المخصصة للمعالم في هذا [`VectorLayer`](../vectorlayer/). |
| abstract [SpatialReferenceSystem](../../aspose.gis/featuressequence/spatialreferencesystem/) { get; } | يحصل على نظام الإحداثيات المكانية لتسلسل هذه الميزات. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| abstract [GetEnumerator](../../aspose.gis/featuressequence/getenumerator/)() | يعيد عدّادًا يتنقل عبر المجموعة. |
| virtual [GetExtent](../../aspose.gis/featuressequence/getextent/)() | يحصل على الامتداد المكاني لهذه الطبقة. |
| [SaveTo](../../aspose.gis/featuressequence/saveto/#saveto)(AbstractPath, FileDriver) | يحفظ تسلسل الميزات إلى الطبقة. |
| [SaveTo](../../aspose.gis/featuressequence/saveto/#saveto_2)(string, FileDriver) | يحفظ تسلسل الميزات إلى الطبقة. |
| [SaveTo](../../aspose.gis/featuressequence/saveto/#saveto_1)(AbstractPath, FileDriver, SavingOptions) | يحفظ تسلسل الميزات إلى الطبقة. |
| [SaveTo](../../aspose.gis/featuressequence/saveto/#saveto_3)(string, FileDriver, SavingOptions) | يحفظ تسلسل الميزات إلى الطبقة. |
| [SplitTo](../../aspose.gis/featuressequence/splitto/)() | يقسم الميزات حسب نوع الهندسة. |
| virtual [WhereEqual&lt;T&gt;](../../aspose.gis/featuressequence/whereequal/)(string, T) | يختار المعالم التي تكون قيمة السمة مساوية للقيمة المقدمة. |
| virtual [WhereGreater&lt;T&gt;](../../aspose.gis/featuressequence/wheregreater/)(string, T) | يختار المعالم التي تكون قيمة السمة أكبر من القيمة المقدمة. |
| virtual [WhereGreaterOrEqual&lt;T&gt;](../../aspose.gis/featuressequence/wheregreaterorequal/)(string, T) | يختار المعالم التي تكون قيمة السمة أكبر أو مساوية للقيمة المقدمة. |
| virtual [WhereIntersects](../../aspose.gis/featuressequence/whereintersects/#whereintersects)(Extent) | يفلتر المعالم بناءً على النطاق. |
| [WhereIntersects](../../aspose.gis/featuressequence/whereintersects/#whereintersects_1)(FeaturesSequence) | يفلتر المعالم بناءً على اتحاد جميع الأشكال الهندسية في تسلسل المعالم الأخرى. |
| virtual [WhereIntersects](../../aspose.gis/featuressequence/whereintersects/#whereintersects_2)(IGeometry) | يفلتر المعالم بناءً على الشكل الهندسي المقدم. |
| virtual [WhereLinq](../../aspose.gis/featuressequence/wherelinq/)(Func&lt;Feature, bool&gt;) | دمج معايير الاختيار في استعلام واحد باستخدام linq. |
| virtual [WhereNotEqual&lt;T&gt;](../../aspose.gis/featuressequence/wherenotequal/)(string, T) | يختار المعالم التي تكون قيمة السمة غير مساوية للقيمة المقدمة. |
| virtual [WhereNotNull](../../aspose.gis/featuressequence/wherenotnull/)(string) | يختار المعالم التي تكون السمة غير مساوية لـ null. |
| virtual [WhereNull](../../aspose.gis/featuressequence/wherenull/)(string) | يختار المعالم التي تكون السمة مساوية لـ null. |
| virtual [WhereSet](../../aspose.gis/featuressequence/whereset/)(string) | يختار المعالم التي تم تعيين السمة لها. |
| virtual [WhereSmaller&lt;T&gt;](../../aspose.gis/featuressequence/wheresmaller/)(string, T) | يختار المعالم التي تكون قيمة السمة أصغر من القيمة المقدمة. |
| virtual [WhereSmallerOrEqual&lt;T&gt;](../../aspose.gis/featuressequence/wheresmallerorequal/)(string, T) | يختار المعالم التي تكون قيمة السمة أصغر أو مساوية للقيمة المقدمة. |
| virtual [WhereUnset](../../aspose.gis/featuressequence/whereunset/)(string) | يختار المعالم حيث السمة المحددة غير مُعينة. |

### انظر أيضًا

* class [Feature](../feature/)
* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


