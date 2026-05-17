---
title: "ImageMetadataReader-klass"
type: docs
weight: 30
url: /sv/python-net/aspose.gis.imagemetadata/imagemetadatareader/
---

**Summary:** Class for editing, adding some EXIF tags

**Module:** [aspose.gis.imagemetadata](/psd/python-net/aspose.gis.imagemetadata/)

**Full Name:** aspose.gis.imagemetadata.ImageMetadataReader

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_reader(file_name)](#get_reader_file_name_1) | Skapar en läsareinstans för EXIF-taggar |
| [get_reader(stream)](#get_reader_stream_2) | Skapar en läsareinstans för EXIF-taggar |
| [read_data()](#read_data__3) | Extraherar alla stödda EXIF-taggar |
| [save(file_name)](#save_file_name_4) | Spara till en ny fil eftersom den ursprungliga är låst för ändringar |
| [save(file_name, format)](#save_file_name_format_5) | Spara till en ny fil eftersom den ursprungliga är låst för ändringar |
| [save(stream)](#save_stream_6) | Sparar ändringar till en separat ström |
| [save(stream, format)](#save_stream_format_7) | Sparar ändringar till en separat ström |
| [set_artist(artist)](#set_artist_artist_8) | Sparar EXIF Artist-taggen, lägger till eller skriver över data. |
| [set_description(description)](#set_description_description_9) | Sparar EXIF ImageDescription-taggen, lägger till eller skriver över data. |
| [set_geo_location(latitude, longitude)](#set_geo_location_latitude_longitude_10) | Sparar EXIF GPSLatitudeRef-, GPSLongitudeRef-, GPSLatitude- och GPSLongitude-taggarna, lägger till eller skriver över data. |
| [set_image_size(width, height)](#set_image_size_width_height_11) | Sparar EXIF ImageWidth- och ImageHeight-taggarna, lägger till eller skriver över data. |
| [set_modify_date(modify_date)](#set_modify_date_modify_date_12) | Sparar EXIF ModifyDate (DataTime)-taggen, lägger till eller skriver över data. |
| [try_get_artist(artist)](#try_get_artist_artist_13) | Den försöker hitta EXIF-taggen Artist, om taggen inte hittas returneras null. |
| [try_get_description(description)](#try_get_description_description_14) | Den försöker hitta EXIF-taggen ImageDescription, om taggen inte hittas returneras null. |
| [try_get_geo_location(geo_location)](#try_get_geo_location_geo_location_15) | Den försöker hitta EXIF‑uppsättningen av taggarna GPSLatitudeRef, GPSLongitudeRef, GPSLatitude, GPSLongitude, om taggarna inte finns returneras null. |
| [try_get_image_size(image_size)](#try_get_image_size_image_size_16) | Den försöker hitta EXIF‑uppsättningen av taggarna ImageWidth och ImageHeight, om taggarna inte finns returneras null. |
| [try_get_modify_date(modify_date)](#try_get_modify_date_modify_date_17) | Den försöker hitta EXIF-taggen ModifyDate (DataTime), om taggen inte hittas returneras standardvärdet för DataTime. |


### Method: get_reader(file_name)  [static] {#get_reader_file_name_1}


```
 get_reader(file_name) 
```

Skapar en läsareinstans för EXIF-taggar

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_name | string | Fullständigt namn på bildfilen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | Instans för metadata‑läsare |


### Method: get_reader(stream)  [static] {#get_reader_stream_2}


```
 get_reader(stream) 
```

Skapar en läsareinstans för EXIF-taggar

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Ström för bilddatakälla |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | Instans för metadata‑läsare |


### Method: read_data() {#read_data__3}


```
 read_data() 
```

Extraherar alla stödda EXIF-taggar

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageData](/psd/python-net/aspose.gis.imagemetadata/imagedata) | ImageData som representerar en uppsättning av stödjade taggar |


### Method: save(file_name) {#save_file_name_4}


```
 save(file_name) 
```

Spara till en ny fil eftersom den ursprungliga är låst för ändringar

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_name | string | Fullständigt namn på destinationsfilen |

### Method: save(file_name, format) {#save_file_name_format_5}


```
 save(file_name, format) 
```

Spara till en ny fil eftersom den ursprungliga är låst för ändringar

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_name | string | Fullständigt namn på destinationsfilen |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | Anger formatet för sparande |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

Sparar ändringar till en separat ström

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Destinationsström |

### Method: save(stream, format) {#save_stream_format_7}


```
 save(stream, format) 
```

Sparar ändringar till en separat ström

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Destinationsström |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | Anger formatet för sparande |

### Method: set_artist(artist) {#set_artist_artist_8}


```
 set_artist(artist) 
```

Sparar EXIF Artist-taggen, lägger till eller skriver över data.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| artist | string | Konstnären. |

### Method: set_description(description) {#set_description_description_9}


```
 set_description(description) 
```

Sparar EXIF ImageDescription-taggen, lägger till eller skriver över data.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| beskrivning | string | Beskrivningen. |

### Method: set_geo_location(latitude, longitude) {#set_geo_location_latitude_longitude_10}


```
 set_geo_location(latitude, longitude) 
```

Sparar EXIF GPSLatitudeRef-, GPSLongitudeRef-, GPSLatitude- och GPSLongitude-taggarna, lägger till eller skriver över data.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| latitud | double | Latituden. |
| longitud | double | Longituden. |

### Method: set_image_size(width, height) {#set_image_size_width_height_11}


```
 set_image_size(width, height) 
```

Sparar EXIF ImageWidth- och ImageHeight-taggarna, lägger till eller skriver över data.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| bredd | int | Bredden. |
| höjd | int | Höjden. |

### Method: set_modify_date(modify_date) {#set_modify_date_modify_date_12}


```
 set_modify_date(modify_date) 
```

Sparar EXIF ModifyDate (DataTime)-taggen, lägger till eller skriver över data.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| modify_date | datetime | Det modifierade datumet. |

### Method: try_get_artist(artist) {#try_get_artist_artist_13}


```
 try_get_artist(artist) 
```

Den försöker hitta EXIF-taggen Artist, om taggen inte hittas returneras null.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| artist | Sträng | Konstnären. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Sant om lyckat |


### Method: try_get_description(description) {#try_get_description_description_14}


```
 try_get_description(description) 
```

Den försöker hitta EXIF-taggen ImageDescription, om taggen inte hittas returneras null.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| beskrivning | Sträng | Beskrivningen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Sant om lyckat |


### Method: try_get_geo_location(geo_location) {#try_get_geo_location_geo_location_15}


```
 try_get_geo_location(geo_location) 
```

Den försöker hitta EXIF‑uppsättningen av taggarna GPSLatitudeRef, GPSLongitudeRef, GPSLatitude, GPSLongitude, om taggarna inte finns returneras null.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| geo_location | [GeoLocation[]](/psd/python-net/aspose.gis.imagemetadata/geolocation) | Den geografiska platsen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Sant om lyckat |


### Method: try_get_image_size(image_size) {#try_get_image_size_image_size_16}


```
 try_get_image_size(image_size) 
```

Den försöker hitta EXIF‑uppsättningen av taggarna ImageWidth och ImageHeight, om taggarna inte finns returneras null.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_size | [ImageSize[]](/psd/python-net/aspose.gis.imagemetadata/imagesize) | Storlek på bilden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Sant om lyckat |


### Method: try_get_modify_date(modify_date) {#try_get_modify_date_modify_date_17}


```
 try_get_modify_date(modify_date) 
```

Den försöker hitta EXIF-taggen ModifyDate (DataTime), om taggen inte hittas returneras standardvärdet för DataTime.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| modify_date | datetime[] | Det modifierade datumet. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Sant om lyckat |


