---
title: "SimpleLabeling Klasse"
type: docs
weight: 80
url: /nl/python-net/aspose.gis.rendering.labelings/simplelabeling/
---

**Summary:** A simple labeling places label on every feature.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.SimpleLabeling

**Inheritance:** Labeling

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [SimpleLabeling()](#SimpleLabeling__1) | Initialiseert een nieuw exemplaar van de [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) klasse. |
| [SimpleLabeling(label_attribute)](#SimpleLabeling_label_attribute_2) | Initialiseert een nieuw exemplaar van de [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) klasse. |
| [SimpleLabeling(other)](#SimpleLabeling_other_3) | Initialiseert een nieuw exemplaar van de [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| font_color | System.Drawing.Color | r/w | Bepaalt de kleur van de tekst. |
| font_family | string | r/w | Lettertypefamilie om tekst weer te geven. De standaard is een systeemafhankelijke waarde. |
| font_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Grootte van de tekst. |
| font_style | [FontStyle](/psd/python-net/aspose.gis.rendering.labelings/fontstyle) | r/w | Stijl toe te passen op tekst. |
| halo_color | System.Drawing.Color | r/w | Kleur van de halo (stroke) rond de tekst. |
| halo_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Grootte van de halo (stroke) rond de tekst. |
| label_attribute | string | r/w | Attribuutnaam die gebruikt wordt als bron voor labels. Genegeerd als [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) is ingesteld.<br/>            Ofwel [SimpleLabeling.label_attribute](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) of [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) moet ingesteld zijn vóór het renderen;<br/>            InvalidOperationException wordt anders gegooid. |
| multipart_mode | [MultipartMode](/psd/python-net/aspose.gis.rendering.labelings/multipartmode) | r/w | Specificeert het rendergedrag voor multipart-geometrieën. Standaard is [MultipartMode.ALL](/psd/python-net/aspose.gis.rendering.labelings/multipartmode/). |
| null [static] | [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling) | r | Haalt een exemplaar op van [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |
| placement | [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | r/w | Labelplaatsing geeft aan hoe labels relatief ten opzichte van de geometrieën van een feature worden geplaatst. |
| prioriteit | int | r/w | Geeft de prioriteit van dit label aan voor het geval het overlapt met een ander label. Het label met een lagere prioriteit wordt niet gerenderd.<br/>            Standaard is 1000. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [clone()](#clone__1) | Kloont deze instantie. |


### Constructor: SimpleLabeling() {#SimpleLabeling__1}


```
 SimpleLabeling() 
```

Initialiseert een nieuw exemplaar van de [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) klasse.

### Constructor: SimpleLabeling(label_attribute) {#SimpleLabeling_label_attribute_2}


```
 SimpleLabeling(label_attribute) 
```

Initialiseert een nieuw exemplaar van de [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| label_attribute | string | Attribuutnaam die gebruikt wordt als bron voor labels. |

### Constructor: SimpleLabeling(other) {#SimpleLabeling_other_3}


```
 SimpleLabeling(other) 
```

Initialiseert een nieuw exemplaar van de [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| other | [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | De andere [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) om gegevens van te kopiëren. |

### Method: clone() {#clone__1}


```
 clone() 
```

Kloont deze instantie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | Een kloon van dit exemplaar. |


