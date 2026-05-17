---
title: "Clase GeoConvert"
type: docs
weight: 1140
url: /es/python-net/aspose.gis/geoconvert/
---

**Summary:** Converts coordinates to/from the different formats.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.GeoConvert

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [as_point_text(latitude, longitude, format)](#as_point_text_latitude_longitude_format_1) | Devuelve la posición calculada como una cadena en el formato especificado. |
| [as_point_text(point, format)](#as_point_text_point_format_2) | Devuelve la posición calculada como una cadena en el formato especificado. |
| [parse_point_text(text)](#parse_point_text_text_3) | Convierte la cadena que contiene coordenadas a un objeto IPoint. |
| [try_parse_point_text(text, point)](#try_parse_point_text_text_point_4) | Convierte la cadena que contiene coordenadas a un objeto IPoint. Un valor de retorno indica si la conversión tuvo éxito o falló. |


### Method: as_point_text(latitude, longitude, format)  [static] {#as_point_text_latitude_longitude_format_1}


```
 as_point_text(latitude, longitude, format) 
```

Devuelve la posición calculada como una cadena en el formato especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| latitud | double | Latitud de la posición. |
| longitud | double | Longitud de la posición. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | Formato del resultado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Posición como cadena. |


### Method: as_point_text(point, format)  [static] {#as_point_text_point_format_2}


```
 as_point_text(point, format) 
```

Devuelve la posición calculada como una cadena en el formato especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Objeto IPoint. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | Formato del resultado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Posición como cadena. |


### Method: parse_point_text(text)  [static] {#parse_point_text_text_3}


```
 parse_point_text(text) 
```

Convierte la cadena que contiene coordenadas a un objeto IPoint.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| text | string | Una cadena que contiene coordenadas para convertir.<br/>            La cadena debe contener tanto la latitud como la longitud de la coordenada.<br/>            Las coordenadas deben estar separadas por espacios, por coma o por punto y coma. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Objeto IPoint con coordenadas equivalentes a la cadena de entrada. |


### Method: try_parse_point_text(text, point)  [static] {#try_parse_point_text_text_point_4}


```
 try_parse_point_text(text, point) 
```

Convierte la cadena que contiene coordenadas a un objeto IPoint. Un valor de retorno indica si la conversión tuvo éxito o falló.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| text | string | Una cadena que contiene coordenadas para convertir.<br/>            La cadena debe contener tanto la latitud como la longitud de la coordenada.<br/>            Las coordenadas deben estar separadas por espacios, por coma o por punto y coma. |
| point | [IPoint[]](/psd/python-net/aspose.gis.geometries/ipoint/) | Al regresar este método, contiene el objeto IPoint con las coordenadas analizadas, si la conversión tuvo éxito, o null si la conversión falló. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | True si el texto se analizó correctamente, de lo contrario False. |


