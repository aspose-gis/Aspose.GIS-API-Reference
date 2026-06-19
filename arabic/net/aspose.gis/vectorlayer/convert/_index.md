---
title: "VectorLayer.Convert"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة VectorLayer. تحويل طبقة إلى تنسيق مختلف."
type: docs
weight: 220
url: /ar/net/aspose.gis/vectorlayer/convert/
---
## Convert(string, FileDriver, string, FileDriver) {#convert_2}

تحويل طبقة إلى تنسيق مختلف.

```csharp
public static void Convert(string sourcePath, FileDriver sourceDriver, string destinationPath, 
    FileDriver destinationDriver)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | المسار إلى الطبقة التي سيتم تحويلها. |
| sourceDriver | FileDriver | سائق التنسيق للطبقة المصدر. |
| destinationPath | String | المسار إلى الطبقة التي سيتم إنشاؤها نتيجةً للتحويل. |
| destinationDriver | FileDriver | سائق التنسيق للطبقة الوجهة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | إحدى المسارات هي `null`. |

### انظر أيضًا

* class [FileDriver](../../filedriver/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Convert(AbstractPath, FileDriver, AbstractPath, FileDriver) {#convert}

تحويل طبقة إلى تنسيق مختلف.

```csharp
public static void Convert(AbstractPath sourcePath, FileDriver sourceDriver, 
    AbstractPath destinationPath, FileDriver destinationDriver)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | AbstractPath | المسار إلى الطبقة التي سيتم تحويلها. |
| sourceDriver | FileDriver | سائق التنسيق للطبقة المصدر. |
| destinationPath | AbstractPath | المسار إلى الطبقة التي سيتم إنشاؤها نتيجةً للتحويل. |
| destinationDriver | FileDriver | سائق التنسيق للطبقة الوجهة. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | إحدى المسارات هي `null`. |

### انظر أيضًا

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Convert(string, FileDriver, string, FileDriver, ConversionOptions) {#convert_3}

تحويل طبقة إلى تنسيق مختلف.

```csharp
public static void Convert(string sourcePath, FileDriver sourceDriver, string destinationPath, 
    FileDriver destinationDriver, ConversionOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | String | المسار إلى الطبقة التي سيتم تحويلها. |
| sourceDriver | FileDriver | سائق التنسيق للطبقة المصدر. |
| destinationPath | String | المسار إلى الطبقة التي سيتم إنشاؤها نتيجةً للتحويل. |
| destinationDriver | FileDriver | سائق التنسيق للطبقة الوجهة. |
| options | ConversionOptions | خيارات لإجراء التحويل. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | إحدى المسارات هي `null`. |
| ArgumentException | كائن Options له نوع غير صحيح لهذا السائق. |
| [GisException](../../gisexception/) | خطأ في قراءة أو كتابة الميزة من/إلى الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | نظام الإحداثيات المكانية المحدد في *options* غير مدعوم من قبل *destinationDriver*. |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception/) | فشل تحويل هندسة المميزات من نظام الإحداثيات المكانية المصدر إلى نظام الإحداثيات المكانية الهدف. |

### انظر أيضًا

* class [FileDriver](../../filedriver/)
* class [ConversionOptions](../../conversionoptions/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Convert(AbstractPath, FileDriver, AbstractPath, FileDriver, ConversionOptions) {#convert_1}

تحويل طبقة إلى تنسيق مختلف.

```csharp
public static void Convert(AbstractPath sourcePath, FileDriver sourceDriver, 
    AbstractPath destinationPath, FileDriver destinationDriver, ConversionOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sourcePath | AbstractPath | المسار إلى الطبقة التي سيتم تحويلها. |
| sourceDriver | FileDriver | سائق التنسيق للطبقة المصدر. |
| destinationPath | AbstractPath | المسار إلى الطبقة التي سيتم إنشاؤها نتيجةً للتحويل. |
| destinationDriver | FileDriver | سائق التنسيق للطبقة الوجهة. |
| options | ConversionOptions | خيارات لإجراء التحويل. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | إحدى المسارات هي `null`. |
| ArgumentException | كائن Options له نوع غير صحيح لهذا السائق. |
| [GisException](../../gisexception/) | خطأ في قراءة أو كتابة الميزة من/إلى الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | نظام الإحداثيات المكانية المحدد في *options* غير مدعوم من قبل *destinationDriver*. |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception/) | فشل تحويل هندسة المميزات من نظام الإحداثيات المكانية المصدر إلى نظام الإحداثيات المكانية الهدف. |

### انظر أيضًا

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [ConversionOptions](../../conversionoptions/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)


