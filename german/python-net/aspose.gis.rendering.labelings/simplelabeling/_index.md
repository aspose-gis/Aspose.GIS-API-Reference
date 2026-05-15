---
title: "SimpleLabeling Klasse"
type: docs
weight: 80
url: /de/python-net/aspose.gis.rendering.labelings/simplelabeling/
---

**Summary:** A simple labeling places label on every feature.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.SimpleLabeling

**Inheritance:** Labeling

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [SimpleLabeling()](#SimpleLabeling__1) | Initialisiert eine neue Instanz der Klasse [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
| [SimpleLabeling(label_attribute)](#SimpleLabeling_label_attribute_2) | Initialisiert eine neue Instanz der Klasse [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
| [SimpleLabeling(other)](#SimpleLabeling_other_3) | Initialisiert eine neue Instanz der Klasse [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| font_color | System.Drawing.Color | r/w | Bestimmt die Farbe des Textes. |
| font_family | string | r/w | Schriftfamilie, die zum Rendern des Textes verwendet wird. Der Standardwert ist systemabhängig. |
| font_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Größe des Textes. |
| font_style | [FontStyle](/psd/python-net/aspose.gis.rendering.labelings/fontstyle) | r/w | Stil, der auf den Text angewendet wird. |
| halo_color | System.Drawing.Color | r/w | Farbe des Halos (Strich) um den Text. |
| halo_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Größe des Halos (Strich) um den Text. |
| label_attribute | string | r/w | Attributname, das als Quelle für Beschriftungen verwendet wird. Ignoriert, wenn [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) gesetzt ist.<br/>            Entweder [SimpleLabeling.label_attribute](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) oder [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) muss vor dem Rendern gesetzt werden;<br/>            Andernfalls wird InvalidOperationException ausgelöst. |
| multipart_mode | [MultipartMode](/psd/python-net/aspose.gis.rendering.labelings/multipartmode) | r/w | Gibt das Renderverhalten für Multipart-Geometrien an. Standard ist [MultipartMode.ALL](/psd/python-net/aspose.gis.rendering.labelings/multipartmode/). |
| null [static] | [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling) | r | Liefert eine Instanz von [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |
| placement | [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | r/w | Die Beschriftungsplatzierung gibt an, wie Beschriftungen relativ zu den Geometrien des Features platziert werden. |
| Priorität | int | r/w | Gibt die Priorität dieser Beschriftung an, falls sie mit einer anderen Beschriftung überlappt. Die Beschriftung mit niedrigerer Priorität wird nicht gerendert.<br/>            Standard ist 1000. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [clone()](#clone__1) | Klont diese Instanz. |


### Constructor: SimpleLabeling() {#SimpleLabeling__1}


```
 SimpleLabeling() 
```

Initialisiert eine neue Instanz der Klasse [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

### Constructor: SimpleLabeling(label_attribute) {#SimpleLabeling_label_attribute_2}


```
 SimpleLabeling(label_attribute) 
```

Initialisiert eine neue Instanz der Klasse [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| label_attribute | string | Attributname, das als Quelle für Beschriftungen verwendet wird. |

### Constructor: SimpleLabeling(other) {#SimpleLabeling_other_3}


```
 SimpleLabeling(other) 
```

Initialisiert eine neue Instanz der Klasse [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| other | [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | Das andere [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) zum Kopieren von Daten. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klont diese Instanz.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | Ein Klon dieser Instanz. |


