---
title: "ImageMetadataReader.GetReader"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة ImageMetadataReader. إنشاء مثيل قارئ لوسوم EXIF"
type: docs
weight: 10
url: /ar/net/aspose.gis.imagemetadata/imagemetadatareader/getreader/
---
## GetReader(string) {#getreader_1}

ينشئ مثيل قارئ لعلامات EXIF

```csharp
public static ImageMetadataReader GetReader(string fileName)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| fileName | String | الاسم الكامل لملف الصورة. |

### قيمة الإرجاع

مثيل قارئ البيانات الوصفية

## ملاحظات

سيتم قفل ملف الصورة للتغييرات حتى يتم تنفيذ Dispose الخاص بالقارئ.

### انظر أيضًا

* class [ImageMetadataReader](../)
* namespace [Aspose.Gis.ImageMetadata](../../imagemetadatareader/)
* assembly [Aspose.GIS](../../../)

---

## GetReader(Stream) {#getreader}

ينشئ مثيل قارئ لعلامات EXIF

```csharp
public static ImageMetadataReader GetReader(Stream stream)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| تدفق | تدفق | تدفق مصدر بيانات الصورة |

### قيمة الإرجاع

مثيل قارئ البيانات الوصفية

## ملاحظات

من المهم عدم إغلاق تدفق المصدر حتى يتم تنفيذ Dispose الخاص بالقارئ.

### انظر أيضًا

* class [ImageMetadataReader](../)
* namespace [Aspose.Gis.ImageMetadata](../../imagemetadatareader/)
* assembly [Aspose.GIS](../../../)


