---
title: "Geometry.AsText"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. تُحوِّل هذه الهندسة إلى تمثيل النص المعروف WellKnown Text الخاص بها"
type: docs
weight: 130
url: /ar/net/aspose.gis.geometries/geometry/astext/
---
## AsText() {#astext}

يحوّل هذه الـ geometry إلى تمثيل Well-Known Text الخاص بها.

```csharp
public string AsText()
```

### قيمة الإرجاع

تمثيل النص المعروف Well-Known Text لهذه الهندسة.

## ملاحظات

مخرجات هذه الطريقة تكون بصيغة Iso WKT. التنسيق الرقمي الافتراضي هو [`General`](../../../aspose.gis/numericformat/general/) (بدقة "0").

### انظر أيضًا

* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
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
| NotSupportedException | لا يمكن تمثيل الهندسة في متغيّر WKT المطلوب. يحدث هذا حاليًا عندما يكون [`HasCurveGeometry`](../hascurvegeometry/) الخاص بالهندسة `true` ومتغيّر WKT هو SimpleFeatureAccessOutdated. |
| ArgumentOutOfRangeException | *variant* ليس متغيّر [`WktVariant`](../../wktvariant/) صالح. |

## ملاحظات

تنسيق الأرقام الافتراضي هو [`General`](../../../aspose.gis/numericformat/general/) (بدقة "0").

### انظر أيضًا

* enum [WktVariant](../../wktvariant/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
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
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


