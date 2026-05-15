---
title: "Classe RasterImageMarker"
type: docs
weight: 80
url: /fr/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/
---

**Summary:** This symbolizer renders a provided raster image.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.RasterImageMarker

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RasterImageMarker(image_path)](#RasterImageMarker_image_path_1) | Initialise une nouvelle instance de la classe [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/). |
| [RasterImageMarker(image_path)](#RasterImageMarker_image_path_2) | Initialise une nouvelle instance de la classe [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/). |
| [RasterImageMarker(other)](#RasterImageMarker_other_3) | Initialise une nouvelle instance de la classe [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Spécifie la hauteur du marqueur. |
| horizontal_anchor_point | [HorizontalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/horizontalanchor) | r/w | spécifie quel côté d'une forme de marqueur sera aligné horizontalement avec l'emplacement du point. |
| horizontal_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Spécifie le décalage horizontal d'un emplacement de point vers le point d'ancrage de la forme. |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | Le [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) ne dessine rien et saute effectivement le rendu d'une géométrie à laquelle il est appliqué. |
| opacité | double | r/w | Opacité du calque. La valeur par défaut est 1,0. |
| rotation | double | r/w | Spécifie la rotation du symbole autour de son point central, en degrés décimaux.<br/>            Les valeurs positives indiquent une rotation dans le sens horaire, les valeurs négatives indiquent une rotation dans le sens antihoraire. |
| vertical_anchor_point | [VerticalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/verticalanchor) | r/w | Spécifie quel côté d'une forme de marqueur sera aligné verticalement avec l'emplacement du point. |
| vertical_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Spécifie le décalage vertical d'un emplacement de point vers le point d'ancrage de la forme. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Spécifie la largeur du marqueur. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clone cette instance. |


### Constructor: RasterImageMarker(image_path) {#RasterImageMarker_image_path_1}


```
 RasterImageMarker(image_path) 
```

Initialise une nouvelle instance de la classe [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image_path | string | Chemin vers le fichier. |

### Constructor: RasterImageMarker(image_path) {#RasterImageMarker_image_path_2}


```
 RasterImageMarker(image_path) 
```

Initialise une nouvelle instance de la classe [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le fichier. |

### Constructor: RasterImageMarker(other) {#RasterImageMarker_other_3}


```
 RasterImageMarker(other) 
```

Initialise une nouvelle instance de la classe [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker) | L'autre [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) pour copier les données depuis. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clone cette instance.

**Returns**

| Type | Description |
| :- | :- |
| [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker) | Un clone de cette instance. |


