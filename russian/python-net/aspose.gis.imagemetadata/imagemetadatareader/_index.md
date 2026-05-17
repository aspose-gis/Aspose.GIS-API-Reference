---
title: "Класс ImageMetadataReader"
type: docs
weight: 30
url: /ru/python-net/aspose.gis.imagemetadata/imagemetadatareader/
---

**Summary:** Class for editing, adding some EXIF tags

**Module:** [aspose.gis.imagemetadata](/psd/python-net/aspose.gis.imagemetadata/)

**Full Name:** aspose.gis.imagemetadata.ImageMetadataReader

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_reader(file_name)](#get_reader_file_name_1) | Создает экземпляр считывателя для тегов EXIF |
| [get_reader(stream)](#get_reader_stream_2) | Создает экземпляр считывателя для тегов EXIF |
| [read_data()](#read_data__3) | Извлекает все поддерживаемые теги EXIF |
| [save(file_name)](#save_file_name_4) | Сохранить в новый файл, так как оригинальный файл заблокирован для изменений |
| [save(file_name, format)](#save_file_name_format_5) | Сохранить в новый файл, так как оригинальный файл заблокирован для изменений |
| [save(stream)](#save_stream_6) | Сохранение изменений в отдельный поток |
| [save(stream, format)](#save_stream_format_7) | Сохранение изменений в отдельный поток |
| [set_artist(artist)](#set_artist_artist_8) | Сохранение тега EXIF Artist, добавление или перезапись данных. |
| [set_description(description)](#set_description_description_9) | Сохранение тега EXIF ImageDescription, добавление или перезапись данных. |
| [set_geo_location(latitude, longitude)](#set_geo_location_latitude_longitude_10) | Сохранение тегов EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude и GPSLongitude, добавление или перезапись данных. |
| [set_image_size(width, height)](#set_image_size_width_height_11) | Сохранение тегов EXIF ImageWidth и ImageHeight, добавление или перезапись данных. |
| [set_modify_date(modify_date)](#set_modify_date_modify_date_12) | Сохранение тега EXIF ModifyDate (DataTime), добавление или перезапись данных. |
| [try_get_artist(artist)](#try_get_artist_artist_13) | Пытается найти тег EXIF Artist, если тег не найден, возвращает null |
| [try_get_description(description)](#try_get_description_description_14) | Пытается найти тег EXIF ImageDescription, если тег не найден, возвращает null |
| [try_get_geo_location(geo_location)](#try_get_geo_location_geo_location_15) | Пытается найти набор тегов EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude, GPSLongitude, если теги не представлены, возвращает null |
| [try_get_image_size(image_size)](#try_get_image_size_image_size_16) | Пытается найти набор тегов EXIF ImageWidth и ImageHeight, если теги не представлены, возвращает null |
| [try_get_modify_date(modify_date)](#try_get_modify_date_modify_date_17) | Пытается найти тег EXIF ModifyDate (DataTime), если тег не найден, возвращает значение DataTime по умолчанию |


### Method: get_reader(file_name)  [static] {#get_reader_file_name_1}


```
 get_reader(file_name) 
```

Создает экземпляр считывателя для тегов EXIF

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_name | string | Полное имя файла изображения. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | Экземпляр считывателя метаданных |


### Method: get_reader(stream)  [static] {#get_reader_stream_2}


```
 get_reader(stream) 
```

Создает экземпляр считывателя для тегов EXIF

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | _io.BufferedRandom | Поток источника данных изображения |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | Экземпляр считывателя метаданных |


### Method: read_data() {#read_data__3}


```
 read_data() 
```

Извлекает все поддерживаемые теги EXIF

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageData](/psd/python-net/aspose.gis.imagemetadata/imagedata) | ImageData, представляющий набор поддерживаемых тегов |


### Method: save(file_name) {#save_file_name_4}


```
 save(file_name) 
```

Сохранить в новый файл, так как оригинальный файл заблокирован для изменений

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_name | string | Полное имя целевого файла |

### Method: save(file_name, format) {#save_file_name_format_5}


```
 save(file_name, format) 
```

Сохранить в новый файл, так как оригинальный файл заблокирован для изменений

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| file_name | string | Полное имя целевого файла |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | Указывает формат сохранения |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

Сохранение изменений в отдельный поток

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | _io.BufferedRandom | Поток назначения |

### Method: save(stream, format) {#save_stream_format_7}


```
 save(stream, format) 
```

Сохранение изменений в отдельный поток

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | _io.BufferedRandom | Поток назначения |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | Указывает формат сохранения |

### Method: set_artist(artist) {#set_artist_artist_8}


```
 set_artist(artist) 
```

Сохранение тега EXIF Artist, добавление или перезапись данных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| artist | string | Автор. |

### Method: set_description(description) {#set_description_description_9}


```
 set_description(description) 
```

Сохранение тега EXIF ImageDescription, добавление или перезапись данных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| описание | string | Описание. |

### Method: set_geo_location(latitude, longitude) {#set_geo_location_latitude_longitude_10}


```
 set_geo_location(latitude, longitude) 
```

Сохранение тегов EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude и GPSLongitude, добавление или перезапись данных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| широта | double | Широта. |
| долгота | double | Долгота. |

### Method: set_image_size(width, height) {#set_image_size_width_height_11}


```
 set_image_size(width, height) 
```

Сохранение тегов EXIF ImageWidth и ImageHeight, добавление или перезапись данных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| width | int | Ширина. |
| высота | int | Высота. |

### Method: set_modify_date(modify_date) {#set_modify_date_modify_date_12}


```
 set_modify_date(modify_date) 
```

Сохранение тега EXIF ModifyDate (DataTime), добавление или перезапись данных.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| modify_date | datetime | Дата изменения. |

### Method: try_get_artist(artist) {#try_get_artist_artist_13}


```
 try_get_artist(artist) 
```

Пытается найти тег EXIF Artist, если тег не найден, возвращает null

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| artist | Строка | Автор. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | True, если успешно |


### Method: try_get_description(description) {#try_get_description_description_14}


```
 try_get_description(description) 
```

Пытается найти тег EXIF ImageDescription, если тег не найден, возвращает null

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| описание | Строка | Описание. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | True, если успешно |


### Method: try_get_geo_location(geo_location) {#try_get_geo_location_geo_location_15}


```
 try_get_geo_location(geo_location) 
```

Пытается найти набор тегов EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude, GPSLongitude, если теги не представлены, возвращает null

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| geo_location | [GeoLocation[]](/psd/python-net/aspose.gis.imagemetadata/geolocation) | Географическое местоположение. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | True, если успешно |


### Method: try_get_image_size(image_size) {#try_get_image_size_image_size_16}


```
 try_get_image_size(image_size) 
```

Пытается найти набор тегов EXIF ImageWidth и ImageHeight, если теги не представлены, возвращает null

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_size | [ImageSize[]](/psd/python-net/aspose.gis.imagemetadata/imagesize) | Размер изображения. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | True, если успешно |


### Method: try_get_modify_date(modify_date) {#try_get_modify_date_modify_date_17}


```
 try_get_modify_date(modify_date) 
```

Пытается найти тег EXIF ModifyDate (DataTime), если тег не найден, возвращает значение DataTime по умолчанию

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| modify_date | datetime[] | Дата изменения. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | True, если успешно |


