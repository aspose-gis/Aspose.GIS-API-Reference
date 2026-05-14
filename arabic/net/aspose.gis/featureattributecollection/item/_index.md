---
title: "FeatureAttributeCollection.Item"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "خاصية FeatureAttributeCollection. تحصل أو تعيين FeatureAttribute في الفهرس المحدد"
type: docs
weight: 30
url: /ar/net/aspose.gis/featureattributecollection/item/
---
## FeatureAttributeCollection indexer (1 of 2)

تحصل أو تعيين [`FeatureAttribute`](../../featureattribute/) في الفهرس المحدد.

```csharp
public FeatureAttribute this[int index] { get; set; }
```

| معامل | الوصف |
| --- | --- |
| الفهرس | الفهرس الصفري للسمة للحصول عليها أو تعيينها. |

### قيمة الإرجاع

السمة في الفهرس المحدد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | المؤشر خارج النطاق. |
| InvalidOperationException | محاولة تعديل مجموعة مقفلة. |

### انظر أيضًا

* class [FeatureAttribute](../../featureattribute/)
* class [FeatureAttributeCollection](../)
* namespace [Aspose.Gis](../../featureattributecollection/)
* assembly [Aspose.GIS](../../../)

---

## FeatureAttributeCollection indexer (2 of 2)

تحصل أو تعيين [`FeatureAttribute`](../../featureattribute/) بالاسم المحدد.

```csharp
public FeatureAttribute this[string name] { get; }
```

| معامل | الوصف |
| --- | --- |
| الاسم | اسم السمات. |

### قيمة الإرجاع

السمة بالاسم المحدد، أو `null` إذا لم تُعثر عليها.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | اسم السمة هو `null`. |

### انظر أيضًا

* class [FeatureAttribute](../../featureattribute/)
* class [FeatureAttributeCollection](../)
* namespace [Aspose.Gis](../../featureattributecollection/)
* assembly [Aspose.GIS](../../../)


