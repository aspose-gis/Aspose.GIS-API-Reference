---
title: "GeoJsonOptions Κλάση"
type: docs
weight: 20
url: /el/python-net/aspose.gis.formats.geojson/geojsonoptions/
---

**Summary:** Driver-specific options for GeoJSON format.

**Module:** [aspose.gis.formats.geojson](/psd/python-net/aspose.gis.formats.geojson/)

**Full Name:** aspose.gis.formats.geojson.GeoJsonOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GeoJsonOptions()](#GeoJsonOptions__1) | Δημιουργήστε νέα παρουσία. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| array_as_string | bool | r/w | Καθορίζει εάν να εκθέτει πίνακες JSon από συμβολοσειρές, ακέραιους ή πραγματικούς ως συμβολοσειρά. |
| attributes_skip | bool | r/w | ελέγχει τη μετάφραση των ιδιοτήτων: ναι - παράλειψη όλων των ιδιοτήτων |
| auto_id | [AutoIds](/psd/python-net/aspose.gis/autoids) | r/w | Αυτόματη δημιουργία αναγνωριστικών |
| close_linear_ring | bool | r/w | Καθορίζει εάν να κλείσει ένα ανοιχτό [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) σε κάθε γεωμετρία. Η προεπιλογή είναι <see langword="false" />. |
| create_midpoints | bool | r/w | Καθορίζει εάν να προσθέσει ένα νέο σημείο στη μέση κάθε τμήματος της γεωμετρίας. Η προεπιλογή είναι <see langword="false" />. |
| date_as_string | bool | r/w | Καθορίζει εάν να εκθέτει ημερομηνίες/ώρα/ημερομηνία-ώρα JSon ως συμβολοσειρά. |
| delete_near_points | bool | r/w | Καθορίζει εάν να διαγράψει τα κοντινά σημεία σε κάθε γεωμετρία. Η προεπιλογή είναι <see langword="false" />. |
| delete_near_points_distance | double | r/w | Καθορίζει την απόσταση για [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). Η προεπιλεγμένη τιμή είναι <see langword=\"0\" />. |
| περιγραφή | string | r/w | Περιγραφή σε επίπεδο συλλογής χαρακτηριστικών (για δημιουργία στρώματος) |
| geometry_as_collection | bool | r/w | έλεγχος μετάφρασης γεωμετριών: ναι - τυλίξτε τις γεωμετρίες με τύπο GeometryCollection |
| linearization_tolerance | double | r/w | Μία ανοχή για την εξομάλυνση γεωμετριών καμπύλης. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ένα [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) που θα εφαρμοστεί στη συντεταγμένη M<br/>            όταν οι γεωμετρίες προστίθενται στο [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ή όταν διαβάζονται από το [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Η προεπιλεγμένη τιμή είναι [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| όνομα | string | r/w | Όνομα σε επίπεδο συλλογής χαρακτηριστικών (για δημιουργία στρώματος) |
| nested_properties_separator | string | r/w | Λαμβάνει ή ορίζει μια συμβολοσειρά που χρησιμοποιείται για το διαχωρισμό των στοιχείων των ένθετων ιδιοτήτων.<br/>            Η προεπιλογή είναι \"_\". |
| read_bounding_boxes | bool | r/w | Καθορίζει εάν τα Bounding Boxes ('bbox') πρέπει να διαβαστούν ως ιδιότητες με όνομα 'bbox_0', 'bbox_1', κ.λπ.<br/>            Η προεπιλεγμένη τιμή είναι <see langword="false" />.<br/>            Η συμβολοσειρά [GeoJsonOptions.nested_properties_separator](/psd/python-net/aspose.gis.formats.geojson/geojsonoptions/) χρησιμοποιείται στα ονόματα bbox_0, bbox_1,.. |
| simplify_segments | bool | r/w | Καθορίζει αν θα διαγραφούν σημεία που βρίσκονται στο ίδιο τμήμα σε κάθε γεωμετρία. Η προεπιλεγμένη τιμή είναι <see langword=\"false\" />. |
| simplify_segments_distance | double | r/w | Καθορίζει την απόσταση για [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). Η προεπιλεγμένη τιμή είναι <see langword=\"0\" />. |
| validate_geometries_on_write | bool | r/w | Καθορίζει αν οι γεωμετρίες πρέπει να επικυρωθούν όταν προστίθενται στο επίπεδο.<br/>            Εάν οριστεί σε <see langword=\"true\" />, καλείται το [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) για κάθε γεωμετρία όταν προστίθεται στο επίπεδο, και εάν η επικύρωση αποτύχει ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) είναι <see langword=\"false\" />), ρίχνεται το [GisException](/psd/python-net/aspose.gis/gisexception/). |
| write_bounding_boxes | bool | r/w | Καθορίζει εάν τα αντικείμενα GeoJSON πρέπει να περιλαμβάνουν πληροφορίες για το εύρος συντεταγμένων των Γεωμετριών τους.<br/>            Εάν οριστεί σε <see langword="true" />, ένα μέλος "bbox" δημιουργείται για κάθε γεωμετρία (μη μηδενική) όταν προστίθεται στο στρώμα.<br/>            Η προεπιλεγμένη τιμή είναι <see langword="false" />. |
| write_polygons_as_lines | bool | r/w | Καθορίζει αν επιτρέπεται η μετατροπή πολυγώνου ή πολλαπλού πολυγώνου σε γραμμή. Η προεπιλεγμένη τιμή είναι <see langword=\"false\" />. |
| write_unset_attribute | bool | r/w | Εάν θα γραφτούν μη ορισμένα χαρακτηριστικά προσθέτοντας τιμή 'null' |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ένα [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) που θα εφαρμοστεί στις συντεταγμένες X και Y<br/>            όταν οι γεωμετρίες προστίθενται στο [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ή όταν διαβάζονται από το [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Η προεπιλεγμένη τιμή είναι [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ένα [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) που θα εφαρμοστεί στη συντεταγμένη Z<br/>            όταν οι γεωμετρίες προστίθενται στο [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ή όταν διαβάζονται από το [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Η προεπιλεγμένη τιμή είναι [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: GeoJsonOptions() {#GeoJsonOptions__1}


```
 GeoJsonOptions() 
```

Δημιουργήστε νέα παρουσία.

