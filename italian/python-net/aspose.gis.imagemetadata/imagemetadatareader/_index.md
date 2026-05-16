---
title: "Classe ImageMetadataReader"
type: docs
weight: 30
url: /it/python-net/aspose.gis.imagemetadata/imagemetadatareader/
---

**Summary:** Class for editing, adding some EXIF tags

**Module:** [aspose.gis.imagemetadata](/psd/python-net/aspose.gis.imagemetadata/)

**Full Name:** aspose.gis.imagemetadata.ImageMetadataReader

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [get_reader(file_name)](#get_reader_file_name_1) | Crea un'istanza del lettore per i tag EXIF |
| [get_reader(stream)](#get_reader_stream_2) | Crea un'istanza del lettore per i tag EXIF |
| [read_data()](#read_data__3) | Estrae tutti i tag EXIF supportati |
| [save(file_name)](#save_file_name_4) | Salva in un nuovo file poiché l'originale è bloccato per modifiche |
| [save(file_name, format)](#save_file_name_format_5) | Salva in un nuovo file poiché l'originale è bloccato per modifiche |
| [save(stream)](#save_stream_6) | Salvataggio delle modifiche in un flusso separato |
| [save(stream, format)](#save_stream_format_7) | Salvataggio delle modifiche in un flusso separato |
| [set_artist(artist)](#set_artist_artist_8) | Salvataggio del tag EXIF Artist, aggiungendo o sovrascrivendo i dati. |
| [set_description(description)](#set_description_description_9) | Salvataggio del tag EXIF ImageDescription, aggiunta o sovrascrittura dei dati. |
| [set_geo_location(latitude, longitude)](#set_geo_location_latitude_longitude_10) | Salvataggio dei tag EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude e GPSLongitude, aggiunta o sovrascrittura dei dati. |
| [set_image_size(width, height)](#set_image_size_width_height_11) | Salvataggio dei tag EXIF ImageWidth e ImageHeight, aggiunta o sovrascrittura dei dati. |
| [set_modify_date(modify_date)](#set_modify_date_modify_date_12) | Salvataggio del tag EXIF ModifyDate (DataTime), aggiunta o sovrascrittura dei dati. |
| [try_get_artist(artist)](#try_get_artist_artist_13) | Cerca il tag EXIF Artist; se il tag non viene trovato restituisce null |
| [try_get_description(description)](#try_get_description_description_14) | Cerca il tag EXIF ImageDescription; se il tag non viene trovato restituisce null |
| [try_get_geo_location(geo_location)](#try_get_geo_location_geo_location_15) | Cerca il set di tag EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude, GPSLongitude; se i tag non sono presenti restituisce null |
| [try_get_image_size(image_size)](#try_get_image_size_image_size_16) | Cerca il set di tag EXIF ImageWidth e ImageHeight; se i tag non sono presenti restituisce null |
| [try_get_modify_date(modify_date)](#try_get_modify_date_modify_date_17) | Cerca il tag EXIF ModifyDate (DataTime); se il tag non viene trovato restituisce il valore predefinito di DataTime |


### Method: get_reader(file_name)  [static] {#get_reader_file_name_1}


```
 get_reader(file_name) 
```

Crea un'istanza del lettore per i tag EXIF

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_name | string | Nome completo del file immagine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | Istanza del lettore di metadati |


### Method: get_reader(stream)  [static] {#get_reader_stream_2}


```
 get_reader(stream) 
```

Crea un'istanza del lettore per i tag EXIF

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Flusso di origine dei dati immagine |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | Istanza del lettore di metadati |


### Method: read_data() {#read_data__3}


```
 read_data() 
```

Estrae tutti i tag EXIF supportati

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageData](/psd/python-net/aspose.gis.imagemetadata/imagedata) | ImageData che rappresenta il set di tag supportati |


### Method: save(file_name) {#save_file_name_4}


```
 save(file_name) 
```

Salva in un nuovo file poiché l'originale è bloccato per modifiche

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_name | string | Nome completo del file di destinazione |

### Method: save(file_name, format) {#save_file_name_format_5}


```
 save(file_name, format) 
```

Salva in un nuovo file poiché l'originale è bloccato per modifiche

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_name | string | Nome completo del file di destinazione |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | Specifica il formato per il salvataggio |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

Salvataggio delle modifiche in un flusso separato

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Flusso di destinazione |

### Method: save(stream, format) {#save_stream_format_7}


```
 save(stream, format) 
```

Salvataggio delle modifiche in un flusso separato

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Flusso di destinazione |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | Specifica il formato per il salvataggio |

### Method: set_artist(artist) {#set_artist_artist_8}


```
 set_artist(artist) 
```

Salvataggio del tag EXIF Artist, aggiungendo o sovrascrivendo i dati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| artista | string | L'artista. |

### Method: set_description(description) {#set_description_description_9}


```
 set_description(description) 
```

Salvataggio del tag EXIF ImageDescription, aggiunta o sovrascrittura dei dati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| descrizione | string | La descrizione. |

### Method: set_geo_location(latitude, longitude) {#set_geo_location_latitude_longitude_10}


```
 set_geo_location(latitude, longitude) 
```

Salvataggio dei tag EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude e GPSLongitude, aggiunta o sovrascrittura dei dati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| latitudine | double | La latitudine. |
| longitudine | double | La longitudine. |

### Method: set_image_size(width, height) {#set_image_size_width_height_11}


```
 set_image_size(width, height) 
```

Salvataggio dei tag EXIF ImageWidth e ImageHeight, aggiunta o sovrascrittura dei dati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| width | int | La larghezza. |
| altezza | int | L'altezza. |

### Method: set_modify_date(modify_date) {#set_modify_date_modify_date_12}


```
 set_modify_date(modify_date) 
```

Salvataggio del tag EXIF ModifyDate (DataTime), aggiunta o sovrascrittura dei dati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| modify_date | datetime | La data di modifica. |

### Method: try_get_artist(artist) {#try_get_artist_artist_13}


```
 try_get_artist(artist) 
```

Cerca il tag EXIF Artist; se il tag non viene trovato restituisce null

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| artista | Stringa | L'artista. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Vero se riuscito |


### Method: try_get_description(description) {#try_get_description_description_14}


```
 try_get_description(description) 
```

Cerca il tag EXIF ImageDescription; se il tag non viene trovato restituisce null

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| descrizione | Stringa | La descrizione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Vero se riuscito |


### Method: try_get_geo_location(geo_location) {#try_get_geo_location_geo_location_15}


```
 try_get_geo_location(geo_location) 
```

Cerca il set di tag EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude, GPSLongitude; se i tag non sono presenti restituisce null

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| geo_location | [GeoLocation[]](/psd/python-net/aspose.gis.imagemetadata/geolocation) | La posizione geografica. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Vero se riuscito |


### Method: try_get_image_size(image_size) {#try_get_image_size_image_size_16}


```
 try_get_image_size(image_size) 
```

Cerca il set di tag EXIF ImageWidth e ImageHeight; se i tag non sono presenti restituisce null

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_size | [ImageSize[]](/psd/python-net/aspose.gis.imagemetadata/imagesize) | Dimensione dell'immagine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Vero se riuscito |


### Method: try_get_modify_date(modify_date) {#try_get_modify_date_modify_date_17}


```
 try_get_modify_date(modify_date) 
```

Cerca il tag EXIF ModifyDate (DataTime); se il tag non viene trovato restituisce il valore predefinito di DataTime

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| modify_date | datetime[] | La data di modifica. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Vero se riuscito |


