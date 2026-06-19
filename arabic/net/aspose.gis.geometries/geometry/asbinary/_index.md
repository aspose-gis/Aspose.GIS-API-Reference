---
title: "Geometry.AsBinary"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. تُحوِّل هذه الهندسة إلى تمثيل WellKnown Binary الخاص بها"
type: docs
weight: 110
url: /ar/net/aspose.gis.geometries/geometry/asbinary/
---
## AsBinary() {#asbinary}

يحوّل هذه الـ geometry إلى تمثيل Well-Known Binary الخاص بها.

```csharp
public byte[] AsBinary()
```

### قيمة الإرجاع

تمثيل Well-Known Binary لهذه الهندسة.

## ملاحظات

إخراج هذه الطريقة يكون في نسخة Iso WKB.

### انظر أيضًا

* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)

---

## AsBinary(WkbVariant) {#asbinary_1}

يحوّل هذه الـ geometry إلى تمثيل Well-Known Binary الخاص بها.

```csharp
public byte[] AsBinary(WkbVariant variant)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| نسخة | WkbVariant | نسخة Well-Known Binary للاستخدام. |

### قيمة الإرجاع

تمثيل Well-Known Binary لهذه الهندسة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| NotSupportedException | لا يمكن تمثيل Geometry في نسخة WKB المطلوبة. يحدث هذا حالياً عندما يكون [`HasCurveGeometry`](../hascurvegeometry/) الخاص بالهندسة `true` وتكون نسخة WKB هي SimpleFeatureAccessOutdated. |
| ArgumentOutOfRangeException | *variant* ليست قيمة صالحة لـ [`WkbVariant`](../../wkbvariant/). |

### انظر أيضًا

* enum [WkbVariant](../../wkbvariant/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


