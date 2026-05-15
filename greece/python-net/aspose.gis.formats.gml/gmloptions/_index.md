---
title: "GmlOptions Κλάση"
type: docs
weight: 20
url: /el/python-net/aspose.gis.formats.gml/gmloptions/
---

**Summary:** Driver-specific options for GML format.

**Module:** [aspose.gis.formats.gml](/psd/python-net/aspose.gis.formats.gml/)

**Full Name:** aspose.gis.formats.gml.GmlOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GmlOptions()](#GmlOptions__1) | Δημιουργήστε νέα παρουσία. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| application_namespace | string | r/w | Αυτό καθορίζει έναν προσαρμοσμένο χώρο ονομάτων που θα χρησιμοποιηθεί ως χώρος ονομάτων της εφαρμογής για τη δημιουργία του εγγράφου gml. |
| close_linear_ring | bool | r/w | Καθορίζει εάν να κλείσει ένα ανοιχτό [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) σε κάθε γεωμετρία. Η προεπιλογή είναι <see langword="false" />. |
| create_midpoints | bool | r/w | Καθορίζει εάν να προσθέσει ένα νέο σημείο στη μέση κάθε τμήματος της γεωμετρίας. Η προεπιλογή είναι <see langword="false" />. |
| delete_near_points | bool | r/w | Καθορίζει εάν να διαγράψει τα κοντινά σημεία σε κάθε γεωμετρία. Η προεπιλογή είναι <see langword="false" />. |
| delete_near_points_distance | double | r/w | Καθορίζει την απόσταση για [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). Η προεπιλεγμένη τιμή είναι <see langword=\"0\" />. |
| linearization_tolerance | double | r/w | Μία ανοχή για την εξομάλυνση γεωμετριών καμπύλης. |
| load_schemas_from_internet | bool | r/w | Καθορίζει εάν το Aspose.GIS επιτρέπεται να φορτώσει σχήμα XML από το Διαδίκτυο.<br/>            Εάν οριστεί σε <see langword="false" />, τα σχήματα με απόλυτα URI που δεν ξεκινούν με 'file://' δεν θα φορτωθούν.<br/>            Η προεπιλογή είναι <see langword="false" />. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ένα [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) που θα εφαρμοστεί στη συντεταγμένη M<br/>            όταν οι γεωμετρίες προστίθενται στο [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ή όταν διαβάζονται από το [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Η προεπιλεγμένη τιμή είναι [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| nested_properties_separator | string | r/w | Λαμβάνει ή ορίζει μια συμβολοσειρά που χρησιμοποιείται για το διαχωρισμό των στοιχείων των ένθετων ιδιοτήτων.<br/>            Η προεπιλογή είναι \"_\". |
| restore_schema | bool | r/w | Καθορίζει εάν το Aspose.GIS επιτρέπεται να αναλύσει τα χαρακτηριστικά σε ένα αρχείο Gml στο οποίο λείπει ή δεν μπορεί να φορτωθεί ένα σχήμα XML.<br/>            Εάν οριστεί σε <see langword="true" />, ο αναγνώστης Aspose.GIS δεν απαιτεί την παρουσία ενός σχήματος XML.<br/>            Η προεπιλογή είναι <see langword="false" />. |
| schema_location | string | r/w | Λίστα ζευγών URI χωρισμένων με κενό. Το πρώτο URI σε κάθε ζεύγος είναι ένα URI του χώρου ονομάτων, το δεύτερο URI είναι μια Διαδρομή προς το σχήμα XML του χώρου ονομάτων.<br/>            Εάν οριστεί σε <see langword="null" />, το [GmlDriver](/psd/python-net/aspose.gis.formats.gml/gmldriver/) θα προσπαθήσει να διαβάσει το schemaLocation από το στοιχείο ρίζας του εγγράφου.<br/>            Η προεπιλογή είναι <see langword="null" />. |
| simplify_segments | bool | r/w | Καθορίζει αν θα διαγραφούν σημεία που βρίσκονται στο ίδιο τμήμα σε κάθε γεωμετρία. Η προεπιλεγμένη τιμή είναι <see langword=\"false\" />. |
| simplify_segments_distance | double | r/w | Καθορίζει την απόσταση για [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). Η προεπιλεγμένη τιμή είναι <see langword=\"0\" />. |
| validate_geometries_on_write | bool | r/w | Καθορίζει αν οι γεωμετρίες πρέπει να επικυρωθούν όταν προστίθενται στο επίπεδο.<br/>            Εάν οριστεί σε <see langword=\"true\" />, καλείται το [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) για κάθε γεωμετρία όταν προστίθεται στο επίπεδο, και εάν η επικύρωση αποτύχει ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) είναι <see langword=\"false\" />), ρίχνεται το [GisException](/psd/python-net/aspose.gis/gisexception/). |
| write_polygons_as_lines | bool | r/w | Καθορίζει αν επιτρέπεται η μετατροπή πολυγώνου ή πολλαπλού πολυγώνου σε γραμμή. Η προεπιλεγμένη τιμή είναι <see langword=\"false\" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ένα [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) που θα εφαρμοστεί στις συντεταγμένες X και Y<br/>            όταν οι γεωμετρίες προστίθενται στο [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ή όταν διαβάζονται από το [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Η προεπιλεγμένη τιμή είναι [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ένα [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) που θα εφαρμοστεί στη συντεταγμένη Z<br/>            όταν οι γεωμετρίες προστίθενται στο [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ή όταν διαβάζονται από το [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Η προεπιλεγμένη τιμή είναι [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: GmlOptions() {#GmlOptions__1}


```
 GmlOptions() 
```

Δημιουργήστε νέα παρουσία.

