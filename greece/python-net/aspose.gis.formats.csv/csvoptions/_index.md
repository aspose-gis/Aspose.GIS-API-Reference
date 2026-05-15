---
title: "CsvOptions Κλάση"
type: docs
weight: 20
url: /el/python-net/aspose.gis.formats.csv/csvoptions/
---

**Summary:** Driver-specific options for CSV format.

**Module:** [aspose.gis.formats.csv](/psd/python-net/aspose.gis.formats.csv/)

**Full Name:** aspose.gis.formats.csv.CsvOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CsvOptions()](#CsvOptions__1) | Δημιουργήστε νέα παρουσία. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | Καθορίζει εάν να κλείσει ένα ανοιχτό [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) σε κάθε γεωμετρία. Η προεπιλογή είναι <see langword="false" />. |
| column_m | string | r/w | Λαμβάνει ή ορίζει ένα όνομα στήλης που περιέχει την τιμή συντεταγμένης M.<br/>            Η προεπιλογή είναι <see langword=\"null\" />. |
| column_wkt | string | r/w | Λαμβάνει ή ορίζει ένα όνομα στήλης που περιέχει το Well-Known Text για την αναπαράσταση γεωμετρίας.<br/>            Η προεπιλογή είναι <see langword=\"null\" />. |
| column_x | string | r/w | Λαμβάνει ή ορίζει ένα όνομα στήλης που περιέχει την τιμή συντεταγμένης X.<br/>            Η προεπιλογή είναι <see langword=\"null\" />. |
| column_y | string | r/w | Λαμβάνει ή ορίζει ένα όνομα στήλης που περιέχει την τιμή συντεταγμένης Y.<br/>            Η προεπιλογή είναι <see langword=\"null\" />. |
| column_z | string | r/w | Λαμβάνει ή ορίζει ένα όνομα στήλης που περιέχει την τιμή συντεταγμένης Z.<br/>            Η προεπιλογή είναι <see langword=\"null\" />. |
| create_midpoints | bool | r/w | Καθορίζει εάν να προσθέσει ένα νέο σημείο στη μέση κάθε τμήματος της γεωμετρίας. Η προεπιλογή είναι <see langword="false" />. |
| delete_near_points | bool | r/w | Καθορίζει εάν να διαγράψει τα κοντινά σημεία σε κάθε γεωμετρία. Η προεπιλογή είναι <see langword="false" />. |
| delete_near_points_distance | double | r/w | Καθορίζει την απόσταση για [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). Η προεπιλεγμένη τιμή είναι <see langword=\"0\" />. |
| delimiter | char | r/w | Λαμβάνει ή ορίζει έναν χαρακτήρα που χρησιμοποιείται ως διαχωριστικό για τον διαχωρισμό τιμών.<br/>            Η προεπιλογή είναι ','. |
| double_quote_escape | char | r/w | Λαμβάνει ή ορίζει έναν χαρακτήρα που χρησιμοποιείται ως χαρακτήρας διαφυγής για διπλά εισαγωγικά.<br/>            Η προεπιλογή είναι '\"'. |
| has_attribute_names | bool | r/w | Καθορίζει αν υπάρχει γραμμή κεφαλίδας με ονόματα χαρακτηριστικών.<br/>            Η προεπιλογή είναι <see langword=\"true\" />. |
| linearization_tolerance | double | r/w | Μία ανοχή για την εξομάλυνση γεωμετριών καμπύλης. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ένα [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) που θα εφαρμοστεί στη συντεταγμένη M<br/>            όταν οι γεωμετρίες προστίθενται στο [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ή όταν διαβάζονται από το [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Η προεπιλεγμένη τιμή είναι [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| simplify_segments | bool | r/w | Καθορίζει αν θα διαγραφούν σημεία που βρίσκονται στο ίδιο τμήμα σε κάθε γεωμετρία. Η προεπιλεγμένη τιμή είναι <see langword=\"false\" />. |
| simplify_segments_distance | double | r/w | Καθορίζει την απόσταση για [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). Η προεπιλεγμένη τιμή είναι <see langword=\"0\" />. |
| start_line_number | int | r/w | Λαμβάνει ή ορίζει έναν μηδενικό αριθμό γραμμής που θα είναι η πρώτη όταν διαβάζονται τα δεδομένα.<br/>            Η προεπιλογή είναι 0. |
| validate_geometries_on_write | bool | r/w | Καθορίζει αν οι γεωμετρίες πρέπει να επικυρωθούν όταν προστίθενται στο επίπεδο.<br/>            Εάν οριστεί σε <see langword=\"true\" />, καλείται το [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) για κάθε γεωμετρία όταν προστίθεται στο επίπεδο, και εάν η επικύρωση αποτύχει ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) είναι <see langword=\"false\" />), ρίχνεται το [GisException](/psd/python-net/aspose.gis/gisexception/). |
| write_polygons_as_lines | bool | r/w | Καθορίζει αν επιτρέπεται η μετατροπή πολυγώνου ή πολλαπλού πολυγώνου σε γραμμή. Η προεπιλεγμένη τιμή είναι <see langword=\"false\" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ένα [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) που θα εφαρμοστεί στις συντεταγμένες X και Y<br/>            όταν οι γεωμετρίες προστίθενται στο [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ή όταν διαβάζονται από το [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Η προεπιλεγμένη τιμή είναι [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ένα [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) που θα εφαρμοστεί στη συντεταγμένη Z<br/>            όταν οι γεωμετρίες προστίθενται στο [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ή όταν διαβάζονται από το [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Η προεπιλεγμένη τιμή είναι [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: CsvOptions() {#CsvOptions__1}


```
 CsvOptions() 
```

Δημιουργήστε νέα παρουσία.

