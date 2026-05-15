---
title: "Κλάση RasterImageMarker"
type: docs
weight: 80
url: /el/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/
---

**Summary:** This symbolizer renders a provided raster image.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.RasterImageMarker

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RasterImageMarker(image_path)](#RasterImageMarker_image_path_1) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/). |
| [RasterImageMarker(image_path)](#RasterImageMarker_image_path_2) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/). |
| [RasterImageMarker(other)](#RasterImageMarker_other_3) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Καθορίζει το ύψος του marker. |
| horizontal_anchor_point | [HorizontalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/horizontalanchor) | r/w | Καθορίζει ποια πλευρά ενός σχήματος δείκτη θα ευθυγραμμιστεί οριζόντια με τη θέση του σημείου. |
| horizontal_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Καθορίζει την οριζόντια μετατόπιση από τη θέση ενός σημείου προς το σημείο αγκύρωσης του σχήματος. |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | Το [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) δεν σχεδιάζει τίποτα και ουσιαστικά παραλείπει την απόδοση μιας γεωμετρίας στην οποία εφαρμόζεται. |
| opacity | double | r/w | Διαφάνεια του επιπέδου. Η προεπιλεγμένη τιμή είναι 1.0. |
| περιστροφή | double | r/w | Καθορίζει την περιστροφή του συμβόλου γύρω από το κεντρικό του σημείο, σε δεκαδικούς μοίρες.<br/>            Οι θετικές τιμές υποδεικνύουν περιστροφή προς τη φορά των δεικτών του ρολογιού, οι αρνητικές τιμές υποδεικνύουν περιστροφή αντίθετη προς τη φορά των δεικτών. |
| vertical_anchor_point | [VerticalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/verticalanchor) | r/w | Καθορίζει ποια πλευρά ενός σχήματος δείκτη θα ευθυγραμμιστεί κάθετα με τη θέση του σημείου. |
| vertical_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Καθορίζει την κάθετη μετατόπιση από τη θέση ενός σημείου προς το σημείο αγκύρωσης του σχήματος. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Καθορίζει το πλάτος του marker. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Κλωνοποιεί αυτό το παράδειγμα. |


### Constructor: RasterImageMarker(image_path) {#RasterImageMarker_image_path_1}


```
 RasterImageMarker(image_path) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image_path | string | Διαδρομή προς το αρχείο. |

### Constructor: RasterImageMarker(image_path) {#RasterImageMarker_image_path_2}


```
 RasterImageMarker(image_path) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το αρχείο. |

### Constructor: RasterImageMarker(other) {#RasterImageMarker_other_3}


```
 RasterImageMarker(other) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker) | Το άλλο [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) για αντιγραφή δεδομένων από. |

### Method: clone() {#clone__1}


```
 clone() 
```

Κλωνοποιεί αυτό το παράδειγμα.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker) | Ένα κλώνο αυτού του αντικειμένου. |


