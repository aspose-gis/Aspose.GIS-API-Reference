---
title: "LineLabelPlacement-klass"
type: docs
weight: 40
url: /sv/python-net/aspose.gis.rendering.labelings/linelabelplacement/
---

**Summary:** Line label placement places labels along line.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LineLabelPlacement

**Inheritance:** LabelPlacement

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [LineLabelPlacement()](#LineLabelPlacement__1) | Skapar ny instans. |
| [LineLabelPlacement(other)](#LineLabelPlacement_other_2) | Skapar ny instans. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| alignment | [LineLabelAlignment](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment) | r/w | Anger hur etiketten är justerad med den linjära vägen. Standard är [LineLabelAlignment.PARALLEL](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment/). |
| max_angle_delta | double | r/w | När den används med [LineLabelAlignment.CURVED](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment/) anger den maximala vinkeln i grader mellan två<br/>            efterföljande tecken i en böjd etikett. Standard är 25. |
| offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Förskjutningen från den linjära vägen.<br/>            Positiva värden förskjuter åt vänster om linjen, negativa åt höger. Standard är 0. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [clone()](#clone__1) | Klonar detta objekt. |


### Constructor: LineLabelPlacement() {#LineLabelPlacement__1}


```
 LineLabelPlacement() 
```

Skapar ny instans.

### Constructor: LineLabelPlacement(other) {#LineLabelPlacement_other_2}


```
 LineLabelPlacement(other) 
```

Skapar ny instans.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [LineLabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/linelabelplacement) | Den andra [LineLabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/linelabelplacement/) att kopiera data från. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klonar detta objekt.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | En klon av denna instans. |


