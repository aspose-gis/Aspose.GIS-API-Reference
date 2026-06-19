---
title: "Polygon.AddInteriorRing"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Polygon. تضيف حلقة داخلية"
type: docs
weight: 90
url: /ar/net/aspose.gis.geometries/polygon/addinteriorring/
---
## Polygon.AddInteriorRing method

يضيف حلقة داخلية.

```csharp
public void AddInteriorRing(ILinearRing ring)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| حلقة | ILinearRing | الحلقة التي ستُضاف. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) لهذا الشكل و[`SpatialReferenceSystem`](../spatialreferencesystem/) للمعامل كلاهما ليس `null` ولا يساويان بعضهما البعض. |

### انظر أيضًا

* interface [ILinearRing](../../ilinearring/)
* class [Polygon](../)
* namespace [Aspose.Gis.Geometries](../../polygon/)
* assembly [Aspose.GIS](../../../)


