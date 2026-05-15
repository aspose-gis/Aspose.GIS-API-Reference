---
title: "GeoConvert Klasse"
type: docs
weight: 1140
url: /de/python-net/aspose.gis/geoconvert/
---

**Summary:** Converts coordinates to/from the different formats.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.GeoConvert

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [as_point_text(latitude, longitude, format)](#as_point_text_latitude_longitude_format_1) | Gibt die berechnete Position als Zeichenkette im angegebenen Format zurück. |
| [as_point_text(point, format)](#as_point_text_point_format_2) | Gibt die berechnete Position als Zeichenkette im angegebenen Format zurück. |
| [parse_point_text(text)](#parse_point_text_text_3) | Konvertiert die Zeichenkette, die Koordinaten enthält, in ein IPoint-Objekt. |
| [try_parse_point_text(text, point)](#try_parse_point_text_text_point_4) | Konvertiert die Zeichenkette, die Koordinaten enthält, in ein IPoint-Objekt. Der Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist. |


### Method: as_point_text(latitude, longitude, format)  [static] {#as_point_text_latitude_longitude_format_1}


```
 as_point_text(latitude, longitude, format) 
```

Gibt die berechnete Position als Zeichenkette im angegebenen Format zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Breitengrad | double | Breitengrad der Position. |
| Längengrad | double | Längengrad der Position. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | Format des Ergebnisses. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Position als Zeichenkette. |


### Method: as_point_text(point, format)  [static] {#as_point_text_point_format_2}


```
 as_point_text(point, format) 
```

Gibt die berechnete Position als Zeichenkette im angegebenen Format zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | IPoint-Objekt. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | Format des Ergebnisses. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Position als Zeichenkette. |


### Method: parse_point_text(text)  [static] {#parse_point_text_text_3}


```
 parse_point_text(text) 
```

Konvertiert die Zeichenkette, die Koordinaten enthält, in ein IPoint-Objekt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| text | string | Eine Zeichenkette, die zu konvertierende Koordinaten enthält.<br/>            Die Zeichenkette sollte sowohl den Breitengrad als auch den Längengrad enthalten.<br/>            Koordinaten sollten durch Leerzeichen, Komma oder Semikolon getrennt sein. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | IPoint-Objekt mit Koordinaten, die dem Eingabestring entsprechen. |


### Method: try_parse_point_text(text, point)  [static] {#try_parse_point_text_text_point_4}


```
 try_parse_point_text(text, point) 
```

Konvertiert die Zeichenkette, die Koordinaten enthält, in ein IPoint-Objekt. Der Rückgabewert gibt an, ob die Konvertierung erfolgreich war oder fehlgeschlagen ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| text | string | Eine Zeichenkette, die zu konvertierende Koordinaten enthält.<br/>            Die Zeichenkette sollte sowohl den Breitengrad als auch den Längengrad enthalten.<br/>            Koordinaten sollten durch Leerzeichen, Komma oder Semikolon getrennt sein. |
| point | [IPoint[]](/psd/python-net/aspose.gis.geometries/ipoint/) | Wenn diese Methode zurückkehrt, enthält sie das IPoint-Objekt mit den geparsten Koordinaten, falls die Konvertierung erfolgreich war, oder null, falls die Konvertierung fehlgeschlagen ist. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | True, wenn der Text erfolgreich geparst wurde, sonst False. |


