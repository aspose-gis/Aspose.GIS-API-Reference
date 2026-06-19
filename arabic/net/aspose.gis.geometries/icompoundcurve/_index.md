---
title: "الواجهة ICompoundCurve"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "واجهة Aspose.Gis.Geometries.ICompoundCurve. منحنى يمثل تسلسلًا من المنحنيات المتجاورة بحيث تُربط المنحنيات المتجاورة بنقاط نهايتها"
type: docs
weight: 2750
url: /ar/net/aspose.gis.geometries/icompoundcurve/
---
## ICompoundCurve interface

منحنى يمثل تسلسلًا من المنحنيات المتصلة بحيث يتم ربط المنحنيات المتجاورة عند نقاط نهايتها.

```csharp
public interface ICompoundCurve : ICurve, IEnumerable<ICurve>, IEquatable<ICompoundCurve>
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.gis.geometries/icompoundcurve/count/) { get; } | يحصل على عدد المنحنيات في `ICompoundCurve`. |
| [Item](../../aspose.gis.geometries/icompoundcurve/item/) { get; } | يحصل على الـ[`ICurve`](../icurve/) عند الفهرس المحدد. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [ToEditable](../../aspose.gis.geometries/icompoundcurve/toeditable/)() | يحصل على نسخة قابلة للتحرير من هذه الهندسة. |

### انظر أيضًا

* interface [ICurve](../icurve/)
* namespace [Aspose.Gis.Geometries](../../aspose.gis.geometries/)
* assembly [Aspose.GIS](../../)


