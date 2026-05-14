---
title: "Extent.Grow"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Extent. توسّع هذا Extent بحيث يشمل المعامل."
type: docs
weight: 160
url: /ar/net/aspose.gis/extent/grow/
---
## Grow(Extent) {#grow}

يوسّع هذا النطاق بحيث يشمل الوسيط.

```csharp
public void Grow(Extent extent)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| مدى | مدى | Extent آخر. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) لهذا النطاق والوسيط كلاهما ليس `null` وليسا متساويين. |

## ملاحظات

إذا كان [`SpatialReferenceSystem`](../spatialreferencesystem/) لهذا SRS هو `null` فسيتم تحديثه بـ SRS الخاص بالمعامل.

### انظر أيضًا

* class [Extent](../)
* namespace [Aspose.Gis](../../extent/)
* assembly [Aspose.GIS](../../../)

---

## Grow(double, double) {#grow_1}

يوسّع هذا النطاق بحيث يشمل النقطة المحددة.

```csharp
public void Grow(double x, double y)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Double | الإحداثي X لتضمينه. |
| y | Double | الإحداثي Y لتضمينه. |

### انظر أيضًا

* class [Extent](../)
* namespace [Aspose.Gis](../../extent/)
* assembly [Aspose.GIS](../../../)


