---
title: "LineLabelPlacement Klasse"
type: docs
weight: 40
url: /de/python-net/aspose.gis.rendering.labelings/linelabelplacement/
---

**Summary:** Line label placement places labels along line.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LineLabelPlacement

**Inheritance:** LabelPlacement

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [LineLabelPlacement()](#LineLabelPlacement__1) | Erstellt eine neue Instanz. |
| [LineLabelPlacement(other)](#LineLabelPlacement_other_2) | Erstellt eine neue Instanz. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| alignment | [LineLabelAlignment](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment) | r/w | Gibt an, wie die Beschriftung mit dem linearen Pfad ausgerichtet wird. Standard ist [LineLabelAlignment.PARALLEL](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment/). |
| max_angle_delta | double | r/w | Wird es zusammen mit [LineLabelAlignment.CURVED](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment/) verwendet, legt es den maximalen Winkel in Grad zwischen zwei<br/>            aufeinanderfolgenden Zeichen in einer gekrümmten Beschriftung fest. Standard ist 25. |
| offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Der Versatz vom linearen Pfad.<br/>            Positive Werte verschieben nach links von der Linie, negative nach rechts. Standard ist 0. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Klont diese Instanz. |


### Constructor: LineLabelPlacement() {#LineLabelPlacement__1}


```
 LineLabelPlacement() 
```

Erstellt eine neue Instanz.

### Constructor: LineLabelPlacement(other) {#LineLabelPlacement_other_2}


```
 LineLabelPlacement(other) 
```

Erstellt eine neue Instanz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [LineLabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/linelabelplacement) | Das andere [LineLabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/linelabelplacement/) zum Kopieren von Daten. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klont diese Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | Ein Klon dieser Instanz. |


