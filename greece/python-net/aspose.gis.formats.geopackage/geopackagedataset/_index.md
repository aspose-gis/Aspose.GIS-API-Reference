---
title: "GeoPackageDataset Κλάση"
type: docs
weight: 10
url: /el/python-net/aspose.gis.formats.geopackage/geopackagedataset/
---

**Summary:** Represents a collection of feature layers and tile layers in GeoPackage format.

**Module:** [aspose.gis.formats.geopackage](/psd/python-net/aspose.gis.formats.geopackage/)

**Full Name:** aspose.gis.formats.geopackage.GeoPackageDataset

**Inheritance:** Dataset

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GeoPackageDataset(path, options)](#GeoPackageDataset_path_options_1) | Δημιουργεί νέο αντικείμενο. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| can_create_layers | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το σύνολο δεδομένων μπορεί να δημιουργήσει διανυσματικά επίπεδα. |
| can_remove_layers | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το σύνολο δεδομένων μπορεί να αφαιρέσει διανυσματικά επίπεδα. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Λαμβάνει το [GeoPackageDataset.driver](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset/) που δημιούργησε αυτό το σύνολο δεδομένων. |
| layers_count | int | r | Λαμβάνει τον αριθμό των επιπέδων σε αυτό το σύνολο δεδομένων. |
| tile_layers_count | int | r | Λαμβάνει τον αριθμό των tile layers σε αυτό το σύνολο δεδομένων. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create(path, driver)](#create_path_driver_1) | Δημιουργεί ένα σύνολο δεδομένων. |
| [create(path, driver)](#create_path_driver_2) | Δημιουργεί ένα σύνολο δεδομένων. |
| [create(path, driver, options)](#create_path_driver_options_3) | Δημιουργεί ένα σύνολο δεδομένων. |
| [create(path, driver, options)](#create_path_driver_options_4) | Δημιουργεί ένα σύνολο δεδομένων. |
| [create_layer()](#create_layer__5) | Δημιουργεί ένα νέο διανυσματικό στρώμα και το ανοίγει για προσθήκη. |
| [create_layer(name, options, spatial_reference_system)](#create_layer_name_options_spatial_reference_system_6) | Δημιουργεί ένα νέο διανυσματικό στρώμα με το καθορισμένο όνομα και το ανοίγει για προσθήκη. |
| [create_layer(name, spatial_reference_system)](#create_layer_name_spatial_reference_system_7) | Δημιουργεί ένα νέο διανυσματικό στρώμα με το καθορισμένο όνομα και το ανοίγει για προσθήκη. |
| [create_layer(options, spatial_reference_system)](#create_layer_options_spatial_reference_system_8) | Δημιουργεί ένα νέο διανυσματικό στρώμα και το ανοίγει για προσθήκη. |
| [create_layer(spatial_reference_system)](#create_layer_spatial_reference_system_9) | Δημιουργεί ένα νέο διανυσματικό στρώμα και το ανοίγει για προσθήκη. |
| [edit_layer(name, options, spatial_reference_system)](#edit_layer_name_options_spatial_reference_system_10) | Αυτή η μέθοδος βρίσκεται ακόμη σε ανάπτυξη. |
| [edit_layer_at(index, options, spatial_reference_system)](#edit_layer_at_index_options_spatial_reference_system_11) | Αυτή η μέθοδος βρίσκεται ακόμη σε ανάπτυξη. |
| [get_layer_name(index)](#get_layer_name_index_12) | Λαμβάνει το όνομα του στρώματος στον καθορισμένο δείκτη. |
| [get_tile_layer_name(index)](#get_tile_layer_name_index_13) | Λαμβάνει το όνομα του tile layer στον καθορισμένο δείκτη. |
| [has_layer_with_name(name)](#has_layer_with_name_name_14) | Ελέγχει αν το τρέχον σύνολο δεδομένων έχει στρώμα με συγκεκριμένο όνομα. |
| [open(path, driver)](#open_path_driver_15) | Ανοίγει το σύνολο δεδομένων. |
| [open(path, driver)](#open_path_driver_16) | Ανοίγει το σύνολο δεδομένων. |
| [open(path, driver, options)](#open_path_driver_options_17) | Ανοίγει το σύνολο δεδομένων. |
| [open(path, driver, options)](#open_path_driver_options_18) | Ανοίγει το σύνολο δεδομένων. |
| [open(path, options)](#open_path_options_19) | Μέθοδος κατασκευής για τη δημιουργία ενός συνόλου δεδομένων από αρχείο gpkg. |
| [open_layer(name, options)](#open_layer_name_options_20) | Ανοίγει το στρώμα με το καθορισμένο όνομα για ανάγνωση. |
| [open_layer_at(index, options)](#open_layer_at_index_options_21) | Ανοίγει το στρώμα στον καθορισμένο δείκτη για ανάγνωση. |
| [open_layer_at(index, options)](#open_layer_at_index_options_22) | Ανοίγει το στρώμα στον καθορισμένο δείκτη για ανάγνωση. |
| [open_tile_layer(name, options)](#open_tile_layer_name_options_23) | Ανοίγει το tile layer με το καθορισμένο όνομα για ανάγνωση. |
| [open_tile_layer_at(index, options)](#open_tile_layer_at_index_options_24) | Ανοίγει το tile layer στον καθορισμένο δείκτη για ανάγνωση. |
| [remove_layer(name)](#remove_layer_name_25) | Αφαιρεί το διανυσματικό στρώμα με το καθορισμένο όνομα. |
| [remove_layer_at(index)](#remove_layer_at_index_26) | Αφαιρεί το διανυσματικό στρώμα στον καθορισμένο δείκτη. |
| [rename_layer(current_name, new_name)](#rename_layer_current_name_new_name_27) | Μετονομασία στρώματος στο σύνολο δεδομένων |


### Constructor: GeoPackageDataset(path, options) {#GeoPackageDataset_path_options_1}


```
 GeoPackageDataset(path, options) 
```

Δημιουργεί νέο αντικείμενο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το αρχείο gpkg. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Ρυθμίσεις σχετικά με τις ιδιαιτερότητες της ανάγνωσης του αρχείου gpkg. |

### Method: create(path, driver)  [static] {#create_path_driver_1}


```
 create(path, driver) 
```

Δημιουργεί ένα σύνολο δεδομένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το σύνολο δεδομένων. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Οδηγός προς χρήση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Μια παρουσία του [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver)  [static] {#create_path_driver_2}


```
 create(path, driver) 
```

Δημιουργεί ένα σύνολο δεδομένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το σύνολο δεδομένων. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Οδηγός προς χρήση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Μια παρουσία του [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_3}


```
 create(path, driver, options) 
```

Δημιουργεί ένα σύνολο δεδομένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το σύνολο δεδομένων. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Οδηγός προς χρήση. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ειδικές για τον οδηγό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Μια παρουσία του [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_4}


```
 create(path, driver, options) 
```

Δημιουργεί ένα σύνολο δεδομένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το σύνολο δεδομένων. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Οδηγός προς χρήση. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ειδικές για τον οδηγό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Μια παρουσία του [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_layer() {#create_layer__5}


```
 create_layer() 
```

Δημιουργεί ένα νέο διανυσματικό στρώμα και το ανοίγει για προσθήκη.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ένα [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ανοιγμένο για εγγραφή. |


### Method: create_layer(name, options, spatial_reference_system) {#create_layer_name_options_spatial_reference_system_6}


```
 create_layer(name, options, spatial_reference_system) 
```

Δημιουργεί ένα νέο διανυσματικό στρώμα με το καθορισμένο όνομα και το ανοίγει για προσθήκη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Όνομα του στρώματος. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ανοίγματος. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Σύστημα αναφοράς χώρου του νέου στρώματος. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ένα [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ανοιγμένο για εγγραφή. |


### Method: create_layer(name, spatial_reference_system) {#create_layer_name_spatial_reference_system_7}


```
 create_layer(name, spatial_reference_system) 
```

Δημιουργεί ένα νέο διανυσματικό στρώμα με το καθορισμένο όνομα και το ανοίγει για προσθήκη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Όνομα του στρώματος. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Σύστημα αναφοράς χώρου του νέου στρώματος. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ένα [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ανοιγμένο για εγγραφή. |


### Method: create_layer(options, spatial_reference_system) {#create_layer_options_spatial_reference_system_8}


```
 create_layer(options, spatial_reference_system) 
```

Δημιουργεί ένα νέο διανυσματικό στρώμα και το ανοίγει για προσθήκη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ανοίγματος. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Σύστημα αναφοράς χώρου του νέου στρώματος. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ένα [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ανοιγμένο για εγγραφή. |


### Method: create_layer(spatial_reference_system) {#create_layer_spatial_reference_system_9}


```
 create_layer(spatial_reference_system) 
```

Δημιουργεί ένα νέο διανυσματικό στρώμα και το ανοίγει για προσθήκη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Σύστημα αναφοράς χώρου του νέου στρώματος. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ένα [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ανοιγμένο για εγγραφή. |


### Method: edit_layer(name, options, spatial_reference_system) {#edit_layer_name_options_spatial_reference_system_10}


```
 edit_layer(name, options, spatial_reference_system) 
```

Αυτή η μέθοδος βρίσκεται ακόμη σε ανάπτυξη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Όνομα του στρώματος για επεξεργασία. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ανοίγματος. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Σύστημα αναφοράς χώρου για νέες γεωμετρίες. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) |


### Method: edit_layer_at(index, options, spatial_reference_system) {#edit_layer_at_index_options_spatial_reference_system_11}


```
 edit_layer_at(index, options, spatial_reference_system) 
```

Αυτή η μέθοδος βρίσκεται ακόμη σε ανάπτυξη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | int | Δείκτης του στρώματος για επεξεργασία. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ανοίγματος. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Σύστημα αναφοράς χώρου για νέες γεωμετρίες. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) |


### Method: get_layer_name(index) {#get_layer_name_index_12}


```
 get_layer_name(index) 
```

Λαμβάνει το όνομα του στρώματος στον καθορισμένο δείκτη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | int | Δείκτης του στρώματος. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Όνομα του στρώματος. |


### Method: get_tile_layer_name(index) {#get_tile_layer_name_index_13}


```
 get_tile_layer_name(index) 
```

Λαμβάνει το όνομα του tile layer στον καθορισμένο δείκτη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | int | Δείκτης του στρώματος. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Όνομα του στρώματος. |


### Method: has_layer_with_name(name) {#has_layer_with_name_name_14}


```
 has_layer_with_name(name) 
```

Ελέγχει αν το τρέχον σύνολο δεδομένων έχει στρώμα με συγκεκριμένο όνομα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Όνομα του στρώματος |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <see langword=\"true\" />, εάν το σύνολο δεδομένων έχει στρώμα με αυτό το όνομα· διαφορετικά, <see langword=\"false\" /> |


### Method: open(path, driver)  [static] {#open_path_driver_15}


```
 open(path, driver) 
```

Ανοίγει το σύνολο δεδομένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το σύνολο δεδομένων. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Οδηγός προς χρήση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Μια παρουσία του [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver)  [static] {#open_path_driver_16}


```
 open(path, driver) 
```

Ανοίγει το σύνολο δεδομένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το σύνολο δεδομένων. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Οδηγός προς χρήση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Μια παρουσία του [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_17}


```
 open(path, driver, options) 
```

Ανοίγει το σύνολο δεδομένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το σύνολο δεδομένων. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Οδηγός προς χρήση. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ειδικές για τον οδηγό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Μια παρουσία του [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_18}


```
 open(path, driver, options) 
```

Ανοίγει το σύνολο δεδομένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το σύνολο δεδομένων. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Οδηγός προς χρήση. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ειδικές για τον οδηγό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Μια παρουσία του [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, options)  [static] {#open_path_options_19}


```
 open(path, options) 
```

Μέθοδος κατασκευής για τη δημιουργία ενός συνόλου δεδομένων από αρχείο gpkg.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το αρχείο gpkg. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Ρυθμίσεις σχετικά με τις ιδιαιτερότητες της ανάγνωσης του αρχείου gpkg. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset) | [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset/) |


### Method: open_layer(name, options) {#open_layer_name_options_20}


```
 open_layer(name, options) 
```

Ανοίγει το στρώμα με το καθορισμένο όνομα για ανάγνωση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Όνομα του στρώματος για άνοιγμα. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ανοίγματος. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Το στρώμα ανοιγμένο για ανάγνωση. |


### Method: open_layer_at(index, options) {#open_layer_at_index_options_21}


```
 open_layer_at(index, options) 
```

Ανοίγει το στρώμα στον καθορισμένο δείκτη για ανάγνωση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | int | Δείκτης του στρώματος για άνοιγμα. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ανοίγματος. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Το στρώμα ανοιγμένο για ανάγνωση. |


### Method: open_layer_at(index, options) {#open_layer_at_index_options_22}


```
 open_layer_at(index, options) 
```

Ανοίγει το στρώμα στον καθορισμένο δείκτη για ανάγνωση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | int | Δείκτης του στρώματος για άνοιγμα. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Επιλογές ανοίγματος. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Το στρώμα ανοιγμένο για ανάγνωση. |


### Method: open_tile_layer(name, options) {#open_tile_layer_name_options_23}


```
 open_tile_layer(name, options) 
```

Ανοίγει το tile layer με το καθορισμένο όνομα για ανάγνωση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Όνομα του στρώματος για άνοιγμα. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Επιλογές ανοίγματος. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) | Το tile layer άνοιξε για ανάγνωση. |


### Method: open_tile_layer_at(index, options) {#open_tile_layer_at_index_options_24}


```
 open_tile_layer_at(index, options) 
```

Ανοίγει το tile layer στον καθορισμένο δείκτη για ανάγνωση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | int | Δείκτης του στρώματος για άνοιγμα. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Επιλογές ανοίγματος. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) | [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) |


### Method: remove_layer(name) {#remove_layer_name_25}


```
 remove_layer(name) 
```

Αφαιρεί το διανυσματικό στρώμα με το καθορισμένο όνομα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Όνομα του στρώματος |

### Method: remove_layer_at(index) {#remove_layer_at_index_26}


```
 remove_layer_at(index) 
```

Αφαιρεί το διανυσματικό στρώμα στον καθορισμένο δείκτη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | int | Δείκτης του στρώματος |

### Method: rename_layer(current_name, new_name) {#rename_layer_current_name_new_name_27}


```
 rename_layer(current_name, new_name) 
```

Μετονομασία στρώματος στο σύνολο δεδομένων

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| current_name | string | Τρέχον όνομα του στρώματος |
| new_name | string | Νέο όνομα για το στρώμα |

