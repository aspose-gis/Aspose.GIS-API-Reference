---
title: "VectorLayer Κλάση"
type: docs
weight: 4060
url: /el/python-net/aspose.gis/vectorlayer/
---

**Summary:** Represents a vector layer.<br/>            A vector layer is a collection of geographic features, stored in a file.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.VectorLayer

**Inheritance:** FeaturesSequence

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | Λαμβάνει τη συλλογή των προσαρμοσμένων χαρακτηριστικών για τα στοιχεία σε αυτό το [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |
| count | int | r | Λαμβάνει τον αριθμό των στοιχείων σε αυτό το στρώμα. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Λαμβάνει το [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) που δημιούργησε αυτό το στρώμα. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype/) | r | Λαμβάνει τον τύπο της γεωμετρίας του στρώματος. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Λαμβάνει το σύστημα αναφοράς χώρου της ακολουθίας χαρακτηριστικών αυτής. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(feature)](#add_feature_1) | Προσθέτει ένα νέο χαρακτηριστικό στο στρώμα, εάν υποστηρίζεται από το [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/). |
| [add(feature, style)](#add_feature_style_2) | Προσθέτει ένα νέο χαρακτηριστικό με το καθορισμένο στυλ στο στρώμα, εάν υποστηρίζεται από το [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/). |
| [as_in_memory()](#as_in_memory__3) | Δημιουργεί ένα κλώνο στρώματος σε μορφή InMemory. |
| [construct_feature()](#construct_feature__4) | Δημιουργεί (αλλά δεν προσθέτει στο στρώμα) ένα νέο χαρακτηριστικό με ιδιότητες που ταιριάζουν με τη συλλογή ιδιοτήτων αυτού του στρώματος.<br/>            Όταν ολοκληρωθεί η ρύθμιση των δεδομένων για το χαρακτηριστικό, χρησιμοποιήστε [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) για να προσθέσετε το χαρακτηριστικό στο στρώμα. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_5) | Μετατρέπει ένα στρώμα σε διαφορετική μορφή. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_6) | Μετατρέπει ένα στρώμα σε διαφορετική μορφή. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_7) | Μετατρέπει ένα στρώμα σε διαφορετική μορφή. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_8) | Μετατρέπει ένα στρώμα σε διαφορετική μορφή. |
| [copy_attributes(features_sequence)](#copy_attributes_features_sequence_9) | Αντιγράφει τις ιδιότητες άλλου [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) σε αυτό. |
| [copy_attributes(features_sequence, converter)](#copy_attributes_features_sequence_converter_10) | Αντιγράφει τις ιδιότητες άλλου [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) σε αυτό. |
| [create(path, driver)](#create_path_driver_11) | Δημιουργεί το στρώμα και το ανοίγει για προσθήκη νέων χαρακτηριστικών. |
| [create(path, driver)](#create_path_driver_12) | Δημιουργεί το στρώμα και το ανοίγει για προσθήκη νέων χαρακτηριστικών. |
| [create(path, driver, options)](#create_path_driver_options_13) | Δημιουργεί το στρώμα και το ανοίγει για προσθήκη νέων χαρακτηριστικών. |
| [create(path, driver, options)](#create_path_driver_options_14) | Δημιουργεί το στρώμα και το ανοίγει για προσθήκη νέων χαρακτηριστικών. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_15) | Δημιουργεί το στρώμα και το ανοίγει για προσθήκη. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_16) | Δημιουργεί το στρώμα και το ανοίγει για προσθήκη. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_17) | Δημιουργεί το στρώμα και το ανοίγει για προσθήκη. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_18) | Δημιουργεί το στρώμα και το ανοίγει για προσθήκη. |
| [get_extent()](#get_extent__19) | Λαμβάνει την χωρική έκταση αυτού του στρώματος. |
| [intersection_by_geometry(layer)](#intersection_by_geometry_layer_20) | Διασταυρώνει ένα στρώμα με το τρέχον στρώμα με βάση τη γεωμετρία. |
| [join(layer, options)](#join_layer_options_21) | Συνδέει ένα στρώμα με το τρέχον στρώμα. |
| [join_by_geometry(layer, options)](#join_by_geometry_layer_options_22) | Συνδέει ένα στρώμα με το τρέχον στρώμα με βάση τη γεωμετρία. |
| [nearest_to(point)](#nearest_to_point_23) | Λαμβάνει το πλησιέστερο χαρακτηριστικό στο δοσμένο σημείο. |
| [nearest_to(x, y)](#nearest_to_x_y_24) | Λαμβάνει το πλησιέστερο χαρακτηριστικό στη δοσμένη συντεταγμένη. |
| [open(path, driver)](#open_path_driver_25) | Ανοίγει το στρώμα για ανάγνωση. |
| [open(path, driver)](#open_path_driver_26) | Ανοίγει το στρώμα για ανάγνωση. |
| [open(path, driver, options)](#open_path_driver_options_27) | Ανοίγει το στρώμα για ανάγνωση. |
| [open(path, driver, options)](#open_path_driver_options_28) | Ανοίγει το στρώμα για ανάγνωση. |
| [remove_at(index)](#remove_at_index_29) | Αφαιρεί το [Feature](/psd/python-net/aspose.gis/feature/) στον καθορισμένο δείκτη. |
| [replace_at(index, feature)](#replace_at_index_feature_30) | Αντικαθιστά το [Feature](/psd/python-net/aspose.gis/feature/) στον καθορισμένο δείκτη. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_31) | Αποθηκεύει τη σειρά χαρακτηριστικών στο στρώμα. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_32) | Αποθηκεύει τη σειρά χαρακτηριστικών στο στρώμα. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_33) | Αποθηκεύει τη σειρά χαρακτηριστικών στο στρώμα. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_34) | Αποθηκεύει τη σειρά χαρακτηριστικών στο στρώμα. |
| [split_to()](#split_to__35) | Διαιρεί τα χαρακτηριστικά ανά τύπο γεωμετρίας. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_36) | Φορτώνει το ευρετήριο ιδιοτήτων για να επιταχύνει το φιλτράρισμα κατά τιμή ιδιοτήτων σε μεθόδους φιλτραρίσματος όπως Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Εάν το ευρετήριο δεν υπάρχει, το δημιουργεί πρώτα. Χρησιμοποιήστε <paramref name="forceRebuild" /> για να εξαναγκάσετε την επαναδημιουργία του ευρετηρίου. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_37) | Φορτώνει το ευρετήριο ιδιοτήτων για να επιταχύνει το φιλτράρισμα κατά τιμή ιδιοτήτων σε μεθόδους φιλτραρίσματος όπως Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Εάν το ευρετήριο δεν υπάρχει, το δημιουργεί πρώτα. Χρησιμοποιήστε <paramref name="forceRebuild" /> για να εξαναγκάσετε την επαναδημιουργία του ευρετηρίου. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_38) | Φορτώνει το χωρικό ευρετήριο για να επιταχύνει το φιλτράρισμα κατά τιμή ιδιοτήτων σε μεθόδους φιλτραρίσματος όπως Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            και Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Εάν το ευρετήριο δεν υπάρχει, το δημιουργεί πρώτα. Χρησιμοποιήστε <paramref name="forceRebuild" /> για να εξαναγκάσετε την επαναδημιουργία του ευρετηρίου. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_39) | Φορτώνει το χωρικό ευρετήριο για να επιταχύνει το φιλτράρισμα κατά τιμή ιδιοτήτων σε μεθόδους φιλτραρίσματος όπως Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            και Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Εάν το ευρετήριο δεν υπάρχει, το δημιουργεί πρώτα. Χρησιμοποιήστε <paramref name="forceRebuild" /> για να εξαναγκάσετε την επαναδημιουργία του ευρετηρίου. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_40) | Επιλέγει χαρακτηριστικά με τιμή ιδιότητας ίση με τη δοσμένη τιμή. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_41) | Επιλέγει χαρακτηριστικά με τιμή ιδιότητας μεγαλύτερη από τη δοσμένη τιμή. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_42) | Επιλέγει χαρακτηριστικά με τιμή ιδιότητας μεγαλύτερη ή ίση με τη δοσμένη τιμή. |
| [where_intersects(extent)](#where_intersects_extent_43) | Φιλτράρει τα χαρακτηριστικά βάσει της έκτασης. |
| [where_intersects(geometry)](#where_intersects_geometry_44) | Φιλτράρει τα χαρακτηριστικά βάσει της παρεχόμενης γεωμετρίας. |
| [where_intersects(sequence)](#where_intersects_sequence_45) | Φιλτράρει τα χαρακτηριστικά βάσει της ένωσης όλων των γεωμετριών στην ακολουθία άλλων χαρακτηριστικών. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_46) | Επιλέγει τα χαρακτηριστικά με τιμή ιδιότητας διαφορετική από την παρεχόμενη τιμή. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_47) | Επιλέγει τα χαρακτηριστικά με ιδιότητα διαφορετική από το null. |
| [where_null(attribute_name)](#where_null_attribute_name_48) | Επιλέγει τα χαρακτηριστικά με ιδιότητα ίση με το null. |
| [where_set(attribute_name)](#where_set_attribute_name_49) | Επιλέγει τα χαρακτηριστικά με ορισμένη ιδιότητα. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_50) | Επιλέγει τα χαρακτηριστικά με τιμή ιδιότητας μικρότερη από την παρεχόμενη τιμή. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_51) | Επιλέγει τα χαρακτηριστικά με τιμή ιδιότητας μικρότερη ή ίση με την παρεχόμενη τιμή. |
| [where_unset(attribute_name)](#where_unset_attribute_name_52) | Επιλέγει τα χαρακτηριστικά όπου η καθορισμένη ιδιότητα δεν είναι ορισμένη. |


### Method: add(feature) {#add_feature_1}


```
 add(feature) 
```

Προσθέτει ένα νέο χαρακτηριστικό στο στρώμα, εάν υποστηρίζεται από το [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | Το χαρακτηριστικό προς προσθήκη. |

### Method: add(feature, style) {#add_feature_style_2}


```
 add(feature, style) 
```

Προσθέτει ένα νέο χαρακτηριστικό με το καθορισμένο στυλ στο στρώμα, εάν υποστηρίζεται από το [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | Το χαρακτηριστικό προς προσθήκη. |
| style | [IFeatureStyle](/psd/python-net/aspose.gis/ifeaturestyle) | Το στυλ του χαρακτηριστικού. Χρησιμοποιήστε <see langword=\"null\" /> για να υποδείξετε το ελλιπές στυλ. |

### Method: as_in_memory() {#as_in_memory__3}


```
 as_in_memory() 
```

Δημιουργεί ένα κλώνο στρώματος σε μορφή InMemory.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Το επίπεδο InMemory. |


### Method: construct_feature() {#construct_feature__4}


```
 construct_feature() 
```

Δημιουργεί (αλλά δεν προσθέτει στο στρώμα) ένα νέο χαρακτηριστικό με ιδιότητες που ταιριάζουν με τη συλλογή ιδιοτήτων αυτού του στρώματος.<br/>            Όταν ολοκληρωθεί η ρύθμιση των δεδομένων για το χαρακτηριστικό, χρησιμοποιήστε [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) για να προσθέσετε το χαρακτηριστικό στο στρώμα.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | Ένα νέο χαρακτηριστικό. |


### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_5}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

Μετατρέπει ένα στρώμα σε διαφορετική μορφή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_path | string | Διαδρομή προς το επίπεδο που θα μετατραπεί. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Ο οδηγός μορφής για το πηγαίο επίπεδο. |
| destination_path | string | Διαδρομή προς το επίπεδο που θα δημιουργηθεί ως αποτέλεσμα της μετατροπής. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Ο οδηγός μορφής για το προορισμένο επίπεδο. |

### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_6}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

Μετατρέπει ένα στρώμα σε διαφορετική μορφή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το επίπεδο που θα μετατραπεί. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Ο οδηγός μορφής για το πηγαίο επίπεδο. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το επίπεδο που θα δημιουργηθεί ως αποτέλεσμα της μετατροπής. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Ο οδηγός μορφής για το προορισμένο επίπεδο. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_7}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

Μετατρέπει ένα στρώμα σε διαφορετική μορφή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_path | string | Διαδρομή προς το επίπεδο που θα μετατραπεί. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Ο οδηγός μορφής για το πηγαίο επίπεδο. |
| destination_path | string | Διαδρομή προς το επίπεδο που θα δημιουργηθεί ως αποτέλεσμα της μετατροπής. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Ο οδηγός μορφής για το προορισμένο επίπεδο. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | Επιλογές για τη διαδικασία μετατροπής. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_8}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

Μετατρέπει ένα στρώμα σε διαφορετική μορφή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το επίπεδο που θα μετατραπεί. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Ο οδηγός μορφής για το πηγαίο επίπεδο. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το επίπεδο που θα δημιουργηθεί ως αποτέλεσμα της μετατροπής. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Ο οδηγός μορφής για το προορισμένο επίπεδο. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | Επιλογές για τη διαδικασία μετατροπής. |

### Method: copy_attributes(features_sequence) {#copy_attributes_features_sequence_9}


```
 copy_attributes(features_sequence) 
```

Αντιγράφει τις ιδιότητες άλλου [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) σε αυτό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Η ακολουθία χαρακτηριστικών από την οποία θα αντιγραφούν οι ιδιότητες. |

### Method: copy_attributes(features_sequence, converter) {#copy_attributes_features_sequence_converter_10}


```
 copy_attributes(features_sequence, converter) 
```

Αντιγράφει τις ιδιότητες άλλου [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) σε αυτό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Η ακολουθία χαρακτηριστικών από την οποία θα αντιγραφούν οι ιδιότητες. |
| converter | [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter) | Μία παρουσία προσαρμοσμένου [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter/) που θα επεξεργάζεται τις ιδιότητες μία προς μία. |

### Method: create(path, driver)  [static] {#create_path_driver_11}


```
 create(path, driver) 
```

Δημιουργεί το στρώμα και το ανοίγει για προσθήκη νέων χαρακτηριστικών.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το αρχείο. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Οδηγός προς χρήση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ένα επίπεδο μόνο για εγγραφή. |


### Method: create(path, driver)  [static] {#create_path_driver_12}


```
 create(path, driver) 
```

Δημιουργεί το στρώμα και το ανοίγει για προσθήκη νέων χαρακτηριστικών.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το αρχείο. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Οδηγός προς χρήση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ένα επίπεδο μόνο για εγγραφή. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_13}


```
 create(path, driver, options) 
```

Δημιουργεί το στρώμα και το ανοίγει για προσθήκη νέων χαρακτηριστικών.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το αρχείο. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Οδηγός προς χρήση. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ειδικές για τον οδηγό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ένα επίπεδο μόνο για εγγραφή. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_14}


```
 create(path, driver, options) 
```

Δημιουργεί το στρώμα και το ανοίγει για προσθήκη νέων χαρακτηριστικών.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το αρχείο. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Οδηγός προς χρήση. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ειδικές για τον οδηγό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ένα επίπεδο μόνο για εγγραφή. |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_15}


```
 create(path, driver, options, spatial_reference_system) 
```

Δημιουργεί το στρώμα και το ανοίγει για προσθήκη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το αρχείο. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Οδηγός προς χρήση. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ειδικές για τον οδηγό. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Σύστημα αναφοράς χώρου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Μια παρουσία του [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_16}


```
 create(path, driver, options, spatial_reference_system) 
```

Δημιουργεί το στρώμα και το ανοίγει για προσθήκη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το αρχείο. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Οδηγός προς χρήση. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ειδικές για τον οδηγό. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Σύστημα αναφοράς χώρου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Μια παρουσία του [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_17}


```
 create(path, driver, spatial_reference_system) 
```

Δημιουργεί το στρώμα και το ανοίγει για προσθήκη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το αρχείο. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Οδηγός προς χρήση. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Σύστημα αναφοράς χώρου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Μια παρουσία του [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_18}


```
 create(path, driver, spatial_reference_system) 
```

Δημιουργεί το στρώμα και το ανοίγει για προσθήκη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το αρχείο. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Οδηγός προς χρήση. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Σύστημα αναφοράς χώρου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Μια παρουσία του [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: get_extent() {#get_extent__19}


```
 get_extent() 
```

Λαμβάνει την χωρική έκταση αυτού του στρώματος.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Μια χωρική έκταση αυτού του επιπέδου. |


### Method: intersection_by_geometry(layer) {#intersection_by_geometry_layer_20}


```
 intersection_by_geometry(layer) 
```

Διασταυρώνει ένα στρώμα με το τρέχον στρώμα με βάση τη γεωμετρία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ένα στρώμα για τομή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ένα νέο στρώμα ως αποτέλεσμα της τομής δύο στρωμάτων. |


### Method: join(layer, options) {#join_layer_options_21}


```
 join(layer, options) 
```

Συνδέει ένα στρώμα με το τρέχον στρώμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ένα στρώμα για ένωση. |
| options | [JoinOptions](/psd/python-net/aspose.gis.relationship.joins/joinoptions/) | Παράμετροι ένωσης. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ένα νέο στρώμα ως αποτέλεσμα της ένωσης δύο στρωμάτων. |


### Method: join_by_geometry(layer, options) {#join_by_geometry_layer_options_22}


```
 join_by_geometry(layer, options) 
```

Συνδέει ένα στρώμα με το τρέχον στρώμα με βάση τη γεωμετρία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ένα στρώμα για ένωση. |
| options | [JoinByGeometryOptions](/psd/python-net/aspose.gis.relationship.joins/joinbygeometryoptions/) | Παράμετροι ένωσης. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ένα νέο στρώμα ως αποτέλεσμα της ένωσης δύο στρωμάτων. |


### Method: nearest_to(point) {#nearest_to_point_23}


```
 nearest_to(point) 
```

Λαμβάνει το πλησιέστερο χαρακτηριστικό στο δοσμένο σημείο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Το σημείο. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | Το πλησιέστερο χαρακτηριστικό στο δοσμένο σημείο. |


### Method: nearest_to(x, y) {#nearest_to_x_y_24}


```
 nearest_to(x, y) 
```

Λαμβάνει το πλησιέστερο χαρακτηριστικό στη δοσμένη συντεταγμένη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | double | X του συντεταγμένου. |
| y | double | Y του συντεταγμένου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | Το πλησιέστερο χαρακτηριστικό στη δοσμένη συντεταγμένη. |


### Method: open(path, driver)  [static] {#open_path_driver_25}


```
 open(path, driver) 
```

Ανοίγει το στρώμα για ανάγνωση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το αρχείο. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Οδηγός προς χρήση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ένα στρώμα μόνο για ανάγνωση. |


### Method: open(path, driver)  [static] {#open_path_driver_26}


```
 open(path, driver) 
```

Ανοίγει το στρώμα για ανάγνωση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το αρχείο. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Οδηγός προς χρήση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ένα στρώμα μόνο για ανάγνωση. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_27}


```
 open(path, driver, options) 
```

Ανοίγει το στρώμα για ανάγνωση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το αρχείο. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Οδηγός προς χρήση. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ειδικές για τον οδηγό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ένα στρώμα μόνο για ανάγνωση. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_28}


```
 open(path, driver, options) 
```

Ανοίγει το στρώμα για ανάγνωση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το αρχείο. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Οδηγός προς χρήση. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ειδικές για τον οδηγό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ένα στρώμα μόνο για ανάγνωση. |


### Method: remove_at(index) {#remove_at_index_29}


```
 remove_at(index) 
```

Αφαιρεί το [Feature](/psd/python-net/aspose.gis/feature/) στον καθορισμένο δείκτη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | int | Το ευρετήριο του χαρακτηριστικού. |

### Method: replace_at(index, feature) {#replace_at_index_feature_30}


```
 replace_at(index, feature) 
```

Αντικαθιστά το [Feature](/psd/python-net/aspose.gis/feature/) στον καθορισμένο δείκτη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | int | Το ευρετήριο του χαρακτηριστικού. |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | Το χαρακτηριστικό προς ορισμό. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_31}


```
 save_to(destination_path, destination_driver) 
```

Αποθηκεύει τη σειρά χαρακτηριστικών στο στρώμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| destination_path | string | Διαδρομή προς το στρώμα εξόδου. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Ο οδηγός μορφής για το στρώμα εξόδου. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_32}


```
 save_to(destination_path, destination_driver) 
```

Αποθηκεύει τη σειρά χαρακτηριστικών στο στρώμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το στρώμα εξόδου. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Ο οδηγός μορφής για το στρώμα εξόδου. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_33}


```
 save_to(destination_path, destination_driver, options) 
```

Αποθηκεύει τη σειρά χαρακτηριστικών στο στρώμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| destination_path | string | Διαδρομή προς το στρώμα εξόδου. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Ο οδηγός μορφής για το στρώμα εξόδου. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Επιλογές για τη διαδικασία αποθήκευσης. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_34}


```
 save_to(destination_path, destination_driver, options) 
```

Αποθηκεύει τη σειρά χαρακτηριστικών στο στρώμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το στρώμα εξόδου. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Ο οδηγός μορφής για το στρώμα εξόδου. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Επιλογές για τη διαδικασία αποθήκευσης. |

### Method: split_to() {#split_to__35}


```
 split_to() 
```

Διαιρεί τα χαρακτηριστικά ανά τύπο γεωμετρίας.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | Στρώματα με τον ίδιο τύπο γεωμετρίας. |


### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_36}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

Φορτώνει το ευρετήριο ιδιοτήτων για να επιταχύνει το φιλτράρισμα κατά τιμή ιδιοτήτων σε μεθόδους φιλτραρίσματος όπως Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Εάν το ευρετήριο δεν υπάρχει, το δημιουργεί πρώτα. Χρησιμοποιήστε <paramref name="forceRebuild" /> για να εξαναγκάσετε την επαναδημιουργία του ευρετηρίου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index_path | string | Διαδρομή προς το αρχείο ευρετηρίου. |
| attribute_name | string | Όνομα του χαρακτηριστικού για το οποίο θα δημιουργηθεί το ευρετήριο. |
| force_rebuild | bool | Αν θα δημιουργηθεί ξανά το ευρετήριο ακόμη και αν υπάρχει ήδη. |

### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_37}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

Φορτώνει το ευρετήριο ιδιοτήτων για να επιταχύνει το φιλτράρισμα κατά τιμή ιδιοτήτων σε μεθόδους φιλτραρίσματος όπως Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Εάν το ευρετήριο δεν υπάρχει, το δημιουργεί πρώτα. Χρησιμοποιήστε <paramref name="forceRebuild" /> για να εξαναγκάσετε την επαναδημιουργία του ευρετηρίου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το αρχείο ευρετηρίου. |
| attribute_name | string | Όνομα του χαρακτηριστικού για το οποίο θα δημιουργηθεί το ευρετήριο. |
| force_rebuild | bool | Αν θα δημιουργηθεί ξανά το ευρετήριο ακόμη και αν υπάρχει ήδη. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_38}


```
 use_spatial_index(index_path, force_rebuild) 
```

Φορτώνει το χωρικό ευρετήριο για να επιταχύνει το φιλτράρισμα κατά τιμή ιδιοτήτων σε μεθόδους φιλτραρίσματος όπως Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            και Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Εάν το ευρετήριο δεν υπάρχει, το δημιουργεί πρώτα. Χρησιμοποιήστε <paramref name="forceRebuild" /> για να εξαναγκάσετε την επαναδημιουργία του ευρετηρίου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index_path | string | Διαδρομή προς το αρχείο ευρετηρίου. |
| force_rebuild | bool | Αν θα δημιουργηθεί ξανά το ευρετήριο ακόμη και αν υπάρχει ήδη. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_39}


```
 use_spatial_index(index_path, force_rebuild) 
```

Φορτώνει το χωρικό ευρετήριο για να επιταχύνει το φιλτράρισμα κατά τιμή ιδιοτήτων σε μεθόδους φιλτραρίσματος όπως Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            και Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Εάν το ευρετήριο δεν υπάρχει, το δημιουργεί πρώτα. Χρησιμοποιήστε <paramref name="forceRebuild" /> για να εξαναγκάσετε την επαναδημιουργία του ευρετηρίου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το αρχείο ευρετηρίου. |
| force_rebuild | bool | Αν θα δημιουργηθεί ξανά το ευρετήριο ακόμη και αν υπάρχει ήδη. |

### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_40}


```
 where_equal(attribute_name, value) 
```

Επιλέγει χαρακτηριστικά με τιμή ιδιότητας ίση με τη δοσμένη τιμή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| attribute_name | string | Χαρακτηριστικό για φιλτράρισμα. |
| value | object | Τιμή για σύγκριση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Χαρακτηριστικά με τιμή χαρακτηριστικού ίση με τη δοσμένη τιμή. |


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_41}


```
 where_greater(attribute_name, value) 
```

Επιλέγει χαρακτηριστικά με τιμή ιδιότητας μεγαλύτερη από τη δοσμένη τιμή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| attribute_name | string | Χαρακτηριστικό για φιλτράρισμα. |
| value | object | Τιμή για σύγκριση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Χαρακτηριστικά με τιμή χαρακτηριστικού μεγαλύτερη από τη δοσμένη τιμή. |


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_42}


```
 where_greater_or_equal(attribute_name, value) 
```

Επιλέγει χαρακτηριστικά με τιμή ιδιότητας μεγαλύτερη ή ίση με τη δοσμένη τιμή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| attribute_name | string | Χαρακτηριστικό για φιλτράρισμα. |
| value | object | Τιμή για σύγκριση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Χαρακτηριστικά με τιμή χαρακτηριστικού μεγαλύτερη ή ίση με τη δοσμένη τιμή. |


### Method: where_intersects(extent) {#where_intersects_extent_43}


```
 where_intersects(extent) 
```

Φιλτράρει τα χαρακτηριστικά βάσει της έκτασης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Φίλτρο έκτασης. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Στοιχεία που τέμνονται με τη δοθείσα γεωμετρία. |


### Method: where_intersects(geometry) {#where_intersects_geometry_44}


```
 where_intersects(geometry) 
```

Φιλτράρει τα χαρακτηριστικά βάσει της παρεχόμενης γεωμετρίας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Φίλτρο γεωμετρίας. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Στοιχεία που τέμνονται με τη δοθείσα γεωμετρία. |


### Method: where_intersects(sequence) {#where_intersects_sequence_45}


```
 where_intersects(sequence) 
```

Φιλτράρει τα χαρακτηριστικά βάσει της ένωσης όλων των γεωμετριών στην ακολουθία άλλων χαρακτηριστικών.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Άλλη ακολουθία στοιχείων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Στοιχεία που τέμνονται με την ένωση όλων των γεωμετριών στην άλλη ακολουθία στοιχείων. |


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_46}


```
 where_not_equal(attribute_name, value) 
```

Επιλέγει τα χαρακτηριστικά με τιμή ιδιότητας διαφορετική από την παρεχόμενη τιμή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| attribute_name | string | Χαρακτηριστικό για φιλτράρισμα. |
| value | object | Τιμή για σύγκριση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Στοιχεία με τιμή ιδιότητας διαφορετική από τη δοθείσα τιμή. |


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_47}


```
 where_not_null(attribute_name) 
```

Επιλέγει τα χαρακτηριστικά με ιδιότητα διαφορετική από το null.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| attribute_name | string | Χαρακτηριστικό για φιλτράρισμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Στοιχεία με τιμή ιδιότητας διαφορετική από το null. |


### Method: where_null(attribute_name) {#where_null_attribute_name_48}


```
 where_null(attribute_name) 
```

Επιλέγει τα χαρακτηριστικά με ιδιότητα ίση με το null.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| attribute_name | string | Χαρακτηριστικό για φιλτράρισμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Στοιχεία με τιμή ιδιότητας ίση με το null. |


### Method: where_set(attribute_name) {#where_set_attribute_name_49}


```
 where_set(attribute_name) 
```

Επιλέγει τα χαρακτηριστικά με ορισμένη ιδιότητα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| attribute_name | string | Χαρακτηριστικό για φιλτράρισμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Στοιχεία με ορισμένη τιμή ιδιότητας. |


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_50}


```
 where_smaller(attribute_name, value) 
```

Επιλέγει τα χαρακτηριστικά με τιμή ιδιότητας μικρότερη από την παρεχόμενη τιμή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| attribute_name | string | Χαρακτηριστικό για φιλτράρισμα. |
| value | object | Τιμή για σύγκριση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Στοιχεία με τιμή ιδιότητας μικρότερη από τη δοθείσα τιμή. |


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_51}


```
 where_smaller_or_equal(attribute_name, value) 
```

Επιλέγει τα χαρακτηριστικά με τιμή ιδιότητας μικρότερη ή ίση με την παρεχόμενη τιμή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| attribute_name | string | Χαρακτηριστικό για φιλτράρισμα. |
| value | object | Τιμή για σύγκριση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Στοιχεία με τιμή ιδιότητας μικρότερη ή ίση με τη δοθείσα τιμή. |


### Method: where_unset(attribute_name) {#where_unset_attribute_name_52}


```
 where_unset(attribute_name) 
```

Επιλέγει τα χαρακτηριστικά όπου η καθορισμένη ιδιότητα δεν είναι ορισμένη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| attribute_name | string | Χαρακτηριστικό για φιλτράρισμα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Στοιχεία με μη ορισμένη τιμή ιδιότητας. |


