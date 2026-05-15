---
title: "GpxDriver Κλάση"
type: docs
weight: 10
url: /el/python-net/aspose.gis.formats.gpx/gpxdriver/
---

**Summary:** A driver for the GPX format.

**Module:** [aspose.gis.formats.gpx](/psd/python-net/aspose.gis.formats.gpx/)

**Full Name:** aspose.gis.formats.gpx.GpxDriver

**Inheritance:** FileDriver

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| can_create_datasets | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτός ο οδηγός μπορεί να δημιουργήσει σύνολα δεδομένων. |
| can_create_layers | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτός ο οδηγός μπορεί να δημιουργήσει διανυσματικά στρώματα. |
| can_open_datasets | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτός ο οδηγός μπορεί να ανοίξει σύνολα δεδομένων. |
| can_open_layers | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτός ο οδηγός μπορεί να ανοίξει διανυσματικά στρώματα. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_dataset(path)](#create_dataset_path_1) | Δημιουργεί ένα σύνολο δεδομένων. |
| [create_dataset(path)](#create_dataset_path_2) | Δημιουργεί ένα σύνολο δεδομένων. |
| [create_dataset(path, options)](#create_dataset_path_options_3) | Δημιουργεί ένα σύνολο δεδομένων. |
| [create_dataset(path, options)](#create_dataset_path_options_4) | Δημιουργεί ένα σύνολο δεδομένων. |
| [create_layer(path)](#create_layer_path_5) | Δημιουργεί το στρώμα και το ανοίγει για προσθήκη. |
| [create_layer(path)](#create_layer_path_6) | Δημιουργεί το στρώμα και το ανοίγει για προσθήκη. |
| [create_layer(path, options)](#create_layer_path_options_7) | Δημιουργεί ένα στρώμα και το ανοίγει για την προσθήκη νέων χαρακτηριστικών. |
| [create_layer(path, options)](#create_layer_path_options_8) | Δημιουργεί ένα στρώμα και το ανοίγει για την προσθήκη νέων χαρακτηριστικών. |
| [create_layer(path, options)](#create_layer_path_options_9) | Δημιουργεί ένα στρώμα και το ανοίγει για την προσθήκη νέων χαρακτηριστικών. |
| [create_layer(path, options)](#create_layer_path_options_10) | Δημιουργεί ένα στρώμα και το ανοίγει για την προσθήκη νέων χαρακτηριστικών. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_11) | Δημιουργεί ένα στρώμα και το ανοίγει για την προσθήκη νέων χαρακτηριστικών. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_12) | Δημιουργεί ένα στρώμα και το ανοίγει για την προσθήκη νέων χαρακτηριστικών. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_13) | Δημιουργεί ένα στρώμα και το ανοίγει για την προσθήκη νέων χαρακτηριστικών. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_14) | Δημιουργεί το στρώμα και το ανοίγει για προσθήκη. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_15) | Δημιουργεί το στρώμα και το ανοίγει για προσθήκη. |
| [edit_layer(path, options)](#edit_layer_path_options_16) | Ανοίγει ένα στρώμα για επεξεργασία. |
| [edit_layer(path, options)](#edit_layer_path_options_17) | Ανοίγει ένα στρώμα για επεξεργασία. |
| [open_dataset(path)](#open_dataset_path_18) | Ανοίγει το σύνολο δεδομένων. |
| [open_dataset(path)](#open_dataset_path_19) | Ανοίγει το σύνολο δεδομένων. |
| [open_dataset(path, options)](#open_dataset_path_options_20) | Ανοίγει το σύνολο δεδομένων. |
| [open_dataset(path, options)](#open_dataset_path_options_21) | Ανοίγει το σύνολο δεδομένων. |
| [open_layer(path)](#open_layer_path_22) | Ανοίγει το στρώμα για ανάγνωση. |
| [open_layer(path)](#open_layer_path_23) | Ανοίγει το στρώμα για ανάγνωση. |
| [open_layer(path, options)](#open_layer_path_options_24) | Ανοίγει ένα στρώμα για ανάγνωση. |
| [open_layer(path, options)](#open_layer_path_options_25) | Ανοίγει ένα στρώμα για ανάγνωση. |
| [open_layer(path, options)](#open_layer_path_options_26) | Ανοίγει ένα στρώμα για ανάγνωση. |
| [open_layer(path, options)](#open_layer_path_options_27) | Ανοίγει ένα στρώμα για ανάγνωση. |
| [supports_spatial_reference_system(spatial_reference_system)](#supports_spatial_reference_system_spatial_reference_system_28) | Καθορίζει εάν το καθορισμένο σύστημα αναφοράς χώρου υποστηρίζεται από τον οδηγό. |


### Method: create_dataset(path) {#create_dataset_path_1}


```
 create_dataset(path) 
```

Δημιουργεί ένα σύνολο δεδομένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το σύνολο δεδομένων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Μια παρουσία του [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path) {#create_dataset_path_2}


```
 create_dataset(path) 
```

Δημιουργεί ένα σύνολο δεδομένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το σύνολο δεδομένων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Μια παρουσία του [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_3}


```
 create_dataset(path, options) 
```

Δημιουργεί ένα σύνολο δεδομένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το σύνολο δεδομένων. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ειδικές για τον οδηγό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Μια παρουσία του [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_4}


```
 create_dataset(path, options) 
```

Δημιουργεί ένα σύνολο δεδομένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το σύνολο δεδομένων. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ειδικές για τον οδηγό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Μια παρουσία του [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_layer(path) {#create_layer_path_5}


```
 create_layer(path) 
```

Δημιουργεί το στρώμα και το ανοίγει για προσθήκη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το αρχείο. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Μια παρουσία του [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path) {#create_layer_path_6}


```
 create_layer(path) 
```

Δημιουργεί το στρώμα και το ανοίγει για προσθήκη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το αρχείο. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Μια παρουσία του [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_7}


```
 create_layer(path, options) 
```

Δημιουργεί ένα στρώμα και το ανοίγει για την προσθήκη νέων χαρακτηριστικών.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το αρχείο. |
| options | [GpxOptions](/psd/python-net/aspose.gis.formats.gpx/gpxoptions) | Επιλογές ειδικές για τον οδηγό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Μια παρουσία του [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_8}


```
 create_layer(path, options) 
```

Δημιουργεί ένα στρώμα και το ανοίγει για την προσθήκη νέων χαρακτηριστικών.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το αρχείο. |
| options | [GpxOptions](/psd/python-net/aspose.gis.formats.gpx/gpxoptions) | Επιλογές ειδικές για τον οδηγό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Μια παρουσία του [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_9}


```
 create_layer(path, options) 
```

Δημιουργεί ένα στρώμα και το ανοίγει για την προσθήκη νέων χαρακτηριστικών.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το αρχείο. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ειδικές για τον οδηγό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Μια παρουσία του [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_10}


```
 create_layer(path, options) 
```

Δημιουργεί ένα στρώμα και το ανοίγει για την προσθήκη νέων χαρακτηριστικών.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το αρχείο. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ειδικές για τον οδηγό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Μια παρουσία του [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_11}


```
 create_layer(path, options, spatial_reference_system) 
```

Δημιουργεί ένα στρώμα και το ανοίγει για την προσθήκη νέων χαρακτηριστικών.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το αρχείο. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ειδικές για τον οδηγό. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Σύστημα αναφοράς χώρου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Μια παρουσία του [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_12}


```
 create_layer(path, options, spatial_reference_system) 
```

Δημιουργεί ένα στρώμα και το ανοίγει για την προσθήκη νέων χαρακτηριστικών.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το αρχείο. |
| options | [GpxOptions](/psd/python-net/aspose.gis.formats.gpx/gpxoptions) | Επιλογές ειδικές για τον οδηγό. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Σύστημα αναφοράς χώρου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Μια παρουσία του [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_13}


```
 create_layer(path, options, spatial_reference_system) 
```

Δημιουργεί ένα στρώμα και το ανοίγει για την προσθήκη νέων χαρακτηριστικών.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το αρχείο. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ειδικές για τον οδηγό. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Σύστημα αναφοράς χώρου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Μια παρουσία του [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_14}


```
 create_layer(path, spatial_reference_system) 
```

Δημιουργεί το στρώμα και το ανοίγει για προσθήκη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το αρχείο. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Σύστημα αναφοράς χώρου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Μια παρουσία του [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_15}


```
 create_layer(path, spatial_reference_system) 
```

Δημιουργεί το στρώμα και το ανοίγει για προσθήκη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το αρχείο. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Σύστημα αναφοράς χώρου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Μια παρουσία του [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: edit_layer(path, options) {#edit_layer_path_options_16}


```
 edit_layer(path, options) 
```

Ανοίγει ένα στρώμα για επεξεργασία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το αρχείο. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ειδικές για τον οδηγό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Μια παρουσία του [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: edit_layer(path, options) {#edit_layer_path_options_17}


```
 edit_layer(path, options) 
```

Ανοίγει ένα στρώμα για επεξεργασία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το αρχείο. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ειδικές για τον οδηγό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Μια παρουσία του [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_dataset(path) {#open_dataset_path_18}


```
 open_dataset(path) 
```

Ανοίγει το σύνολο δεδομένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το σύνολο δεδομένων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Μια παρουσία του [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path) {#open_dataset_path_19}


```
 open_dataset(path) 
```

Ανοίγει το σύνολο δεδομένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το σύνολο δεδομένων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Μια παρουσία του [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_20}


```
 open_dataset(path, options) 
```

Ανοίγει το σύνολο δεδομένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το σύνολο δεδομένων. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ειδικές για τον οδηγό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Μια παρουσία του [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_21}


```
 open_dataset(path, options) 
```

Ανοίγει το σύνολο δεδομένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το σύνολο δεδομένων. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ειδικές για τον οδηγό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Μια παρουσία του [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_layer(path) {#open_layer_path_22}


```
 open_layer(path) 
```

Ανοίγει το στρώμα για ανάγνωση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το αρχείο. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Μια παρουσία του [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path) {#open_layer_path_23}


```
 open_layer(path) 
```

Ανοίγει το στρώμα για ανάγνωση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το αρχείο. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Μια παρουσία του [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_24}


```
 open_layer(path, options) 
```

Ανοίγει ένα στρώμα για ανάγνωση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το αρχείο. |
| options | [GpxOptions](/psd/python-net/aspose.gis.formats.gpx/gpxoptions) | Επιλογές ειδικές για τον οδηγό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Μια παρουσία του [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_25}


```
 open_layer(path, options) 
```

Ανοίγει ένα στρώμα για ανάγνωση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το αρχείο. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ειδικές για τον οδηγό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Μια παρουσία του [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_26}


```
 open_layer(path, options) 
```

Ανοίγει ένα στρώμα για ανάγνωση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το αρχείο. |
| options | [GpxOptions](/psd/python-net/aspose.gis.formats.gpx/gpxoptions) | Επιλογές ειδικές για τον οδηγό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Μια παρουσία του [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_27}


```
 open_layer(path, options) 
```

Ανοίγει ένα στρώμα για ανάγνωση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το αρχείο. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Επιλογές ειδικές για τον οδηγό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Μια παρουσία του [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: supports_spatial_reference_system(spatial_reference_system) {#supports_spatial_reference_system_spatial_reference_system_28}


```
 supports_spatial_reference_system(spatial_reference_system) 
```

Καθορίζει εάν το καθορισμένο σύστημα αναφοράς χώρου υποστηρίζεται από τον οδηγό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Σύστημα αναφοράς χώρου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Τιμή Boolean, που υποδεικνύει εάν το καθορισμένο σύστημα αναφοράς χώρου υποστηρίζεται από τον οδηγό. |


