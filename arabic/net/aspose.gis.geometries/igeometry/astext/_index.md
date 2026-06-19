---
title: "IGeometry.AsText"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. تُحوِّل هذه الهندسة إلى تمثيل WellKnown Text الخاص بها"
type: docs
weight: 120
url: /ar/net/aspose.gis.geometries/igeometry/astext/
---
## AsText() {#astext}

يحوّل هذه الـ geometry إلى تمثيل Well-Known Text الخاص بها.

```csharp
public string AsText()
```

### قيمة الإرجاع

تمثيل النص المعروف Well-Known Text لهذه الهندسة.

## ملاحظات

إخراج هذه الطريقة يكون بصيغة Iso WKT.

### انظر أيضًا

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)

---

## AsText(WktVariant) {#astext_1}

يحوّل هذه الـ geometry إلى تمثيل Well-Known Text الخاص بها.

```csharp
public string AsText(WktVariant variant)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| نسخة | WktVariant | متغيّر Well-Known Text لاستخدامه. |

### قيمة الإرجاع

تمثيل النص المعروف Well-Known Text لهذه الهندسة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| NotSupportedException | هذه الهندسة غير مدعومة من قبل صيغة WKT المطلوبة. الهندسات التالية مدعومة فقط بصيغة Iso WKT: [`CircularString`](../../circularstring/)[`CompoundCurve`](../../compoundcurve/)[`CurvePolygon`](../../curvepolygon/)[`MultiCurve`](../../multicurve/)[`MultiSurface`](../../multisurface/) جميع الهندسات الأخرى مدعومة بأي صيغة WKT. |
| ArgumentOutOfRangeException | *variant* ليس متغيّر [`WktVariant`](../../wktvariant/) صالح. |

### انظر أيضًا

* enum [WktVariant](../../wktvariant/)
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)

---

## AsText(WktVariant, NumericFormat) {#astext_2}

يحوّل هذه الـ geometry إلى تمثيل Well-Known Text الخاص بها.

```csharp
public string AsText(WktVariant variant, NumericFormat format)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| نسخة | WktVariant | متغيّر Well-Known Text لاستخدامه. |
| format | NumericFormat | تنسيق الإحداثيات للتحويل إلى سلسلة. راجع [`NumericFormat`](../../../aspose.gis/numericformat/) للحصول عليه. |

### قيمة الإرجاع

تمثيل النص المعروف Well-Known Text لهذه الهندسة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| NotSupportedException | لا يمكن تمثيل الهندسة في متغيّر WKT المطلوب. يحدث هذا حاليًا عندما يكون [`HasCurveGeometry`](../hascurvegeometry/) الخاص بالهندسة `true` ومتغيّر WKT هو SimpleFeatureAccessOutdated. |
| ArgumentOutOfRangeException | *variant* ليس متغيّر [`WktVariant`](../../wktvariant/) صالح. |

### انظر أيضًا

* enum [WktVariant](../../wktvariant/)
* class [NumericFormat](../../../aspose.gis/numericformat/)
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


