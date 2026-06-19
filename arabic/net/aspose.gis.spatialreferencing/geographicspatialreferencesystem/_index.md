---
title: "فئة GeographicSpatialReferenceSystem"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "Aspose.Gis.SpatialReferencing.GeographicSpatialReferenceSystem فئة. نظام الإحداثيات الجغرافي (SRS) هو نظام إحداثيات يعتمد على خط الطول وخط العرض. يمكن أن يكون نظام الإحداثيات الجغرافي ثنائي الأبعاد أو ثلاثي الأبعاد. إذا كان نظام الإحداثيات الجغرافي ثلاثي الأبعاد فإنه في الواقع نظام مركب يتكون من نظام إحداثيات ثنائي الأبعاد ونظام إحداثيات عمودي."
type: docs
weight: 4580
url: /ar/net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/
---
## GeographicSpatialReferenceSystem class

نظام الإشارة المكانية الجغرافي هو نظام إشارة يعتمد على خط الطول وخط العرض. يمكن أن يكون نظام الإشارة المكانية الجغرافي ثنائي الأبعاد أو ثلاثي الأبعاد. إذا كان نظام الإشارة المكانية الجغرافي ثلاثيًا الأبعاد، فإنه في الواقع نظام مركب يتكون من نظام إشارة ثنائي الأبعاد ونظام إشارة عمودي.

```csharp
public abstract class GeographicSpatialReferenceSystem : SpatialReferenceSystem
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| abstract [AngularUnit](../../aspose.gis.spatialreferencing/geographicspatialreferencesystem/angularunit/) { get; } | الوحدة، المستخدمة للأبعاد الزاوية، في هذا النظام (SRS). |
| virtual [AsCompound](../../aspose.gis.spatialreferencing/spatialreferencesystem/ascompound/) { get; } | يعيد هذا SRS محولًا إلى [`CompoundSpatialReferenceSystem`](../compoundspatialreferencesystem/). استخدم [`IsCompound`](../spatialreferencesystem/iscompound/) لمعرفة ما إذا كان التحويل ممكنًا. |
| virtual [AsGeocentric](../../aspose.gis.spatialreferencing/spatialreferencesystem/asgeocentric/) { get; } | يعيد هذا SRS محولًا إلى [`GeocentricSpatialReferenceSystem`](../geocentricspatialreferencesystem/). استخدم [`Type`](../spatialreferencesystem/type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| [AsGeographic](../../aspose.gis.spatialreferencing/geographicspatialreferencesystem/asgeographic/) { get; } | يرجع هذا. |
| virtual [AsLocal](../../aspose.gis.spatialreferencing/spatialreferencesystem/aslocal/) { get; } | يعيد هذا SRS محولًا إلى [`LocalSpatialReferenceSystem`](../localspatialreferencesystem/). استخدم [`Type`](../spatialreferencesystem/type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| virtual [AsProjected](../../aspose.gis.spatialreferencing/spatialreferencesystem/asprojected/) { get; } | يعيد هذا SRS محولًا إلى [`ProjectedSpatialReferenceSystem`](../projectedspatialreferencesystem/). استخدم [`Type`](../spatialreferencesystem/type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| virtual [AsVertical](../../aspose.gis.spatialreferencing/spatialreferencesystem/asvertical/) { get; } | يرجع هذا SRS محوَّلًا إلى [`VerticalSpatialReferenceSystem`](../verticalspatialreferencesystem/). استخدم [`Type`](../spatialreferencesystem/type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| abstract [AxisesOrder](../../aspose.gis.spatialreferencing/geographicspatialreferencesystem/axisesorder/) { get; } | ترتيب المحاور في هذا الـ SRS. إذا لم يكن هذا الـ SRS صالحًا وكان لديه اتجاهات محاور خاطئة، يتم إرجاع Invalid. |
| abstract [DimensionsCount](../../aspose.gis.spatialreferencing/geographicspatialreferencesystem/dimensionscount/) { get; } | يرجع عدد الأبعاد في هذا النظام (SRS). بالنسبة لنظام الإحداثيات الجغرافي يمكن أن يكون: اثنان - إذا كان هذا نظام إحداثيات جغرافي واحد. ثلاثة - إذا كان هذا نظامًا مركبًا، يتكون من نظام إحداثيات جغرافي واحد ثنائي الأبعاد ونظام إحداثيات عمودي، يضيف البعد الثالث. |
| [EpsgCode](../../aspose.gis.spatialreferencing/identifiableobject/epsgcode/) { get; } | إذا كان معرف هذا الكائن هو معرف EPSG - أعد رمزه. وإلا - أعد -1. |
| abstract [GeographicDatum](../../aspose.gis.spatialreferencing/spatialreferencesystem/geographicdatum/) { get; } | يعيد المرجع الجغرافي لهذا الـ SRS. |
| [HasGeographicDatum](../../aspose.gis.spatialreferencing/geographicspatialreferencesystem/hasgeographicdatum/) { get; } | يرجع `true`، لأن نظام الإحداثيات الجغرافي دائمًا ما يكون له خط الزوال الرئيسي. |
| [HasPrimeMeridian](../../aspose.gis.spatialreferencing/geographicspatialreferencesystem/hasprimemeridian/) { get; } | يرجع `true`، لأن نظام الإحداثيات الجغرافي دائمًا ما يكون له خط الزوال الرئيسي. |
| [Identifier](../../aspose.gis.spatialreferencing/identifiableobject/identifier/) { get; } | معرف هذا الكائن القابل للتعريف. |
| virtual [IsCompound](../../aspose.gis.spatialreferencing/spatialreferencesystem/iscompound/) { get; } | يعيد ما إذا كان هذا SRS مركبًا (اتحاد بين SRSين). تُعتبر التركيبات التالية من SRS في SRS المركب صالحة: Geographic SRS + Vertical SRS، في هذه الحالة سيكون نوع SRS المركب جغرافيًا. Projected SRS + Vertical SRS، في هذه الحالة سيكون نوع SRS المركب إسقاطيًا. إذا اختلفت تركيبة الـ SRSs، سيكون نوع SRS المركب غير معروف. |
| [IsSingle](../../aspose.gis.spatialreferencing/spatialreferencesystem/issingle/) { get; } | يعيد ما إذا كان هذا SRS منفردًا (ليس اتحادًا بين SRSين). |
| [IsValid](../../aspose.gis.spatialreferencing/spatialreferencesystem/isvalid/) { get; } | نفس ما في [`Validate`](../spatialreferencesystem/validate/)، لكن لا تُعيد رسالة خطأ. |
| [Name](../../aspose.gis.spatialreferencing/identifiableobject/name/) { get; } | اسم هذا الكائن. |
| abstract [PrimeMeridian](../../aspose.gis.spatialreferencing/spatialreferencesystem/primemeridian/) { get; } | يعيد خط الزوال الأساسي لهذا الـ SRS. |
| [Type](../../aspose.gis.spatialreferencing/geographicspatialreferencesystem/type/) { get; } | يرجع جغرافي. |

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


