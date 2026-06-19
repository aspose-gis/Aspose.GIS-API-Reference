---
title: "FileGdbCoordinatePrecisionGrid.XYScale"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "خاصية FileGdbCoordinatePrecisionGrid. تحصل على مقياس إحداثيات X و Y أو تعينه. إذا تم تعيينها إلى null تُستخدم القيمة الافتراضية"
type: docs
weight: 60
url: /ar/net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/xyscale/
---
## FileGdbCoordinatePrecisionGrid.XYScale property

يحصل أو يضبط مقياس إحداثيات X و Y. إذا تم تعيينه إلى `null` تُستخدم القيمة الافتراضية.

```csharp
public double? XYScale { get; set; }
```

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | المعامل ليس موجبًا. |

## ملاحظات

القيمة الافتراضية هي `1e9` لـ [`VectorLayer`](../../../aspose.gis/vectorlayer/) مع نظام إسناد مكاني جغرافي [`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem/) و `XYScale = 1 / XYTolerance * 10` لـ [`VectorLayer`](../../../aspose.gis/vectorlayer/) مع نظام إسناد مكاني إسقاطي [`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem/).

### انظر أيضًا

* class [FileGdbCoordinatePrecisionGrid](../)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdbcoordinateprecisiongrid/)
* assembly [Aspose.GIS](../../../)


