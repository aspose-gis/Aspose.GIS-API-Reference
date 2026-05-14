---
title: "Geometry.Intersects"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. تحدد ما إذا كان هذا الشكل يتقاطع مع مدى محدد"
type: docs
weight: 280
url: /ar/net/aspose.gis.geometries/geometry/intersects/
---
## Intersects(Extent) {#intersects}

يحدد ما إذا كانت هذه الهندسة تتقاطع مع نطاق محدد.

```csharp
public bool Intersects(Extent extent)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| مدى | مدى | المدى. |

### قيمة الإرجاع

`true` إذا كان هذا الشكل يتقاطع مع المدى؛ `false` خلاف ذلك.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |

### انظر أيضًا

* method [Intersects](../../../aspose.gis/extent/intersects/)
* class [Extent](../../../aspose.gis/extent/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)

---

## Intersects(IGeometry) {#intersects_1}

يحدد ما إذا كانت هذه الهندسة وهندسة محددة تتقاطع.

```csharp
public bool Intersects(IGeometry other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | هندسة. |

### قيمة الإرجاع

`true` إذا كان هذا الشكل "يتقاطع مكانيًا" مع شكل آخر. `false` خلاف ذلك.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | إحدى الهندسات غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) الخاص بالهندسات غير متكافئ. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الهندسات إلى نفس نظام الإشارة المكانية. |

## ملاحظات

هذه الطريقة مكافئة لـ:

```csharp
!this.Disjoint(other);
```

هذا هو نفي [`Disjoint`](../../igeometry/disjoint/). راجع [`Disjoint`](../../igeometry/disjoint/) لمزيد من التفاصيل.

### انظر أيضًا

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


