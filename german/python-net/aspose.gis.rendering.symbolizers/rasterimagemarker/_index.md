---
title: "RasterImageMarker Klasse"
type: docs
weight: 80
url: /de/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/
---

**Summary:** This symbolizer renders a provided raster image.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.RasterImageMarker

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [RasterImageMarker(image_path)](#RasterImageMarker_image_path_1) | Initialisiert eine neue Instanz der [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) Klasse. |
| [RasterImageMarker(image_path)](#RasterImageMarker_image_path_2) | Initialisiert eine neue Instanz der [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) Klasse. |
| [RasterImageMarker(other)](#RasterImageMarker_other_3) | Initialisiert eine neue Instanz der [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Gibt die Höhe des Markers an. |
| horizontal_anchor_point | [HorizontalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/horizontalanchor) | r/w | gibt an, welche Seite einer Markierungsform horizontal mit dem Punktstandort ausgerichtet wird. |
| horizontal_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Gibt den horizontalen Versatz von einem Punktstandort zum Ankerpunkt der Form an. |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | Der [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) zeichnet nichts und überspringt effektiv das Rendern einer Geometrie, auf die er angewendet wird. |
| Deckkraft | double | r/w | Deckkraft der Ebene. Standardwert ist 1.0. |
| Drehung | double | r/w | Gibt die Drehung des Symbols um seinen Mittelpunkt in Dezimalgrad an.<br/>            Positive Werte bedeuten eine Drehung im Uhrzeigersinn, negative Werte bedeuten eine Drehung gegen den Uhrzeigersinn. |
| vertical_anchor_point | [VerticalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/verticalanchor) | r/w | Gibt an, welche Seite einer Markierungsform vertikal mit dem Punktstandort ausgerichtet wird. |
| vertical_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Gibt den vertikalen Versatz von einem Punktstandort zum Ankerpunkt der Form an. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Gibt die Breite des Markers an. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Klont diese Instanz. |


### Constructor: RasterImageMarker(image_path) {#RasterImageMarker_image_path_1}


```
 RasterImageMarker(image_path) 
```

Initialisiert eine neue Instanz der [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_path | string | Pfad zur Datei. |

### Constructor: RasterImageMarker(image_path) {#RasterImageMarker_image_path_2}


```
 RasterImageMarker(image_path) 
```

Initialisiert eine neue Instanz der [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| image_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Datei. |

### Constructor: RasterImageMarker(other) {#RasterImageMarker_other_3}


```
 RasterImageMarker(other) 
```

Initialisiert eine neue Instanz der [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker) | Der andere [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) zum Kopieren von Daten. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klont diese Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker) | Ein Klon dieser Instanz. |


