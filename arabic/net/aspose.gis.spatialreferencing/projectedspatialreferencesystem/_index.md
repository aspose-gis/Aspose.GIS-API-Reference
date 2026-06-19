---
title: "الفئة ProjectedSpatialReferenceSystem"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.SpatialReferencing.ProjectedSpatialReferenceSystem. نظام الإحداثيات الإسقاطي (Projected SRS) هو نتيجة تطبيق إسقاط على SRS الجغرافي. يمكن أن يكون الـ Projected SRS ثنائي الأبعاد أو ثلاثي الأبعاد. إذا كان الـ Projected SRS ثلاثيًا الأبعاد، فإنه في الواقع نظام إحداثيات مركب يتكون من نظام إحداثيات إسقاطي ثنائي الأبعاد ونظام إحداثيات عمودي أحادي البعد."
type: docs
weight: 4670
url: /ar/net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/
---
## ProjectedSpatialReferenceSystem class

نظام الإشارة المكانية الإسقاطي هو نتيجة تطبيق إسقاط على نظام إشارة مكانية جغرافي. يمكن أن يكون نظام الإشارة المكانية الإسقاطي ثنائي الأبعاد أو ثلاثي الأبعاد. إذا كان نظام الإشارة المكانية الإسقاطي ثلاثيًا الأبعاد، فإنه في الواقع نظام مركب يتكون من نظام إشارة إسقاطي ثنائي الأبعاد ونظام إشارة عمودي أحادي البعد.

```csharp
public abstract class ProjectedSpatialReferenceSystem : SpatialReferenceSystem
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| abstract [AngularUnit](../../aspose.gis.spatialreferencing/projectedspatialreferencesystem/angularunit/) { get; } | الوحدة المستخدمة للقيم الزاوية في هذا SRS وللمعلمات الزاوية لـ [`Projection`](./projection/). تتطابق مع الوحدة الزاوية لـ [`Base`](./base/). |
| virtual [AsCompound](../../aspose.gis.spatialreferencing/spatialreferencesystem/ascompound/) { get; } | يعيد هذا SRS محولًا إلى [`CompoundSpatialReferenceSystem`](../compoundspatialreferencesystem/). استخدم [`IsCompound`](../spatialreferencesystem/iscompound/) لمعرفة ما إذا كان التحويل ممكنًا. |
| virtual [AsGeocentric](../../aspose.gis.spatialreferencing/spatialreferencesystem/asgeocentric/) { get; } | يعيد هذا SRS محولًا إلى [`GeocentricSpatialReferenceSystem`](../geocentricspatialreferencesystem/). استخدم [`Type`](../spatialreferencesystem/type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| virtual [AsGeographic](../../aspose.gis.spatialreferencing/spatialreferencesystem/asgeographic/) { get; } | يعيد هذا SRS محولًا إلى [`GeographicSpatialReferenceSystem`](../geographicspatialreferencesystem/). استخدم [`Type`](../spatialreferencesystem/type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| virtual [AsLocal](../../aspose.gis.spatialreferencing/spatialreferencesystem/aslocal/) { get; } | يعيد هذا SRS محولًا إلى [`LocalSpatialReferenceSystem`](../localspatialreferencesystem/). استخدم [`Type`](../spatialreferencesystem/type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| [AsProjected](../../aspose.gis.spatialreferencing/projectedspatialreferencesystem/asprojected/) { get; } | إرجاع هذا. |
| virtual [AsVertical](../../aspose.gis.spatialreferencing/spatialreferencesystem/asvertical/) { get; } | يرجع هذا SRS محوَّلًا إلى [`VerticalSpatialReferenceSystem`](../verticalspatialreferencesystem/). استخدم [`Type`](../spatialreferencesystem/type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| abstract [AxisesOrder](../../aspose.gis.spatialreferencing/projectedspatialreferencesystem/axisesorder/) { get; } | ترتيب المحاور في هذا الـ SRS. إذا لم يكن هذا الـ SRS صالحًا وكان لديه اتجاهات محاور خاطئة، يتم إرجاع Invalid. |
| abstract [Base](../../aspose.gis.spatialreferencing/projectedspatialreferencesystem/base/) { get; } | نظام الإحداثيات الجغرافي (SRS) الذي تم تطبيق [`Projection`](./projection/) عليه للحصول على هذا الـ SRS. |
| abstract [DimensionsCount](../../aspose.gis.spatialreferencing/projectedspatialreferencesystem/dimensionscount/) { get; } | يعيد عدد الأبعاد في هذا الـ SRS. بالنسبة للـ SRS المُسقَّط يمكن أن يكون: اثنان - إذا كان هذا SRS مسقَّطًا واحدًا. ثلاثة - إذا كان هذا SRS مركبًا، يتكون من SRS مسقَّط أحادي البعد ثنائي الأبعاد و SRS رأسي، مما يضيف البُعد الثالث. |
| [EpsgCode](../../aspose.gis.spatialreferencing/identifiableobject/epsgcode/) { get; } | إذا كان معرف هذا الكائن هو معرف EPSG - أعد رمزه. وإلا - أعد -1. |
| abstract [GeographicDatum](../../aspose.gis.spatialreferencing/spatialreferencesystem/geographicdatum/) { get; } | يعيد المرجع الجغرافي لهذا الـ SRS. |
| [HasGeographicDatum](../../aspose.gis.spatialreferencing/projectedspatialreferencesystem/hasgeographicdatum/) { get; } | يعيد true، لأن الـ SRS المسقَّط دائمًا ما يكون له خط الزوال الأساسي. |
| [HasPrimeMeridian](../../aspose.gis.spatialreferencing/projectedspatialreferencesystem/hasprimemeridian/) { get; } | يعيد true، لأن الـ SRS المسقَّط دائمًا ما يكون له خط الزوال الأساسي. |
| [Identifier](../../aspose.gis.spatialreferencing/identifiableobject/identifier/) { get; } | معرف هذا الكائن القابل للتعريف. |
| virtual [IsCompound](../../aspose.gis.spatialreferencing/spatialreferencesystem/iscompound/) { get; } | يعيد ما إذا كان هذا SRS مركبًا (اتحاد بين SRSين). تُعتبر التركيبات التالية من SRS في SRS المركب صالحة: Geographic SRS + Vertical SRS، في هذه الحالة سيكون نوع SRS المركب جغرافيًا. Projected SRS + Vertical SRS، في هذه الحالة سيكون نوع SRS المركب إسقاطيًا. إذا اختلفت تركيبة الـ SRSs، سيكون نوع SRS المركب غير معروف. |
| [IsSingle](../../aspose.gis.spatialreferencing/spatialreferencesystem/issingle/) { get; } | يعيد ما إذا كان هذا SRS منفردًا (ليس اتحادًا بين SRSين). |
| [IsValid](../../aspose.gis.spatialreferencing/spatialreferencesystem/isvalid/) { get; } | نفس ما في [`Validate`](../spatialreferencesystem/validate/)، لكن لا تُعيد رسالة خطأ. |
| abstract [LinearUnit](../../aspose.gis.spatialreferencing/projectedspatialreferencesystem/linearunit/) { get; } | الوحدة المستخدمة للأبعاد الخطية في هذا الـ SRS وللمعلمات الخطية لـ [`Projection`](./projection/). |
| [Name](../../aspose.gis.spatialreferencing/identifiableobject/name/) { get; } | اسم هذا الكائن. |
| abstract [PrimeMeridian](../../aspose.gis.spatialreferencing/spatialreferencesystem/primemeridian/) { get; } | يعيد خط الزوال الأساسي لهذا الـ SRS. |
| abstract [Projection](../../aspose.gis.spatialreferencing/projectedspatialreferencesystem/projection/) { get; } | الإسقاط الذي تم تطبيقه على [`Base`](./base/) للحصول على هذا الـ SRS. |
| [Type](../../aspose.gis.spatialreferencing/projectedspatialreferencesystem/type/) { get; } | يعيد Projected. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CreateTransformationTo](../../aspose.gis.spatialreferencing/spatialreferencesystem/createtransformationto/)(SpatialReferenceSystem) | ينشئ تحويلًا من هذا `SpatialReferenceSystem` إلى `SpatialReferenceSystem` آخر. |
| [ExportToWkt](../../aspose.gis.spatialreferencing/spatialreferencesystem/exporttowkt/)() | يرجع تمثيل هذا SRS كسلسلة WKT. سلسلة WKT الناتجة ستطابق مواصفة OGC 01-009، وعادةً ما تُسمى "WKT1". |
| abstract [GetAxis](../../aspose.gis.spatialreferencing/spatialreferencesystem/getaxis/)(int) | احصل على [`Axis`](../axis/) الذي يصف البُعد. |
| abstract [GetUnit](../../aspose.gis.spatialreferencing/spatialreferencesystem/getunit/)(int) | احصل على [`Unit`](../unit/) للبُعد. |
| virtual [IsEquivalent](../../aspose.gis.spatialreferencing/spatialreferencesystem/isequivalent/)(SpatialReferenceSystem) | يكشف ما إذا كان هذا SRS مكافئًا لـ SRS آخر. |
| override [ToString](../../aspose.gis.spatialreferencing/identifiableobject/tostring/)() | يرجع سلسلة تمثل الكائن الحالي. |
| [TryCreateTransformationTo](../../aspose.gis.spatialreferencing/spatialreferencesystem/trycreatetransformationto/)(SpatialReferenceSystem, out SpatialReferenceSystemTransformation) | ينشئ تحويلًا من هذا `SpatialReferenceSystem` إلى `SpatialReferenceSystem` آخر. |
| abstract [Validate](../../aspose.gis.spatialreferencing/spatialreferencesystem/validate/)(out string) | تحديد ما إذا كان هذا الـ SRS صالحًا. |

### انظر أيضًا

* class [SpatialReferenceSystem](../spatialreferencesystem/)
* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


