---
title: "IGeometry.AsBinary"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. يترجم هذا الشكل إلى تمثيله الثنائي المعروف (WellKnown Binary)"
type: docs
weight: 100
url: /ar/net/aspose.gis.geometries/igeometry/asbinary/
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

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
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
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


