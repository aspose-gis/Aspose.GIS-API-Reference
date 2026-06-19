---
title: "Extent.Grow"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Extent. توسّع هذا الـ extent بحيث يشمل الوسيط."
type: docs
weight: 160
url: /ar/net/aspose.gis/extent/grow/
---
## Grow(Extent) {#grow}

يوسع هذا النطاق بحيث يشمل الوسيط.

```csharp
public void Grow(Extent extent)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| مدى | مدى | الـ extent الآخر. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) لهذا النطاق والوسيط كلاهما ليس `null` ولا متساويين. |

## ملاحظات

إذا كان [`SpatialReferenceSystem`](../spatialreferencesystem/) لهذا الـ SRS هو `null` فسيتم تحديثه بـ SRS الخاص بالوسيط.

### انظر أيضًا

* class [Extent](../)
* namespace [Aspose.Gis](../../extent/)
* assembly [Aspose.GIS](../../../)

---

## Grow(double, double) {#grow_1}

يوسع هذا النطاق بحيث يشمل النقطة المحددة.

```csharp
public void Grow(double x, double y)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| x | Double | إحداثي X لتضمينه. |
| y | Double | إحداثي Y لتضمينه. |

### انظر أيضًا

* class [Extent](../)
* namespace [Aspose.Gis](../../extent/)
* assembly [Aspose.GIS](../../../)


