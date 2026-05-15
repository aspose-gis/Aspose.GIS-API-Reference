---
title: "Κλάση SimpleMarker"
type: docs
weight: 130
url: /el/python-net/aspose.gis.rendering.symbolizers/simplemarker/
---

**Summary:** Simple point symbolizer.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.SimpleMarker

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SimpleMarker()](#SimpleMarker__1) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/). |
| [SimpleMarker(other)](#SimpleMarker_other_2) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| fill_color | System.Drawing.Color | r/w | Καθορίζει το χρώμα και τη διαφάνεια για τη γέμιση. |
| horizontal_anchor_point | [HorizontalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/horizontalanchor) | r/w | Καθορίζει ποια πλευρά του σχήματος του δείκτη θα ευθυγραμμιστεί οριζόντια με τη θέση του σημείου. |
| horizontal_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Καθορίζει την οριζόντια μετατόπιση από τη θέση ενός σημείου προς το σημείο αγκύρωσης του σχήματος. |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | Το [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) δεν σχεδιάζει τίποτα και ουσιαστικά παραλείπει την απόδοση μιας γεωμετρίας στην οποία εφαρμόζεται. |
| περιστροφή | double | r/w | Καθορίζει την περιστροφή του συμβόλου γύρω από το κεντρικό του σημείο, σε δεκαδικούς μοίρες.<br/>            Οι θετικές τιμές υποδεικνύουν περιστροφή προς τη φορά των δεικτών του ρολογιού, οι αρνητικές τιμές υποδεικνύουν περιστροφή αντίθετη προς τη φορά των δεικτών. |
| shape_type | [MarkerShapeType](/psd/python-net/aspose.gis.rendering.symbolizers/markershapetype) | r/w | Καθορίζει το σχήμα του δείκτη. |
| size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Καθορίζει το μέγεθος του δείκτη. |
| stroke_color | System.Drawing.Color | r/w | Καθορίζει το χρώμα και τη διαφάνεια που δίνονται στη γραμμή. |
| stroke_dash_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Καθορίζει την απόσταση από την αρχή μιας γραμμής μέχρι την αρχή του μοτίβου παύλας. |
| stroke_dash_pattern | System.Collections.Generic.IEnumerable<Measurement> | r/w | Καθορίζει έναν πίνακα αποστάσεων που καθορίζει τα μήκη των εναλλασσόμενων παύλων και κενών<br/>            σε γραμμές με παύλες. |
| stroke_line_join | [LineJoin](/psd/python-net/aspose.gis.rendering/linejoin) | r/w | Καθορίζει πώς αποδίδονται οι γραμμές στη διασταύρωση των τμημάτων γραμμής. |
| stroke_style | [StrokeStyle](/psd/python-net/aspose.gis.rendering/strokestyle) | r/w | Καθορίζει πώς πρέπει να σχεδιαστούν οι γραμμές του συμβόλου. |
| stroke_width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Καθορίζει το πλάτος της γραμμής. |
| vertical_anchor_point | [VerticalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/verticalanchor) | r/w | Καθορίζει ποια πλευρά ενός σχήματος δείκτη θα ευθυγραμμιστεί κάθετα με τη θέση του σημείου. |
| vertical_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Καθορίζει την κάθετη μετατόπιση από τη θέση ενός σημείου προς το σημείο αγκύρωσης του σχήματος. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Κλωνοποιεί αυτό το παράδειγμα. |


### Constructor: SimpleMarker() {#SimpleMarker__1}


```
 SimpleMarker() 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/).

### Constructor: SimpleMarker(other) {#SimpleMarker_other_2}


```
 SimpleMarker(other) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker) | Ο άλλος [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/) από τον οποίο θα αντιγραφούν τα δεδομένα. |

### Method: clone() {#clone__1}


```
 clone() 
```

Κλωνοποιεί αυτό το παράδειγμα.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker) | Ένα κλώνο αυτού του αντικειμένου. |


