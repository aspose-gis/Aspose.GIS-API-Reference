---
title: "IGeometry.Covers"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. تحدد ما إذا كانت هذه الهندسة تغطي هندسة محددة"
type: docs
weight: 150
url: /ar/net/aspose.gis.geometries/igeometry/covers/
---
## IGeometry.Covers method

يحدد ما إذا كانت هذه الـ geometry تغطي هندسة محددة.

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
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem/) للهندسات غير متكافئة. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الهندسات إلى نظام إسناد مكاني موحد. |

## ملاحظات

تختبر هذه الطريقة ما إذا كانت هندسة واحدة تغطي أخرى وفقًا لمصفوفة تقاطع DE-9IM. تغطي هندسة واحدة أخرى إذا كانت تحتوي على كل نقطة من الهندسة الأخرى. هذه الطريقة مشابهة لـ[`SpatiallyContains`](../spatiallycontains/)، لكنها تُعيد `true` في كثير من الأحيان، لأنها لا تميز بين النقاط الداخلية والنقاط الحدية. لذا، إذا كانت الهندسة A تقع على حد الهندسة B، فإن [`SpatiallyContains`](../spatiallycontains/) تُعيد `false`، بينما تُعيد هذه الطريقة `true`. هذه الطريقة مكافئة لـ:

```csharp
this.Relate(other, "T*****FF*") || this.Relate(other, "*T****FF*") || this.Relate(other, "***T**FF*) || this.Relate(other, "***T*FF*");
```

### انظر أيضًا

* method [SpatiallyContains](../spatiallycontains/)
* method [CoveredBy](../coveredby/)
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


