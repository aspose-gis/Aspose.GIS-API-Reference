---
title: "Extent.Intersects"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Extent. تحدد ما إذا كان هذا النطاق يتقاطع مع الوسيط"
type: docs
weight: 190
url: /ar/net/aspose.gis/extent/intersects/
---
## Intersects(Extent) {#intersects}

يحدد ما إذا كان هذا النطاق يتقاطع مع الوسيط.

```csharp
public bool Intersects(Extent extent)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| مدى | مدى | نطاق آخر. |

### قيمة الإرجاع

قيمة تشير إلى ما إذا كان هذا النطاق يتقاطع مع الوسيط.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) لهذا النطاق والوسيط كلاهما ليس `null` وليسا متساويين. |

### انظر أيضًا

* class [Extent](../)
* namespace [Aspose.Gis](../../extent/)
* assembly [Aspose.GIS](../../../)

---

## Intersects(IGeometry) {#intersects_1}

يحدد ما إذا كان هذا النطاق يتقاطع مع الوسيط.

```csharp
public bool Intersects(IGeometry geometry)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| هندسة | IGeometry | هندسة لاختبار التقاطع |

### قيمة الإرجاع

قيمة تشير إلى ما إذا كان هذا النطاق يتقاطع مع الوسيط.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) لهذا النطاق والوسيط كلاهما ليس `null` وليسا متساويين. |

### انظر أيضًا

* interface [IGeometry](../../../aspose.gis.geometries/igeometry/)
* class [Extent](../)
* namespace [Aspose.Gis](../../extent/)
* assembly [Aspose.GIS](../../../)


