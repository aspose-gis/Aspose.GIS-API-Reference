---
title: "Classe SimpleLabeling"
type: docs
weight: 80
url: /fr/python-net/aspose.gis.rendering.labelings/simplelabeling/
---

**Summary:** A simple labeling places label on every feature.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.SimpleLabeling

**Inheritance:** Labeling

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SimpleLabeling()](#SimpleLabeling__1) | Initialise une nouvelle instance de la classe [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
| [SimpleLabeling(label_attribute)](#SimpleLabeling_label_attribute_2) | Initialise une nouvelle instance de la classe [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
| [SimpleLabeling(other)](#SimpleLabeling_other_3) | Initialise une nouvelle instance de la classe [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| font_color | System.Drawing.Color | r/w | Détermine la couleur du texte. |
| font_family | string | r/w | Famille de police à utiliser pour rendre le texte. La valeur par défaut dépend du système. |
| font_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Taille du texte. |
| font_style | [FontStyle](/psd/python-net/aspose.gis.rendering.labelings/fontstyle) | r/w | Style à appliquer au texte. |
| halo_color | System.Drawing.Color | r/w | Couleur du halo (contour) autour du texte. |
| halo_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Taille du halo (contour) autour du texte. |
| label_attribute | string | r/w | Nom d'attribut à utiliser comme source d'étiquettes. Ignoré si [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) est défini.<br/>            Soit [SimpleLabeling.label_attribute](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) ou [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) doit être défini avant le rendu;<br/>            InvalidOperationException est levée sinon. |
| multipart_mode | [MultipartMode](/psd/python-net/aspose.gis.rendering.labelings/multipartmode) | r/w | Spécifie le comportement de rendu pour les géométries multiparties. La valeur par défaut est [MultipartMode.ALL](/psd/python-net/aspose.gis.rendering.labelings/multipartmode/). |
| null [static] | [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling) | r | Obtient une instance de [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |
| placement | [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | r/w | Le placement des étiquettes spécifie comment les étiquettes sont positionnées par rapport aux géométries de l'entité. |
| priorité | int | r/w | Indique la priorité de cette étiquette au cas où elle chevauche une autre étiquette. L'étiquette avec la priorité la plus basse n'est pas rendue.<br/>            La valeur par défaut est 1000. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Clone cette instance. |


### Constructor: SimpleLabeling() {#SimpleLabeling__1}


```
 SimpleLabeling() 
```

Initialise une nouvelle instance de la classe [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

### Constructor: SimpleLabeling(label_attribute) {#SimpleLabeling_label_attribute_2}


```
 SimpleLabeling(label_attribute) 
```

Initialise une nouvelle instance de la classe [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| label_attribute | string | Nom d'attribut à utiliser comme source d'étiquettes. |

### Constructor: SimpleLabeling(other) {#SimpleLabeling_other_3}


```
 SimpleLabeling(other) 
```

Initialise une nouvelle instance de la classe [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| other | [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | L'autre [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) dont les données sont copiées. |

### Method: clone() {#clone__1}


```
 clone() 
```

Clone cette instance.

**Returns**

| Type | Description |
| :- | :- |
| [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | Un clone de cette instance. |


