---
title: "MapInfoTabOptions Κλάση"
type: docs
weight: 20
url: /el/python-net/aspose.gis.formats.mapinfotab/mapinfotaboptions/
---

**Summary:** Driver-specific options for MapInfo Tab format.

**Module:** [aspose.gis.formats.mapinfotab](/psd/python-net/aspose.gis.formats.mapinfotab/)

**Full Name:** aspose.gis.formats.mapinfotab.MapInfoTabOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MapInfoTabOptions()](#MapInfoTabOptions__1) | Δημιουργήστε νέα παρουσία. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| block_size | int | r/w | Μέγεθος μπλοκ για αρχεία '*.map' (πολλαπλάσια του 512). Η προεπιλογή είναι 16384. Έγκυρες τιμές: 512 έως 32256. |
| close_linear_ring | bool | r/w | Καθορίζει εάν να κλείσει ένα ανοιχτό [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) σε κάθε γεωμετρία. Η προεπιλογή είναι <see langword="false" />. |
| create_midpoints | bool | r/w | Καθορίζει εάν να προσθέσει ένα νέο σημείο στη μέση κάθε τμήματος της γεωμετρίας. Η προεπιλογή είναι <see langword="false" />. |
| delete_near_points | bool | r/w | Καθορίζει εάν να διαγράψει τα κοντινά σημεία σε κάθε γεωμετρία. Η προεπιλογή είναι <see langword="false" />. |
| delete_near_points_distance | double | r/w | Καθορίζει την απόσταση για [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). Η προεπιλεγμένη τιμή είναι <see langword=\"0\" />. |
| is_ignore_wrong_data | bool | r/w | Καθορίζει αν πρέπει να ρίξουμε εξαίρεση κατά την εργασία με λανθασμένα δεδομένα ή να ορίσουμε προεπιλεγμένες τιμές γι' αυτά. |
| linearization_tolerance | double | r/w | Μία ανοχή για την εξομάλυνση γεωμετριών καμπύλης. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ένα [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) που θα εφαρμοστεί στη συντεταγμένη M<br/>            όταν οι γεωμετρίες προστίθενται στο [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ή όταν διαβάζονται από το [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Η προεπιλεγμένη τιμή είναι [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| simplify_segments | bool | r/w | Καθορίζει αν θα διαγραφούν σημεία που βρίσκονται στο ίδιο τμήμα σε κάθε γεωμετρία. Η προεπιλεγμένη τιμή είναι <see langword=\"false\" />. |
| simplify_segments_distance | double | r/w | Καθορίζει την απόσταση για [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). Η προεπιλεγμένη τιμή είναι <see langword=\"0\" />. |
| text_string_attribute | string | r/w | Καθορίζει το όνομα του χαρακτηριστικού που αντιπροσωπεύει το κείμενο του γραφικού αντικειμένου 'Text'. |
| validate_geometries_on_write | bool | r/w | Καθορίζει αν οι γεωμετρίες πρέπει να επικυρωθούν όταν προστίθενται στο επίπεδο.<br/>            Εάν οριστεί σε <see langword=\"true\" />, καλείται το [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) για κάθε γεωμετρία όταν προστίθεται στο επίπεδο, και εάν η επικύρωση αποτύχει ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) είναι <see langword=\"false\" />), ρίχνεται το [GisException](/psd/python-net/aspose.gis/gisexception/). |
| write_polygons_as_lines | bool | r/w | Καθορίζει αν επιτρέπεται η μετατροπή πολυγώνου ή πολλαπλού πολυγώνου σε γραμμή. Η προεπιλεγμένη τιμή είναι <see langword=\"false\" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ένα [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) που θα εφαρμοστεί στις συντεταγμένες X και Y<br/>            όταν οι γεωμετρίες προστίθενται στο [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ή όταν διαβάζονται από το [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Η προεπιλεγμένη τιμή είναι [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ένα [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) που θα εφαρμοστεί στη συντεταγμένη Z<br/>            όταν οι γεωμετρίες προστίθενται στο [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ή όταν διαβάζονται από το [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Η προεπιλεγμένη τιμή είναι [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: MapInfoTabOptions() {#MapInfoTabOptions__1}


```
 MapInfoTabOptions() 
```

Δημιουργήστε νέα παρουσία.

