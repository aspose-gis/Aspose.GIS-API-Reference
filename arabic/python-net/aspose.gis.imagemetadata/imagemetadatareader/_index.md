---
title: "الفئة ImageMetadataReader"
type: docs
weight: 30
url: /ar/python-net/aspose.gis.imagemetadata/imagemetadatareader/
---

**Summary:** Class for editing, adding some EXIF tags

**Module:** [aspose.gis.imagemetadata](/psd/python-net/aspose.gis.imagemetadata/)

**Full Name:** aspose.gis.imagemetadata.ImageMetadataReader

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_reader(file_name)](#get_reader_file_name_1) | ينشئ مثيل قارئ لعلامات EXIF |
| [get_reader(stream)](#get_reader_stream_2) | ينشئ مثيل قارئ لعلامات EXIF |
| [read_data()](#read_data__3) | يستخرج جميع علامات EXIF المدعومة |
| [save(file_name)](#save_file_name_4) | احفظ إلى ملف جديد لأن الملف الأصلي مقفل للتغييرات |
| [save(file_name, format)](#save_file_name_format_5) | احفظ إلى ملف جديد لأن الملف الأصلي مقفل للتغييرات |
| [save(stream)](#save_stream_6) | حفظ التغييرات إلى تدفق منفصل |
| [save(stream, format)](#save_stream_format_7) | حفظ التغييرات إلى تدفق منفصل |
| [set_artist(artist)](#set_artist_artist_8) | حفظ علامة EXIF Artist، إضافة أو استبدال البيانات. |
| [set_description(description)](#set_description_description_9) | حفظ علامة EXIF ImageDescription، إضافة أو استبدال البيانات. |
| [set_geo_location(latitude, longitude)](#set_geo_location_latitude_longitude_10) | حفظ علامات EXIF GPSLatitudeRef و GPSLongitudeRef و GPSLatitude و GPSLongitude، إضافة أو استبدال البيانات. |
| [set_image_size(width, height)](#set_image_size_width_height_11) | حفظ علامات EXIF ImageWidth و ImageHeight، إضافة أو استبدال البيانات. |
| [set_modify_date(modify_date)](#set_modify_date_modify_date_12) | حفظ علامة EXIF ModifyDate (DataTime)، إضافة أو استبدال البيانات. |
| [try_get_artist(artist)](#try_get_artist_artist_13) | يحاول العثور على علامة EXIF Artist، إذا لم يتم العثور على العلامة يُعيد null |
| [try_get_description(description)](#try_get_description_description_14) | يحاول العثور على علامة EXIF ImageDescription، إذا لم يتم العثور على العلامة يُعيد null |
| [try_get_geo_location(geo_location)](#try_get_geo_location_geo_location_15) | يحاول العثور على مجموعة علامات EXIF GPSLatitudeRef و GPSLongitudeRef و GPSLatitude و GPSLongitude، إذا لم تكن العلامات موجودة يُعيد null |
| [try_get_image_size(image_size)](#try_get_image_size_image_size_16) | يحاول العثور على مجموعة علامات EXIF ImageWidth و ImageHeight، إذا لم تكن العلامات موجودة يُعيد null |
| [try_get_modify_date(modify_date)](#try_get_modify_date_modify_date_17) | يحاول العثور على علامة EXIF ModifyDate (DataTime)، إذا لم يتم العثور على العلامة يُعيد القيمة الافتراضية لـ DataTime |


### Method: get_reader(file_name)  [static] {#get_reader_file_name_1}


```
 get_reader(file_name) 
```

ينشئ مثيل قارئ لعلامات EXIF

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| file_name | string | الاسم الكامل لملف الصورة. |

**Returns**

| نوع | وصف |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | مثيل قارئ البيانات الوصفية |


### Method: get_reader(stream)  [static] {#get_reader_stream_2}


```
 get_reader(stream) 
```

ينشئ مثيل قارئ لعلامات EXIF

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | دفق مصدر بيانات الصورة |

**Returns**

| نوع | وصف |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | مثيل قارئ البيانات الوصفية |


### Method: read_data() {#read_data__3}


```
 read_data() 
```

يستخرج جميع علامات EXIF المدعومة

**Returns**

| نوع | وصف |
| :- | :- |
| [ImageData](/psd/python-net/aspose.gis.imagemetadata/imagedata) | ImageData التي تمثل مجموعة العلامات المدعومة |


### Method: save(file_name) {#save_file_name_4}


```
 save(file_name) 
```

احفظ إلى ملف جديد لأن الملف الأصلي مقفل للتغييرات

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| file_name | string | الاسم الكامل للملف الوجهة |

### Method: save(file_name, format) {#save_file_name_format_5}


```
 save(file_name, format) 
```

احفظ إلى ملف جديد لأن الملف الأصلي مقفل للتغييرات

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| file_name | string | الاسم الكامل للملف الوجهة |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | يحدد التنسيق للحفظ |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

حفظ التغييرات إلى تدفق منفصل

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | دفق الوجهة |

### Method: save(stream, format) {#save_stream_format_7}


```
 save(stream, format) 
```

حفظ التغييرات إلى تدفق منفصل

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| دفق | _io.BufferedRandom | دفق الوجهة |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | يحدد التنسيق للحفظ |

### Method: set_artist(artist) {#set_artist_artist_8}


```
 set_artist(artist) 
```

حفظ علامة EXIF Artist، إضافة أو استبدال البيانات.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الفنان | string | الفنان. |

### Method: set_description(description) {#set_description_description_9}


```
 set_description(description) 
```

حفظ علامة EXIF ImageDescription، إضافة أو استبدال البيانات.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الوصف | string | الوصف. |

### Method: set_geo_location(latitude, longitude) {#set_geo_location_latitude_longitude_10}


```
 set_geo_location(latitude, longitude) 
```

حفظ علامات EXIF GPSLatitudeRef و GPSLongitudeRef و GPSLatitude و GPSLongitude، إضافة أو استبدال البيانات.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| خط العرض | double | خط العرض. |
| خط الطول | double | خط الطول. |

### Method: set_image_size(width, height) {#set_image_size_width_height_11}


```
 set_image_size(width, height) 
```

حفظ علامات EXIF ImageWidth و ImageHeight، إضافة أو استبدال البيانات.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| width | int | العرض. |
| الارتفاع | int | الارتفاع. |

### Method: set_modify_date(modify_date) {#set_modify_date_modify_date_12}


```
 set_modify_date(modify_date) 
```

حفظ علامة EXIF ModifyDate (DataTime)، إضافة أو استبدال البيانات.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| modify_date | datetime | تاريخ التعديل. |

### Method: try_get_artist(artist) {#try_get_artist_artist_13}


```
 try_get_artist(artist) 
```

يحاول العثور على علامة EXIF Artist، إذا لم يتم العثور على العلامة يُعيد null

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الفنان | سلسلة | الفنان. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | صحيح إذا نجح |


### Method: try_get_description(description) {#try_get_description_description_14}


```
 try_get_description(description) 
```

يحاول العثور على علامة EXIF ImageDescription، إذا لم يتم العثور على العلامة يُعيد null

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الوصف | سلسلة | الوصف. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | صحيح إذا نجح |


### Method: try_get_geo_location(geo_location) {#try_get_geo_location_geo_location_15}


```
 try_get_geo_location(geo_location) 
```

يحاول العثور على مجموعة علامات EXIF GPSLatitudeRef و GPSLongitudeRef و GPSLatitude و GPSLongitude، إذا لم تكن العلامات موجودة يُعيد null

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| geo_location | [GeoLocation[]](/psd/python-net/aspose.gis.imagemetadata/geolocation) | الموقع الجغرافي. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | صحيح إذا نجح |


### Method: try_get_image_size(image_size) {#try_get_image_size_image_size_16}


```
 try_get_image_size(image_size) 
```

يحاول العثور على مجموعة علامات EXIF ImageWidth و ImageHeight، إذا لم تكن العلامات موجودة يُعيد null

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| image_size | [ImageSize[]](/psd/python-net/aspose.gis.imagemetadata/imagesize) | حجم الصورة. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | صحيح إذا نجح |


### Method: try_get_modify_date(modify_date) {#try_get_modify_date_modify_date_17}


```
 try_get_modify_date(modify_date) 
```

يحاول العثور على علامة EXIF ModifyDate (DataTime)، إذا لم يتم العثور على العلامة يُعيد القيمة الافتراضية لـ DataTime

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| modify_date | datetime[] | تاريخ التعديل. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | صحيح إذا نجح |


