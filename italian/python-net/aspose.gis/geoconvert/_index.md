---
title: "Classe GeoConvert"
type: docs
weight: 1140
url: /it/python-net/aspose.gis/geoconvert/
---

**Summary:** Converts coordinates to/from the different formats.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.GeoConvert

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [as_point_text(latitude, longitude, format)](#as_point_text_latitude_longitude_format_1) | Restituisce la posizione calcolata come stringa nel formato specificato. |
| [as_point_text(point, format)](#as_point_text_point_format_2) | Restituisce la posizione calcolata come stringa nel formato specificato. |
| [parse_point_text(text)](#parse_point_text_text_3) | Converte la stringa che contiene le coordinate in un oggetto IPoint. |
| [try_parse_point_text(text, point)](#try_parse_point_text_text_point_4) | Converte la stringa che contiene le coordinate in un oggetto IPoint. Un valore di ritorno indica se la conversione è riuscita o meno. |


### Method: as_point_text(latitude, longitude, format)  [static] {#as_point_text_latitude_longitude_format_1}


```
 as_point_text(latitude, longitude, format) 
```

Restituisce la posizione calcolata come stringa nel formato specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| latitudine | double | Latitudine della posizione. |
| longitudine | double | Longitudine della posizione. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | Formato del risultato. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Posizione come stringa. |


### Method: as_point_text(point, format)  [static] {#as_point_text_point_format_2}


```
 as_point_text(point, format) 
```

Restituisce la posizione calcolata come stringa nel formato specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Oggetto IPoint. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | Formato del risultato. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Posizione come stringa. |


### Method: parse_point_text(text)  [static] {#parse_point_text_text_3}


```
 parse_point_text(text) 
```

Converte la stringa che contiene le coordinate in un oggetto IPoint.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| text | string | Una stringa che contiene le coordinate da convertire.<br/>            La stringa deve contenere sia la latitudine che la longitudine.<br/>            Le coordinate devono essere separate da spazi, da una virgola o da un punto e virgola. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Oggetto IPoint con coordinate equivalenti alla stringa di input. |


### Method: try_parse_point_text(text, point)  [static] {#try_parse_point_text_text_point_4}


```
 try_parse_point_text(text, point) 
```

Converte la stringa che contiene le coordinate in un oggetto IPoint. Un valore di ritorno indica se la conversione è riuscita o meno.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| text | string | Una stringa che contiene le coordinate da convertire.<br/>            La stringa deve contenere sia la latitudine che la longitudine.<br/>            Le coordinate devono essere separate da spazi, da una virgola o da un punto e virgola. |
| point | [IPoint[]](/psd/python-net/aspose.gis.geometries/ipoint/) | Al termine di questo metodo, contiene l'oggetto IPoint con le coordinate analizzate, se la conversione è riuscita, oppure null se la conversione è fallita. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | True se il testo è stato analizzato correttamente, altrimenti False. |


