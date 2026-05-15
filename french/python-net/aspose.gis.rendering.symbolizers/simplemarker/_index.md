---
title: "Classe SimpleMarker"
type: docs
weight: 130
url: /fr/python-net/aspose.gis.rendering.symbolizers/simplemarker/
---

**Summary:** Simple point symbolizer.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.SimpleMarker

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SimpleMarker()](#SimpleMarker__1) | Initialise une nouvelle instance de la classe [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/). |
| [SimpleMarker(other)](#SimpleMarker_other_2) | Initialise une nouvelle instance de la classe [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| fill_color | System.Drawing.Color | r/w | Spécifie la couleur et la transparence du remplissage. |
| horizontal_anchor_point | [HorizontalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/horizontalanchor) | r/w | Spécifie quel côté d’une forme de marqueur sera aligné horizontalement avec l’emplacement du point. |
| horizontal_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Spécifie le décalage horizontal d'un emplacement de point vers le point d'ancrage de la forme. |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | Le [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) ne dessine rien et saute effectivement le rendu d'une géométrie à laquelle il est appliqué. |
| rotation | double | r/w | Spécifie la rotation du symbole autour de son point central, en degrés décimaux.<br/>            Les valeurs positives indiquent une rotation dans le sens horaire, les valeurs négatives indiquent une rotation dans le sens antihoraire. |
| shape_type | [MarkerShapeType](/psd/python-net/aspose.gis.rendering.symbolizers/markershapetype) | r/w | Spécifie la forme du marqueur. |
| size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Spécifie la taille du marqueur. |
| stroke_color | System.Drawing.Color | r/w | Spécifie la couleur et la transparence appliquées à la ligne. |
| stroke_dash_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Spécifie la distance du début d'une ligne au commencement d'un motif de tirets. |
| stroke_dash_pattern | System.Collections.Generic.IEnumerable<Measurement> | r/w | Spécifie un tableau de distances qui indique les longueurs des tirets et espaces alternés<br/>            dans les lignes pointillées. |
| stroke_line_join | [LineJoin](/psd/python-net/aspose.gis.rendering/linejoin) | r/w | Détermine comment les lignes sont rendues à l'intersection des segments de ligne. |
| stroke_style | [StrokeStyle](/psd/python-net/aspose.gis.rendering/strokestyle) | r/w | Spécifie comment les lignes du symbole doivent être dessinées. |
| stroke_width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Spécifie la largeur de la ligne. |
| vertical_anchor_point | [VerticalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/verticalanchor) | r/w | Spécifie quel côté d'une forme de marqueur sera aligné verticalement avec l'emplacement du point. |
| vertical_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Spécifie le décalage vertical d'un emplacement de point vers le point d'ancrage de la forme. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clone cette instance. |


### Constructor: SimpleMarker() {#SimpleMarker__1}


```
 SimpleMarker() 
```

Initialise une nouvelle instance de la classe [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/).

### Constructor: SimpleMarker(other) {#SimpleMarker_other_2}


```
 SimpleMarker(other) 
```

Initialise une nouvelle instance de la classe [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker) | L’autre [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/) dont les données seront copiées. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clone cette instance.

**Returns**

| Type | Description |
| :- | :- |
| [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker) | Un clone de cette instance. |


