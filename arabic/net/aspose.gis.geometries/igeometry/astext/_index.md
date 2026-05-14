---
title: "IGeometry.AsText"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "IGeometry طريقة. يترجم هذه الهندسة إلى تمثيل WellKnown Text الخاص بها"
type: docs
weight: 120
url: /ar/net/aspose.gis.geometries/igeometry/astext/
---
## AsText() {#astext}

يحوّل هذه الهندسة إلى تمثيلها بصيغة Well-Known Text.

```csharp
public string AsText()
```

### قيمة الإرجاع

تمثيل Well-Known Text لهذه الهندسة.

## ملاحظات

إخراج هذه الطريقة يكون في صيغة Iso WKT.

### انظر أيضًا

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
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
| NotSupportedException | الهندسة غير مدعومة من قبل صيغة WKT المطلوبة. الهندسات التالية مدعومة فقط بواسطة صيغة Iso WKT: [`CircularString`](../../circularstring/)[`CompoundCurve`](../../compoundcurve/)[`CurvePolygon`](../../curvepolygon/)[`MultiCurve`](../../multicurve/)[`MultiSurface`](../../multisurface/) جميع الهندسات الأخرى مدعومة بأي صيغة WKT. |
| ArgumentOutOfRangeException | *variant* ليس قيمة صالحة لـ [`WktVariant`](../../wktvariant/). |

### انظر أيضًا

* enum [WktVariant](../../wktvariant/)
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
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
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


