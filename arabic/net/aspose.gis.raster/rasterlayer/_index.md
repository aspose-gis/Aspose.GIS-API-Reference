---
title: "الفئة RasterLayer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.Raster.RasterLayer. تمثل طبقة راستر"
type: docs
weight: 3830
url: /ar/net/aspose.gis.raster/rasterlayer/
---
## RasterLayer class

يمثل طبقة راستر.

```csharp
public abstract class RasterLayer : IDisposable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| abstract [BandCount](../../aspose.gis.raster/rasterlayer/bandcount/) { get; } | يسترجع عدد القنوات في طبقة الراستر. |
| [Bounds](../../aspose.gis.raster/rasterlayer/bounds/) { get; } | يسترجع حدود الراستر. |
| abstract [CellSize](../../aspose.gis.raster/rasterlayer/cellsize/) { get; } | يسترجع حجم الخلية أو البكسل للراستر. |
| abstract [Driver](../../aspose.gis.raster/rasterlayer/driver/) { get; } | يسترجع [`Driver`](./driver/) الذي أنشأ هذه الطبقة. |
| abstract [Height](../../aspose.gis.raster/rasterlayer/height/) { get; } | يسترجع ارتفاع الراستر بالبكسل. كما يُعرف أيضًا بعدد الصفوف. |
| abstract [NoDataValues](../../aspose.gis.raster/rasterlayer/nodatavalues/) { get; } | يسترجع القيم التي تمثل الخلفية أو "لا بيانات" للراستر. |
| abstract [SpatialReferenceSystem](../../aspose.gis.raster/rasterlayer/spatialreferencesystem/) { get; } | يسترجع نظام الإحداثيات المكانية للراستر. يمكن أن يكون `null` إذا كان غير معروف. |
| abstract [UpperLeftX](../../aspose.gis.raster/rasterlayer/upperleftx/) { get; } | يسترجع إحداثي x للزاوية العليا اليسرى للراستر. |
| abstract [UpperLeftY](../../aspose.gis.raster/rasterlayer/upperlefty/) { get; } | يسترجع إحداثي y للزاوية العليا اليسرى للراستر. |
| abstract [Width](../../aspose.gis.raster/rasterlayer/width/) { get; } | يسترجع عرض الراستر بالبكسل. كما يُعرف أيضًا بعدد الأعمدة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Crop](../../aspose.gis.raster/rasterlayer/crop/#crop_1)(double[]) | يقص طبقة الراستر باستخدام قناع القناة). |
| [Crop](../../aspose.gis.raster/rasterlayer/crop/#crop)(IGeometry, double[]) | يقص طبقة الراستر باستخدام شكل (و قناع القناة). |
| [Dispose](../../aspose.gis.raster/rasterlayer/dispose/)() | يطلق الموارد المستخدمة من قبل `RasterLayer`. |
| abstract [GetBand](../../aspose.gis.raster/rasterlayer/getband/)(int) | يسترجع قناة بالمؤشر المحدد. |
| virtual [GetExtent](../../aspose.gis.raster/rasterlayer/getextent/)() | يحسب الامتداد المكاني لهذه الطبقة. |
| [GetSpatialPoint](../../aspose.gis.raster/rasterlayer/getspatialpoint/)(int, int) | يحوّل العمود والصف المحددين إلى الإحداثيات المكانية. |
| [GetStatistics](../../aspose.gis.raster/rasterlayer/getstatistics/)(int, bool) | احسب إحصائيات ملخصة تتضمن العدد، المجموع، المتوسط، الحد الأدنى، الحد الأقصى. |
| [GetValues](../../aspose.gis.raster/rasterlayer/getvalues/)(int, int) | يقرأ القيم في الخلية المحددة. |
| [GetValuesDump](../../aspose.gis.raster/rasterlayer/getvaluesdump/)(RasterRect) | يقرأ القيم في الكتلة المحددة كمصفوفة ذات بعد واحد. |
| [GetValuesOnExpression](../../aspose.gis.raster/rasterlayer/getvaluesonexpression/)(RasterRect, RasterReadExpression) | يقرأ ويعالج قيم القناة في تعبير. |
| override [ToString](../../aspose.gis.raster/rasterlayer/tostring/)() | يرجع سلسلة تمثل الكائن الحالي. |
| [Warp](../../aspose.gis.raster/rasterlayer/warp/)(WarpOptions) | يشوه طبقة الراستر إلى أخرى. |

### انظر أيضًا

* namespace [Aspose.Gis.Raster](../../aspose.gis.raster/)
* assembly [Aspose.GIS](../../)


