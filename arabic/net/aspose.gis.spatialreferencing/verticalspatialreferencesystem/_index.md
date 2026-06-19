---
title: "فئة VerticalSpatialReferenceSystem"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "فئة Aspose.Gis.SpatialReferencing.VerticalSpatialReferenceSystem. SRS العمودي هو SRS أحادي البُعد يصف إحداثيات الارتفاع"
type: docs
weight: 4760
url: /ar/net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/
---
## VerticalSpatialReferenceSystem class

نظام الإحداثيات المرجعية العمودي هو نظام إحداثيات مرجعية أحادي البعد يصف إحداثيات الارتفاع.

```csharp
public class VerticalSpatialReferenceSystem : SpatialReferenceSystem
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [AsCompound](../../aspose.gis.spatialreferencing/spatialreferencesystem/ascompound/) { get; } | يعيد هذا SRS محولًا إلى [`CompoundSpatialReferenceSystem`](../compoundspatialreferencesystem/). استخدم [`IsCompound`](../spatialreferencesystem/iscompound/) لمعرفة ما إذا كان التحويل ممكنًا. |
| virtual [AsGeocentric](../../aspose.gis.spatialreferencing/spatialreferencesystem/asgeocentric/) { get; } | يعيد هذا SRS محولًا إلى [`GeocentricSpatialReferenceSystem`](../geocentricspatialreferencesystem/). استخدم [`Type`](../spatialreferencesystem/type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| virtual [AsGeographic](../../aspose.gis.spatialreferencing/spatialreferencesystem/asgeographic/) { get; } | يعيد هذا SRS محولًا إلى [`GeographicSpatialReferenceSystem`](../geographicspatialreferencesystem/). استخدم [`Type`](../spatialreferencesystem/type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| virtual [AsLocal](../../aspose.gis.spatialreferencing/spatialreferencesystem/aslocal/) { get; } | يعيد هذا SRS محولًا إلى [`LocalSpatialReferenceSystem`](../localspatialreferencesystem/). استخدم [`Type`](../spatialreferencesystem/type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| virtual [AsProjected](../../aspose.gis.spatialreferencing/spatialreferencesystem/asprojected/) { get; } | يعيد هذا SRS محولًا إلى [`ProjectedSpatialReferenceSystem`](../projectedspatialreferencesystem/). استخدم [`Type`](../spatialreferencesystem/type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| override [AsVertical](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/asvertical/) { get; } | يعيد هذا SRS. |
| override [DimensionsCount](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/dimensionscount/) { get; } | يعيد 1، لأن SRS العمودي دائمًا أحادي البُعد. |
| [EpsgCode](../../aspose.gis.spatialreferencing/identifiableobject/epsgcode/) { get; } | إذا كان معرف هذا الكائن هو معرف EPSG - أعد رمزه. وإلا - أعد -1. |
| override [GeographicDatum](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/geographicdatum/) { get; } | يرمي InvalidOperationException، لأن SRS العمودي لا يحتوي على مرجع جغرافي. |
| override [HasGeographicDatum](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/hasgeographicdatum/) { get; } | يعيد `false`، لأن SRS العمودي لا يحتوي على مرجع جغرافي. |
| override [HasPrimeMeridian](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/hasprimemeridian/) { get; } | يعيد `false`، لأن SRS العمودي لا يحتوي على خط طول رئيسي. |
| [Identifier](../../aspose.gis.spatialreferencing/identifiableobject/identifier/) { get; } | معرف هذا الكائن القابل للتعريف. |
| virtual [IsCompound](../../aspose.gis.spatialreferencing/spatialreferencesystem/iscompound/) { get; } | يعيد ما إذا كان هذا SRS مركبًا (اتحاد بين SRSين). تُعتبر التركيبات التالية من SRS في SRS المركب صالحة: Geographic SRS + Vertical SRS، في هذه الحالة سيكون نوع SRS المركب جغرافيًا. Projected SRS + Vertical SRS، في هذه الحالة سيكون نوع SRS المركب إسقاطيًا. إذا اختلفت تركيبة الـ SRSs، سيكون نوع SRS المركب غير معروف. |
| [IsSingle](../../aspose.gis.spatialreferencing/spatialreferencesystem/issingle/) { get; } | يعيد ما إذا كان هذا SRS منفردًا (ليس اتحادًا بين SRSين). |
| [IsValid](../../aspose.gis.spatialreferencing/spatialreferencesystem/isvalid/) { get; } | نفس ما في [`Validate`](../spatialreferencesystem/validate/)، لكن لا تُعيد رسالة خطأ. |
| [Name](../../aspose.gis.spatialreferencing/identifiableobject/name/) { get; } | اسم هذا الكائن. |
| override [PrimeMeridian](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/primemeridian/) { get; } | يرمي InvalidOperationException، لأن نظام الإحداثيات العمودي (Vertical SRS) لا يحتوي على خط الزوال الرئيسي. |
| override [Type](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/type/) { get; } | إرجاع Vertical. |
| [VerticalDatum](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/verticaldatum/) { get; } | المرجع الجيوديسي المستخدم في هذا SRS. |
| [VerticalUnit](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/verticalunit/) { get; } | الوحدة المستخدمة في هذا SRS. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CreateTransformationTo](../../aspose.gis.spatialreferencing/spatialreferencesystem/createtransformationto/)(SpatialReferenceSystem) | ينشئ تحويلًا من هذا `SpatialReferenceSystem` إلى `SpatialReferenceSystem` آخر. |
| [ExportToWkt](../../aspose.gis.spatialreferencing/spatialreferencesystem/exporttowkt/)() | يرجع تمثيل هذا SRS كسلسلة WKT. سلسلة WKT الناتجة ستطابق مواصفة OGC 01-009، وعادةً ما تُسمى "WKT1". |
| override [GetAxis](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/getaxis/)(int) | احصل على [`Axis`](../axis/) الذي يصف البُعد. |
| override [GetUnit](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/getunit/)(int) | احصل على [`Unit`](../unit/) للبُعد. |
| override [IsEquivalent](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/isequivalent/)(SpatialReferenceSystem) | يكشف ما إذا كان هذا SRS مكافئًا لـ SRS آخر. |
| override [ToString](../../aspose.gis.spatialreferencing/identifiableobject/tostring/)() | يرجع سلسلة تمثل الكائن الحالي. |
| [TryCreateTransformationTo](../../aspose.gis.spatialreferencing/spatialreferencesystem/trycreatetransformationto/)(SpatialReferenceSystem, out SpatialReferenceSystemTransformation) | ينشئ تحويلًا من هذا `SpatialReferenceSystem` إلى `SpatialReferenceSystem` آخر. |
| override [Validate](../../aspose.gis.spatialreferencing/verticalspatialreferencesystem/validate/)(out string) | حدد ما إذا كان هذا SRS صالحًا. راجع [`Validate`](../spatialreferencesystem/validate/) للحصول على وصف الصلاحية. |

### انظر أيضًا

* class [SpatialReferenceSystem](../spatialreferencesystem/)
* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


