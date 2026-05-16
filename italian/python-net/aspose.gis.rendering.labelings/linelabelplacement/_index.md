---
title: "Classe LineLabelPlacement"
type: docs
weight: 40
url: /it/python-net/aspose.gis.rendering.labelings/linelabelplacement/
---

**Summary:** Line label placement places labels along line.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LineLabelPlacement

**Inheritance:** LabelPlacement

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [LineLabelPlacement()](#LineLabelPlacement__1) | Crea una nuova istanza. |
| [LineLabelPlacement(other)](#LineLabelPlacement_other_2) | Crea una nuova istanza. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| alignment | [LineLabelAlignment](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment) | r/w | Specifica come l'etichetta è allineata al percorso lineare. L'impostazione predefinita è [LineLabelAlignment.PARALLEL](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment/). |
| max_angle_delta | double | r/w | Quando usato con [LineLabelAlignment.CURVED](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment/) imposta l'angolo massimo in gradi tra due<br/>            caratteri successivi in un'etichetta curva. Il valore predefinito è 25. |
| offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Lo spostamento dal percorso lineare.<br/>            I valori positivi spostano a sinistra della linea, i valori negativi a destra. Il valore predefinito è 0. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [clone()](#clone__1) | Clona questa istanza. |


### Constructor: LineLabelPlacement() {#LineLabelPlacement__1}


```
 LineLabelPlacement() 
```

Crea una nuova istanza.

### Constructor: LineLabelPlacement(other) {#LineLabelPlacement_other_2}


```
 LineLabelPlacement(other) 
```

Crea una nuova istanza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | [LineLabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/linelabelplacement) | L'altro [LineLabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/linelabelplacement/) da cui copiare i dati. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clona questa istanza.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | Una copia di questa istanza. |


