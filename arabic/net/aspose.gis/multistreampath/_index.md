---
title: "الفئة MultiStreamPath"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.MultiStreamPath. هذه الفئة تعمل مع الصيغ التي تحتوي على عدة ملفات"
type: docs
weight: 3430
url: /ar/net/aspose.gis/multistreampath/
---
## MultiStreamPath class

هذه الفئة تعمل مع الصيغ التي تحتوي على عدة ملفات.

```csharp
public class MultiStreamPath : AbstractPath, IDisposable
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [MultiStreamPath](multistreampath/)(string, Dictionary&lt;string, Stream&gt;) | أنشئ مثيلًا من `MultiStreamPath`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| override [Location](../../aspose.gis/multistreampath/location/) { get; } | يحصل على تمثيل نصي لموقع هذا `AbstractPath`. |
| override [Separator](../../aspose.gis/multistreampath/separator/) { get; } | يحصل على حرف الفاصل المستخدم لتقسيم مستويات الدليل في سلسلة [`Location`](./location/). |
| [StreamSet](../../aspose.gis/multistreampath/streamset/) { get; } | مجموعة من التدفقات الفعلية التي تم ربطها بأسماء الملفات. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [Combine](../../aspose.gis/abstractpath/combine/)(string) | يجمع هذا [`AbstractPath`](../abstractpath/) مع مكوّنات المسار المحددة. |
| override [Delete](../../aspose.gis/multistreampath/delete/)() | يحذف ملفًا يشير إليه هذا المسار. |
| [Dispose](../../aspose.gis/multistreampath/dispose/)() | يدمر الكائن ومحتوياته. |
| [GetExtension](../../aspose.gis/abstractpath/getextension/)() | يعيد الامتداد لهذا [`AbstractPath`](../abstractpath/). |
| [GetFileName](../../aspose.gis/abstractpath/getfilename/)() | يعيد اسم الملف والامتداد لهذا [`AbstractPath`](../abstractpath/). |
| [GetFileNameWithoutExtension](../../aspose.gis/abstractpath/getfilenamewithoutextension/)() | يعيد اسم الملف لهذا [`AbstractPath`](../abstractpath/) بدون الامتداد. |
| override [IsFile](../../aspose.gis/multistreampath/isfile/)() | يحصل على قيمة تشير إلى ما إذا كان هذا المسار يشير إلى ملف موجود يمكن فتحه للقراءة. |
| override [ListDirectory](../../aspose.gis/multistreampath/listdirectory/)() | يعيد المسارات الموجودة داخل هذا `AbstractPath`، إذا كان دليلًا. |
| override [Open](../../aspose.gis/multistreampath/open/)(FileAccess) | يُجرد مجموعة من صيغ الملفات المتعددة المفتوحة المتدفقة كمسار للوصول إلى البيانات. |
| virtual [WithExtension](../../aspose.gis/abstractpath/withextension/)(string) | يعيد [`AbstractPath`](../abstractpath/) جديدًا مع تغيير امتداد الملف إلى القيمة المحددة. |

### انظر أيضًا

* class [AbstractPath](../abstractpath/)
* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


