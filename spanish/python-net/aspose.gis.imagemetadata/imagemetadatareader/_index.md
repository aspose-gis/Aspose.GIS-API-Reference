---
title: "Clase ImageMetadataReader"
type: docs
weight: 30
url: /es/python-net/aspose.gis.imagemetadata/imagemetadatareader/
---

**Summary:** Class for editing, adding some EXIF tags

**Module:** [aspose.gis.imagemetadata](/psd/python-net/aspose.gis.imagemetadata/)

**Full Name:** aspose.gis.imagemetadata.ImageMetadataReader

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_reader(file_name)](#get_reader_file_name_1) | Crea una instancia de lector para etiquetas EXIF |
| [get_reader(stream)](#get_reader_stream_2) | Crea una instancia de lector para etiquetas EXIF |
| [read_data()](#read_data__3) | Extrae todas las etiquetas EXIF compatibles |
| [save(file_name)](#save_file_name_4) | Guardar en un archivo nuevo ya que el original está bloqueado para cambios |
| [save(file_name, format)](#save_file_name_format_5) | Guardar en un archivo nuevo ya que el original está bloqueado para cambios |
| [save(stream)](#save_stream_6) | Guardando cambios en un flujo separado |
| [save(stream, format)](#save_stream_format_7) | Guardando cambios en un flujo separado |
| [set_artist(artist)](#set_artist_artist_8) | Guardando la etiqueta EXIF Artist, añadiendo o sobrescribiendo los datos. |
| [set_description(description)](#set_description_description_9) | Guardando la etiqueta EXIF ImageDescription, añadiendo o sobrescribiendo los datos. |
| [set_geo_location(latitude, longitude)](#set_geo_location_latitude_longitude_10) | Guardando las etiquetas EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude y GPSLongitude, añadiendo o sobrescribiendo los datos. |
| [set_image_size(width, height)](#set_image_size_width_height_11) | Guardando las etiquetas EXIF ImageWidth y ImageHeight, añadiendo o sobrescribiendo los datos. |
| [set_modify_date(modify_date)](#set_modify_date_modify_date_12) | Guardando la etiqueta EXIF ModifyDate (DataTime), añadiendo o sobrescribiendo los datos. |
| [try_get_artist(artist)](#try_get_artist_artist_13) | Intenta encontrar la etiqueta EXIF Artist, si no se encuentra la etiqueta devuelve null |
| [try_get_description(description)](#try_get_description_description_14) | Intenta encontrar la etiqueta EXIF ImageDescription, si no se encuentra la etiqueta devuelve null |
| [try_get_geo_location(geo_location)](#try_get_geo_location_geo_location_15) | Intenta encontrar el conjunto de etiquetas EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude, GPSLongitude, si las etiquetas no están presentes devuelve null |
| [try_get_image_size(image_size)](#try_get_image_size_image_size_16) | Intenta encontrar el conjunto de etiquetas EXIF ImageWidth y ImageHeight, si las etiquetas no están presentes devuelve null |
| [try_get_modify_date(modify_date)](#try_get_modify_date_modify_date_17) | Intenta encontrar la etiqueta EXIF ModifyDate (DataTime), si no se encuentra la etiqueta devuelve el valor predeterminado de DataTime |


### Method: get_reader(file_name)  [static] {#get_reader_file_name_1}


```
 get_reader(file_name) 
```

Crea una instancia de lector para etiquetas EXIF

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_name | string | Nombre completo del archivo de imagen. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | Instancia del lector de metadatos |


### Method: get_reader(stream)  [static] {#get_reader_stream_2}


```
 get_reader(stream) 
```

Crea una instancia de lector para etiquetas EXIF

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | Flujo de origen de datos de la imagen |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | Instancia del lector de metadatos |


### Method: read_data() {#read_data__3}


```
 read_data() 
```

Extrae todas las etiquetas EXIF compatibles

**Returns**

| Tipo | Descripción |
| :- | :- |
| [ImageData](/psd/python-net/aspose.gis.imagemetadata/imagedata) | ImageData que representa el conjunto de etiquetas compatibles |


### Method: save(file_name) {#save_file_name_4}


```
 save(file_name) 
```

Guardar en un archivo nuevo ya que el original está bloqueado para cambios

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_name | string | Nombre completo del archivo de destino |

### Method: save(file_name, format) {#save_file_name_format_5}


```
 save(file_name, format) 
```

Guardar en un archivo nuevo ya que el original está bloqueado para cambios

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| file_name | string | Nombre completo del archivo de destino |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | Especifica el formato para guardar |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

Guardando cambios en un flujo separado

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | Flujo de destino |

### Method: save(stream, format) {#save_stream_format_7}


```
 save(stream, format) 
```

Guardando cambios en un flujo separado

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| flujo | _io.BufferedRandom | Flujo de destino |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | Especifica el formato para guardar |

### Method: set_artist(artist) {#set_artist_artist_8}


```
 set_artist(artist) 
```

Guardando la etiqueta EXIF Artist, añadiendo o sobrescribiendo los datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| artista | string | El artista. |

### Method: set_description(description) {#set_description_description_9}


```
 set_description(description) 
```

Guardando la etiqueta EXIF ImageDescription, añadiendo o sobrescribiendo los datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| descripción | string | La descripción. |

### Method: set_geo_location(latitude, longitude) {#set_geo_location_latitude_longitude_10}


```
 set_geo_location(latitude, longitude) 
```

Guardando las etiquetas EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude y GPSLongitude, añadiendo o sobrescribiendo los datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| latitud | double | La latitud. |
| longitud | double | La longitud. |

### Method: set_image_size(width, height) {#set_image_size_width_height_11}


```
 set_image_size(width, height) 
```

Guardando las etiquetas EXIF ImageWidth y ImageHeight, añadiendo o sobrescribiendo los datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| width | int | El ancho. |
| altura | int | La altura. |

### Method: set_modify_date(modify_date) {#set_modify_date_modify_date_12}


```
 set_modify_date(modify_date) 
```

Guardando la etiqueta EXIF ModifyDate (DataTime), añadiendo o sobrescribiendo los datos.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| modify_date | datetime | La fecha de modificación. |

### Method: try_get_artist(artist) {#try_get_artist_artist_13}


```
 try_get_artist(artist) 
```

Intenta encontrar la etiqueta EXIF Artist, si no se encuentra la etiqueta devuelve null

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| artista | Cadena | El artista. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Verdadero si tiene éxito |


### Method: try_get_description(description) {#try_get_description_description_14}


```
 try_get_description(description) 
```

Intenta encontrar la etiqueta EXIF ImageDescription, si no se encuentra la etiqueta devuelve null

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| descripción | Cadena | La descripción. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Verdadero si tiene éxito |


### Method: try_get_geo_location(geo_location) {#try_get_geo_location_geo_location_15}


```
 try_get_geo_location(geo_location) 
```

Intenta encontrar el conjunto de etiquetas EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude, GPSLongitude, si las etiquetas no están presentes devuelve null

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| geo_location | [GeoLocation[]](/psd/python-net/aspose.gis.imagemetadata/geolocation) | La ubicación geográfica. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Verdadero si tiene éxito |


### Method: try_get_image_size(image_size) {#try_get_image_size_image_size_16}


```
 try_get_image_size(image_size) 
```

Intenta encontrar el conjunto de etiquetas EXIF ImageWidth y ImageHeight, si las etiquetas no están presentes devuelve null

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| image_size | [ImageSize[]](/psd/python-net/aspose.gis.imagemetadata/imagesize) | Tamaño de la imagen. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Verdadero si tiene éxito |


### Method: try_get_modify_date(modify_date) {#try_get_modify_date_modify_date_17}


```
 try_get_modify_date(modify_date) 
```

Intenta encontrar la etiqueta EXIF ModifyDate (DataTime), si no se encuentra la etiqueta devuelve el valor predeterminado de DataTime

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| modify_date | datetime[] | La fecha de modificación. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Verdadero si tiene éxito |


