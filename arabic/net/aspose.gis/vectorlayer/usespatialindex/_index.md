---
title: "VectorLayer.UseSpatialIndex"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة VectorLayer. يحمل الفهرس المكاني لتسريع الترشيح حسب قيمة السمات في طرق الفلترة مثل WhereIntersects و NearestTo. إذا لم يكن الفهرس موجودًا ينشئه أولاً. استخدم forceRebuild لإجبار إعادة إنشاء الفهرس"
type: docs
weight: 210
url: /ar/net/aspose.gis/vectorlayer/usespatialindex/
---
## UseSpatialIndex(string, bool) {#usespatialindex_1}

يقوم بتحميل الفهرس المكاني لتسريع الترشيح حسب قيمة السمات في طرق الفلترة مثل [`WhereIntersects`](../../featuressequence/whereintersects/) و [`NearestTo`](../nearestto/). إذا لم يكن الفهرس موجودًا يتم إنشاؤه أولاً. استخدم *forceRebuild* لإجبار إعادة إنشاء الفهرس.

```csharp
public void UseSpatialIndex(string indexPath, bool forceRebuild = false)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| indexPath | String | المسار إلى ملف الفهرس. |
| forceRebuild | Boolean | ما إذا كان يجب إعادة إنشاء الفهرس حتى وإن كان موجودًا بالفعل. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المسار هو `null`. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| InvalidOperationException | الفهرس المكاني محمّل بالفعل لهذه الطبقة. |
| [GisException](../../gisexception/) | الملف موجود وليس ملف فهرس مكاني تم إنشاؤه بواسطة Aspose.GIS. |

### انظر أيضًا

* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## UseSpatialIndex(AbstractPath, bool) {#usespatialindex}

يقوم بتحميل الفهرس المكاني لتسريع الترشيح حسب قيمة السمات في طرق الفلترة مثل [`WhereIntersects`](../../featuressequence/whereintersects/) و [`NearestTo`](../nearestto/). إذا لم يكن الفهرس موجودًا يتم إنشاؤه أولاً. استخدم *forceRebuild* لإجبار إعادة إنشاء الفهرس.

```csharp
public virtual void UseSpatialIndex(AbstractPath indexPath, bool forceRebuild = false)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| indexPath | AbstractPath | المسار إلى ملف الفهرس. |
| forceRebuild | Boolean | ما إذا كان يجب إعادة إنشاء الفهرس حتى وإن كان موجودًا بالفعل. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المسار هو `null`. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| InvalidOperationException | الفهرس المكاني محمّل بالفعل لهذه الطبقة. |
| [GisException](../../gisexception/) | الملف موجود وليس ملف فهرس مكاني تم إنشاؤه بواسطة Aspose.GIS. |

### انظر أيضًا

* class [AbstractPath](../../abstractpath/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)


