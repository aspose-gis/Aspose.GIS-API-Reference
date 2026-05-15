---
title: "Κλάση SimpleLabeling"
type: docs
weight: 80
url: /el/python-net/aspose.gis.rendering.labelings/simplelabeling/
---

**Summary:** A simple labeling places label on every feature.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.SimpleLabeling

**Inheritance:** Labeling

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SimpleLabeling()](#SimpleLabeling__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
| [SimpleLabeling(label_attribute)](#SimpleLabeling_label_attribute_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
| [SimpleLabeling(other)](#SimpleLabeling_other_3) | Αρχικοποιεί μια νέα παρουσία της κλάσης [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| font_color | System.Drawing.Color | r/w | Καθορίζει το χρώμα του κειμένου. |
| font_family | string | r/w | Οικογένεια γραμματοσειράς που χρησιμοποιείται για την απόδοση του κειμένου. Η προεπιλογή είναι τιμή εξαρτώμενη από το σύστημα. |
| font_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Μέγεθος του κειμένου. |
| font_style | [FontStyle](/psd/python-net/aspose.gis.rendering.labelings/fontstyle) | r/w | Στυλ που εφαρμόζεται στο κείμενο. |
| halo_color | System.Drawing.Color | r/w | Χρώμα του περιγράμματος (stroke) γύρω από το κείμενο. |
| halo_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Μέγεθος του περιγράμματος (stroke) γύρω από το κείμενο. |
| label_attribute | string | r/w | Όνομα ιδιότητας για χρήση ως πηγή ετικετών. Αγνοείται εάν το [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) είναι ορισμένο.<br/>            Είτε το [SimpleLabeling.label_attribute](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) είτε το [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) πρέπει να οριστεί πριν από την απόδοση;<br/>            Η InvalidOperationException ρίχνεται διαφορετικά. |
| multipart_mode | [MultipartMode](/psd/python-net/aspose.gis.rendering.labelings/multipartmode) | r/w | Καθορίζει τη συμπεριφορά απόδοσης για γεωμετρίες πολλαπλών τμημάτων. Η προεπιλογή είναι το [MultipartMode.ALL](/psd/python-net/aspose.gis.rendering.labelings/multipartmode/). |
| null [static] | [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling) | r | Λαμβάνει ένα αντικείμενο του [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |
| placement | [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | r/w | Η τοποθέτηση ετικετών καθορίζει πώς τοποθετούνται οι ετικέτες σχετικά με τις γεωμετρίες του χαρακτηριστικού. |
| προτεραιότητα | int | r/w | Δείχνει την προτεραιότητα αυτής της ετικέτας σε περίπτωση που επικαλύπτεται με άλλη ετικέτα. Η ετικέτα με χαμηλότερη προτεραιότητα δεν αποδίδεται.<br/>            Η προεπιλογή είναι 1000. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Κλωνοποιεί αυτό το παράδειγμα. |


### Constructor: SimpleLabeling() {#SimpleLabeling__1}


```
 SimpleLabeling() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

### Constructor: SimpleLabeling(label_attribute) {#SimpleLabeling_label_attribute_2}


```
 SimpleLabeling(label_attribute) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| label_attribute | string | Όνομα ιδιότητας για χρήση ως πηγή ετικετών. |

### Constructor: SimpleLabeling(other) {#SimpleLabeling_other_3}


```
 SimpleLabeling(other) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | Το άλλο [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) από το οποίο θα αντιγραφούν τα δεδομένα. |

### Method: clone() {#clone__1}


```
 clone() 
```

Κλωνοποιεί αυτό το παράδειγμα.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | Ένα κλώνο αυτού του αντικειμένου. |


