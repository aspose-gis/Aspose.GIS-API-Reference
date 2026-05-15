---
title: "Κλάση GeographicDatum"
type: docs
weight: 70
url: /el/python-net/aspose.gis.spatialreferencing/geographicdatum/
---

**Summary:** Geographic datum relates longitude and latitude to particular place on earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicDatum

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier)](#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1) | Δημιουργεί νέο αντικείμενο. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ellipsoid, που χρησιμοποιείται σε αυτό το datum για την προσέγγιση της Γης. |
| epsg_code | int | r | Εάν το αναγνωριστικό αυτού του αντικειμένου είναι αναγνωριστικό EPSG - επιστρέφει τον κωδικό του. Διαφορετικά - επιστρέφει -1. |
| etrs89 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Datum ETRS 89. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Αναγνωριστικό αυτού του αναγνωρίσιμου αντικειμένου. |
| nad83 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Datum NAD 83. |
| όνομα | string | r | Όνομα αυτού του αντικειμένου. |
| osgb36 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Datum OSGB 1936. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | r | BursaWolfParamters που μπορούν να χρησιμοποιηθούν για τη μετατροπή των συντεταγμένων σε αυτό το datum σε συντεταγμένες στο datum WGS84. |
| wgs72 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Datum WGS 72. |
| wgs84 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Datum WGS 84. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [is_equivalent(datum1, datum2)](#is_equivalent_datum1_datum2_1) | Καθορίζει αν δύο datums είναι ισοδύναμα.<br/>            Οι ίδιες συντεταγμένες ισοδύναμων datums ταιριάζουν στο ίδιο σημείο στη Γη.<br/>            Ορισμένες παράμετροι ισοδύναμων datums μπορεί να διαφέρουν, για παράδειγμα [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [is_equivalent(other)](#is_equivalent_other_2) | Καθορίζει αν δύο datums είναι ισοδύναμα.<br/>            Οι ίδιες συντεταγμένες ισοδύναμων datums ταιριάζουν στο ίδιο σημείο στη Γη.<br/>            Ορισμένες παράμετροι ισοδύναμων datums μπορεί να διαφέρουν, για παράδειγμα [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |


### Constructor: GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) {#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1}


```
 GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) 
```

Δημιουργεί νέο αντικείμενο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Όνομα αυτού του datum. |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Ellipsoid αυτού του datum. Δεν μπορεί να είναι κενό. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | Παράμετροι που μπορούν να δοθούν στον τύπο bursa wolf, για τη μετατροπή των συντεταγμένων σε αυτό το datum σε συντεταγμένες στο datum WGS84.<br/>            Εάν αυτό το datum είναι κοντά στο WGS84 και δεν απαιτείται μετασχηματισμός, περάστε τις παραμέτρους bursa wolf με όλες τις τιμές ίσες με 0.<br/>            Εάν είναι null, το ToWgs84 θα οριστεί στις παραμέτρους [BursaWolfParameters.is_null](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/). |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Αναγνωριστικό αυτού του datum. |

### Method: is_equivalent(datum1, datum2)  [static] {#is_equivalent_datum1_datum2_1}


```
 is_equivalent(datum1, datum2) 
```

Καθορίζει αν δύο datums είναι ισοδύναμα.<br/>            Οι ίδιες συντεταγμένες ισοδύναμων datums ταιριάζουν στο ίδιο σημείο στη Γη.<br/>            Ορισμένες παράμετροι ισοδύναμων datums μπορεί να διαφέρουν, για παράδειγμα [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| datum1 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Πρώτο datum. |
| datum2 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Δεύτερο datum. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Τιμή bool, που υποδεικνύει αν δύο datums είναι ισοδύναμα. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

Καθορίζει αν δύο datums είναι ισοδύναμα.<br/>            Οι ίδιες συντεταγμένες ισοδύναμων datums ταιριάζουν στο ίδιο σημείο στη Γη.<br/>            Ορισμένες παράμετροι ισοδύναμων datums μπορεί να διαφέρουν, για παράδειγμα [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Άλλο datum. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Τιμή bool, που υποδεικνύει αν δύο datums είναι ισοδύναμα. |


