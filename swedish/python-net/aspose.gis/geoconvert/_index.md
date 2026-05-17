---
title: "GeoConvert-klass"
type: docs
weight: 1140
url: /sv/python-net/aspose.gis/geoconvert/
---

**Summary:** Converts coordinates to/from the different formats.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.GeoConvert

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [as_point_text(latitude, longitude, format)](#as_point_text_latitude_longitude_format_1) | Returnerar den beräknade positionen som en sträng i det angivna formatet. |
| [as_point_text(point, format)](#as_point_text_point_format_2) | Returnerar den beräknade positionen som en sträng i det angivna formatet. |
| [parse_point_text(text)](#parse_point_text_text_3) | Konverterar strängen som innehåller koordinater till IPoint-objekt. |
| [try_parse_point_text(text, point)](#try_parse_point_text_text_point_4) | Konverterar strängen som innehåller koordinater till IPoint-objekt. Ett returvärde indikerar om konverteringen lyckades eller misslyckades. |


### Method: as_point_text(latitude, longitude, format)  [static] {#as_point_text_latitude_longitude_format_1}


```
 as_point_text(latitude, longitude, format) 
```

Returnerar den beräknade positionen som en sträng i det angivna formatet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| latitud | double | Positionslatitud. |
| longitud | double | Positionslongitud. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | Resultatets format. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Position som sträng. |


### Method: as_point_text(point, format)  [static] {#as_point_text_point_format_2}


```
 as_point_text(point, format) 
```

Returnerar den beräknade positionen som en sträng i det angivna formatet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | IPoint-objekt. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | Resultatets format. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Position som sträng. |


### Method: parse_point_text(text)  [static] {#parse_point_text_text_3}


```
 parse_point_text(text) 
```

Konverterar strängen som innehåller koordinater till IPoint-objekt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| text | string | En sträng som innehåller koordinater att konvertera.<br/>            Strängen bör innehålla både koordinatens latitud och longitud.<br/>            Koordinaterna bör separeras med blanksteg, komma eller semikolon. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | IPoint-objekt med koordinater som är ekvivalenta med inmatningssträngen. |


### Method: try_parse_point_text(text, point)  [static] {#try_parse_point_text_text_point_4}


```
 try_parse_point_text(text, point) 
```

Konverterar strängen som innehåller koordinater till IPoint-objekt. Ett returvärde indikerar om konverteringen lyckades eller misslyckades.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| text | string | En sträng som innehåller koordinater att konvertera.<br/>            Strängen bör innehålla både koordinatens latitud och longitud.<br/>            Koordinaterna bör separeras med blanksteg, komma eller semikolon. |
| point | [IPoint[]](/psd/python-net/aspose.gis.geometries/ipoint/) | När denna metod returnerar, innehåller den IPoint-objektet med parsade koordinater om konverteringen lyckades, eller null om konverteringen misslyckades. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Sant om texten parsades framgångsrikt, annars Falskt. |


