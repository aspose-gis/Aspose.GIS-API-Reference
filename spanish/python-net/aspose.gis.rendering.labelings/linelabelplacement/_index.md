---
title: "Clase LineLabelPlacement"
type: docs
weight: 40
url: /es/python-net/aspose.gis.rendering.labelings/linelabelplacement/
---

**Summary:** Line label placement places labels along line.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LineLabelPlacement

**Inheritance:** LabelPlacement

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [LineLabelPlacement()](#LineLabelPlacement__1) | Crea una nueva instancia. |
| [LineLabelPlacement(other)](#LineLabelPlacement_other_2) | Crea una nueva instancia. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| alignment | [LineLabelAlignment](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment) | r/w | Especifica cómo se alinea la etiqueta con la ruta lineal. El valor predeterminado es [LineLabelAlignment.PARALLEL](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment/). |
| max_angle_delta | double | r/w | Cuando se usa con [LineLabelAlignment.CURVED](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment/) establece el ángulo máximo en grados entre dos<br/>            caracteres subsecuentes en una etiqueta curvada. El valor predeterminado es 25. |
| offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | El desplazamiento desde la ruta lineal.<br/>            Los valores positivos se desplazan a la izquierda de la línea, los negativos a la derecha. El valor predeterminado es 0. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [clone()](#clone__1) | Clona esta instancia. |


### Constructor: LineLabelPlacement() {#LineLabelPlacement__1}


```
 LineLabelPlacement() 
```

Crea una nueva instancia.

### Constructor: LineLabelPlacement(other) {#LineLabelPlacement_other_2}


```
 LineLabelPlacement(other) 
```

Crea una nueva instancia.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [LineLabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/linelabelplacement) | El otro [LineLabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/linelabelplacement/) del cual copiar datos. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clona esta instancia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | Una copia de esta instancia. |


