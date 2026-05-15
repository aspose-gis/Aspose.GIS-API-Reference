---
title: "FileGdbOptions Κλάση"
type: docs
weight: 30
url: /el/python-net/aspose.gis.formats.filegdb/filegdboptions/
---

**Summary:** Driver-specific options for FileGDB format.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FileGdbOptions()](#FileGdbOptions__1) | Δημιουργήστε νέα παρουσία. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | Καθορίζει εάν να κλείσει ένα ανοιχτό [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) σε κάθε γεωμετρία. Η προεπιλογή είναι <see langword="false" />. |
| coordinate_precision_grid | [FileGdbCoordinatePrecisionGrid](/psd/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid) | r/w | Ένα πλέγμα ακρίβειας συντεταγμένων για χρήση σε νέο επίπεδο. |
| create_midpoints | bool | r/w | Καθορίζει εάν να προσθέσει ένα νέο σημείο στη μέση κάθε τμήματος της γεωμετρίας. Η προεπιλογή είναι <see langword="false" />. |
| delete_near_points | bool | r/w | Καθορίζει εάν να διαγράψει τα κοντινά σημεία σε κάθε γεωμετρία. Η προεπιλογή είναι <see langword="false" />. |
| delete_near_points_distance | double | r/w | Καθορίζει την απόσταση για [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). Η προεπιλεγμένη τιμή είναι <see langword=\"0\" />. |
| ensure_valid_coordinates_range | bool | r/w | Κατά πόσο οι συντεταγμένες πρέπει να βρίσκονται σε έγκυρο εύρος. |
| expected_geometry_type | Nullable<Aspose.Gis.Geometries.GeometryType> | r/w | Αναμενόμενος τύπος γεωμετρίας για το επίπεδο. Εάν αυτή η επιλογή οριστεί, τότε επιτρέπεται η προσθήκη μόνο γεωμετριών με αυτόν τον τύπο. |
| geometry_field_name | string | r/w | Όνομα του πεδίου γεωμετρίας. |
| has_m | bool | r/w | Μπορούν οι γεωμετρίες του επιπέδου να έχουν συντεταγμένη 'm'. Από προεπιλογή είναι true. |
| has_z | bool | r/w | Μπορούν οι γεωμετρίες του επιπέδου να έχουν συντεταγμένη 'z'. Από προεπιλογή είναι true |
| linearization_tolerance | double | r/w | Μία ανοχή για την εξομάλυνση γεωμετριών καμπύλης. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ένα [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) που θα εφαρμοστεί στη συντεταγμένη M<br/>            όταν οι γεωμετρίες προστίθενται στο [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ή όταν διαβάζονται από το [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Η προεπιλεγμένη τιμή είναι [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| m_tolerance | Nullable<double> | r/w | Απόσταση προσαρμογής M. |
| object_id_field_name | string | r/w | Όνομα του πεδίου αναγνωριστικού αντικειμένου. |
| simplify_segments | bool | r/w | Καθορίζει αν θα διαγραφούν σημεία που βρίσκονται στο ίδιο τμήμα σε κάθε γεωμετρία. Η προεπιλεγμένη τιμή είναι <see langword=\"false\" />. |
| simplify_segments_distance | double | r/w | Καθορίζει την απόσταση για [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). Η προεπιλεγμένη τιμή είναι <see langword=\"0\" />. |
| validate_geometries_on_write | bool | r/w | Καθορίζει αν οι γεωμετρίες πρέπει να επικυρωθούν όταν προστίθενται στο επίπεδο.<br/>            Εάν οριστεί σε <see langword=\"true\" />, καλείται το [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) για κάθε γεωμετρία όταν προστίθεται στο επίπεδο, και εάν η επικύρωση αποτύχει ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) είναι <see langword=\"false\" />), ρίχνεται το [GisException](/psd/python-net/aspose.gis/gisexception/). |
| write_polygons_as_lines | bool | r/w | Καθορίζει αν επιτρέπεται η μετατροπή πολυγώνου ή πολλαπλού πολυγώνου σε γραμμή. Η προεπιλεγμένη τιμή είναι <see langword=\"false\" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ένα [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) που θα εφαρμοστεί στις συντεταγμένες X και Y<br/>            όταν οι γεωμετρίες προστίθενται στο [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ή όταν διαβάζονται από το [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Η προεπιλεγμένη τιμή είναι [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| xy_tolerance | Nullable<double> | r/w | Απόσταση προσαρμογής X και Y. |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ένα [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) που θα εφαρμοστεί στη συντεταγμένη Z<br/>            όταν οι γεωμετρίες προστίθενται στο [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ή όταν διαβάζονται από το [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Η προεπιλεγμένη τιμή είναι [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_tolerance | Nullable<double> | r/w | Απόσταση προσαρμογής Z. |


### Constructor: FileGdbOptions() {#FileGdbOptions__1}


```
 FileGdbOptions() 
```

Δημιουργήστε νέα παρουσία.

