---
title: "Geometry.AsText"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. تُحوِّل هذه الهندسة إلى تمثيل Well-Known Text الخاص بها"
type: docs
weight: 130
url: /ar/net/aspose.gis.geometries/geometry/astext/
---
## AsText() {#astext}

يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Text.

```csharp
public string AsText()
```

### قيمة الإرجاع

تمثيل Well-Known Text لهذه الهندسة.

## ملاحظات

مخرجات هذه الطريقة تكون بصيغة Iso WKT. التنسيق الرقمي الافتراضي هو [`General`](../../../aspose.gis/numericformat/general/) (بدقة "0").

### انظر أيضًا

* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)

---

## AsText(WktVariant) {#astext_1}

يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Text.

```csharp
public string AsText(WktVariant variant)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| متغيّر | WktVariant | متغيّر Well-Known Text المراد استخدامه. |

### قيمة الإرجاع

تمثيل Well-Known Text لهذه الهندسة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| NotSupportedException | لا يمكن تمثيل الهندسة في صيغة WKT المطلوبة. يحدث هذا حاليًا عندما تكون خاصية [`HasCurveGeometry`](../hascurvegeometry/) للهندسة `true` وتكون صيغة WKT هي SimpleFeatureAccessOutdated. |
| ArgumentOutOfRangeException | *variant* ليس قيمة صالحة لـ [`WktVariant`](../../wktvariant/). |

## ملاحظات

تنسيق الأرقام الافتراضي هو [`General`](../../../aspose.gis/numericformat/general/) (بدقة "0").

### انظر أيضًا

* enum [WktVariant](../../wktvariant/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)

---

## AsText(WktVariant, NumericFormat) {#astext_2}

يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Text.

```csharp
public string AsText(WktVariant variant, NumericFormat format)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| متغيّر | WktVariant | متغيّر Well-Known Text المراد استخدامه. |
| format | NumericFormat | تنسيق الإحداثيات للتحويل إلى سلسلة. راجع [`NumericFormat`](../../../aspose.gis/numericformat/) للحصول عليه. |

### قيمة الإرجاع

تمثيل Well-Known Text لهذه الهندسة.

### استثناءات

| استثناء | شرط |
| --- | --- |
| NotSupportedException | لا يمكن تمثيل الهندسة في صيغة WKT المطلوبة. يحدث هذا حاليًا عندما تكون خاصية [`HasCurveGeometry`](../hascurvegeometry/) للهندسة `true` وتكون صيغة WKT هي SimpleFeatureAccessOutdated. |
| ArgumentOutOfRangeException | *variant* ليس قيمة صالحة لـ [`WktVariant`](../../wktvariant/). |

### انظر أيضًا

* enum [WktVariant](../../wktvariant/)
* class [NumericFormat](../../../aspose.gis/numericformat/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


