---
title: "ImageMetadataReader Sınıfı"
type: docs
weight: 30
url: /tr/python-net/aspose.gis.imagemetadata/imagemetadatareader/
---

**Summary:** Class for editing, adding some EXIF tags

**Module:** [aspose.gis.imagemetadata](/psd/python-net/aspose.gis.imagemetadata/)

**Full Name:** aspose.gis.imagemetadata.ImageMetadataReader

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_reader(file_name)](#get_reader_file_name_1) | EXIF etiketleri için bir okuyucu örneği oluşturur |
| [get_reader(stream)](#get_reader_stream_2) | EXIF etiketleri için bir okuyucu örneği oluşturur |
| [read_data()](#read_data__3) | Desteklenen tüm EXIF etiketlerini çıkarır |
| [save(file_name)](#save_file_name_4) | Orijinal dosya değişiklikler için kilitli olduğundan yeni bir dosyaya kaydet |
| [save(file_name, format)](#save_file_name_format_5) | Orijinal dosya değişiklikler için kilitli olduğundan yeni bir dosyaya kaydet |
| [save(stream)](#save_stream_6) | Değişiklikleri ayrı bir akışa kaydetme |
| [save(stream, format)](#save_stream_format_7) | Değişiklikleri ayrı bir akışa kaydetme |
| [set_artist(artist)](#set_artist_artist_8) | EXIF Artist etiketini kaydetme, veriyi ekleyerek veya üzerine yazarak. |
| [set_description(description)](#set_description_description_9) | EXIF ImageDescription etiketini kaydeder, veriyi ekler veya üzerine yazar. |
| [set_geo_location(latitude, longitude)](#set_geo_location_latitude_longitude_10) | EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude ve GPSLongitude etiketlerini kaydeder, veriyi ekler veya üzerine yazar. |
| [set_image_size(width, height)](#set_image_size_width_height_11) | EXIF ImageWidth ve ImageHeight etiketlerini kaydeder, veriyi ekler veya üzerine yazar. |
| [set_modify_date(modify_date)](#set_modify_date_modify_date_12) | EXIF ModifyDate (DataTime) etiketini kaydeder, veriyi ekler veya üzerine yazar. |
| [try_get_artist(artist)](#try_get_artist_artist_13) | EXIF Artist etiketini bulmaya çalışır, etiket bulunamazsa null döndürür |
| [try_get_description(description)](#try_get_description_description_14) | EXIF ImageDescription etiketini bulmaya çalışır, etiket bulunamazsa null döndürür |
| [try_get_geo_location(geo_location)](#try_get_geo_location_geo_location_15) | EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude ve GPSLongitude etiketlerini bulmaya çalışır, etiketler mevcut değilse null döndürür |
| [try_get_image_size(image_size)](#try_get_image_size_image_size_16) | EXIF ImageWidth ve ImageHeight etiketlerini bulmaya çalışır, etiketler mevcut değilse null döndürür |
| [try_get_modify_date(modify_date)](#try_get_modify_date_modify_date_17) | EXIF ModifyDate (DataTime) etiketini bulmaya çalışır, etiket bulunamazsa varsayılan DataTime değerini döndürür |


### Method: get_reader(file_name)  [static] {#get_reader_file_name_1}


```
 get_reader(file_name) 
```

EXIF etiketleri için bir okuyucu örneği oluşturur

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_name | string | Görüntü dosyasının tam adı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | Meta veri okuyucu örneği |


### Method: get_reader(stream)  [static] {#get_reader_stream_2}


```
 get_reader(stream) 
```

EXIF etiketleri için bir okuyucu örneği oluşturur

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Görüntü veri kaynağı akışı |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | Meta veri okuyucu örneği |


### Method: read_data() {#read_data__3}


```
 read_data() 
```

Desteklenen tüm EXIF etiketlerini çıkarır

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ImageData](/psd/python-net/aspose.gis.imagemetadata/imagedata) | Desteklenen etiket kümesini temsil eden ImageData |


### Method: save(file_name) {#save_file_name_4}


```
 save(file_name) 
```

Orijinal dosya değişiklikler için kilitli olduğundan yeni bir dosyaya kaydet

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_name | string | Hedef dosyanın tam adı |

### Method: save(file_name, format) {#save_file_name_format_5}


```
 save(file_name, format) 
```

Orijinal dosya değişiklikler için kilitli olduğundan yeni bir dosyaya kaydet

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| file_name | string | Hedef dosyanın tam adı |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | Kaydetme formatını belirtir |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

Değişiklikleri ayrı bir akışa kaydetme

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Hedef akış |

### Method: save(stream, format) {#save_stream_format_7}


```
 save(stream, format) 
```

Değişiklikleri ayrı bir akışa kaydetme

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| akış | _io.BufferedRandom | Hedef akış |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | Kaydetme formatını belirtir |

### Method: set_artist(artist) {#set_artist_artist_8}


```
 set_artist(artist) 
```

EXIF Artist etiketini kaydetme, veriyi ekleyerek veya üzerine yazarak.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| sanatçı | string | Sanatçı. |

### Method: set_description(description) {#set_description_description_9}


```
 set_description(description) 
```

EXIF ImageDescription etiketini kaydeder, veriyi ekler veya üzerine yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| açıklama | string | Açıklama. |

### Method: set_geo_location(latitude, longitude) {#set_geo_location_latitude_longitude_10}


```
 set_geo_location(latitude, longitude) 
```

EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude ve GPSLongitude etiketlerini kaydeder, veriyi ekler veya üzerine yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| enlem | double | Enlem. |
| boylam | double | Boylam. |

### Method: set_image_size(width, height) {#set_image_size_width_height_11}


```
 set_image_size(width, height) 
```

EXIF ImageWidth ve ImageHeight etiketlerini kaydeder, veriyi ekler veya üzerine yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| genişlik | int | Genişlik. |
| yükseklik | int | Yükseklik. |

### Method: set_modify_date(modify_date) {#set_modify_date_modify_date_12}


```
 set_modify_date(modify_date) 
```

EXIF ModifyDate (DataTime) etiketini kaydeder, veriyi ekler veya üzerine yazar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| modify_date | datetime | Değiştirme tarihi. |

### Method: try_get_artist(artist) {#try_get_artist_artist_13}


```
 try_get_artist(artist) 
```

EXIF Artist etiketini bulmaya çalışır, etiket bulunamazsa null döndürür

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| sanatçı | Dize | Sanatçı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Başarılıysa doğru |


### Method: try_get_description(description) {#try_get_description_description_14}


```
 try_get_description(description) 
```

EXIF ImageDescription etiketini bulmaya çalışır, etiket bulunamazsa null döndürür

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| açıklama | Dize | Açıklama. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Başarılıysa doğru |


### Method: try_get_geo_location(geo_location) {#try_get_geo_location_geo_location_15}


```
 try_get_geo_location(geo_location) 
```

EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude ve GPSLongitude etiketlerini bulmaya çalışır, etiketler mevcut değilse null döndürür

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| geo_location | [GeoLocation[]](/psd/python-net/aspose.gis.imagemetadata/geolocation) | Coğrafi konum. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Başarılıysa doğru |


### Method: try_get_image_size(image_size) {#try_get_image_size_image_size_16}


```
 try_get_image_size(image_size) 
```

EXIF ImageWidth ve ImageHeight etiketlerini bulmaya çalışır, etiketler mevcut değilse null döndürür

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| image_size | [ImageSize[]](/psd/python-net/aspose.gis.imagemetadata/imagesize) | Görselin boyutu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Başarılıysa doğru |


### Method: try_get_modify_date(modify_date) {#try_get_modify_date_modify_date_17}


```
 try_get_modify_date(modify_date) 
```

EXIF ModifyDate (DataTime) etiketini bulmaya çalışır, etiket bulunamazsa varsayılan DataTime değerini döndürür

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| modify_date | datetime[] | Değiştirme tarihi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Başarılıysa doğru |


