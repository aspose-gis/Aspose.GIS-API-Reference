---
title: "GeoConvert Klasse"
type: docs
weight: 1140
url: /nl/python-net/aspose.gis/geoconvert/
---

**Summary:** Converts coordinates to/from the different formats.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.GeoConvert

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [as_point_text(latitude, longitude, format)](#as_point_text_latitude_longitude_format_1) | Retourneert de berekende positie als een tekenreeks in het opgegeven formaat. |
| [as_point_text(point, format)](#as_point_text_point_format_2) | Retourneert de berekende positie als een tekenreeks in het opgegeven formaat. |
| [parse_point_text(text)](#parse_point_text_text_3) | Converteert de tekenreeks die coördinaten bevat naar een IPoint-object. |
| [try_parse_point_text(text, point)](#try_parse_point_text_text_point_4) | Converteert de tekenreeks die coördinaten bevat naar een IPoint-object. Een retourwaarde geeft aan of de conversie geslaagd is of mislukt. |


### Method: as_point_text(latitude, longitude, format)  [static] {#as_point_text_latitude_longitude_format_1}


```
 as_point_text(latitude, longitude, format) 
```

Retourneert de berekende positie als een tekenreeks in het opgegeven formaat.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| latitude | double | Positie breedtegraad. |
| longitude | double | Positie lengtegraad. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | Formaat van het resultaat. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | Positie als tekenreeks. |


### Method: as_point_text(point, format)  [static] {#as_point_text_point_format_2}


```
 as_point_text(point, format) 
```

Retourneert de berekende positie als een tekenreeks in het opgegeven formaat.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | IPoint-object. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | Formaat van het resultaat. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | Positie als tekenreeks. |


### Method: parse_point_text(text)  [static] {#parse_point_text_text_3}


```
 parse_point_text(text) 
```

Converteert de tekenreeks die coördinaten bevat naar een IPoint-object.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | string | Een tekenreeks die coördinaten bevat om te converteren.<br/>            De tekenreeks moet zowel breedtegraad als lengtegraad bevatten.<br/>            Coördinaten moeten gescheiden worden door witruimte, een komma of een puntkomma. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | IPoint-object met coördinaten die gelijk zijn aan de invoertekenreeks. |


### Method: try_parse_point_text(text, point)  [static] {#try_parse_point_text_text_point_4}


```
 try_parse_point_text(text, point) 
```

Converteert de tekenreeks die coördinaten bevat naar een IPoint-object. Een retourwaarde geeft aan of de conversie geslaagd is of mislukt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | string | Een tekenreeks die coördinaten bevat om te converteren.<br/>            De tekenreeks moet zowel breedtegraad als lengtegraad bevatten.<br/>            Coördinaten moeten gescheiden worden door witruimte, een komma of een puntkomma. |
| point | [IPoint[]](/psd/python-net/aspose.gis.geometries/ipoint/) | Wanneer deze methode terugkeert, bevat het het IPoint-object met geparseerde coördinaten, als de conversie geslaagd is, of null als de conversie mislukt. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | True als de tekst succesvol is geparseerd, anders False. |


