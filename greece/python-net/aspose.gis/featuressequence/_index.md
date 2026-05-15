---
title: "FeaturesSequence Κλάση"
type: docs
weight: 870
url: /el/python-net/aspose.gis/featuressequence/
---

**Summary:** [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence/) represents a set of vector features.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeaturesSequence

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | Λαμβάνει τη συλλογή των προσαρμοσμένων χαρακτηριστικών για τα στοιχεία σε αυτό το [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Λαμβάνει το σύστημα αναφοράς χώρου της ακολουθίας χαρακτηριστικών αυτής. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_extent()](#get_extent__1) | Λαμβάνει την χωρική έκταση αυτού του στρώματος. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_2) | Αποθηκεύει τη σειρά χαρακτηριστικών στο στρώμα. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_3) | Αποθηκεύει τη σειρά χαρακτηριστικών στο στρώμα. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_4) | Αποθηκεύει τη σειρά χαρακτηριστικών στο στρώμα. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_5) | Αποθηκεύει τη σειρά χαρακτηριστικών στο στρώμα. |
| [split_to()](#split_to__6) | Διαιρεί τα χαρακτηριστικά ανά τύπο γεωμετρίας. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_7) | Επιλέγει χαρακτηριστικά με τιμή ιδιότητας ίση με τη δοσμένη τιμή. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_8) | Επιλέγει χαρακτηριστικά με τιμή ιδιότητας μεγαλύτερη από τη δοσμένη τιμή. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_9) | Επιλέγει χαρακτηριστικά με τιμή ιδιότητας μεγαλύτερη ή ίση με τη δοσμένη τιμή. |
| [where_intersects(extent)](#where_intersects_extent_10) | Φιλτράρει τα χαρακτηριστικά βάσει της έκτασης. |
| [where_intersects(geometry)](#where_intersects_geometry_11) | Φιλτράρει τα χαρακτηριστικά βάσει της παρεχόμενης γεωμετρίας. |
| [where_intersects(sequence)](#where_intersects_sequence_12) | Φιλτράρει τα χαρακτηριστικά βάσει της ένωσης όλων των γεωμετριών στην ακολουθία άλλων χαρακτηριστικών. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_13) | Επιλέγει τα χαρακτηριστικά με τιμή ιδιότητας διαφορετική από την παρεχόμενη τιμή. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_14) | Επιλέγει τα χαρακτηριστικά με ιδιότητα διαφορετική από το null. |
| [where_null(attribute_name)](#where_null_attribute_name_15) | Επιλέγει τα χαρακτηριστικά με ιδιότητα ίση με το null. |
| [where_set(attribute_name)](#where_set_attribute_name_16) | Επιλέγει τα χαρακτηριστικά με ορισμένη ιδιότητα. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_17) | Επιλέγει τα χαρακτηριστικά με τιμή ιδιότητας μικρότερη από την παρεχόμενη τιμή. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_18) | Επιλέγει τα χαρακτηριστικά με τιμή ιδιότητας μικρότερη ή ίση με την παρεχόμενη τιμή. |
| [where_unset(attribute_name)](#where_unset_attribute_name_19) | Επιλέγει τα χαρακτηριστικά όπου η καθορισμένη ιδιότητα δεν είναι ορισμένη. |


### Method: get_extent() {#get_extent__1}


```
 get_extent() 
```

Λαμβάνει την χωρική έκταση αυτού του στρώματος.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Μια χωρική έκταση αυτού του επιπέδου. |


### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_2}


```
 save_to(destination_path, destination_driver) 
```

Αποθηκεύει τη σειρά χαρακτηριστικών στο στρώμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| destination_path | string | Διαδρομή προς το στρώμα εξόδου. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Ο οδηγός μορφής για το στρώμα εξόδου. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_3}


```
 save_to(destination_path, destination_driver) 
```

Αποθηκεύει τη σειρά χαρακτηριστικών στο στρώμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το στρώμα εξόδου. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Ο οδηγός μορφής για το στρώμα εξόδου. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_4}


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

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_5}


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

### Method: split_to() {#split_to__6}


```
 split_to() 
```

Διαιρεί τα χαρακτηριστικά ανά τύπο γεωμετρίας.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | Στρώματα με τον ίδιο τύπο γεωμετρίας. |


### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_7}


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


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_8}


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


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_9}


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


### Method: where_intersects(extent) {#where_intersects_extent_10}


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


### Method: where_intersects(geometry) {#where_intersects_geometry_11}


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


### Method: where_intersects(sequence) {#where_intersects_sequence_12}


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


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_13}


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


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_14}


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


### Method: where_null(attribute_name) {#where_null_attribute_name_15}


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


### Method: where_set(attribute_name) {#where_set_attribute_name_16}


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


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_17}


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


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_18}


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


### Method: where_unset(attribute_name) {#where_unset_attribute_name_19}


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


