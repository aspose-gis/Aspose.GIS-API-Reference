---
title: "الفئة LocalSpatialReferenceSystem"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.SpatialReferencing.LocalSpatialReferenceSystem. نظام الإسناد المكاني المحلي يربط الإحداثيات ببعض الكائنات غير الأرض."
type: docs
weight: 4630
url: /ar/net/aspose.gis.spatialreferencing/localspatialreferencesystem/
---
## LocalSpatialReferenceSystem class

نظام الإشارة المكانية المحلي يربط الإحداثيات بكائن ما، وليس بالأرض.

```csharp
public class LocalSpatialReferenceSystem : SpatialReferenceSystem
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [AsCompound](../../aspose.gis.spatialreferencing/spatialreferencesystem/ascompound/) { get; } | يعيد هذا SRS محولًا إلى [`CompoundSpatialReferenceSystem`](../compoundspatialreferencesystem/). استخدم [`IsCompound`](../spatialreferencesystem/iscompound/) لمعرفة ما إذا كان التحويل ممكنًا. |
| virtual [AsGeocentric](../../aspose.gis.spatialreferencing/spatialreferencesystem/asgeocentric/) { get; } | يعيد هذا SRS محولًا إلى [`GeocentricSpatialReferenceSystem`](../geocentricspatialreferencesystem/). استخدم [`Type`](../spatialreferencesystem/type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| virtual [AsGeographic](../../aspose.gis.spatialreferencing/spatialreferencesystem/asgeographic/) { get; } | يعيد هذا SRS محولًا إلى [`GeographicSpatialReferenceSystem`](../geographicspatialreferencesystem/). استخدم [`Type`](../spatialreferencesystem/type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| override [AsLocal](../../aspose.gis.spatialreferencing/localspatialreferencesystem/aslocal/) { get; } | إرجاع هذا. |
| virtual [AsProjected](../../aspose.gis.spatialreferencing/spatialreferencesystem/asprojected/) { get; } | يعيد هذا SRS محولًا إلى [`ProjectedSpatialReferenceSystem`](../projectedspatialreferencesystem/). استخدم [`Type`](../spatialreferencesystem/type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| virtual [AsVertical](../../aspose.gis.spatialreferencing/spatialreferencesystem/asvertical/) { get; } | يرجع هذا SRS محوَّلًا إلى [`VerticalSpatialReferenceSystem`](../verticalspatialreferencesystem/). استخدم [`Type`](../spatialreferencesystem/type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| override [DimensionsCount](../../aspose.gis.spatialreferencing/localspatialreferencesystem/dimensionscount/) { get; } | عدد الأبعاد في هذا SRS. |
| [EpsgCode](../../aspose.gis.spatialreferencing/identifiableobject/epsgcode/) { get; } | إذا كان معرف هذا الكائن هو معرف EPSG - أعد رمزه. وإلا - أعد -1. |
| override [GeographicDatum](../../aspose.gis.spatialreferencing/localspatialreferencesystem/geographicdatum/) { get; } | يرمي InvalidOperationException، لأن نظام الإحداثيات المحلي لا يحتوي على مرجع جغرافي. |
| override [HasGeographicDatum](../../aspose.gis.spatialreferencing/localspatialreferencesystem/hasgeographicdatum/) { get; } | يرجع `false`، لأن نظام الإحداثيات المحلي لا يحتوي على مرجع جغرافي. |
| override [HasPrimeMeridian](../../aspose.gis.spatialreferencing/localspatialreferencesystem/hasprimemeridian/) { get; } | يرجع `false`، لأن نظام الإحداثيات المحلي لا يحتوي على خط الزوال الرئيسي. |
| [Identifier](../../aspose.gis.spatialreferencing/identifiableobject/identifier/) { get; } | معرف هذا الكائن القابل للتعريف. |
| virtual [IsCompound](../../aspose.gis.spatialreferencing/spatialreferencesystem/iscompound/) { get; } | يعيد ما إذا كان هذا SRS مركبًا (اتحاد بين SRSين). تُعتبر التركيبات التالية من SRS في SRS المركب صالحة: Geographic SRS + Vertical SRS، في هذه الحالة سيكون نوع SRS المركب جغرافيًا. Projected SRS + Vertical SRS، في هذه الحالة سيكون نوع SRS المركب إسقاطيًا. إذا اختلفت تركيبة الـ SRSs، سيكون نوع SRS المركب غير معروف. |
| [IsSingle](../../aspose.gis.spatialreferencing/spatialreferencesystem/issingle/) { get; } | يعيد ما إذا كان هذا SRS منفردًا (ليس اتحادًا بين SRSين). |
| [IsValid](../../aspose.gis.spatialreferencing/spatialreferencesystem/isvalid/) { get; } | نفس ما في [`Validate`](../spatialreferencesystem/validate/)، لكن لا تُعيد رسالة خطأ. |
| [LocalDatum](../../aspose.gis.spatialreferencing/localspatialreferencesystem/localdatum/) { get; } | مرجع، يصف طريقة القياسات. |
| [Name](../../aspose.gis.spatialreferencing/identifiableobject/name/) { get; } | اسم هذا الكائن. |
| override [PrimeMeridian](../../aspose.gis.spatialreferencing/localspatialreferencesystem/primemeridian/) { get; } | يرمي InvalidOperationException، لأن نظام الإحداثيات المحلي لا يحتوي على خط الزوال الرئيسي. |
| override [Type](../../aspose.gis.spatialreferencing/localspatialreferencesystem/type/) { get; } | إرجاع Local. |
| [Unit](../../aspose.gis.spatialreferencing/localspatialreferencesystem/unit/) { get; } | وحدة هذا SRS. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CreateTransformationTo](../../aspose.gis.spatialreferencing/spatialreferencesystem/createtransformationto/)(SpatialReferenceSystem) | ينشئ تحويلًا من هذا `SpatialReferenceSystem` إلى `SpatialReferenceSystem` آخر. |
| [ExportToWkt](../../aspose.gis.spatialreferencing/spatialreferencesystem/exporttowkt/)() | يرجع تمثيل هذا SRS كسلسلة WKT. سلسلة WKT الناتجة ستطابق مواصفة OGC 01-009، وعادةً ما تُسمى "WKT1". |
| override [GetAxis](../../aspose.gis.spatialreferencing/localspatialreferencesystem/getaxis/)(int) | احصل على [`Axis`](../axis/) الذي يصف البُعد. |
| override [GetUnit](../../aspose.gis.spatialreferencing/localspatialreferencesystem/getunit/)(int) | احصل على [`Unit`](./unit/) للبعد. |
| override [IsEquivalent](../../aspose.gis.spatialreferencing/localspatialreferencesystem/isequivalent/)(SpatialReferenceSystem) | يكشف ما إذا كان هذا SRS مكافئًا لـ SRS آخر. |
| override [ToString](../../aspose.gis.spatialreferencing/identifiableobject/tostring/)() | يرجع سلسلة تمثل الكائن الحالي. |
| [TryCreateTransformationTo](../../aspose.gis.spatialreferencing/spatialreferencesystem/trycreatetransformationto/)(SpatialReferenceSystem, out SpatialReferenceSystemTransformation) | ينشئ تحويلًا من هذا `SpatialReferenceSystem` إلى `SpatialReferenceSystem` آخر. |
| override [Validate](../../aspose.gis.spatialreferencing/localspatialreferencesystem/validate/)(out string) | حدد ما إذا كان هذا SRS صالحًا. راجع [`Validate`](../spatialreferencesystem/validate/) للحصول على وصف الصلاحية. |

### انظر أيضًا

* class [SpatialReferenceSystem](../spatialreferencesystem/)
* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


