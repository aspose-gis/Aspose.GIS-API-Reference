---
title: "LineString.Item"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "خاصية LineString. تحصل أو تعيّن الـ IPoint في الفهرس المحدد"
type: docs
weight: 80
url: /ar/net/aspose.gis.geometries/linestring/item/
---
## LineString indexer

تحصل أو تعيّن الـ [`IPoint`](../../ipoint/) في الفهرس المحدد.

```csharp
public IPoint this[int index] { get; set; }
```

| معامل | الوصف |
| --- | --- |
| فهرس | الفهرس. |

### Property Value

الـ [`IPoint`](../../ipoint/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | الفهرس خارج النطاق. |
| ArgumentNullException | القيمة هي `null`. |
| ArgumentException | النقطة فارغة. |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) لهذا الشكل و[`SpatialReferenceSystem`](../spatialreferencesystem/) للمعامل كلاهما ليس `null` ولا يساويان بعضهما البعض. |

### انظر أيضًا

* interface [IPoint](../../ipoint/)
* class [LineString](../)
* namespace [Aspose.Gis.Geometries](../../linestring/)
* assembly [Aspose.GIS](../../../)


