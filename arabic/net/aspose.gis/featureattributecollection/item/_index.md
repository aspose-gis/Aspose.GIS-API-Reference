---
title: "FeatureAttributeCollection.Item"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "خاصية FeatureAttributeCollection. يحصل أو يضبط الـ FeatureAttribute عند الفهرس المحدد"
type: docs
weight: 30
url: /ar/net/aspose.gis/featureattributecollection/item/
---
## FeatureAttributeCollection indexer (1 of 2)

يحصل أو يضبط الـ [`FeatureAttribute`](../../featureattribute/) عند الفهرس المحدد.

```csharp
public FeatureAttribute this[int index] { get; set; }
```

| معامل | الوصف |
| --- | --- |
| فهرس | الفهرس الصفري للسمة التي يتم الحصول عليها أو ضبطها. |

### قيمة الإرجاع

السمة عند الفهرس المحدد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | الفهرس خارج النطاق. |
| InvalidOperationException | محاولة تعديل مجموعة مقفلة. |

### انظر أيضًا

* class [FeatureAttribute](../../featureattribute/)
* class [FeatureAttributeCollection](../)
* namespace [Aspose.Gis](../../featureattributecollection/)
* assembly [Aspose.GIS](../../../)

---

## FeatureAttributeCollection indexer (2 of 2)

يحصل أو يضبط الـ [`FeatureAttribute`](../../featureattribute/) بالاسم المحدد.

```csharp
public FeatureAttribute this[string name] { get; }
```

| معامل | الوصف |
| --- | --- |
| الاسم | اسم السمات. |

### قيمة الإرجاع

السمة بالاسم المحدد، أو `null` إذا لم يتم العثور عليها.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | اسم السمة هو `null`. |

### انظر أيضًا

* class [FeatureAttribute](../../featureattribute/)
* class [FeatureAttributeCollection](../)
* namespace [Aspose.Gis](../../featureattributecollection/)
* assembly [Aspose.GIS](../../../)


