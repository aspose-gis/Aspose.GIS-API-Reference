---
title: "FeaturesSequence.SaveTo"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة FeaturesSequence. تحفظ تسلسل العناصر إلى الطبقة"
type: docs
weight: 50
url: /ar/net/aspose.gis/featuressequence/saveto/
---
## SaveTo(string, FileDriver) {#saveto_2}

يحفظ تسلسل الميزات إلى الطبقة.

```csharp
public void SaveTo(string destinationPath, FileDriver destinationDriver)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| destinationPath | String | المسار إلى طبقة الإخراج. |
| destinationDriver | FileDriver | برنامج تشغيل التنسيق لطبقة الإخراج. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | أي وسيط هو `null`. |
| [GisException](../../gisexception/) | خطأ في قراءة أو كتابة العنصر من/إلى الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception/) | فشل تحويل هندسة العناصر من نظام الإحداثيات المكانية المصدر إلى نظام الإحداثيات المكانية الهدف. |

### انظر أيضًا

* class [FileDriver](../../filedriver/)
* class [FeaturesSequence](../)
* namespace [Aspose.Gis](../../featuressequence/)
* assembly [Aspose.GIS](../../../)

---

## SaveTo(AbstractPath, FileDriver) {#saveto}

يحفظ تسلسل الميزات إلى الطبقة.

```csharp
public void SaveTo(AbstractPath destinationPath, FileDriver destinationDriver)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| destinationPath | AbstractPath | المسار إلى طبقة الإخراج. |
| destinationDriver | FileDriver | برنامج تشغيل التنسيق لطبقة الإخراج. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| [GisException](../../gisexception/) | خطأ في قراءة أو كتابة العنصر من/إلى الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception/) | فشل تحويل هندسة العناصر من نظام الإحداثيات المكانية المصدر إلى نظام الإحداثيات المكانية الهدف. |

### انظر أيضًا

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [FeaturesSequence](../)
* namespace [Aspose.Gis](../../featuressequence/)
* assembly [Aspose.GIS](../../../)

---

## SaveTo(string, FileDriver, SavingOptions) {#saveto_3}

يحفظ تسلسل الميزات إلى الطبقة.

```csharp
public void SaveTo(string destinationPath, FileDriver destinationDriver, SavingOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| destinationPath | String | المسار إلى طبقة الإخراج. |
| destinationDriver | FileDriver | برنامج تشغيل التنسيق لطبقة الإخراج. |
| الخيارات | SavingOptions | خيارات عملية الحفظ. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| [GisException](../../gisexception/) | خطأ في قراءة أو كتابة العنصر من/إلى الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception/) | فشل تحويل هندسة العناصر من نظام الإحداثيات المكانية المصدر إلى نظام الإحداثيات المكانية الهدف. |
| NotSupportedException | نظام الإحداثيات المكانية المحدد في *options* غير مدعوم من قبل *destinationDriver*. |

### انظر أيضًا

* class [FileDriver](../../filedriver/)
* class [SavingOptions](../../savingoptions/)
* class [FeaturesSequence](../)
* namespace [Aspose.Gis](../../featuressequence/)
* assembly [Aspose.GIS](../../../)

---

## SaveTo(AbstractPath, FileDriver, SavingOptions) {#saveto_1}

يحفظ تسلسل الميزات إلى الطبقة.

```csharp
public void SaveTo(AbstractPath destinationPath, FileDriver destinationDriver, 
    SavingOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| destinationPath | AbstractPath | المسار إلى طبقة الإخراج. |
| destinationDriver | FileDriver | برنامج تشغيل التنسيق لطبقة الإخراج. |
| الخيارات | SavingOptions | خيارات عملية الحفظ. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| [GisException](../../gisexception/) | خطأ في قراءة أو كتابة العنصر من/إلى الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception/) | فشل تحويل هندسة العناصر من نظام الإحداثيات المكانية المصدر إلى نظام الإحداثيات المكانية الهدف. |
| NotSupportedException | نظام الإحداثيات المكانية المحدد في *options* غير مدعوم من قبل *destinationDriver*. |

### انظر أيضًا

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [SavingOptions](../../savingoptions/)
* class [FeaturesSequence](../)
* namespace [Aspose.Gis](../../featuressequence/)
* assembly [Aspose.GIS](../../../)


