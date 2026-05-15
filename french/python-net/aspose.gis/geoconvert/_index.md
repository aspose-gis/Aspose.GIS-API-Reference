---
title: "GeoConvert Classe"
type: docs
weight: 1140
url: /fr/python-net/aspose.gis/geoconvert/
---

**Summary:** Converts coordinates to/from the different formats.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.GeoConvert

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [as_point_text(latitude, longitude, format)](#as_point_text_latitude_longitude_format_1) | Renvoie la position calculée sous forme de chaîne dans le format spécifié. |
| [as_point_text(point, format)](#as_point_text_point_format_2) | Renvoie la position calculée sous forme de chaîne dans le format spécifié. |
| [parse_point_text(text)](#parse_point_text_text_3) | Convertit la chaîne contenant des coordonnées en objet IPoint. |
| [try_parse_point_text(text, point)](#try_parse_point_text_text_point_4) | Convertit la chaîne contenant des coordonnées en objet IPoint. Une valeur de retour indique si la conversion a réussi ou échoué. |


### Method: as_point_text(latitude, longitude, format)  [static] {#as_point_text_latitude_longitude_format_1}


```
 as_point_text(latitude, longitude, format) 
```

Renvoie la position calculée sous forme de chaîne dans le format spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| latitude | double | Latitude de la position. |
| longitude | double | Longitude de la position. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | Format du résultat. |

**Returns**

| Type | Description |
| :- | :- |
| string | Position sous forme de chaîne. |


### Method: as_point_text(point, format)  [static] {#as_point_text_point_format_2}


```
 as_point_text(point, format) 
```

Renvoie la position calculée sous forme de chaîne dans le format spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Objet IPoint. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | Format du résultat. |

**Returns**

| Type | Description |
| :- | :- |
| string | Position sous forme de chaîne. |


### Method: parse_point_text(text)  [static] {#parse_point_text_text_3}


```
 parse_point_text(text) 
```

Convertit la chaîne contenant des coordonnées en objet IPoint.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| text | string | Une chaîne contenant des coordonnées à convertir.<br/>            La chaîne doit contenir à la fois la latitude et la longitude.<br/>            Les coordonnées doivent être séparées par un espace, une virgule ou un point-virgule. |

**Returns**

| Type | Description |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Objet IPoint avec des coordonnées équivalentes à la chaîne d'entrée. |


### Method: try_parse_point_text(text, point)  [static] {#try_parse_point_text_text_point_4}


```
 try_parse_point_text(text, point) 
```

Convertit la chaîne contenant des coordonnées en objet IPoint. Une valeur de retour indique si la conversion a réussi ou échoué.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| text | string | Une chaîne contenant des coordonnées à convertir.<br/>            La chaîne doit contenir à la fois la latitude et la longitude.<br/>            Les coordonnées doivent être séparées par un espace, une virgule ou un point-virgule. |
| point | [IPoint[]](/psd/python-net/aspose.gis.geometries/ipoint/) | Lorsque cette méthode retourne, elle contient l'objet IPoint avec les coordonnées analysées si la conversion a réussi, ou null si la conversion a échoué. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Vrai si le texte a été analysé avec succès, sinon Faux. |


