---
title: "Clase SimpleLabeling"
type: docs
weight: 80
url: /es/python-net/aspose.gis.rendering.labelings/simplelabeling/
---

**Summary:** A simple labeling places label on every feature.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.SimpleLabeling

**Inheritance:** Labeling

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [SimpleLabeling()](#SimpleLabeling__1) | Inicializa una nueva instancia de la clase [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
| [SimpleLabeling(label_attribute)](#SimpleLabeling_label_attribute_2) | Inicializa una nueva instancia de la clase [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
| [SimpleLabeling(other)](#SimpleLabeling_other_3) | Inicializa una nueva instancia de la clase [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| font_color | System.Drawing.Color | r/w | Determina el color del texto. |
| font_family | string | r/w | Familia tipográfica a usar para renderizar texto. El valor predeterminado depende del sistema. |
| font_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Tamaño del texto. |
| font_style | [FontStyle](/psd/python-net/aspose.gis.rendering.labelings/fontstyle) | r/w | Estilo a aplicar al texto. |
| halo_color | System.Drawing.Color | r/w | Color del halo (trazo) alrededor del texto. |
| halo_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Tamaño del halo (trazo) alrededor del texto. |
| label_attribute | string | r/w | Nombre del atributo a usar como fuente de etiquetas. Se ignora si [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) está establecido.<br/>            Ya sea [SimpleLabeling.label_attribute](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) o [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) deben estar establecidos antes de renderizar;<br/>            De lo contrario se lanza InvalidOperationException. |
| multipart_mode | [MultipartMode](/psd/python-net/aspose.gis.rendering.labelings/multipartmode) | r/w | Especifica el comportamiento de renderizado para geometrías multipartes. El valor predeterminado es [MultipartMode.ALL](/psd/python-net/aspose.gis.rendering.labelings/multipartmode/). |
| null [static] | [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling) | r | Obtiene una instancia de [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |
| placement | [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | r/w | La ubicación de la etiqueta especifica cómo se colocan las etiquetas en relación con las geometrías de la entidad. |
| prioridad | int | r/w | Indica la prioridad de esta etiqueta en caso de que se superponga con otra etiqueta. La etiqueta con menor prioridad no se renderiza.<br/>            El valor predeterminado es 1000. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [clone()](#clone__1) | Clona esta instancia. |


### Constructor: SimpleLabeling() {#SimpleLabeling__1}


```
 SimpleLabeling() 
```

Inicializa una nueva instancia de la clase [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

### Constructor: SimpleLabeling(label_attribute) {#SimpleLabeling_label_attribute_2}


```
 SimpleLabeling(label_attribute) 
```

Inicializa una nueva instancia de la clase [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| label_attribute | string | Nombre del atributo a usar como fuente de etiquetas. |

### Constructor: SimpleLabeling(other) {#SimpleLabeling_other_3}


```
 SimpleLabeling(other) 
```

Inicializa una nueva instancia de la clase [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| other | [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | El otro [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) del cual copiar datos. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clona esta instancia.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | Una copia de esta instancia. |


