---
title: "SimpleLabeling-klass"
type: docs
weight: 80
url: /sv/python-net/aspose.gis.rendering.labelings/simplelabeling/
---

**Summary:** A simple labeling places label on every feature.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.SimpleLabeling

**Inheritance:** Labeling

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [SimpleLabeling()](#SimpleLabeling__1) | Initierar en ny instans av klassen [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
| [SimpleLabeling(label_attribute)](#SimpleLabeling_label_attribute_2) | Initierar en ny instans av klassen [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
| [SimpleLabeling(other)](#SimpleLabeling_other_3) | Initierar en ny instans av klassen [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| font_color | System.Drawing.Color | läs/skriv | Bestämmer färgen på texten. |
| font_family | string | läs/skriv | Typsnittsfamilj att använda för att rendera text. Standardvärdet beror på systemet. |
| font_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Textens storlek. |
| font_style | [FontStyle](/psd/python-net/aspose.gis.rendering.labelings/fontstyle) | r/w | Stil att tillämpa på text. |
| halo_color | System.Drawing.Color | läs/skriv | Färgen på halo (kontur) runt texten. |
| halo_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Storleken på halo (kontur) runt texten. |
| label_attribute | string | r/w | Attributnamn att använda som källa för etiketter. Ignoreras om [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) är angivet.<br/>            Antingen [SimpleLabeling.label_attribute](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) eller [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) måste vara angivet innan rendering;<br/>            InvalidOperationException kastas annars. |
| multipart_mode | [MultipartMode](/psd/python-net/aspose.gis.rendering.labelings/multipartmode) | r/w | Anger renderingsbeteende för multipart-geometrier. Standard är [MultipartMode.ALL](/psd/python-net/aspose.gis.rendering.labelings/multipartmode/). |
| null [static] | [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling) | r | Hämtar en instans av [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |
| placement | [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | r/w | Etikettplacering specificerar hur etiketter placeras relativt till objektets geometrier. |
| prioritet | int | läs/skriv | Anger prioriteten för denna etikett om den överlappar en annan etikett. Etiketten med lägre prioritet renderas inte.<br/>            Standard är 1000. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [clone()](#clone__1) | Klonar detta objekt. |


### Constructor: SimpleLabeling() {#SimpleLabeling__1}


```
 SimpleLabeling() 
```

Initierar en ny instans av klassen [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

### Constructor: SimpleLabeling(label_attribute) {#SimpleLabeling_label_attribute_2}


```
 SimpleLabeling(label_attribute) 
```

Initierar en ny instans av klassen [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| label_attribute | string | Attributnamn att använda som källa för etiketter. |

### Constructor: SimpleLabeling(other) {#SimpleLabeling_other_3}


```
 SimpleLabeling(other) 
```

Initierar en ny instans av klassen [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | Den andra [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) att kopiera data från. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klonar detta objekt.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | En klon av denna instans. |


