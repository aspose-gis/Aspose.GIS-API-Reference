---
title: "SpatialReferenceSystem.GetAxis"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة SpatialReferenceSystem. احصل على المحور الذي يصف البُعد"
type: docs
weight: 200
url: /ar/net/aspose.gis.spatialreferencing/spatialreferencesystem/getaxis/
---
## SpatialReferenceSystem.GetAxis method

احصل على [`Axis`](../../axis/) التي تصف البُعد.

```csharp
public abstract Axis GetAxis(int dimension)
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
* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


