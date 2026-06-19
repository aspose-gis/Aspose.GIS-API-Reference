---
title: "واجهة IGeometryCollection"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "واجهة Aspose.Gis.Geometries.IGeometryCollection. IGeometryCollection هي IGeometry تُعد مجموعة من هندسة واحدة أو أكثر."
type: docs
weight: 2790
url: /ar/net/aspose.gis.geometries/igeometrycollection/
---
## IGeometryCollection interface

`IGeometryCollection` هي [`IGeometry`](../igeometry/) تُعد مجموعة من هندسة واحدة أو أكثر.

```csharp
public interface IGeometryCollection : IEnumerable<IGeometry>, IEquatable<IGeometryCollection>, 
    IGeometry
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.gis.geometries/igeometrycollection/count/) { get; } | يحصل على عدد الهندسات في هذه المجموعة. |
| [Item](../../aspose.gis.geometries/igeometrycollection/item/) { get; } | يحصل على [`IGeometry`](../igeometry/) في الفهرس المحدد. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetPointOnSurface](../../aspose.gis.geometries/igeometrycollection/getpointonsurface/)() | يجد نقطة مضمونة أن تكون على أحد الأسطح في هذه المجموعة. |
| [ReplacePolygonsByLines](../../aspose.gis.geometries/igeometrycollection/replacepolygonsbylines/)() | يحصل على المضلعات الممثلة كخطوط لهذه الهندسة. |
| [ToEditable](../../aspose.gis.geometries/igeometrycollection/toeditable/)() | يحصل على نسخة قابلة للتحرير من هذه الهندسة. |
| [ToLinearGeometry](../../aspose.gis.geometries/igeometrycollection/tolineargeometry/#tolineargeometry)() | يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` الافتراضي. |
| [ToLinearGeometry](../../aspose.gis.geometries/igeometrycollection/tolineargeometry/#tolineargeometry_1)(double) | يحصل على نسخة تقريبية أو مكافئة غير منحنية لهذه الهندسة باستخدام `tolerance` المحدد. |

### انظر أيضًا

* interface [IGeometry](../igeometry/)
* namespace [Aspose.Gis.Geometries](../../aspose.gis.geometries/)
* assembly [Aspose.GIS](../../)


