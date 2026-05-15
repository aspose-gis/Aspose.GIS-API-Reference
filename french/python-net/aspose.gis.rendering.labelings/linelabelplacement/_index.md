---
title: "LineLabelPlacement Classe"
type: docs
weight: 40
url: /fr/python-net/aspose.gis.rendering.labelings/linelabelplacement/
---

**Summary:** Line label placement places labels along line.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LineLabelPlacement

**Inheritance:** LabelPlacement

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LineLabelPlacement()](#LineLabelPlacement__1) | Crée une nouvelle instance. |
| [LineLabelPlacement(other)](#LineLabelPlacement_other_2) | Crée une nouvelle instance. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alignment | [LineLabelAlignment](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment) | r/w | Spécifie comment l'étiquette est alignée avec le chemin linéaire. La valeur par défaut est [LineLabelAlignment.PARALLEL](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment/). |
| max_angle_delta | double | r/w | Lorsqu'il est utilisé avec [LineLabelAlignment.CURVED](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment/), définit l'angle maximal en degrés entre deux<br/>            caractères subséquents dans une étiquette courbée. La valeur par défaut est 25. |
| offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Le décalage par rapport au chemin linéaire.<br/>            Les valeurs positives décalent vers la gauche de la ligne, les négatives vers la droite. La valeur par défaut est 0. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clone cette instance. |


### Constructor: LineLabelPlacement() {#LineLabelPlacement__1}


```
 LineLabelPlacement() 
```

Crée une nouvelle instance.

### Constructor: LineLabelPlacement(other) {#LineLabelPlacement_other_2}


```
 LineLabelPlacement(other) 
```

Crée une nouvelle instance.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [LineLabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/linelabelplacement) | L'autre [LineLabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/linelabelplacement/) dont les données seront copiées. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clone cette instance.

**Returns**

| Type | Description |
| :- | :- |
| [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | Un clone de cette instance. |


