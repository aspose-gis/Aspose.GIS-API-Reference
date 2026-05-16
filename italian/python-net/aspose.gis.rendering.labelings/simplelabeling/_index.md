---
title: "Classe SimpleLabeling"
type: docs
weight: 80
url: /it/python-net/aspose.gis.rendering.labelings/simplelabeling/
---

**Summary:** A simple labeling places label on every feature.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.SimpleLabeling

**Inheritance:** Labeling

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [SimpleLabeling()](#SimpleLabeling__1) | Inizializza una nuova istanza della classe [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
| [SimpleLabeling(label_attribute)](#SimpleLabeling_label_attribute_2) | Inizializza una nuova istanza della classe [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
| [SimpleLabeling(other)](#SimpleLabeling_other_3) | Inizializza una nuova istanza della classe [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| font_color | System.Drawing.Color | r/w | Determina il colore del testo. |
| font_family | string | r/w | Famiglia di caratteri da utilizzare per renderizzare il testo. Il valore predefinito dipende dal sistema. |
| font_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Dimensione del testo. |
| font_style | [FontStyle](/psd/python-net/aspose.gis.rendering.labelings/fontstyle) | r/w | Stile da applicare al testo. |
| halo_color | System.Drawing.Color | r/w | Colore dell'alone (tratto) attorno al testo. |
| halo_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Dimensione dell'alone (tratto) attorno al testo. |
| label_attribute | string | r/w | Nome dell'attributo da utilizzare come origine delle etichette. Ignorato se [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) è impostato.<br/>            O [SimpleLabeling.label_attribute](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) o [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) devono essere impostati prima del rendering;<br/>            Altrimenti viene sollevata InvalidOperationException. |
| multipart_mode | [MultipartMode](/psd/python-net/aspose.gis.rendering.labelings/multipartmode) | r/w | Specifica il comportamento di rendering per geometrie multipart. L'impostazione predefinita è [MultipartMode.ALL](/psd/python-net/aspose.gis.rendering.labelings/multipartmode/). |
| null [static] | [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling) | r | Ottiene un'istanza di [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |
| placement | [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | r/w | Il posizionamento delle etichette specifica come le etichette sono collocate rispetto alle geometrie della feature. |
| priorità | int | r/w | Indica la priorità di questa etichetta nel caso si sovrapponga a un'altra etichetta. L'etichetta con priorità più bassa non viene renderizzata.<br/>            Il valore predefinito è 1000. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [clone()](#clone__1) | Clona questa istanza. |


### Constructor: SimpleLabeling() {#SimpleLabeling__1}


```
 SimpleLabeling() 
```

Inizializza una nuova istanza della classe [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

### Constructor: SimpleLabeling(label_attribute) {#SimpleLabeling_label_attribute_2}


```
 SimpleLabeling(label_attribute) 
```

Inizializza una nuova istanza della classe [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| label_attribute | string | Nome dell'attributo da utilizzare come fonte delle etichette. |

### Constructor: SimpleLabeling(other) {#SimpleLabeling_other_3}


```
 SimpleLabeling(other) 
```

Inizializza una nuova istanza della classe [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| other | [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | L'altro [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) da cui copiare i dati. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clona questa istanza.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | Una copia di questa istanza. |


