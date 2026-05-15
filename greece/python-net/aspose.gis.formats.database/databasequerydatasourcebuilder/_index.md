---
title: "DatabaseQueryDataSourceBuilder Κλάση"
type: docs
weight: 40
url: /el/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/
---

**Summary:** Provides the ability to configure a query to database to to extract geospatial information.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseQueryDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | Ρυθμίζει το όνομα του πεδίου που θα περιέχει πληροφορίες για το χαρακτηριστικό του στοιχείου. |
| [as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func)](#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2) | Διαμορφώστε το τελικό επίπεδο ώστε να παρακολουθεί τις αλλαγές και δημιουργήστε μια πηγή δεδομένων για συγχρονισμό των πραγματοποιηθέντων αλλαγών. |
| [build()](#build__3) | Η μέθοδος ανακτά μια υλοποίηση του [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) |
| [geometry_field(name)](#geometry_field_name_4) | Ρυθμίζει το όνομα του πεδίου από το οποίο θα εξαχθεί η γεωμετρία. |
| [srid_field(name)](#srid_field_name_5) | Διαμόρφωση του ονόματος του πεδίου ερωτήματος που θα περιέχει το αναγνωριστικό του συστήματος αναφοράς χώρου (srid). |
| [use_external_srs_from_query(srs_query)](#use_external_srs_from_query_srs_query_6) | Σας επιτρέπει να διαμορφώσετε την πηγή δεδομένων ώστε να χρησιμοποιεί δεδομένα συστήματος αναφοράς χώρου τρίτων, παρακάμπτοντας τα προεγκατεστημένα δεδομένα στη βιβλιοθήκη Aspose.GIS. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

Ρυθμίζει το όνομα του πεδίου που θα περιέχει πληροφορίες για το χαρακτηριστικό του στοιχείου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Όνομα του πεδίου ερωτήματος για το χαρακτηριστικό. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Τύπος δεδομένων στον οποίο πρέπει να μετατραπούν τα δεδομένα από τη βάση δεδομένων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) {#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2}


```
 as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) 
```

Διαμορφώστε το τελικό επίπεδο ώστε να παρακολουθεί τις αλλαγές και δημιουργήστε μια πηγή δεδομένων για συγχρονισμό των πραγματοποιηθέντων αλλαγών.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| table_name | string | Το όνομα του πίνακα όπου θα γίνουν οι αλλαγές. |
| identity_attribute | string | Ένα χαρακτηριστικό ενός στοιχείου που θα θεωρείται ως μοναδική ταυτοποίηση του στοιχείου. |
| overwrite_same_key | bool | Εάν αυτή η σημαία οριστεί σε true, τότε τα νεοεισαχθέντα χαρακτηριστικά με μοναδικό αναγνωριστικό που είναι ήδη παρόν στο επίπεδο, θα αντικατασταθούν από το τρέχον, και τα δεδομένα θα διαβαστούν ως ενημερωμένα εάν εντοπιστούν διαφορές. |
| db_func | string | Συνάρτηση που θα παρασχεθεί στο ερώτημα SQL για τη μετατροπή των δυαδικών δεδομένων σε γεωγραφική αναπαράσταση δεδομένων της τρέχουσας βάσης. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) | [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) |


### Method: build() {#build__3}


```
 build() 
```

Η μέθοδος ανακτά μια υλοποίηση του [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/)

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource) | Υλοποίηση του [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) |


### Method: geometry_field(name) {#geometry_field_name_4}


```
 geometry_field(name) 
```

Ρυθμίζει το όνομα του πεδίου από το οποίο θα εξαχθεί η γεωμετρία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Όνομα του πεδίου γεωμετρίας. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: srid_field(name) {#srid_field_name_5}


```
 srid_field(name) 
```

Διαμόρφωση του ονόματος του πεδίου ερωτήματος που θα περιέχει το αναγνωριστικό του συστήματος αναφοράς χώρου (srid).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Όνομα του πεδίου ερωτήματος που περιέχει το αναγνωριστικό του συστήματος αναφοράς χώρου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: use_external_srs_from_query(srs_query) {#use_external_srs_from_query_srs_query_6}


```
 use_external_srs_from_query(srs_query) 
```

Σας επιτρέπει να διαμορφώσετε την πηγή δεδομένων ώστε να χρησιμοποιεί δεδομένα συστήματος αναφοράς χώρου τρίτων, παρακάμπτοντας τα προεγκατεστημένα δεδομένα στη βιβλιοθήκη Aspose.GIS.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| srs_query | string | Ερώτημα για την ανάκτηση πληροφοριών σχετικά με πρόσθετα χωρικά συστήματα συντεταγμένων που χρησιμοποιούνται στο κύριο ερώτημα για την ανάκτηση χαρακτηριστικών. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


