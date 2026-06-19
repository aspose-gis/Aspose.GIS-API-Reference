---
title: "الواجهة ICurve"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "واجهة Aspose.Gis.Geometries.ICurve. واجهة لنوع ICurve هي تسلسل من النقاط"
type: docs
weight: 2760
url: /ar/net/aspose.gis.geometries/icurve/
---
## ICurve interface

واجهة لنوع ICurve `ICurve` هي تسلسل من النقاط.

```csharp
public interface ICurve : IGeometry
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [EndPoint](../../aspose.gis.geometries/icurve/endpoint/) { get; } | يعيد نسخة من نقطة النهاية للمنحنى. |
| [IsClosed](../../aspose.gis.geometries/icurve/isclosed/) { get; } | يحصل على قيمة تشير إلى ما إذا كان المنحنى مغلقًا. يكون المنحنى مغلقًا إذا كانت نقطة البداية مساوية لنقطة النهاية. |
| [StartPoint](../../aspose.gis.geometries/icurve/startpoint/) { get; } | يعيد نسخة من نقطة البداية للمنحنى. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [ToEditable](../../aspose.gis.geometries/icurve/toeditable/)() | يحصل على نسخة قابلة للتحرير من هذه الهندسة. |
| [ToLinearGeometry](../../aspose.gis.geometries/icurve/tolineargeometry/#tolineargeometry)() | يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` الافتراضي. |
| [ToLinearGeometry](../../aspose.gis.geometries/icurve/tolineargeometry/#tolineargeometry_1)(double) | يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` المحدد. |

### انظر أيضًا

* interface [IGeometry](../igeometry/)
* namespace [Aspose.Gis.Geometries](../../aspose.gis.geometries/)
* assembly [Aspose.GIS](../../)


