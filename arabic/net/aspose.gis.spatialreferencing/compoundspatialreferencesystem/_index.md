---
title: "الفئة CompoundSpatialReferenceSystem"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.SpatialReferencing.CompoundSpatialReferenceSystem. يجمع نظام الإحداثيات المركب بين نظامي إحداثيات أساسيين لا يمكن لأي منهما أن يكون مركبًا."
type: docs
weight: 4510
url: /ar/net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/
---
## CompoundSpatialReferenceSystem class

نظام الإشارة المكانية المركب يجمع نظامين أساسيين، ولا يمكن لأي منهما أن يكون مركبًا.

```csharp
public class CompoundSpatialReferenceSystem : SpatialReferenceSystem
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [AsCompound](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/ascompound/) { get; } | إرجاع هذا. |
| virtual [AsGeocentric](../../aspose.gis.spatialreferencing/spatialreferencesystem/asgeocentric/) { get; } | يعيد هذا SRS محولًا إلى [`GeocentricSpatialReferenceSystem`](../geocentricspatialreferencesystem/). استخدم [`Type`](../spatialreferencesystem/type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| override [AsGeographic](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/asgeographic/) { get; } | إرجاع تمثيل جغرافي لهذا النظام. إذا كان هذا النظام المركب يمثل بالفعل نظام إحداثيات جغرافي، فستكون النتيجة نظام إحداثيات جغرافي ثلاثي الأبعاد (مع أبعاد الطول والعرض والارتفاع). وإلا سيتم إلقاء استثناء. |
| virtual [AsLocal](../../aspose.gis.spatialreferencing/spatialreferencesystem/aslocal/) { get; } | يعيد هذا SRS محولًا إلى [`LocalSpatialReferenceSystem`](../localspatialreferencesystem/). استخدم [`Type`](../spatialreferencesystem/type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| override [AsProjected](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/asprojected/) { get; } | إرجاع تمثيل إسقاطي لهذا النظام. إذا كان هذا النظام المركب يمثل بالفعل نظام إحداثيات إسقاطي، فستكون النتيجة نظام إحداثيات إسقاطي ثلاثي الأبعاد (مع أبعاد X وY والارتفاع). وإلا سيتم إلقاء استثناء. |
| virtual [AsVertical](../../aspose.gis.spatialreferencing/spatialreferencesystem/asvertical/) { get; } | يرجع هذا SRS محوَّلًا إلى [`VerticalSpatialReferenceSystem`](../verticalspatialreferencesystem/). استخدم [`Type`](../spatialreferencesystem/type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| override [DimensionsCount](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/dimensionscount/) { get; } | عدد الأبعاد. بالنسبة للنظام المركب، هذا هو مجموع عدد أبعاد أنظمة الإحداثيات الأساسية. |
| [EpsgCode](../../aspose.gis.spatialreferencing/identifiableobject/epsgcode/) { get; } | إذا كان معرف هذا الكائن هو معرف EPSG - أعد رمزه. وإلا - أعد -1. |
| override [GeographicDatum](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/geographicdatum/) { get; } | إرجاع المرجع الجغرافي لهذا SRS. إذا كان كل من [`Head`](./head/) و[`Tail`](./tail/) يحتويان على المرجع الجغرافي - إرجاع المرجع الجغرافي للـ head. |
| override [HasGeographicDatum](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/hasgeographicdatum/) { get; } | تحتوي SRS المركبة على مرجع جغرافي إذا كان أي من SRS الأساسي يحتوي على مرجع جغرافي. |
| override [HasPrimeMeridian](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/hasprimemeridian/) { get; } | تحتوي SRS المركبة على خط الطول الرئيسي إذا كان أي من SRS الأساسي يحتوي على خط الطول الرئيسي. |
| [Head](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/head/) { get; } | أول SRS أساسي. |
| [Identifier](../../aspose.gis.spatialreferencing/identifiableobject/identifier/) { get; } | معرف هذا الكائن القابل للتعريف. |
| override [IsCompound](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/iscompound/) { get; } | تُعيد `true`. |
| [IsSingle](../../aspose.gis.spatialreferencing/spatialreferencesystem/issingle/) { get; } | يعيد ما إذا كان هذا SRS منفردًا (ليس اتحادًا بين SRSين). |
| [IsValid](../../aspose.gis.spatialreferencing/spatialreferencesystem/isvalid/) { get; } | نفس ما في [`Validate`](../spatialreferencesystem/validate/)، لكن لا تُعيد رسالة خطأ. |
| [Name](../../aspose.gis.spatialreferencing/identifiableobject/name/) { get; } | اسم هذا الكائن. |
| override [PrimeMeridian](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/primemeridian/) { get; } | إرجاع خط الطول الرئيسي لهذا SRS. إذا كان كل من [`Head`](./head/) و[`Tail`](./tail/) يحتويان على خط الطول الرئيسي - إرجاع خط الطول الرئيسي للـ head. |
| [Tail](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/tail/) { get; } | ثاني SRS أساسي. |
| override [Type](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/type/) { get; } | نوع هذا SRS المركب. يمكن أن يكون Geographic إذا كان هذا SRS المركب مزيجًا من SRS جغرافي وعمودي، أو Projected إذا كان هذا SRS المركب مزيجًا من SRS مسقّط وعمودي. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [CreateTransformationTo](../../aspose.gis.spatialreferencing/spatialreferencesystem/createtransformationto/)(SpatialReferenceSystem) | ينشئ تحويلًا من هذا `SpatialReferenceSystem` إلى `SpatialReferenceSystem` آخر. |
| [ExportToWkt](../../aspose.gis.spatialreferencing/spatialreferencesystem/exporttowkt/)() | يرجع تمثيل هذا SRS كسلسلة WKT. سلسلة WKT الناتجة ستطابق مواصفة OGC 01-009، وعادةً ما تُسمى "WKT1". |
| override [GetAxis](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/getaxis/)(int) | احصل على [`Axis`](../axis/) الذي يصف البُعد. |
| override [GetUnit](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/getunit/)(int) | احصل على [`Unit`](../unit/) للبُعد. |
| override [IsEquivalent](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/isequivalent/)(SpatialReferenceSystem) | يكشف ما إذا كان هذا SRS مكافئًا لـ SRS آخر. |
| override [ToString](../../aspose.gis.spatialreferencing/identifiableobject/tostring/)() | يرجع سلسلة تمثل الكائن الحالي. |
| [TryCreateTransformationTo](../../aspose.gis.spatialreferencing/spatialreferencesystem/trycreatetransformationto/)(SpatialReferenceSystem, out SpatialReferenceSystemTransformation) | ينشئ تحويلًا من هذا `SpatialReferenceSystem` إلى `SpatialReferenceSystem` آخر. |
| override [Validate](../../aspose.gis.spatialreferencing/compoundspatialreferencesystem/validate/)(out string) | حدد ما إذا كان هذا SRS صالحًا. راجع [`Validate`](../spatialreferencesystem/validate/) للحصول على وصف الصلاحية. |

### انظر أيضًا

* class [SpatialReferenceSystem](../spatialreferencesystem/)
* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


