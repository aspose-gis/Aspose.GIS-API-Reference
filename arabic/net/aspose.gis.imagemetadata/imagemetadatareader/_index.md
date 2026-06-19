---
title: "الفئة ImageMetadataReader"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.ImageMetadata.ImageMetadataReader. فئة لتعديل وإضافة بعض علامات EXIF"
type: docs
weight: 3080
url: /ar/net/aspose.gis.imagemetadata/imagemetadatareader/
---
## ImageMetadataReader class

فئة لتحرير وإضافة بعض علامات EXIF

```csharp
public class ImageMetadataReader : IDisposable
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [GetReader](../../aspose.gis.imagemetadata/imagemetadatareader/getreader/#getreader)(Stream) | ينشئ مثيل قارئ لعلامات EXIF |
| static [GetReader](../../aspose.gis.imagemetadata/imagemetadatareader/getreader/#getreader_1)(string) | ينشئ مثيل قارئ لعلامات EXIF |
| [Dispose](../../aspose.gis.imagemetadata/imagemetadatareader/dispose/)() | تنفيذ عام لنمط Dispose يمكن استدعاؤه من قبل المستهلكين. |
| [ReadData](../../aspose.gis.imagemetadata/imagemetadatareader/readdata/)() | يستخرج جميع علامات EXIF المدعومة |
| [Save](../../aspose.gis.imagemetadata/imagemetadatareader/save/#save)(Stream) | حفظ التغييرات إلى تدفق منفصل |
| [Save](../../aspose.gis.imagemetadata/imagemetadatareader/save/#save_2)(string) | احفظ إلى ملف جديد لأن الملف الأصلي مقفل للتغييرات |
| [Save](../../aspose.gis.imagemetadata/imagemetadatareader/save/#save_1)(Stream, ImageFormat) | حفظ التغييرات إلى تدفق منفصل |
| [Save](../../aspose.gis.imagemetadata/imagemetadatareader/save/#save_3)(string, ImageFormat) | احفظ إلى ملف جديد لأن الملف الأصلي مقفل للتغييرات |
| [SetArtist](../../aspose.gis.imagemetadata/imagemetadatareader/setartist/)(string) | حفظ علامة EXIF Artist، إضافة أو استبدال البيانات. |
| [SetDescription](../../aspose.gis.imagemetadata/imagemetadatareader/setdescription/)(string) | حفظ علامة EXIF ImageDescription، إضافة أو استبدال البيانات. |
| [SetGeoLocation](../../aspose.gis.imagemetadata/imagemetadatareader/setgeolocation/)(double, double) | حفظ علامات EXIF GPSLatitudeRef و GPSLongitudeRef و GPSLatitude و GPSLongitude، إضافة أو استبدال البيانات. |
| [SetImageSize](../../aspose.gis.imagemetadata/imagemetadatareader/setimagesize/)(int, int) | حفظ علامات EXIF ImageWidth و ImageHeight، إضافة أو استبدال البيانات. |
| [SetModifyDate](../../aspose.gis.imagemetadata/imagemetadatareader/setmodifydate/)(DateTime) | حفظ علامة EXIF ModifyDate (DataTime)، إضافة أو استبدال البيانات. |
| [TryGetArtist](../../aspose.gis.imagemetadata/imagemetadatareader/trygetartist/)(out string) | يحاول العثور على علامة EXIF Artist، إذا لم تُعثر على العلامة يُعيد null. |
| [TryGetDescription](../../aspose.gis.imagemetadata/imagemetadatareader/trygetdescription/)(out string) | يحاول العثور على علامة EXIF ImageDescription، إذا لم تُعثر على العلامة يُعيد null. |
| [TryGetGeoLocation](../../aspose.gis.imagemetadata/imagemetadatareader/trygetgeolocation/)(out GeoLocation) | يحاول العثور على مجموعة علامات EXIF GPSLatitudeRef و GPSLongitudeRef و GPSLatitude و GPSLongitude، إذا لم تكن العلامات موجودة يُعيد null. |
| [TryGetImageSize](../../aspose.gis.imagemetadata/imagemetadatareader/trygetimagesize/)(out ImageSize) | يحاول العثور على مجموعة علامات EXIF ImageWidth و ImageHeight، إذا لم تكن العلامات موجودة يُعيد null. |
| [TryGetModifyDate](../../aspose.gis.imagemetadata/imagemetadatareader/trygetmodifydate/)(out DateTime) | يحاول العثور على علامة EXIF ModifyDate (DataTime)، إذا لم تُعثر على العلامة يُعيد قيمة DataTime الافتراضية. |

### انظر أيضًا

* namespace [Aspose.Gis.ImageMetadata](../../aspose.gis.imagemetadata/)
* assembly [Aspose.GIS](../../)


