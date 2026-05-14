---
title: "Geometry.Covers"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. تحدد ما إذا كانت هذه الهندسة تغطي هندسة محددة."
type: docs
weight: 160
url: /ar/net/aspose.gis.geometries/geometry/covers/
---
## Geometry.Covers method

يحدد ما إذا كانت هذه الهندسة تغطي هندسة محددة.

```csharp
public bool Covers(IGeometry other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | هندسة. |

### قيمة الإرجاع

`true` إذا كانت هذه الهندسة "تغطي مكانيًا" هندسة أخرى. `false` خلاف ذلك.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | إحدى الهندسات غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) الخاص بالهندسات غير متكافئ. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الهندسات إلى نفس نظام الإشارة المكانية. |

## ملاحظات

تختبر هذه الطريقة ما إذا كانت هندسة واحدة تغطي أخرى من حيث مصفوفة تقاطع DE-9IM. تغطي هندسة ما هندسة أخرى إذا كانت تحتوي كل نقطة من الهندسة الأخرى. هذه الطريقة مشابهة لـ [`SpatiallyContains`](../../igeometry/spatiallycontains/)، لكنها تُعيد `true` في كثير من الأحيان، لأنها لا تفرق بين النقاط الداخلية ونقاط الحدود. لذا، إذا كانت الهندسة A تقع على حد الهندسة B، فإن [`SpatiallyContains`](../../igeometry/spatiallycontains/) تُعيد `false`، بينما تُعيد هذه الطريقة `true`. هذه الطريقة مكافئة لـ:

```csharp
this.Relate(other, "T*****FF*") || this.Relate(other, "*T****FF*") || this.Relate(other, "***T**FF*) || this.Relate(other, "***T*FF*");
```

### انظر أيضًا

* method [SpatiallyContains](../../igeometry/spatiallycontains/)
* method [CoveredBy](../../igeometry/coveredby/)
* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


