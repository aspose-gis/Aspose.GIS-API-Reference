---
title: "CircularString.Item"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "خاصية CircularString. تحصل أو تعيّن الـ IPoint عند الفهرس المحدد"
type: docs
weight: 90
url: /ar/net/aspose.gis.geometries/circularstring/item/
---
## CircularString indexer

تحصل أو تُعيّن الـ [`IPoint`](../../ipoint/) عند الفهرس المحدد.

```csharp
public IPoint this[int index] { get; set; }
```

| معامل | الوصف |
| --- | --- |
| الفهرس | الفهرس. |

### Property Value

الـ [`IPoint`](../../ipoint/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | الفهرس خارج النطاق. |
| ArgumentNullException | القيمة هي `null`. |
| ArgumentException | النقطة فارغة. |
| ArgumentException | الـ[`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) لهذا الشكل و[`SpatialReferenceSystem`](../spatialreferencesystem/) للمعامل كلاهما ليسا `null` ولا يتساويان. |

### انظر أيضًا

* interface [IPoint](../../ipoint/)
* class [CircularString](../)
* namespace [Aspose.Gis.Geometries](../../circularstring/)
* assembly [Aspose.GIS](../../../)


