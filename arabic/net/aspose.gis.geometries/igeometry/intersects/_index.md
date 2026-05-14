---
title: "IGeometry.Intersects"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. يحدد ما إذا كان هذا الشكل يتقاطع مع نطاق محدد"
type: docs
weight: 270
url: /ar/net/aspose.gis.geometries/igeometry/intersects/
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
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
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
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) للأشكال غير متكافئة. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الأشكال إلى نفس نظام الإسناد المكاني. |

## ملاحظات

هذه الطريقة مكافئة لـ:

```csharp
!this.Disjoint(other);
```

هذا هو نفي [`Disjoint`](../disjoint/). راجع [`Disjoint`](../disjoint/) لمزيد من التفاصيل.

### انظر أيضًا

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


