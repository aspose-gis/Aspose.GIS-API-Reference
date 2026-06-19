---
title: "الفئة VectorLayer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.VectorLayer. تمثّل طبقة متجهية. الطبقة المتجهية هي مجموعة من الميزات الجغرافية المخزنة في ملف."
type: docs
weight: 5050
url: /ar/net/aspose.gis/vectorlayer/
---
## VectorLayer class

يمثل طبقة متجهية. الطبقة المتجهية هي مجموعة من الميزات الجغرافية، مخزنة في ملف.

```csharp
public abstract class VectorLayer : FeaturesSequence, IDisposable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [Attributes](../../aspose.gis/vectorlayer/attributes/) { get; } | يسترجع مجموعة السمات المخصصة للميزات في هذا `VectorLayer`. |
| virtual [Count](../../aspose.gis/vectorlayer/count/) { get; } | يسترجع عدد الميزات في هذه الطبقة. |
| abstract [Driver](../../aspose.gis/vectorlayer/driver/) { get; } | يسترجع [`Driver`](./driver/) الذي أنشأ هذه الطبقة. |
| abstract [GeometryType](../../aspose.gis/vectorlayer/geometrytype/) { get; } | يسترجع نوع الهندسة للطبقة. |
| virtual [Item](../../aspose.gis/vectorlayer/item/) { get; } | يسترجع [`Feature`](../feature/) في الفهرس المحدد. |
| abstract [SpatialReferenceSystem](../../aspose.gis/featuressequence/spatialreferencesystem/) { get; } | يسترجع نظام الإحداثيات المكاني لتسلسل هذه الميزات. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Create](../../aspose.gis/vectorlayer/create/#create)(AbstractPath, FileDriver) | ينشئ الطبقة ويفتحها لإضافة ميزات جديدة. |
| static [Create](../../aspose.gis/vectorlayer/create/#create_4)(string, FileDriver) | ينشئ الطبقة ويفتحها لإضافة ميزات جديدة. |
| static [Create](../../aspose.gis/vectorlayer/create/#create_1)(AbstractPath, FileDriver, DriverOptions) | ينشئ الطبقة ويفتحها لإضافة ميزات جديدة. |
| static [Create](../../aspose.gis/vectorlayer/create/#create_3)(AbstractPath, FileDriver, SpatialReferenceSystem) | ينشئ الطبقة ويفتحها للإلحاق. |
| static [Create](../../aspose.gis/vectorlayer/create/#create_5)(string, FileDriver, DriverOptions) | ينشئ الطبقة ويفتحها لإضافة ميزات جديدة. |
| static [Create](../../aspose.gis/vectorlayer/create/#create_7)(string, FileDriver, SpatialReferenceSystem) | ينشئ الطبقة ويفتحها للإلحاق. |
| static [Create](../../aspose.gis/vectorlayer/create/#create_2)(AbstractPath, FileDriver, DriverOptions, SpatialReferenceSystem) | ينشئ الطبقة ويفتحها للإلحاق. |
| static [Create](../../aspose.gis/vectorlayer/create/#create_6)(string, FileDriver, DriverOptions, SpatialReferenceSystem) | ينشئ الطبقة ويفتحها للإلحاق. |
| static [Open](../../aspose.gis/vectorlayer/open/#open)(AbstractPath, FileDriver) | افتح الطبقة للقراءة. |
| static [Open](../../aspose.gis/vectorlayer/open/#open_2)(string, FileDriver) | افتح الطبقة للقراءة. |
| static [Open](../../aspose.gis/vectorlayer/open/#open_1)(AbstractPath, FileDriver, DriverOptions) | افتح الطبقة للقراءة. |
| static [Open](../../aspose.gis/vectorlayer/open/#open_3)(string, FileDriver, DriverOptions) | افتح الطبقة للقراءة. |
| virtual [Add](../../aspose.gis/vectorlayer/add/#add)(Feature) | يضيف ميزة جديدة إلى الطبقة، إذا كان ذلك مدعومًا من قبل [`Driver`](./driver/) الخاص بـ `VectorLayer`. |
| virtual [Add](../../aspose.gis/vectorlayer/add/#add_1)(Feature, IFeatureStyle) | يضيف ميزة جديدة بالأسلوب المحدد إلى الطبقة، إذا كان ذلك مدعومًا من قبل [`Driver`](./driver/) الخاص بـ `VectorLayer`. |
| [AsInMemory](../../aspose.gis/vectorlayer/asinmemory/)() | أنشئ نسخة من الطبقة بصيغة InMemory. |
| [ConstructFeature](../../aspose.gis/vectorlayer/constructfeature/)() | ينشئ (لكن لا يضيف إلى الطبقة) ميزة جديدة بسمات تتطابق مع مجموعة سمات هذه الطبقة. عند الانتهاء من تعيين البيانات للميزة، استخدم [`Add`](./add/) لإضافة الميزة إلى الطبقة. |
| [CopyAttributes](../../aspose.gis/vectorlayer/copyattributes/#copyattributes)(FeaturesSequence) | ينسخ سمات `VectorLayer` أخرى إلى هذه. |
| [CopyAttributes](../../aspose.gis/vectorlayer/copyattributes/#copyattributes_1)(FeaturesSequence, IAttributesConverter) | ينسخ سمات `VectorLayer` أخرى إلى هذه. |
| [Dispose](../../aspose.gis/vectorlayer/dispose/)() | يحرر الموارد المستخدمة من قبل `VectorLayer`. |
| override [Equals](../../aspose.gis/vectorlayer/equals/)(object) | يحدد ما إذا كان الكائن المحدد مساويًا للكائن الحالي. |
| virtual [FindIndex](../../aspose.gis/vectorlayer/findindex/)(Func&lt;Feature, bool&gt;) | البحث عن فهرس [`Feature`](../feature/) وفقًا للشرط. |
| abstract [GetEnumerator](../../aspose.gis/featuressequence/getenumerator/)() | يرجع عدّادًا يتنقل عبر المجموعة. |
| virtual [GetExtent](../../aspose.gis/featuressequence/getextent/)() | يسترجع النطاق المكاني لهذه الطبقة. |
| [Join](../../aspose.gis/vectorlayer/join/)(VectorLayer, JoinOptions) | ينضم طبقة إلى الطبقة الحالية. |
| [JoinByGeometry](../../aspose.gis/vectorlayer/joinbygeometry/)(VectorLayer, JoinByGeometryOptions) | يجمع طبقة مع الطبقة الحالية حسب الهندسة. |
| [NearestTo](../../aspose.gis/vectorlayer/nearestto/#nearestto)(IPoint) | يسترجع أقرب ميزة إلى النقطة المقدمة. |
| [NearestTo](../../aspose.gis/vectorlayer/nearestto/#nearestto_1)(double, double) | يسترجع أقرب ميزة إلى الإحداثي المقدم. |
| virtual [RemoveAt](../../aspose.gis/vectorlayer/removeat/)(int) | إزالة [`Feature`](../feature/) في الفهرس المحدد. |
| virtual [ReplaceAt](../../aspose.gis/vectorlayer/replaceat/)(int, Feature) | استبدال [`Feature`](../feature/) في الفهرس المحدد. |
| [SaveTo](../../aspose.gis/featuressequence/saveto/)(AbstractPath, FileDriver) | يحفظ تسلسل الميزات إلى الطبقة. |
| [SaveTo](../../aspose.gis/featuressequence/saveto/)(string, FileDriver) | يحفظ تسلسل الميزات إلى الطبقة. |
| [SaveTo](../../aspose.gis/featuressequence/saveto/)(AbstractPath, FileDriver, SavingOptions) | يحفظ تسلسل الميزات إلى الطبقة. |
| [SaveTo](../../aspose.gis/featuressequence/saveto/)(string, FileDriver, SavingOptions) | يحفظ تسلسل الميزات إلى الطبقة. |
| [SplitTo](../../aspose.gis/featuressequence/splitto/)() | يقسم الميزات حسب نوع الهندسة. |
| virtual [UseAttributesIndex](../../aspose.gis/vectorlayer/useattributesindex/#useattributesindex)(AbstractPath, string, bool) | يقوم بتحميل فهرس السمات لتسريع التصفية حسب قيمة السمات في طرق التصفية مثل [`WhereGreater`](../featuressequence/wheregreater/). إذا لم يكن الفهرس موجودًا، يتم إنشاؤه أولاً. استخدم *forceRebuild* لإجبار إعادة إنشاء الفهرس. |
| [UseAttributesIndex](../../aspose.gis/vectorlayer/useattributesindex/#useattributesindex_1)(string, string, bool) | يقوم بتحميل فهرس السمات لتسريع التصفية حسب قيمة السمات في طرق التصفية مثل [`WhereGreater`](../featuressequence/wheregreater/). إذا لم يكن الفهرس موجودًا، يتم إنشاؤه أولاً. استخدم *forceRebuild* لإجبار إعادة إنشاء الفهرس. |
| virtual [UseSpatialIndex](../../aspose.gis/vectorlayer/usespatialindex/#usespatialindex)(AbstractPath, bool) | يقوم بتحميل الفهرس المكاني لتسريع الترشيح حسب قيمة الخصائص في طرق الفلترة مثل [`WhereIntersects`](../featuressequence/whereintersects/) و [`NearestTo`](./nearestto/). إذا لم يكن الفهرس موجودًا يتم إنشاؤه أولاً. استخدم *forceRebuild* لإجبار إعادة إنشاء الفهرس. |
| [UseSpatialIndex](../../aspose.gis/vectorlayer/usespatialindex/#usespatialindex_1)(string, bool) | يقوم بتحميل الفهرس المكاني لتسريع الترشيح حسب قيمة الخصائص في طرق الفلترة مثل [`WhereIntersects`](../featuressequence/whereintersects/) و [`NearestTo`](./nearestto/). إذا لم يكن الفهرس موجودًا يتم إنشاؤه أولاً. استخدم *forceRebuild* لإجبار إعادة إنشاء الفهرس. |
| virtual [WhereEqual&lt;T&gt;](../../aspose.gis/featuressequence/whereequal/)(string, T) | يختار المعالم التي تكون قيمة الخاصية فيها مساوية للقيمة المقدمة. |
| virtual [WhereGreater&lt;T&gt;](../../aspose.gis/featuressequence/wheregreater/)(string, T) | يختار المعالم التي تكون قيمة الخاصية فيها أكبر من القيمة المقدمة. |
| virtual [WhereGreaterOrEqual&lt;T&gt;](../../aspose.gis/featuressequence/wheregreaterorequal/)(string, T) | يختار المعالم التي تكون قيمة الخاصية فيها أكبر أو مساوية للقيمة المقدمة. |
| virtual [WhereIntersects](../../aspose.gis/featuressequence/whereintersects/)(Extent) | يقوم بترشيح المعالم بناءً على النطاق. |
| [WhereIntersects](../../aspose.gis/featuressequence/whereintersects/)(FeaturesSequence) | يقوم بترشيح المعالم بناءً على اتحاد جميع الأشكال الهندسية في تسلسل المعالم الآخر. |
| virtual [WhereIntersects](../../aspose.gis/featuressequence/whereintersects/)(IGeometry) | يقوم بترشيح المعالم بناءً على الشكل الهندسي المقدم. |
| virtual [WhereLinq](../../aspose.gis/featuressequence/wherelinq/)(Func&lt;Feature, bool&gt;) | دمج معايير الاختيار في استعلام واحد باستخدام linq. |
| virtual [WhereNotEqual&lt;T&gt;](../../aspose.gis/featuressequence/wherenotequal/)(string, T) | يختار المعالم التي تكون قيمة الخاصية فيها غير مساوية للقيمة المقدمة. |
| virtual [WhereNotNull](../../aspose.gis/featuressequence/wherenotnull/)(string) | يختار المعالم التي تكون قيمة الخاصية فيها غير مساوية لـ null. |
| virtual [WhereNull](../../aspose.gis/featuressequence/wherenull/)(string) | يختار المعالم التي تكون قيمة الخاصية فيها مساوية لـ null. |
| virtual [WhereSet](../../aspose.gis/featuressequence/whereset/)(string) | يختار المعالم التي تم تعيين الخاصية لها. |
| virtual [WhereSmaller&lt;T&gt;](../../aspose.gis/featuressequence/wheresmaller/)(string, T) | يختار المعالم التي تكون قيمة الخاصية فيها أصغر من القيمة المقدمة. |
| virtual [WhereSmallerOrEqual&lt;T&gt;](../../aspose.gis/featuressequence/wheresmallerorequal/)(string, T) | يختار المعالم التي تكون قيمة الخاصية فيها أصغر أو مساوية للقيمة المقدمة. |
| virtual [WhereUnset](../../aspose.gis/featuressequence/whereunset/)(string) | يختار المعالم التي لم يتم تعيين الخاصية المحددة لها. |
| static [Convert](../../aspose.gis/vectorlayer/convert/#convert)(AbstractPath, FileDriver, AbstractPath, FileDriver) | تحويل طبقة إلى تنسيق مختلف. |
| static [Convert](../../aspose.gis/vectorlayer/convert/#convert_2)(string, FileDriver, string, FileDriver) | تحويل طبقة إلى تنسيق مختلف. |
| static [Convert](../../aspose.gis/vectorlayer/convert/#convert_1)(AbstractPath, FileDriver, AbstractPath, FileDriver, ConversionOptions) | تحويل طبقة إلى تنسيق مختلف. |
| static [Convert](../../aspose.gis/vectorlayer/convert/#convert_3)(string, FileDriver, string, FileDriver, ConversionOptions) | تحويل طبقة إلى تنسيق مختلف. |

### انظر أيضًا

* class [FeaturesSequence](../featuressequence/)
* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


