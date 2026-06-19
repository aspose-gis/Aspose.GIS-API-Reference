---
title: "الفئة AbstractPath"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.AbstractPath. الـ AbstractPath هي فئة أساسية للفئات التي تحدد موقعًا فريدًا في بيئة تشبه نظام الملفات مثل نظام ملفات محلي أو تخزين ملفات عن بُعد أو أرشيف ZIP وغيرها."
type: docs
weight: 10
url: /ar/net/aspose.gis/abstractpath/
---
## AbstractPath class

`AbstractPath` هي فئة أساسية للفئات التي تحدد موقعًا فريدًا في بيئة مشابهة لنظام الملفات، مثل نظام ملفات محلي أو تخزين ملفات بعيد أو أرشيف ZIP، من بين أمور أخرى.

```csharp
public abstract class AbstractPath
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| abstract [Location](../../aspose.gis/abstractpath/location/) { get; } | يحصل على تمثيل نصي لموقع هذا `AbstractPath`. |
| abstract [Separator](../../aspose.gis/abstractpath/separator/) { get; } | يحصل على حرف الفاصل المستخدم لتقسيم مستويات الدليل في سلسلة [`Location`](./location/). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [FromLocalPath](../../aspose.gis/abstractpath/fromlocalpath/)(string) | ينشئ `AbstractPath` يمثل موقعًا على نظام الملفات المحلي. |
| static [FromStream](../../aspose.gis/abstractpath/fromstream/)(Stream) | ينشئ `AbstractPath` من تدفق (Stream). |
| virtual [Combine](../../aspose.gis/abstractpath/combine/)(string) | يجمع هذا `AbstractPath` مع مكونات المسار المحددة. |
| abstract [Delete](../../aspose.gis/abstractpath/delete/)() | يحذف ملفًا يشير إليه هذا المسار. |
| [GetExtension](../../aspose.gis/abstractpath/getextension/)() | يعيد امتداد هذا `AbstractPath`. |
| [GetFileName](../../aspose.gis/abstractpath/getfilename/)() | يعيد اسم الملف وامتداده لهذا `AbstractPath`. |
| [GetFileNameWithoutExtension](../../aspose.gis/abstractpath/getfilenamewithoutextension/)() | يعيد اسم الملف لهذا `AbstractPath` بدون الامتداد. |
| abstract [IsFile](../../aspose.gis/abstractpath/isfile/)() | يحصل على قيمة تشير إلى ما إذا كان هذا المسار يشير إلى ملف موجود يمكن فتحه للقراءة. |
| abstract [ListDirectory](../../aspose.gis/abstractpath/listdirectory/)() | يعيد المسارات الموجودة داخل هذا `AbstractPath`، إذا كان دليلًا. |
| abstract [Open](../../aspose.gis/abstractpath/open/)(FileAccess) | يفتح هذا `AbstractPath` كملف. |
| virtual [WithExtension](../../aspose.gis/abstractpath/withextension/)(string) | يعيد `AbstractPath` جديدًا مع تغيير امتداد الملف إلى القيمة المحددة. |

## ملاحظات

قد يحدد `AbstractPath` موقعًا على نظام ملفات محلي، أو موقعًا على نظام ملفات بعيد أو تخزينًا خارجيًا مثل تخزين Azure Blob، وما إلى ذلك. قد يشير الموقع إلى كائنات شبيهة بالملف موجودة أو غير موجودة، أو كائنات شبيهة بالدليل، أو قد يكون له أي معنى آخر معقول للبيئة التي ينتمي إليها. على سبيل المثال، يمكن للوارث من `AbstractPath` الذي يمثل موقعًا على نظام الملفات المحلي أن يشير إلى ملف موجود، أو دليل، أو إلى مكان في نظام الملفات لم يتم إنشاؤه بعد. لجعل تخزينًا شبيهًا بنظام الملفات متاحًا لـ `Aspose.GIS`، يجب وراثة هذه الفئة وتنفيذ طرقها المجردة.

### انظر أيضًا

* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


