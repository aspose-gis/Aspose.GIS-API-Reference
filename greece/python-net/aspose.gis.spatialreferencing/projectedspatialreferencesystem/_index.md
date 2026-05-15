---
title: "Κλάση ProjectedSpatialReferenceSystem"
type: docs
weight: 150
url: /el/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/
---

**Summary:** Projected SRS is a result of application a projection to geographic SRS.<br/>            A projected SRS can be two dimensional or three dimensional.<br/>            If projected SRS is three dimensional, then it is actually a compound SRS of two dimensional projected SRS and one dimensional vertical SRS.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.ProjectedSpatialReferenceSystem

**Inheritance:** SpatialReferenceSystem

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| angular_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Μονάδα που χρησιμοποιείται για γωνιακές τιμές σε αυτό το SRS και για γωνιακές παραμέτρους του [ProjectedSpatialReferenceSystem.projection](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/).<br/>            Συμφωνεί με τη γωνιακή μονάδα του [ProjectedSpatialReferenceSystem.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/). |
| as_compound | [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | r | Επιστρέφει αυτό το SRS μετατρεπόμενο σε [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/).<br/>            Χρησιμοποιήστε το [SpatialReferenceSystem.is_compound](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) για να διαπιστώσετε αν η μετατροπή είναι δυνατή. |
| as_geocentric | [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | r | Επιστρέφει αυτό το SRS μετατρεπόμενο σε [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/).<br/>            Χρησιμοποιήστε το [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) για να διαπιστώσετε αν η μετατροπή είναι δυνατή. |
| as_geographic | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Επιστρέφει αυτό το SRS μετατρεπόμενο σε [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/).<br/>            Χρησιμοποιήστε το [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) για να διαπιστώσετε αν η μετατροπή είναι δυνατή. |
| as_local | [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | r | Επιστρέφει αυτό το SRS μετατρεπόμενο σε [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/).<br/>            Χρησιμοποιήστε το [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) για να διαπιστώσετε αν η μετατροπή είναι δυνατή. |
| as_projected | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Επιστρέψτε αυτό. |
| as_vertical | [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | r | Επιστρέφει αυτό το SRS μετατρεπόμενο σε [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/).<br/>            Χρησιμοποιήστε το [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) για να διαπιστώσετε αν η μετατροπή είναι δυνατή. |
| axises_order | [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder) | r | Σειρά των αξόνων σε αυτό το SRS.<br/>            Εάν αυτό το SRS δεν είναι έγκυρο και έχει λανθασμένες κατευθύνσεις αξόνων, επιστρέφεται το [ProjectedAxisesOrder.INVALID](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/). |
| base | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Γεωγραφικό SRS στο οποίο εφαρμόστηκε η [ProjectedSpatialReferenceSystem.projection](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/) για να ληφθεί αυτό το SRS. |
| dimensions_count | int | r | Επιστρέφει τον αριθμό διαστάσεων σε αυτό το SRS. Για προβλεπόμενο SRS αυτό μπορεί να είναι:<br/>            δύο - εάν αυτό είναι ένα μοναδικό προβλεπόμενο SRS.<br/>            τρία - εάν αυτό είναι σύνθετο SRS, που αποτελείται από ένα μοναδικό, δισδιάστατο, προβλεπόμενο SRS και ένα κατακόρυφο SRS, που προσθέτει την τρίτη διάσταση. |
| epsg_code | int | r | Εάν το αναγνωριστικό αυτού του αντικειμένου είναι αναγνωριστικό EPSG - επιστρέφει τον κωδικό του. Διαφορετικά - επιστρέφει -1. |
| etrs89 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | ETRS 89 (EPSG:4258) σύστημα αναφοράς χώρου. |
| etrs_89_lambert_azimuthal_equal_area [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / ETRS Lambert Azimuthal Equal Area (EPSG:3035) σύστημα αναφοράς χώρου. |
| etrs_89_lambert_conformal_conic [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / Lambert Conformal Conic (EPSG:3034) σύστημα αναφοράς χώρου. |
| geographic_datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Επιστρέφει το γεωγραφικό datum αυτού του SRS. |
| has_geographic_datum | bool | r | Επιστρέφει true, επειδή το προβλεπόμενο SRS έχει πάντα πρωτεύον μεσημβρινό. |
| has_prime_meridian | bool | r | Επιστρέφει true, επειδή το προβλεπόμενο SRS έχει πάντα πρωτεύον μεσημβρινό. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Αναγνωριστικό αυτού του αναγνωρίσιμου αντικειμένου. |
| is_compound | bool | r | Επιστρέφει εάν αυτό το SRS είναι σύνθετο (ένωση δύο SRS).<br/>            Οι ακόλουθοι συνδυασμοί SRS σε σύνθετο SRS θεωρούνται έγκυροι:<br/>            Γεωγραφικό SRS + Κατακόρυφο SRS, σε αυτήν την περίπτωση ο τύπος του σύνθετου SRS θα είναι [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/).<br/>            Προβλεπόμενο SRS + Κατακόρυφο SRS, σε αυτήν την περίπτωση ο τύπος του σύνθετου SRS θα είναι [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/).<br/>            Εάν ο συνδυασμός των SRS διαφέρει, ο τύπος του σύνθετου SRS θα είναι [SpatialReferenceSystemType.UNKNOWN](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/). |
| is_single | bool | r | Επιστρέφει εάν αυτό το SRS είναι μοναδικό (δεν είναι ένωση δύο SRS). |
| is_valid | bool | r | Ίδιο με <see cref=\"M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)\" />, αλλά δεν επιστρέφει μήνυμα σφάλματος. |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Μονάδα, που χρησιμοποιείται για γραμμικές διαστάσεις σε αυτό το SRS και για γραμμικές παραμέτρους της [ProjectedSpatialReferenceSystem.projection](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/). |
| nad83 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | NAD 83 (EPSG:4269) σύστημα αναφοράς χώρου. |
| όνομα | string | r | Όνομα αυτού του αντικειμένου. |
| osgb36 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | OSGB 36 (EPSG:4277) σύστημα αναφοράς χώρου. |
| osgb_36_british_national_grid [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | OSGB 36 / British National Grid (EPSG:27700) σύστημα αναφοράς χώρου. |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r | Επιστρέφει το πρωτεύον μεσημβρινό αυτού του SRS. |
| projection | [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection) | r | Προβολή, που εφαρμόστηκε στο [ProjectedSpatialReferenceSystem.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/) για να ληφθεί αυτό το SRS. |
| type | [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype) | r | Επιστρέφει [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/). |
| web_mercator [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Σύστημα αναφοράς χώρου Web Mercator (EPSG:3857). |
| wgs72 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Σύστημα αναφοράς χώρου WGS 72 (EPSG:4322). |
| wgs84 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Σύστημα αναφοράς χώρου WGS 84 (EPSG:4326). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_compound(name, head, tail, identifier)](#create_compound_name_head_tail_identifier_1) | Δημιουργία σύνθετου SRS. |
| [create_from_epsg(epsg)](#create_from_epsg_epsg_2) | Δημιουργήστε ένα σύστημα αναφοράς χώρου με βάση τον καθορισμένο κωδικό EPSG. |
| [create_from_wkt(wkt)](#create_from_wkt_wkt_3) | Δημιουργεί ένα νέο <c>SpatialReferenceSystem</c> με βάση τη συμβολοσειρά WKT (Well-Known Text). |
| [create_geocentric(parameters, identifier)](#create_geocentric_parameters_identifier_4) | Δημιουργία γεωκεντρικού SRS από προσαρμοσμένες παραμέτρους. |
| [create_geographic(parameters, identifier)](#create_geographic_parameters_identifier_5) | Δημιουργία γεωγραφικού SRS από προσαρμοσμένες παραμέτρους. |
| [create_local(name, datum, unit, axises, identifier)](#create_local_name_datum_unit_axises_identifier_6) | Δημιουργία τοπικού Spatial Reference System. |
| [create_projected(parameters, identifier)](#create_projected_parameters_identifier_7) | Δημιουργία προβλεπόμενου SRS από προσαρμοσμένες παραμέτρους. |
| [create_transformation_to(target_srs)](#create_transformation_to_target_srs_8) | Δημιουργεί μετασχηματισμό από αυτό το <c>SpatialReferenceSystem</c> σε ένα άλλο <c>SpatialReferenceSystem</c>. |
| [create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)](#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9) | Δημιουργία κατακόρυφου SRS. |
| [export_to_wkt()](#export_to_wkt__10) | Επιστρέφει την αναπαράσταση αυτού του SRS ως συμβολοσειρά WKT.<br/>            Η τελική συμβολοσειρά WKT θα ταιριάζει με την προδιαγραφή OGC 01-009, συνήθως ονομάζεται "WKT1". |
| [get_axis(dimension)](#get_axis_dimension_11) | Αποκτήστε το [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) που περιγράφει τη διάσταση. |
| [get_unit(dimension)](#get_unit_dimension_12) | Αποκτήστε το [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) της διάστασης. |
| [is_equivalent(other)](#is_equivalent_other_13) | Εντοπίζει αν αυτό το SRS είναι ισοδύναμο με άλλο SRS. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/). |
| [is_equivalent(srs1, srs2)](#is_equivalent_srs1_srs2_14) | Καθορίζει εάν δύο SRS είναι ισοδύναμα.<br/>            Οι ίδιες συντεταγμένες ισοδύναμου SRS αντιστοιχούν στο ίδιο σημείο στη Γη.<br/>            Ορισμένες παράμετροι του ισοδύναμου SRS μπορεί να διαφέρουν, για παράδειγμα [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [try_create_from_epsg(epsg, value)](#try_create_from_epsg_epsg_value_15) | Δημιουργήστε ένα σύστημα αναφοράς χώρου με βάση τον καθορισμένο κωδικό EPSG. |
| [try_create_from_wkt(wkt, value)](#try_create_from_wkt_wkt_value_16) | Δημιουργεί ένα νέο <c>SpatialReferenceSystem</c> με βάση τη συμβολοσειρά WKT (Well-Known Text). |
| [try_create_transformation_to(target_srs, value)](#try_create_transformation_to_target_srs_value_17) | Δημιουργεί μετασχηματισμό από αυτό το <c>SpatialReferenceSystem</c> σε ένα άλλο <c>SpatialReferenceSystem</c>. |
| [validate(error_message)](#validate_error_message_18) | Καθορίστε εάν αυτό το SRS είναι έγκυρο. |


### Method: create_compound(name, head, tail, identifier)  [static] {#create_compound_name_head_tail_identifier_1}


```
 create_compound(name, head, tail, identifier) 
```

Δημιουργία σύνθετου SRS.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Όνομα του νέου SRS. |
| head | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Κεφαλή SRS του νέου SRS. |
| tail | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Ουρά SRS του νέου SRS. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Αναγνωριστικό, που θα προσαρτηθεί στο SRS. Η προσθήκη Αναγνωριστικού δεν θα τροποποιήσει άλλες παραμέτρους του SRS.<br/>            Εξαρτάται από εσάς να διασφαλίσετε τη συνέπεια του αναγνωριστικού και των παραμέτρων του SRS. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | Νέο σύνθετο SRS. |


### Method: create_from_epsg(epsg)  [static] {#create_from_epsg_epsg_2}


```
 create_from_epsg(epsg) 
```

Δημιουργήστε ένα σύστημα αναφοράς χώρου με βάση τον καθορισμένο κωδικό EPSG.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| epsg | int | Κωδικός EPSG του συστήματος αναφοράς χώρου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Ένα νέο σύστημα αναφοράς χώρου με τον καθορισμένο κωδικό EPSG. |


### Method: create_from_wkt(wkt)  [static] {#create_from_wkt_wkt_3}


```
 create_from_wkt(wkt) 
```

Δημιουργεί ένα νέο <c>SpatialReferenceSystem</c> με βάση τη συμβολοσειρά WKT (Well-Known Text).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| wkt | string | Συμβολοσειρά WKT. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Νέο <c>SpatialReferenceSystem</c>. |


### Method: create_geocentric(parameters, identifier)  [static] {#create_geocentric_parameters_identifier_4}


```
 create_geocentric(parameters, identifier) 
```

Δημιουργία γεωκεντρικού SRS από προσαρμοσμένες παραμέτρους.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| parameters | [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters) | Παράμετροι για δημιουργία. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Αναγνωριστικό, που θα προσαρτηθεί στο SRS. Η προσθήκη Αναγνωριστικού δεν θα τροποποιήσει άλλες παραμέτρους του SRS.<br/>            Εξαρτάται από εσάς να διασφαλίσετε τη συνέπεια του αναγνωριστικού και των παραμέτρων του SRS. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | Νέο Γεωκεντρικό SRS. |


### Method: create_geographic(parameters, identifier)  [static] {#create_geographic_parameters_identifier_5}


```
 create_geographic(parameters, identifier) 
```

Δημιουργία γεωγραφικού SRS από προσαρμοσμένες παραμέτρους.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| parameters | [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters) | Παράμετροι για δημιουργία. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Αναγνωριστικό, που θα προσαρτηθεί στο SRS. Η προσθήκη Αναγνωριστικού δεν θα τροποποιήσει άλλες παραμέτρους του SRS.<br/>            Εξαρτάται από εσάς να διασφαλίσετε τη συνέπεια του αναγνωριστικού και των παραμέτρων του SRS. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | Νέο Γεωγραφικό SRS. |


### Method: create_local(name, datum, unit, axises, identifier)  [static] {#create_local_name_datum_unit_axises_identifier_6}


```
 create_local(name, datum, unit, axises, identifier) 
```

Δημιουργία τοπικού Spatial Reference System.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Όνομα του Συστήματος Αναφοράς Χώρου. |
| datum | [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum) | Datum που θα χρησιμοποιηθεί στο SRS. |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Μονάδα που θα χρησιμοποιηθεί στο SRS. |
| άξονες | System.Collections.Generic.ICollection<Axis> | Άξονες που θα χρησιμοποιηθούν στο SRS. Πρέπει να μην είναι κενό. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Αναγνωριστικό, που θα προσαρτηθεί στο SRS. Η προσθήκη Αναγνωριστικού δεν θα τροποποιήσει άλλες παραμέτρους του SRS.<br/>            Εξαρτάται από εσάς να διασφαλίσετε τη συνέπεια του αναγνωριστικού και των παραμέτρων του SRS. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | Νέο Τοπικό Σύστημα Αναφοράς Χώρου. |


### Method: create_projected(parameters, identifier)  [static] {#create_projected_parameters_identifier_7}


```
 create_projected(parameters, identifier) 
```

Δημιουργία προβλεπόμενου SRS από προσαρμοσμένες παραμέτρους.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| parameters | [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters) | Παράμετροι για δημιουργία. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Αναγνωριστικό, που θα προσαρτηθεί στο SRS. Η προσθήκη Αναγνωριστικού δεν θα τροποποιήσει άλλες παραμέτρους του SRS.<br/>            Εξαρτάται από εσάς να διασφαλίσετε τη συνέπεια του αναγνωριστικού και των παραμέτρων του SRS. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | Νέο Προβολικό SRS. |


### Method: create_transformation_to(target_srs) {#create_transformation_to_target_srs_8}


```
 create_transformation_to(target_srs) 
```

Δημιουργεί μετασχηματισμό από αυτό το <c>SpatialReferenceSystem</c> σε ένα άλλο <c>SpatialReferenceSystem</c>.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Άλλο <c>SpatialReferenceSystem</c>. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | Μετασχηματισμός από αυτό το <c>SpatialReferenceSystem</c> σε άλλο <c>SpatialReferenceSystem</c>. |


### Method: create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)  [static] {#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9}


```
 create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier) 
```

Δημιουργία κατακόρυφου SRS.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Όνομα του SRS. Εάν <see langword=\"null\" />. |
| vertical_datum | [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum) | Datum που θα χρησιμοποιηθεί στο SRS. |
| vertical_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Μονάδα που θα χρησιμοποιηθεί στο SRS. Εάν <see langword=\"null\" />, [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/) θα χρησιμοποιηθεί. |
| vertical_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | Άξονας με κατεύθυνση \"up\" ή \"down\", που θα χρησιμοποιηθεί στο SRS. Εάν <see langword=\"null\" />, θα χρησιμοποιηθεί άξονας με κατεύθυνση up. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Αναγνωριστικό, που θα προσαρτηθεί στο SRS. Η προσθήκη Αναγνωριστικού δεν θα τροποποιήσει άλλες παραμέτρους του SRS.<br/>            Εξαρτάται από εσάς να διασφαλίσετε τη συνέπεια του αναγνωριστικού και των παραμέτρων του SRS. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | Νέο Κατακόρυφο SRS. |


### Method: export_to_wkt() {#export_to_wkt__10}


```
 export_to_wkt() 
```

Επιστρέφει την αναπαράσταση αυτού του SRS ως συμβολοσειρά WKT.<br/>            Η τελική συμβολοσειρά WKT θα ταιριάζει με την προδιαγραφή OGC 01-009, συνήθως ονομάζεται "WKT1".

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Αναπαράσταση WKT αυτού του SRS. |


### Method: get_axis(dimension) {#get_axis_dimension_11}


```
 get_axis(dimension) 
```

Αποκτήστε το [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) που περιγράφει τη διάσταση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| διάσταση | int | Αριθμός διάστασης. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | Άξονας που περιγράφει τη διάσταση. |


### Method: get_unit(dimension) {#get_unit_dimension_12}


```
 get_unit(dimension) 
```

Αποκτήστε το [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) της διάστασης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| διάσταση | int | Αριθμός διάστασης. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Μονάδα διάστασης. |


### Method: is_equivalent(other) {#is_equivalent_other_13}


```
 is_equivalent(other) 
```

Εντοπίζει αν αυτό το SRS είναι ισοδύναμο με άλλο SRS. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Άλλο SRS. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Τιμή bool, που υποδεικνύει εάν αυτό το SRS είναι ισοδύναμο με άλλο SRS. |


### Method: is_equivalent(srs1, srs2)  [static] {#is_equivalent_srs1_srs2_14}


```
 is_equivalent(srs1, srs2) 
```

Καθορίζει εάν δύο SRS είναι ισοδύναμα.<br/>            Οι ίδιες συντεταγμένες ισοδύναμου SRS αντιστοιχούν στο ίδιο σημείο στη Γη.<br/>            Ορισμένες παράμετροι του ισοδύναμου SRS μπορεί να διαφέρουν, για παράδειγμα [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| srs1 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Πρώτο SRS. |
| srs2 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Δεύτερο SRS. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Τιμή bool, που υποδεικνύει εάν δύο SRS είναι ισοδύναμα. |


### Method: try_create_from_epsg(epsg, value)  [static] {#try_create_from_epsg_epsg_value_15}


```
 try_create_from_epsg(epsg, value) 
```

Δημιουργήστε ένα σύστημα αναφοράς χώρου με βάση τον καθορισμένο κωδικό EPSG.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| epsg | int | Κωδικός EPSG του συστήματος αναφοράς χώρου. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Όταν αυτή η μέθοδος επιστρέφει <see langword=\"true\" />, περιέχει ένα SRS με τον καθορισμένο κωδικό EPSG· διαφορετικά,<br/>            περιέχει <see langword=\"null\" />. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <see langword=\"true\" /> εάν ο καθορισμένος κωδικός EPSG είναι γνωστός και το SRS δημιουργήθηκε· <see langword=\"false\" /> διαφορετικά. |


### Method: try_create_from_wkt(wkt, value)  [static] {#try_create_from_wkt_wkt_value_16}


```
 try_create_from_wkt(wkt, value) 
```

Δημιουργεί ένα νέο <c>SpatialReferenceSystem</c> με βάση τη συμβολοσειρά WKT (Well-Known Text).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| wkt | string | Συμβολοσειρά WKT. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Όταν αυτή η μέθοδος επιστρέφει <see langword=\"true\" />, περιέχει ένα SRS που δημιουργήθηκε από WKT· διαφορετικά,<br/>            περιέχει <see langword=\"null\" />. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <see langword=\"true\" /> εάν το SRS δημιουργήθηκε επιτυχώς· <see langword=\"false\" /> διαφορετικά. |


### Method: try_create_transformation_to(target_srs, value) {#try_create_transformation_to_target_srs_value_17}


```
 try_create_transformation_to(target_srs, value) 
```

Δημιουργεί μετασχηματισμό από αυτό το <c>SpatialReferenceSystem</c> σε ένα άλλο <c>SpatialReferenceSystem</c>.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Άλλο <c>SpatialReferenceSystem</c>. |
| value | [SpatialReferenceSystemTransformation[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | Όταν αυτή η μέθοδος επιστρέφει <see langword=\"true\" />, περιέχει έναν μετασχηματισμό· διαφορετικά, περιέχει <see langword=\"null\" />. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Μετασχηματισμός από αυτό το <c>SpatialReferenceSystem</c> σε άλλο <c>SpatialReferenceSystem</c>. |


### Method: validate(error_message) {#validate_error_message_18}


```
 validate(error_message) 
```

Καθορίστε εάν αυτό το SRS είναι έγκυρο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| error_message | Συμβολοσειρά | Εάν η μέθοδος επιστρέψει <see langword=\"false\" />, τότε αυτό είναι η περιγραφή της μη εγκυρότητας. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <see langword=\"true\" /> εάν το SRS είναι έγκυρο, <see langword=\"false\" /> διαφορετικά. |


