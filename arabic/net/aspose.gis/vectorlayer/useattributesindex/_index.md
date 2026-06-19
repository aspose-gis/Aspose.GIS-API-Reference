---
title: "VectorLayer.UseAttributesIndex"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة VectorLayer. يحمل فهرس السمات لتسريع التصفية حسب قيمة السمات في طرق الفلترة مثل WhereGreater. إذا لم يكن الفهرس موجودًا ينشئه أولاً. استخدم forceRebuild لإجبار إعادة إنشاء الفهرس"
type: docs
weight: 200
url: /ar/net/aspose.gis/vectorlayer/useattributesindex/
---
## UseAttributesIndex(string, string, bool) {#useattributesindex_1}

يحمل فهرس السمات لتسريع التصفية حسب قيمة السمات في طرق الفلترة مثل [`WhereGreater`](../../featuressequence/wheregreater/). إذا لم يكن الفهرس موجودًا ينشئه أولاً. استخدم *forceRebuild* لإجبار إعادة إنشاء الفهرس.

```csharp
public void UseAttributesIndex(string indexPath, string attributeName, bool forceRebuild = false)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| indexPath | String | المسار إلى ملف الفهرس. |
| attributeName | String | اسم السمة التي سيُبنى عليها الفهرس. |
| forceRebuild | Boolean | ما إذا كان يجب إعادة إنشاء الفهرس حتى لو كان موجودًا بالفعل. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | السمة بهذا الاسم غير موجودة في الطبقة. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| InvalidOperationException | الفهرس للصفة المحددة محمّل بالفعل لهذه الطبقة. |
| [GisException](../../gisexception/) | الملف موجود وليس ملف فهرس سمات تم إنشاؤه بواسطة Aspose.GIS. |

### انظر أيضًا

* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## UseAttributesIndex(AbstractPath, string, bool) {#useattributesindex}

يحمل فهرس السمات لتسريع التصفية حسب قيمة السمات في طرق الفلترة مثل [`WhereGreater`](../../featuressequence/wheregreater/). إذا لم يكن الفهرس موجودًا ينشئه أولاً. استخدم *forceRebuild* لإجبار إعادة إنشاء الفهرس.

```csharp
public virtual void UseAttributesIndex(AbstractPath indexPath, string attributeName, 
    bool forceRebuild = false)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| indexPath | AbstractPath | المسار إلى ملف الفهرس. |
| attributeName | String | اسم السمة التي سيُبنى عليها الفهرس. |
| forceRebuild | Boolean | ما إذا كان يجب إعادة إنشاء الفهرس حتى لو كان موجودًا بالفعل. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| ArgumentException | السمة بهذا الاسم غير موجودة في الطبقة. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| InvalidOperationException | الفهرس للصفة المحددة محمّل بالفعل لهذه الطبقة. |
| [GisException](../../gisexception/) | الملف موجود وليس ملف فهرس سمات تم إنشاؤه بواسطة Aspose.GIS. |

### انظر أيضًا

* class [AbstractPath](../../abstractpath/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)


