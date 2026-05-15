---
title: "ImageMetadataReader Klasse"
type: docs
weight: 30
url: /de/python-net/aspose.gis.imagemetadata/imagemetadatareader/
---

**Summary:** Class for editing, adding some EXIF tags

**Module:** [aspose.gis.imagemetadata](/psd/python-net/aspose.gis.imagemetadata/)

**Full Name:** aspose.gis.imagemetadata.ImageMetadataReader

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_reader(file_name)](#get_reader_file_name_1) | Erstellt eine Reader-Instanz für EXIF-Tags |
| [get_reader(stream)](#get_reader_stream_2) | Erstellt eine Reader-Instanz für EXIF-Tags |
| [read_data()](#read_data__3) | Extrahiert alle unterstützten EXIF-Tags |
| [save(file_name)](#save_file_name_4) | Speichern in eine neue Datei, da die Originaldatei für Änderungen gesperrt ist |
| [save(file_name, format)](#save_file_name_format_5) | Speichern in eine neue Datei, da die Originaldatei für Änderungen gesperrt ist |
| [save(stream)](#save_stream_6) | Speichern von Änderungen in einen separaten Stream |
| [save(stream, format)](#save_stream_format_7) | Speichern von Änderungen in einen separaten Stream |
| [set_artist(artist)](#set_artist_artist_8) | Speichern des EXIF-Artist-Tags, Hinzufügen oder Überschreiben der Daten. |
| [set_description(description)](#set_description_description_9) | Speichern des EXIF ImageDescription-Tags, Hinzufügen oder Überschreiben der Daten. |
| [set_geo_location(latitude, longitude)](#set_geo_location_latitude_longitude_10) | Speichern der EXIF GPSLatitudeRef-, GPSLongitudeRef-, GPSLatitude- und GPSLongitude-Tags, Hinzufügen oder Überschreiben der Daten. |
| [set_image_size(width, height)](#set_image_size_width_height_11) | Speichern der EXIF ImageWidth- und ImageHeight-Tags, Hinzufügen oder Überschreiben der Daten. |
| [set_modify_date(modify_date)](#set_modify_date_modify_date_12) | Speichern des EXIF ModifyDate (DataTime)-Tags, Hinzufügen oder Überschreiben der Daten. |
| [try_get_artist(artist)](#try_get_artist_artist_13) | Es versucht, den EXIF-Tag Artist zu finden; wenn der Tag nicht gefunden wird, gibt es null zurück. |
| [try_get_description(description)](#try_get_description_description_14) | Es versucht, den EXIF-Tag ImageDescription zu finden; wenn der Tag nicht gefunden wird, gibt es null zurück. |
| [try_get_geo_location(geo_location)](#try_get_geo_location_geo_location_15) | Es versucht, das EXIF-Set der Tags GPSLatitudeRef, GPSLongitudeRef, GPSLatitude und GPSLongitude zu finden; wenn die Tags nicht vorhanden sind, gibt es null zurück. |
| [try_get_image_size(image_size)](#try_get_image_size_image_size_16) | Es versucht, das EXIF-Set der Tags ImageWidth und ImageHeight zu finden; wenn die Tags nicht vorhanden sind, gibt es null zurück. |
| [try_get_modify_date(modify_date)](#try_get_modify_date_modify_date_17) | Es versucht, den EXIF-Tag ModifyDate (DataTime) zu finden; wenn der Tag nicht gefunden wird, gibt es den Standardwert für DataTime zurück. |


### Method: get_reader(file_name)  [static] {#get_reader_file_name_1}


```
 get_reader(file_name) 
```

Erstellt eine Reader-Instanz für EXIF-Tags

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_name | string | Vollständiger Name der Bilddatei. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | Instanz des Metadaten-Lesers |


### Method: get_reader(stream)  [static] {#get_reader_stream_2}


```
 get_reader(stream) 
```

Erstellt eine Reader-Instanz für EXIF-Tags

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Bilddaten-Quellstream |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | Instanz des Metadaten-Lesers |


### Method: read_data() {#read_data__3}


```
 read_data() 
```

Extrahiert alle unterstützten EXIF-Tags

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [ImageData](/psd/python-net/aspose.gis.imagemetadata/imagedata) | ImageData, das den Satz unterstützter Tags darstellt |


### Method: save(file_name) {#save_file_name_4}


```
 save(file_name) 
```

Speichern in eine neue Datei, da die Originaldatei für Änderungen gesperrt ist

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_name | string | Vollständiger Name der Zieldatei |

### Method: save(file_name, format) {#save_file_name_format_5}


```
 save(file_name, format) 
```

Speichern in eine neue Datei, da die Originaldatei für Änderungen gesperrt ist

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| file_name | string | Vollständiger Name der Zieldatei |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | Gibt das Format zum Speichern an |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

Speichern von Änderungen in einen separaten Stream

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Ziel-Stream |

### Method: save(stream, format) {#save_stream_format_7}


```
 save(stream, format) 
```

Speichern von Änderungen in einen separaten Stream

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Stream | _io.BufferedRandom | Ziel-Stream |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | Gibt das Format zum Speichern an |

### Method: set_artist(artist) {#set_artist_artist_8}


```
 set_artist(artist) 
```

Speichern des EXIF-Artist-Tags, Hinzufügen oder Überschreiben der Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Künstler | string | Der Künstler. |

### Method: set_description(description) {#set_description_description_9}


```
 set_description(description) 
```

Speichern des EXIF ImageDescription-Tags, Hinzufügen oder Überschreiben der Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Beschreibung | string | Die Beschreibung. |

### Method: set_geo_location(latitude, longitude) {#set_geo_location_latitude_longitude_10}


```
 set_geo_location(latitude, longitude) 
```

Speichern der EXIF GPSLatitudeRef-, GPSLongitudeRef-, GPSLatitude- und GPSLongitude-Tags, Hinzufügen oder Überschreiben der Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Breitengrad | double | Der Breitengrad. |
| Längengrad | double | Der Längengrad. |

### Method: set_image_size(width, height) {#set_image_size_width_height_11}


```
 set_image_size(width, height) 
```

Speichern der EXIF ImageWidth- und ImageHeight-Tags, Hinzufügen oder Überschreiben der Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| width | int | Die Breite. |
| Höhe | int | Die Höhe. |

### Method: set_modify_date(modify_date) {#set_modify_date_modify_date_12}


```
 set_modify_date(modify_date) 
```

Speichern des EXIF ModifyDate (DataTime)-Tags, Hinzufügen oder Überschreiben der Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| modify_date | datetime | Das Änderungsdatum. |

### Method: try_get_artist(artist) {#try_get_artist_artist_13}


```
 try_get_artist(artist) 
```

Es versucht, den EXIF-Tag Artist zu finden; wenn der Tag nicht gefunden wird, gibt es null zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Künstler | String | Der Künstler. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | True, wenn erfolgreich |


### Method: try_get_description(description) {#try_get_description_description_14}


```
 try_get_description(description) 
```

Es versucht, den EXIF-Tag ImageDescription zu finden; wenn der Tag nicht gefunden wird, gibt es null zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Beschreibung | String | Die Beschreibung. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | True, wenn erfolgreich |


### Method: try_get_geo_location(geo_location) {#try_get_geo_location_geo_location_15}


```
 try_get_geo_location(geo_location) 
```

Es versucht, das EXIF-Set der Tags GPSLatitudeRef, GPSLongitudeRef, GPSLatitude und GPSLongitude zu finden; wenn die Tags nicht vorhanden sind, gibt es null zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| geo_location | [GeoLocation[]](/psd/python-net/aspose.gis.imagemetadata/geolocation) | Der Geo-Standort. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | True, wenn erfolgreich |


### Method: try_get_image_size(image_size) {#try_get_image_size_image_size_16}


```
 try_get_image_size(image_size) 
```

Es versucht, das EXIF-Set der Tags ImageWidth und ImageHeight zu finden; wenn die Tags nicht vorhanden sind, gibt es null zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_size | [ImageSize[]](/psd/python-net/aspose.gis.imagemetadata/imagesize) | Größe des Bildes. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | True, wenn erfolgreich |


### Method: try_get_modify_date(modify_date) {#try_get_modify_date_modify_date_17}


```
 try_get_modify_date(modify_date) 
```

Es versucht, den EXIF-Tag ModifyDate (DataTime) zu finden; wenn der Tag nicht gefunden wird, gibt es den Standardwert für DataTime zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| modify_date | datetime[] | Das Änderungsdatum. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | True, wenn erfolgreich |


