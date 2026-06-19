---
title: "الفئة FeaturesSequence"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.FeaturesSequence. تمثل FeaturesSequence مجموعة من المعالم المتجهية."
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
| abstract [Attributes](../../aspose.gis/featuressequence/attributes/) { get; } | يحصل على مجموعة الخصائص المخصصة للمعالم في هذه [`VectorLayer`](../vectorlayer/). |
| abstract [SpatialReferenceSystem](../../aspose.gis/featuressequence/spatialreferencesystem/) { get; } | يسترجع نظام الإحداثيات المكاني لتسلسل هذه الميزات. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| abstract [GetEnumerator](../../aspose.gis/featuressequence/getenumerator/)() | يرجع عدّادًا يتنقل عبر المجموعة. |
| virtual [GetExtent](../../aspose.gis/featuressequence/getextent/)() | يسترجع النطاق المكاني لهذه الطبقة. |
| [SaveTo](../../aspose.gis/featuressequence/saveto/#saveto)(AbstractPath, FileDriver) | يحفظ تسلسل الميزات إلى الطبقة. |
| [SaveTo](../../aspose.gis/featuressequence/saveto/#saveto_2)(string, FileDriver) | يحفظ تسلسل الميزات إلى الطبقة. |
| [SaveTo](../../aspose.gis/featuressequence/saveto/#saveto_1)(AbstractPath, FileDriver, SavingOptions) | يحفظ تسلسل الميزات إلى الطبقة. |
| [SaveTo](../../aspose.gis/featuressequence/saveto/#saveto_3)(string, FileDriver, SavingOptions) | يحفظ تسلسل الميزات إلى الطبقة. |
| [SplitTo](../../aspose.gis/featuressequence/splitto/)() | يقسم الميزات حسب نوع الهندسة. |
| virtual [WhereEqual&lt;T&gt;](../../aspose.gis/featuressequence/whereequal/)(string, T) | يختار المعالم التي تكون قيمة الخاصية فيها مساوية للقيمة المقدمة. |
| virtual [WhereGreater&lt;T&gt;](../../aspose.gis/featuressequence/wheregreater/)(string, T) | يختار المعالم التي تكون قيمة الخاصية فيها أكبر من القيمة المقدمة. |
| virtual [WhereGreaterOrEqual&lt;T&gt;](../../aspose.gis/featuressequence/wheregreaterorequal/)(string, T) | يختار المعالم التي تكون قيمة الخاصية فيها أكبر أو مساوية للقيمة المقدمة. |
| virtual [WhereIntersects](../../aspose.gis/featuressequence/whereintersects/#whereintersects)(Extent) | يقوم بترشيح المعالم بناءً على النطاق. |
| [WhereIntersects](../../aspose.gis/featuressequence/whereintersects/#whereintersects_1)(FeaturesSequence) | يقوم بترشيح المعالم بناءً على اتحاد جميع الأشكال الهندسية في تسلسل المعالم الآخر. |
| virtual [WhereIntersects](../../aspose.gis/featuressequence/whereintersects/#whereintersects_2)(IGeometry) | يقوم بترشيح المعالم بناءً على الشكل الهندسي المقدم. |
| virtual [WhereLinq](../../aspose.gis/featuressequence/wherelinq/)(Func&lt;Feature, bool&gt;) | دمج معايير الاختيار في استعلام واحد باستخدام linq. |
| virtual [WhereNotEqual&lt;T&gt;](../../aspose.gis/featuressequence/wherenotequal/)(string, T) | يختار المعالم التي تكون قيمة الخاصية فيها غير مساوية للقيمة المقدمة. |
| virtual [WhereNotNull](../../aspose.gis/featuressequence/wherenotnull/)(string) | يختار المعالم التي تكون قيمة الخاصية فيها غير مساوية لـ null. |
| virtual [WhereNull](../../aspose.gis/featuressequence/wherenull/)(string) | يختار المعالم التي تكون قيمة الخاصية فيها مساوية لـ null. |
| virtual [WhereSet](../../aspose.gis/featuressequence/whereset/)(string) | يختار المعالم التي تم تعيين الخاصية لها. |
| virtual [WhereSmaller&lt;T&gt;](../../aspose.gis/featuressequence/wheresmaller/)(string, T) | يختار المعالم التي تكون قيمة الخاصية فيها أصغر من القيمة المقدمة. |
| virtual [WhereSmallerOrEqual&lt;T&gt;](../../aspose.gis/featuressequence/wheresmallerorequal/)(string, T) | يختار المعالم التي تكون قيمة الخاصية فيها أصغر أو مساوية للقيمة المقدمة. |
| virtual [WhereUnset](../../aspose.gis/featuressequence/whereunset/)(string) | يختار المعالم التي لم يتم تعيين الخاصية المحددة لها. |

### انظر أيضًا

* class [Feature](../feature/)
* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


