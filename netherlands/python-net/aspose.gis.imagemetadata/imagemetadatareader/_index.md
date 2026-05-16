---
title: "ImageMetadataReader-klasse"
type: docs
weight: 30
url: /nl/python-net/aspose.gis.imagemetadata/imagemetadatareader/
---

**Summary:** Class for editing, adding some EXIF tags

**Module:** [aspose.gis.imagemetadata](/psd/python-net/aspose.gis.imagemetadata/)

**Full Name:** aspose.gis.imagemetadata.ImageMetadataReader

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_reader(file_name)](#get_reader_file_name_1) | Creëert een lezerinstantie voor EXIF-tags |
| [get_reader(stream)](#get_reader_stream_2) | Creëert een lezerinstantie voor EXIF-tags |
| [read_data()](#read_data__3) | Extraheert alle ondersteunde EXIF-tags |
| [save(file_name)](#save_file_name_4) | Opslaan naar nieuw bestand omdat het originele bestand vergrendeld is voor wijzigingen |
| [save(file_name, format)](#save_file_name_format_5) | Opslaan naar nieuw bestand omdat het originele bestand vergrendeld is voor wijzigingen |
| [save(stream)](#save_stream_6) | Opslaan van wijzigingen naar een aparte stream |
| [save(stream, format)](#save_stream_format_7) | Opslaan van wijzigingen naar een aparte stream |
| [set_artist(artist)](#set_artist_artist_8) | Opslaan van de EXIF Artist-tag, toevoegen of overschrijven van de gegevens. |
| [set_description(description)](#set_description_description_9) | Opslaan van de EXIF ImageDescription-tag, toevoegen of overschrijven van de gegevens. |
| [set_geo_location(latitude, longitude)](#set_geo_location_latitude_longitude_10) | Opslaan van de EXIF GPSLatitudeRef-, GPSLongitudeRef-, GPSLatitude- en GPSLongitude-tags, toevoegen of overschrijven van de gegevens. |
| [set_image_size(width, height)](#set_image_size_width_height_11) | Opslaan van de EXIF ImageWidth- en ImageHeight-tags, toevoegen of overschrijven van de gegevens. |
| [set_modify_date(modify_date)](#set_modify_date_modify_date_12) | Opslaan van de EXIF ModifyDate (DataTime)-tag, toevoegen of overschrijven van de gegevens. |
| [try_get_artist(artist)](#try_get_artist_artist_13) | Het probeert de EXIF-tag Artist te vinden; als de tag niet wordt gevonden, retourneert het null. |
| [try_get_description(description)](#try_get_description_description_14) | Het probeert de EXIF-tag ImageDescription te vinden; als de tag niet wordt gevonden, retourneert het null. |
| [try_get_geo_location(geo_location)](#try_get_geo_location_geo_location_15) | Het probeert de EXIF-set van tags GPSLatitudeRef, GPSLongitudeRef, GPSLatitude, GPSLongitude te vinden; als de tags niet aanwezig zijn, retourneert het null. |
| [try_get_image_size(image_size)](#try_get_image_size_image_size_16) | Het probeert de EXIF-set van tags ImageWidth en ImageHeight te vinden; als de tags niet aanwezig zijn, retourneert het null. |
| [try_get_modify_date(modify_date)](#try_get_modify_date_modify_date_17) | Het probeert de EXIF-tag ModifyDate (DataTime) te vinden; als de tag niet wordt gevonden, retourneert het de standaard DataTime-waarde. |


### Method: get_reader(file_name)  [static] {#get_reader_file_name_1}


```
 get_reader(file_name) 
```

Creëert een lezerinstantie voor EXIF-tags

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_name | string | Volledige naam van het afbeeldingsbestand. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | Metadata-lezer instantie |


### Method: get_reader(stream)  [static] {#get_reader_stream_2}


```
 get_reader(stream) 
```

Creëert een lezerinstantie voor EXIF-tags

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | Afbeeldingsgegevensbronstroom |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | Metadata-lezer instantie |


### Method: read_data() {#read_data__3}


```
 read_data() 
```

Extraheert alle ondersteunde EXIF-tags

**Returns**

| Type | Beschrijving |
| :- | :- |
| [ImageData](/psd/python-net/aspose.gis.imagemetadata/imagedata) | ImageData die een set van ondersteunde tags vertegenwoordigt |


### Method: save(file_name) {#save_file_name_4}


```
 save(file_name) 
```

Opslaan naar nieuw bestand omdat het originele bestand vergrendeld is voor wijzigingen

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_name | string | Volledige naam van het bestemmingsbestand |

### Method: save(file_name, format) {#save_file_name_format_5}


```
 save(file_name, format) 
```

Opslaan naar nieuw bestand omdat het originele bestand vergrendeld is voor wijzigingen

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| file_name | string | Volledige naam van het bestemmingsbestand |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | Specificeert het formaat voor opslaan |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

Opslaan van wijzigingen naar een aparte stream

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | Bestemmingsstroom |

### Method: save(stream, format) {#save_stream_format_7}


```
 save(stream, format) 
```

Opslaan van wijzigingen naar een aparte stream

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom | Bestemmingsstroom |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | Specificeert het formaat voor opslaan |

### Method: set_artist(artist) {#set_artist_artist_8}


```
 set_artist(artist) 
```

Opslaan van de EXIF Artist-tag, toevoegen of overschrijven van de gegevens.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| artiest | string | De artiest. |

### Method: set_description(description) {#set_description_description_9}


```
 set_description(description) 
```

Opslaan van de EXIF ImageDescription-tag, toevoegen of overschrijven van de gegevens.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| beschrijving | string | De beschrijving. |

### Method: set_geo_location(latitude, longitude) {#set_geo_location_latitude_longitude_10}


```
 set_geo_location(latitude, longitude) 
```

Opslaan van de EXIF GPSLatitudeRef-, GPSLongitudeRef-, GPSLatitude- en GPSLongitude-tags, toevoegen of overschrijven van de gegevens.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| latitude | double | De breedtegraad. |
| longitude | double | De lengtegraad. |

### Method: set_image_size(width, height) {#set_image_size_width_height_11}


```
 set_image_size(width, height) 
```

Opslaan van de EXIF ImageWidth- en ImageHeight-tags, toevoegen of overschrijven van de gegevens.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| width | int | De breedte. |
| hoogte | int | De hoogte. |

### Method: set_modify_date(modify_date) {#set_modify_date_modify_date_12}


```
 set_modify_date(modify_date) 
```

Opslaan van de EXIF ModifyDate (DataTime)-tag, toevoegen of overschrijven van de gegevens.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| modify_date | datetime | De wijzigingsdatum. |

### Method: try_get_artist(artist) {#try_get_artist_artist_13}


```
 try_get_artist(artist) 
```

Het probeert de EXIF-tag Artist te vinden; als de tag niet wordt gevonden, retourneert het null.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| artiest | String | De artiest. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | True als succesvol |


### Method: try_get_description(description) {#try_get_description_description_14}


```
 try_get_description(description) 
```

Het probeert de EXIF-tag ImageDescription te vinden; als de tag niet wordt gevonden, retourneert het null.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| beschrijving | String | De beschrijving. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | True als succesvol |


### Method: try_get_geo_location(geo_location) {#try_get_geo_location_geo_location_15}


```
 try_get_geo_location(geo_location) 
```

Het probeert de EXIF-set van tags GPSLatitudeRef, GPSLongitudeRef, GPSLatitude, GPSLongitude te vinden; als de tags niet aanwezig zijn, retourneert het null.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| geo_location | [GeoLocation[]](/psd/python-net/aspose.gis.imagemetadata/geolocation) | De geolocatie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | True als succesvol |


### Method: try_get_image_size(image_size) {#try_get_image_size_image_size_16}


```
 try_get_image_size(image_size) 
```

Het probeert de EXIF-set van tags ImageWidth en ImageHeight te vinden; als de tags niet aanwezig zijn, retourneert het null.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| image_size | [ImageSize[]](/psd/python-net/aspose.gis.imagemetadata/imagesize) | Grootte van de afbeelding. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | True als succesvol |


### Method: try_get_modify_date(modify_date) {#try_get_modify_date_modify_date_17}


```
 try_get_modify_date(modify_date) 
```

Het probeert de EXIF-tag ModifyDate (DataTime) te vinden; als de tag niet wordt gevonden, retourneert het de standaard DataTime-waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| modify_date | datetime[] | De wijzigingsdatum. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | True als succesvol |


