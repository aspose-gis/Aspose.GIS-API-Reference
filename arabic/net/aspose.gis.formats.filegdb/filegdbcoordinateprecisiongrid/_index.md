---
title: "الفئة FileGdbCoordinatePrecisionGrid"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "Aspose.Gis.Formats.FileGdb.FileGdbCoordinatePrecisionGrid فئة. شبكة دقة إحداثيات داخل طبقة FileGDB"
type: docs
weight: 1840
url: /ar/net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/
---
## FileGdbCoordinatePrecisionGrid class

شبكة دقة إحداثيات داخل طبقة FileGDB.

```csharp
public sealed class FileGdbCoordinatePrecisionGrid
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [FileGdbCoordinatePrecisionGrid](filegdbcoordinateprecisiongrid/)() | المُنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [MOrigin](../../aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/morigin/) { get; set; } | يحصل أو يضبط أصل إحداثية M. إذا تم تعيينه إلى `null` يتم استخدام القيمة الافتراضية. |
| [MScale](../../aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/mscale/) { get; set; } | يحصل أو يضبط مقياس إحداثية M. إذا تم تعيينه إلى `null` يتم استخدام القيمة الافتراضية. |
| [XOrigin](../../aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/xorigin/) { get; set; } | يحصل أو يضبط أصل إحداثية X. إذا تم تعيينه إلى `null` يتم استخدام القيمة الافتراضية. |
| [XYScale](../../aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/xyscale/) { get; set; } | يحصل أو يضبط مقياس إحداثيات X و Y. إذا تم تعيينه إلى `null` يتم استخدام القيمة الافتراضية. |
| [YOrigin](../../aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/yorigin/) { get; set; } | يحصل أو يضبط أصل إحداثية Y. إذا تم تعيينه إلى `null` يتم استخدام القيمة الافتراضية. |
| [ZOrigin](../../aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/zorigin/) { get; set; } | يحصل أو يضبط أصل إحداثية Z. إذا تم تعيينه إلى `null` يتم استخدام القيمة الافتراضية. |
| [ZScale](../../aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/zscale/) { get; set; } | يحصل أو يضبط مقياس إحداثية Z. إذا تم تعيينه إلى `null` يتم استخدام القيمة الافتراضية. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [CreateFromRectangle](../../aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/createfromrectangle/)(IPoint, IPoint) | ينشئ `FileGdbCoordinatePrecisionGrid` جديد بحيث تكون جميع القيم داخل مستطيل قابلة للتمثيل. |

## ملاحظات

تحدد شبكة دقة الإحداثيات المجال الصالح ودقة الإحداثيات في طبقة FileGDB. يحدد الأصل المسار إلى شبكة دقة الإحداثيات في الفضاء. يحدد المقياس الدقة (كلما كان المقياس أكبر، كلما كتبت القيم بدقة أكبر). تحدد شبكة الدقة النطاق الصالح للقيم الخاصة بالإحداثيات:

```csharp
XMin = XOrigin
YMin = YOrigin
ZMin = ZOrigin
MMin = MOrigin
XMax = XOrigin + 9e+15 / XYScale
YMax = YOrigin + 9e+15 / XYScale
ZMax = ZOrigin + 9e+15 / ZScale
MMax = MOrigin + 9e+15 / MScale
```

يجب أن تكون كل إحداثية في [`VectorLayer`](../../aspose.gis/vectorlayer/) ضمن هذا النطاق. الإحداثيات التي تقع خارج النطاق قد تتسبب في أخطاء قراءة لاحقًا وستُعالج بشكل خاطئ بواسطة ArcGIS. إذا لم تحدد أي خصائص (اتركها `null`) سيتم استخدام القيم الافتراضية. تعتمد القيم الافتراضية على [`SpatialReferenceSystem`](../../aspose.gis.spatialreferencing/spatialreferencesystem/) الخاص بـ [`VectorLayer`](../../aspose.gis/vectorlayer/). للأنظمة الجغرافية [`SpatialReferenceSystem`](../../aspose.gis.spatialreferencing/spatialreferencesystem/) القيم الافتراضية هي:

```csharp
XOrigin = -400
YOrigin = -400
ZOrigin = -1e5
MOrigin = -1e5
XYScale = 1e9
ZScale  = 1 / ZTolerance * 10
MScale  = 1 / MTolerance * 10
```

لأنظمة الإسقاط [`SpatialReferenceSystem`](../../aspose.gis.spatialreferencing/spatialreferencesystem/) القيم الافتراضية هي:

```csharp
XOrigin = -2147483647
YOrigin = -2147483647
ZOrigin = -1e5
MOrigin = -1e5
XYScale = 1 / XYTolerance * 10
ZScale  = 1 / ZTolerance  * 10
MScale  = 1 / MTolerance  * 10
```

حيث `XYTolerance` و `ZTolerance` و `MTolerance` هي قيم من [`FileGdbOptions`](../filegdboptions/).

### انظر أيضًا

* namespace [Aspose.Gis.Formats.FileGdb](../../aspose.gis.formats.filegdb/)
* assembly [Aspose.GIS](../../)


