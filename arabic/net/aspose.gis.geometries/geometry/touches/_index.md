---
title: "Geometry.Touches"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. تحدد ما إذا كانت هذه الهندسة وهندسة محددة تلامسان"
type: docs
weight: 430
url: /ar/net/aspose.gis.geometries/geometry/touches/
---
## Geometry.Touches method

يحدد ما إذا كانت هذه الهندسة وهندسة محددة تلامسان.

```csharp
public bool Touches(IGeometry other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| آخر | IGeometry | هندسة. |

### قيمة الإرجاع

`true` إذا كانت هذه الهندسة "تلامس مكانيًا" هندسة أخرى. `false` خلاف ذلك.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | إحدى الهندسات غير صالحة بطريقة تجعل العملية لا يمكن إكمالها. |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) للهندسات غير متكافئة. يمكنك استخدام [`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) لتحويل الهندسات إلى نفس نظام الإسناد المكاني. |

## ملاحظات

تختبر هذه الطريقة ما إذا كانت الهندسات تلامس بعضها البعض وفقًا لمصفوفة تقاطع DE-9IM. تلامس هندستان بعضها إذا كان لديهما نقطة حد واحدة على الأقل مشتركة، ولكن لا نقاط داخلية. أي: يلامس اثنان من [`LineString`](../../linestring/) بعضهما إذا شاركا نقطة نهائية، ولكن لا يشتركان في مقطع، وتلامس مضلعان بعضهما إذا شاركا جزءًا من الحلقة الخارجية أو الداخلية، ولكن لا تتداخل داخلياتهما. هذه الطريقة مكافئة لـ:

```csharp
this.Relate(other, "FT*******") || this.Relate(other, "F**T*****") || this.Relate(other, "F***T****");
```

انظر مواصفة OpenGIS Simple Features لمزيد من التفاصيل حول DE-9IM وعلاقة "التلامس المكاني".

### انظر أيضًا

* interface [IGeometry](../../igeometry/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


