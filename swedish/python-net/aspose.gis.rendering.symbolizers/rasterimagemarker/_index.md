---
title: "RasterImageMarker klass"
type: docs
weight: 80
url: /sv/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/
---

**Summary:** This symbolizer renders a provided raster image.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.RasterImageMarker

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [RasterImageMarker(image_path)](#RasterImageMarker_image_path_1) | Initierar en ny instans av klassen [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/). |
| [RasterImageMarker(image_path)](#RasterImageMarker_image_path_2) | Initierar en ny instans av klassen [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/). |
| [RasterImageMarker(other)](#RasterImageMarker_other_3) | Initierar en ny instans av klassen [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Anger markörens höjd. |
| horizontal_anchor_point | [HorizontalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/horizontalanchor) | r/w | anger vilken sida av en markörform som ska justeras horisontellt med punktens position. |
| horizontal_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Anger horisontell förskjutning från en punktposition till formens ankarpunkt. |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | Den [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) ritar ingenting och hoppar effektivt över rendering av en geometri som den tillämpas på. |
| opacitet | double | läs/skriv | Opacitet för lagret. Standardvärdet är 1.0. |
| rotation | double | läs/skriv | Anger symbolens rotation kring dess mittpunkt, i decimalgrader.<br/>            Positiva värden indikerar rotation i medurs riktning, negativa värden indikerar moturs rotation. |
| vertical_anchor_point | [VerticalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/verticalanchor) | r/w | Anger vilken sida av en markörform som ska justeras vertikalt med punktens position. |
| vertical_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Anger vertikal förskjutning från en punktposition till formens ankarpunkt. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Anger markörens bredd. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [clone()](#clone__1) | Klonar detta objekt. |


### Constructor: RasterImageMarker(image_path) {#RasterImageMarker_image_path_1}


```
 RasterImageMarker(image_path) 
```

Initierar en ny instans av klassen [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_path | string | Sökväg till filen. |

### Constructor: RasterImageMarker(image_path) {#RasterImageMarker_image_path_2}


```
 RasterImageMarker(image_path) 
```

Initierar en ny instans av klassen [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till filen. |

### Constructor: RasterImageMarker(other) {#RasterImageMarker_other_3}


```
 RasterImageMarker(other) 
```

Initierar en ny instans av klassen [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker) | Den andra [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) att kopiera data från. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klonar detta objekt.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker) | En klon av denna instans. |


