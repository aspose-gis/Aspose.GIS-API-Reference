---
title: "IGeometry.AsBinary"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. تُحوّل هذه الهندسة إلى تمثيلها الثنائي المعروف (WellKnown Binary)"
type: docs
weight: 100
url: /ar/net/aspose.gis.geometries/igeometry/asbinary/
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

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
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
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


