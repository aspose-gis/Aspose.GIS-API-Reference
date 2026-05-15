---
title: "Classe ImageMetadataReader"
type: docs
weight: 30
url: /fr/python-net/aspose.gis.imagemetadata/imagemetadatareader/
---

**Summary:** Class for editing, adding some EXIF tags

**Module:** [aspose.gis.imagemetadata](/psd/python-net/aspose.gis.imagemetadata/)

**Full Name:** aspose.gis.imagemetadata.ImageMetadataReader

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_reader(file_name)](#get_reader_file_name_1) | Crée une instance de lecteur pour les balises EXIF |
| [get_reader(stream)](#get_reader_stream_2) | Crée une instance de lecteur pour les balises EXIF |
| [read_data()](#read_data__3) | Extrait toutes les balises EXIF prises en charge |
| [save(file_name)](#save_file_name_4) | Enregistre dans un nouveau fichier car l'original est verrouillé pour les modifications |
| [save(file_name, format)](#save_file_name_format_5) | Enregistre dans un nouveau fichier car l'original est verrouillé pour les modifications |
| [save(stream)](#save_stream_6) | Enregistrement des modifications dans un flux séparé |
| [save(stream, format)](#save_stream_format_7) | Enregistrement des modifications dans un flux séparé |
| [set_artist(artist)](#set_artist_artist_8) | Enregistrement de la balise EXIF Artist, en ajoutant ou en écrasant les données. |
| [set_description(description)](#set_description_description_9) | Enregistrement du tag EXIF ImageDescription, ajout ou écrasement des données. |
| [set_geo_location(latitude, longitude)](#set_geo_location_latitude_longitude_10) | Enregistrement des tags EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude et GPSLongitude, ajout ou écrasement des données. |
| [set_image_size(width, height)](#set_image_size_width_height_11) | Enregistrement des tags EXIF ImageWidth et ImageHeight, ajout ou écrasement des données. |
| [set_modify_date(modify_date)](#set_modify_date_modify_date_12) | Enregistrement du tag EXIF ModifyDate (DataTime), ajout ou écrasement des données. |
| [try_get_artist(artist)](#try_get_artist_artist_13) | Il tente de trouver le tag EXIF Artist, si le tag n'est pas trouvé il renvoie null |
| [try_get_description(description)](#try_get_description_description_14) | Il tente de trouver le tag EXIF ImageDescription, si le tag n'est pas trouvé il renvoie null |
| [try_get_geo_location(geo_location)](#try_get_geo_location_geo_location_15) | Il tente de trouver l'ensemble des tags EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude, GPSLongitude, si les tags ne sont pas présents il renvoie null |
| [try_get_image_size(image_size)](#try_get_image_size_image_size_16) | Il tente de trouver l'ensemble des tags EXIF ImageWidth et ImageHeight, si les tags ne sont pas présents il renvoie null |
| [try_get_modify_date(modify_date)](#try_get_modify_date_modify_date_17) | Il tente de trouver le tag EXIF ModifyDate (DataTime), si le tag n'est pas trouvé il renvoie la valeur par défaut de DataTime |


### Method: get_reader(file_name)  [static] {#get_reader_file_name_1}


```
 get_reader(file_name) 
```

Crée une instance de lecteur pour les balises EXIF

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_name | string | Nom complet du fichier image. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | Instance du lecteur de métadonnées |


### Method: get_reader(stream)  [static] {#get_reader_stream_2}


```
 get_reader(stream) 
```

Crée une instance de lecteur pour les balises EXIF

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Flux source de données d'image |

**Returns**

| Type | Description |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | Instance du lecteur de métadonnées |


### Method: read_data() {#read_data__3}


```
 read_data() 
```

Extrait toutes les balises EXIF prises en charge

**Returns**

| Type | Description |
| :- | :- |
| [ImageData](/psd/python-net/aspose.gis.imagemetadata/imagedata) | ImageData qui représente l'ensemble des tags pris en charge |


### Method: save(file_name) {#save_file_name_4}


```
 save(file_name) 
```

Enregistre dans un nouveau fichier car l'original est verrouillé pour les modifications

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_name | string | Nom complet du fichier de destination |

### Method: save(file_name, format) {#save_file_name_format_5}


```
 save(file_name, format) 
```

Enregistre dans un nouveau fichier car l'original est verrouillé pour les modifications

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_name | string | Nom complet du fichier de destination |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | Spécifie le format d'enregistrement |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

Enregistrement des modifications dans un flux séparé

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Flux de destination |

### Method: save(stream, format) {#save_stream_format_7}


```
 save(stream, format) 
```

Enregistrement des modifications dans un flux séparé

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Flux de destination |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | Spécifie le format d'enregistrement |

### Method: set_artist(artist) {#set_artist_artist_8}


```
 set_artist(artist) 
```

Enregistrement de la balise EXIF Artist, en ajoutant ou en écrasant les données.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| artiste | string | L'artiste. |

### Method: set_description(description) {#set_description_description_9}


```
 set_description(description) 
```

Enregistrement du tag EXIF ImageDescription, ajout ou écrasement des données.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| description | string | La description. |

### Method: set_geo_location(latitude, longitude) {#set_geo_location_latitude_longitude_10}


```
 set_geo_location(latitude, longitude) 
```

Enregistrement des tags EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude et GPSLongitude, ajout ou écrasement des données.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| latitude | double | La latitude. |
| longitude | double | La longitude. |

### Method: set_image_size(width, height) {#set_image_size_width_height_11}


```
 set_image_size(width, height) 
```

Enregistrement des tags EXIF ImageWidth et ImageHeight, ajout ou écrasement des données.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| width | int | La largeur. |
| hauteur | int | La hauteur. |

### Method: set_modify_date(modify_date) {#set_modify_date_modify_date_12}


```
 set_modify_date(modify_date) 
```

Enregistrement du tag EXIF ModifyDate (DataTime), ajout ou écrasement des données.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| date_modification | datetime | La date de modification. |

### Method: try_get_artist(artist) {#try_get_artist_artist_13}


```
 try_get_artist(artist) 
```

Il tente de trouver le tag EXIF Artist, si le tag n'est pas trouvé il renvoie null

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| artiste | String | L'artiste. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Vrai si réussi |


### Method: try_get_description(description) {#try_get_description_description_14}


```
 try_get_description(description) 
```

Il tente de trouver le tag EXIF ImageDescription, si le tag n'est pas trouvé il renvoie null

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| description | String | La description. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Vrai si réussi |


### Method: try_get_geo_location(geo_location) {#try_get_geo_location_geo_location_15}


```
 try_get_geo_location(geo_location) 
```

Il tente de trouver l'ensemble des tags EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude, GPSLongitude, si les tags ne sont pas présents il renvoie null

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| geo_location | [GeoLocation[]](/psd/python-net/aspose.gis.imagemetadata/geolocation) | La géolocalisation. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Vrai si réussi |


### Method: try_get_image_size(image_size) {#try_get_image_size_image_size_16}


```
 try_get_image_size(image_size) 
```

Il tente de trouver l'ensemble des tags EXIF ImageWidth et ImageHeight, si les tags ne sont pas présents il renvoie null

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image_size | [ImageSize[]](/psd/python-net/aspose.gis.imagemetadata/imagesize) | Taille de l'image. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Vrai si réussi |


### Method: try_get_modify_date(modify_date) {#try_get_modify_date_modify_date_17}


```
 try_get_modify_date(modify_date) 
```

Il tente de trouver le tag EXIF ModifyDate (DataTime), si le tag n'est pas trouvé il renvoie la valeur par défaut de DataTime

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| date_modification | datetime[] | La date de modification. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Vrai si réussi |


