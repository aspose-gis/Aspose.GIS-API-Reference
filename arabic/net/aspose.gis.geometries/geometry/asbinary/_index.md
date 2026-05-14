---
title: "Geometry.AsBinary"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. تُحوِّل هذه الهندسة إلى تمثيل WellKnown Binary الخاص بها"
type: docs
weight: 110
url: /ar/net/aspose.gis.geometries/geometry/asbinary/
---
## AsBinary() {#asbinary}

يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Binary.

```csharp
public byte[] AsBinary()
```

### قيمة الإرجاع

تمثيل Well-Known Binary لهذه الهندسة.

## ملاحظات

إخراج هذه الطريقة هو في متغيّر Iso WKB.

### انظر أيضًا

* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)

---

## AsBinary(WkbVariant) {#asbinary_1}

يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Binary.

```csharp
public byte[] AsBinary(WkbVariant variant)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| متغيّر | WkbVariant | متغيّر Well-Known Binary للاستخدام. |

### قيمة الإرجاع

تمثيل Well-Known Binary لهذه الهندسة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| NotSupportedException | لا يمكن تمثيل Geometry في متغيّر WKB المطلوب. يحدث هذا حاليًا عندما يكون [`HasCurveGeometry`](../hascurvegeometry/) الخاص بالهندسة `true` و متغيّر WKB هو SimpleFeatureAccessOutdated. |
| ArgumentOutOfRangeException | *variant* ليس متغيّرًا صالحًا لـ [`WkbVariant`](../../wkbvariant/). |

### انظر أيضًا

* enum [WkbVariant](../../wkbvariant/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


