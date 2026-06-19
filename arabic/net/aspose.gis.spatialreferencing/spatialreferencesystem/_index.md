---
title: "الفئة SpatialReferenceSystem"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.SpatialReferencing.SpatialReferenceSystem. نظام الإحداثيات المكانية يربط الإحداثيات بالأماكن على الأرض. هناك أنواع مختلفة من SRS انظر Type. والأكثر من ذلك إذا كان نوع SRS جغرافيًا أو مسقَّطًا يمكن أن يكون مركبًا أو فرديًا انظر IsCompound"
type: docs
weight: 4700
url: /ar/net/aspose.gis.spatialreferencing/spatialreferencesystem/
---
## SpatialReferenceSystem class

نظام الإحداثيات المكانية يربط الإحداثيات بالأماكن على الأرض. هناك أنواع مختلفة من SRS، انظر [`Type`](./type/). والأكثر من ذلك، إذا كان نوع SRS جغرافيًا أو مسقَّطًا، يمكن أن يكون SRS مركبًا أو فرديًا، انظر [`IsCompound`](./iscompound/).

```csharp
public abstract class SpatialReferenceSystem : IdentifiableObject
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| virtual [AsCompound](../../aspose.gis.spatialreferencing/spatialreferencesystem/ascompound/) { get; } | يعيد هذا SRS محولًا إلى [`CompoundSpatialReferenceSystem`](../compoundspatialreferencesystem/). استخدم [`IsCompound`](./iscompound/) لمعرفة ما إذا كان التحويل ممكنًا. |
| virtual [AsGeocentric](../../aspose.gis.spatialreferencing/spatialreferencesystem/asgeocentric/) { get; } | يعيد هذا SRS محولًا إلى [`GeocentricSpatialReferenceSystem`](../geocentricspatialreferencesystem/). استخدم [`Type`](./type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| virtual [AsGeographic](../../aspose.gis.spatialreferencing/spatialreferencesystem/asgeographic/) { get; } | يعيد هذا SRS محولًا إلى [`GeographicSpatialReferenceSystem`](../geographicspatialreferencesystem/). استخدم [`Type`](./type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| virtual [AsLocal](../../aspose.gis.spatialreferencing/spatialreferencesystem/aslocal/) { get; } | يعيد هذا SRS محولًا إلى [`LocalSpatialReferenceSystem`](../localspatialreferencesystem/). استخدم [`Type`](./type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| virtual [AsProjected](../../aspose.gis.spatialreferencing/spatialreferencesystem/asprojected/) { get; } | يعيد هذا SRS محولًا إلى [`ProjectedSpatialReferenceSystem`](../projectedspatialreferencesystem/). استخدم [`Type`](./type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| virtual [AsVertical](../../aspose.gis.spatialreferencing/spatialreferencesystem/asvertical/) { get; } | يعيد هذا SRS محولًا إلى [`VerticalSpatialReferenceSystem`](../verticalspatialreferencesystem/). استخدم [`Type`](./type/) لمعرفة ما إذا كان التحويل ممكنًا. |
| abstract [DimensionsCount](../../aspose.gis.spatialreferencing/spatialreferencesystem/dimensionscount/) { get; } | يعيد عدد الأبعاد في هذا SRS. |
| [EpsgCode](../../aspose.gis.spatialreferencing/identifiableobject/epsgcode/) { get; } | إذا كان معرف هذا الكائن هو معرف EPSG - أعد رمزه. وإلا - أعد -1. |
| abstract [GeographicDatum](../../aspose.gis.spatialreferencing/spatialreferencesystem/geographicdatum/) { get; } | يعيد المرجع الجغرافي لهذا الـ SRS. |
| abstract [HasGeographicDatum](../../aspose.gis.spatialreferencing/spatialreferencesystem/hasgeographicdatum/) { get; } | يحدد ما إذا كان لهذا SRS معيار جغرافي. هذا صحيح لكل SRS جغرافي أو مسقَّط أو مركزي. |
| abstract [HasPrimeMeridian](../../aspose.gis.spatialreferencing/spatialreferencesystem/hasprimemeridian/) { get; } | يعيد ما إذا كان لهذا SRS خط طول رئيسي. هذا صحيح لكل SRS جغرافي أو مسقَّط أو مركزي. |
| [Identifier](../../aspose.gis.spatialreferencing/identifiableobject/identifier/) { get; } | معرف هذا الكائن القابل للتعريف. |
| virtual [IsCompound](../../aspose.gis.spatialreferencing/spatialreferencesystem/iscompound/) { get; } | يعيد ما إذا كان هذا SRS مركبًا (اتحاد بين SRSين). تُعتبر التركيبات التالية من SRS في SRS المركب صالحة: Geographic SRS + Vertical SRS، في هذه الحالة سيكون نوع SRS المركب جغرافيًا. Projected SRS + Vertical SRS، في هذه الحالة سيكون نوع SRS المركب إسقاطيًا. إذا اختلفت تركيبة الـ SRSs، سيكون نوع SRS المركب غير معروف. |
| [IsSingle](../../aspose.gis.spatialreferencing/spatialreferencesystem/issingle/) { get; } | يعيد ما إذا كان هذا SRS منفردًا (ليس اتحادًا بين SRSين). |
| [IsValid](../../aspose.gis.spatialreferencing/spatialreferencesystem/isvalid/) { get; } | نفس ما في [`Validate`](./validate/)، لكن لا يُعيد رسالة الخطأ. |
| [Name](../../aspose.gis.spatialreferencing/identifiableobject/name/) { get; } | اسم هذا الكائن. |
| abstract [PrimeMeridian](../../aspose.gis.spatialreferencing/spatialreferencesystem/primemeridian/) { get; } | يعيد خط الزوال الأساسي لهذا الـ SRS. |
| abstract [Type](../../aspose.gis.spatialreferencing/spatialreferencesystem/type/) { get; } | يحصل على نوع هذا SRS، انظر [`SpatialReferenceSystemType`](../spatialreferencesystemtype/). |
| static [Etrs89](../../aspose.gis.spatialreferencing/spatialreferencesystem/etrs89/) { get; } | نظام الإحداثيات المكانية ETRS 89 (EPSG:4258). |
| static [Etrs89LambertAzimuthalEqualArea](../../aspose.gis.spatialreferencing/spatialreferencesystem/etrs89lambertazimuthalequalarea/) { get; } | نظام الإحداثيات المكانية ETRS 89 / ETRS Lambert Azimuthal Equal Area (EPSG:3035). |
| static [Etrs89LambertConformalConic](../../aspose.gis.spatialreferencing/spatialreferencesystem/etrs89lambertconformalconic/) { get; } | نظام الإحداثيات المكانية ETRS 89 / Lambert Conformal Conic (EPSG:3034). |
| static [Nad83](../../aspose.gis.spatialreferencing/spatialreferencesystem/nad83/) { get; } | نظام الإحداثيات المكانية NAD 83 (EPSG:4269). |
| static [Osgb36](../../aspose.gis.spatialreferencing/spatialreferencesystem/osgb36/) { get; } | نظام الإحداثيات المكانية OSGB 36 (EPSG:4277). |
| static [Osgb36BritishNationalGrid](../../aspose.gis.spatialreferencing/spatialreferencesystem/osgb36britishnationalgrid/) { get; } | نظام الإحداثيات المكانية OSGB 36 / British National Grid (EPSG:27700). |
| static [WebMercator](../../aspose.gis.spatialreferencing/spatialreferencesystem/webmercator/) { get; } | نظام الإحداثيات المكانية Web Mercator (EPSG:3857). |
| static [Wgs72](../../aspose.gis.spatialreferencing/spatialreferencesystem/wgs72/) { get; } | نظام الإحداثيات المكانية WGS 72 (EPSG:4322). |
| static [Wgs84](../../aspose.gis.spatialreferencing/spatialreferencesystem/wgs84/) { get; } | نظام الإحداثيات المكانية WGS 84 (EPSG:4326). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [CreateFromEpsg](../../aspose.gis.spatialreferencing/spatialreferencesystem/createfromepsg/)(int) | أنشئ نظام إحداثيات مكاني بناءً على رمز EPSG المحدد. |
| static [CreateFromWkt](../../aspose.gis.spatialreferencing/spatialreferencesystem/createfromwkt/)(string) | ينشئ `SpatialReferenceSystem` جديدًا بناءً على سلسلة WKT (نص معروف جيدًا). |
| [CreateTransformationTo](../../aspose.gis.spatialreferencing/spatialreferencesystem/createtransformationto/)(SpatialReferenceSystem) | ينشئ تحويلًا من هذا `SpatialReferenceSystem` إلى `SpatialReferenceSystem` آخر. |
| [ExportToWkt](../../aspose.gis.spatialreferencing/spatialreferencesystem/exporttowkt/)() | يرجع تمثيل هذا SRS كسلسلة WKT. سلسلة WKT الناتجة ستطابق مواصفة OGC 01-009، وعادةً ما تُسمى "WKT1". |
| abstract [GetAxis](../../aspose.gis.spatialreferencing/spatialreferencesystem/getaxis/)(int) | احصل على [`Axis`](../axis/) الذي يصف البُعد. |
| abstract [GetUnit](../../aspose.gis.spatialreferencing/spatialreferencesystem/getunit/)(int) | احصل على [`Unit`](../unit/) للبُعد. |
| virtual [IsEquivalent](../../aspose.gis.spatialreferencing/spatialreferencesystem/isequivalent/)(SpatialReferenceSystem) | يكشف ما إذا كان هذا SRS مكافئًا لـ SRS آخر. |
| override [ToString](../../aspose.gis.spatialreferencing/identifiableobject/tostring/)() | يرجع سلسلة تمثل الكائن الحالي. |
| [TryCreateTransformationTo](../../aspose.gis.spatialreferencing/spatialreferencesystem/trycreatetransformationto/)(SpatialReferenceSystem, out SpatialReferenceSystemTransformation) | ينشئ تحويلًا من هذا `SpatialReferenceSystem` إلى `SpatialReferenceSystem` آخر. |
| abstract [Validate](../../aspose.gis.spatialreferencing/spatialreferencesystem/validate/)(out string) | تحديد ما إذا كان هذا الـ SRS صالحًا. |
| static [CreateCompound](../../aspose.gis.spatialreferencing/spatialreferencesystem/createcompound/)(string, SpatialReferenceSystem, SpatialReferenceSystem, Identifier) | إنشاء نظام إسناد مركب. |
| static [CreateGeocentric](../../aspose.gis.spatialreferencing/spatialreferencesystem/creategeocentric/)(GeocentricSpatialReferenceSystemParameters, Identifier) | إنشاء نظام إسناد جغرافي مركزي من معلمات مخصصة. |
| static [CreateGeographic](../../aspose.gis.spatialreferencing/spatialreferencesystem/creategeographic/)(GeographicSpatialReferenceSystemParameters, Identifier) | إنشاء نظام إسناد جغرافي من معلمات مخصصة. |
| static [CreateLocal](../../aspose.gis.spatialreferencing/spatialreferencesystem/createlocal/)(string, LocalDatum, Unit, ICollection&lt;Axis&gt;, Identifier) | إنشاء نظام إسناد مكاني محلي. |
| static [CreateProjected](../../aspose.gis.spatialreferencing/spatialreferencesystem/createprojected/)(ProjectedSpatialReferenceSystemParameters, Identifier) | إنشاء نظام إسناد إسقاطي من معلمات مخصصة. |
| static [CreateVertical](../../aspose.gis.spatialreferencing/spatialreferencesystem/createvertical/)(string, VerticalDatum, Unit, Axis, Identifier) | إنشاء نظام إسناد عمودي. |
| static [IsEquivalent](../../aspose.gis.spatialreferencing/spatialreferencesystem/isequivalent/)(SpatialReferenceSystem, SpatialReferenceSystem) | يحدد ما إذا كان نظاما إسناد اثنان متكافئان. تتطابق إحداثيات نظام الإسناد المتكافئ مع نفس الموقع على الأرض. يمكن أن تكون بعض معلمات نظام الإسناد المتكافئ مختلفة، على سبيل المثال [`Name`](../identifiableobject/name/). |
| static [TryCreateFromEpsg](../../aspose.gis.spatialreferencing/spatialreferencesystem/trycreatefromepsg/)(int, out SpatialReferenceSystem) | أنشئ نظام إحداثيات مكاني بناءً على رمز EPSG المحدد. |
| static [TryCreateFromWkt](../../aspose.gis.spatialreferencing/spatialreferencesystem/trycreatefromwkt/)(string, out SpatialReferenceSystem) | ينشئ `SpatialReferenceSystem` جديدًا بناءً على سلسلة WKT (نص معروف جيدًا). |

### انظر أيضًا

* class [IdentifiableObject](../identifiableobject/)
* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


