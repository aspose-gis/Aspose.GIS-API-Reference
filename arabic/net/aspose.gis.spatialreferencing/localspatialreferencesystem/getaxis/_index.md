---
title: "LocalSpatialReferenceSystem.GetAxis"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة LocalSpatialReferenceSystem. احصل على المحور الذي يصف البُعد"
type: docs
weight: 100
url: /ar/net/aspose.gis.spatialreferencing/localspatialreferencesystem/getaxis/
---
## LocalSpatialReferenceSystem.GetAxis method

احصل على [`Axis`](../../axis/) التي تصف البُعد.

```csharp
public override Axis GetAxis(int dimension)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| البُعد | Int32 | عدد البُعد. |

### قيمة الإرجاع

Axis التي تصف البُعد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | *dimension* أقل من 0 أو أكبر أو يساوي [`DimensionsCount`](../dimensionscount/) |

### انظر أيضًا

* class [Axis](../../axis/)
* class [LocalSpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../localspatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


