---
title: "Classe SimpleLine"
type: docs
weight: 120
url: /fr/python-net/aspose.gis.rendering.symbolizers/simpleline/
---

**Summary:** Simple line symbolizer.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.SimpleLine

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SimpleLine()](#SimpleLine__1) | Crée une nouvelle instance. |
| [SimpleLine(other)](#SimpleLine_other_2) | Initialise une nouvelle instance de la classe [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cap_style | [CapStyle](/psd/python-net/aspose.gis.rendering/capstyle) | r/w | Spécifie comment les lignes sont rendues à leurs extrémités. |
| couleur | System.Drawing.Color | r/w | Spécifie la couleur et la transparence appliquées à la ligne. |
| dash_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Spécifie la distance du début d'une ligne au commencement d'un motif de tirets. |
| dash_pattern | System.Collections.Generic.IEnumerable<Measurement> | r/w | Spécifie un tableau de distances qui indique les longueurs des tirets et espaces alternés<br/>            dans les lignes pointillées. |
| line_join | [LineJoin](/psd/python-net/aspose.gis.rendering/linejoin) | r/w | Détermine comment les lignes sont rendues à l'intersection des segments de ligne. |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | Le [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) ne dessine rien et saute effectivement le rendu d'une géométrie à laquelle il est appliqué. |
| offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Spécifie le décalage par rapport à la ligne originale.<br/>            Pour une distance positive, le décalage sera du côté gauche de la ligne d'entrée (par rapport à la direction de la ligne).<br/>            Pour une distance négative, il sera du côté droit. |
| style | [StrokeStyle](/psd/python-net/aspose.gis.rendering/strokestyle) | r/w | Spécifie comment les lignes du symbole doivent être dessinées. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Spécifie la largeur de la ligne. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clone cette instance. |


### Constructor: SimpleLine() {#SimpleLine__1}


```
 SimpleLine() 
```

Crée une nouvelle instance.

### Constructor: SimpleLine(other) {#SimpleLine_other_2}


```
 SimpleLine(other) 
```

Initialise une nouvelle instance de la classe [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline) | L'autre [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline/) pour copier les données depuis. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clone cette instance.

**Returns**

| Type | Description |
| :- | :- |
| [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline) | Un clone de cette instance. |


