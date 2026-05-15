---
title: "Κλάση ImageMetadataReader"
type: docs
weight: 30
url: /el/python-net/aspose.gis.imagemetadata/imagemetadatareader/
---

**Summary:** Class for editing, adding some EXIF tags

**Module:** [aspose.gis.imagemetadata](/psd/python-net/aspose.gis.imagemetadata/)

**Full Name:** aspose.gis.imagemetadata.ImageMetadataReader

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_reader(file_name)](#get_reader_file_name_1) | Δημιουργεί μια παρουσία αναγνώστη για ετικέτες EXIF |
| [get_reader(stream)](#get_reader_stream_2) | Δημιουργεί μια παρουσία αναγνώστη για ετικέτες EXIF |
| [read_data()](#read_data__3) | Εξάγει όλες τις υποστηριζόμενες ετικέτες EXIF |
| [save(file_name)](#save_file_name_4) | Αποθηκεύει σε νέο αρχείο επειδή το αρχικό είναι κλειδωμένο για αλλαγές |
| [save(file_name, format)](#save_file_name_format_5) | Αποθηκεύει σε νέο αρχείο επειδή το αρχικό είναι κλειδωμένο για αλλαγές |
| [save(stream)](#save_stream_6) | Αποθήκευση αλλαγών σε ξεχωριστή ροή |
| [save(stream, format)](#save_stream_format_7) | Αποθήκευση αλλαγών σε ξεχωριστή ροή |
| [set_artist(artist)](#set_artist_artist_8) | Αποθήκευση της ετικέτας EXIF Artist, προσθήκη ή αντικατάσταση των δεδομένων. |
| [set_description(description)](#set_description_description_9) | Αποθήκευση της ετικέτας EXIF ImageDescription, προσθήκη ή αντικατάσταση των δεδομένων. |
| [set_geo_location(latitude, longitude)](#set_geo_location_latitude_longitude_10) | Αποθήκευση των ετικετών EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude και GPSLongitude, προσθήκη ή αντικατάσταση των δεδομένων. |
| [set_image_size(width, height)](#set_image_size_width_height_11) | Αποθήκευση των ετικετών EXIF ImageWidth και ImageHeight, προσθήκη ή αντικατάσταση των δεδομένων. |
| [set_modify_date(modify_date)](#set_modify_date_modify_date_12) | Αποθήκευση της ετικέτας EXIF ModifyDate (DataTime), προσθήκη ή αντικατάσταση των δεδομένων. |
| [try_get_artist(artist)](#try_get_artist_artist_13) | Προσπαθεί να βρει την ετικέτα EXIF Artist, εάν η ετικέτα δεν βρεθεί επιστρέφει null |
| [try_get_description(description)](#try_get_description_description_14) | Προσπαθεί να βρει την ετικέτα EXIF ImageDescription, εάν η ετικέτα δεν βρεθεί επιστρέφει null |
| [try_get_geo_location(geo_location)](#try_get_geo_location_geo_location_15) | Προσπαθεί να βρει το σύνολο ετικετών EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude, GPSLongitude, εάν οι ετικέτες δεν εμφανιστούν επιστρέφει null |
| [try_get_image_size(image_size)](#try_get_image_size_image_size_16) | Προσπαθεί να βρει το σύνολο ετικετών EXIF ImageWidth και ImageHeight, εάν οι ετικέτες δεν εμφανιστούν επιστρέφει null |
| [try_get_modify_date(modify_date)](#try_get_modify_date_modify_date_17) | Προσπαθεί να βρει την ετικέτα EXIF ModifyDate (DataTime), εάν η ετικέτα δεν βρεθεί επιστρέφει την προεπιλεγμένη τιμή DataTime |


### Method: get_reader(file_name)  [static] {#get_reader_file_name_1}


```
 get_reader(file_name) 
```

Δημιουργεί μια παρουσία αναγνώστη για ετικέτες EXIF

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_name | string | Πλήρες όνομα του αρχείου εικόνας. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | Παράδειγμα αναγνώστη μεταδεδομένων |


### Method: get_reader(stream)  [static] {#get_reader_stream_2}


```
 get_reader(stream) 
```

Δημιουργεί μια παρουσία αναγνώστη για ετικέτες EXIF

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Ροή πηγής δεδομένων εικόνας |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | Παράδειγμα αναγνώστη μεταδεδομένων |


### Method: read_data() {#read_data__3}


```
 read_data() 
```

Εξάγει όλες τις υποστηριζόμενες ετικέτες EXIF

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ImageData](/psd/python-net/aspose.gis.imagemetadata/imagedata) | ImageData που αντιπροσωπεύει το σύνολο των υποστηριζόμενων ετικετών |


### Method: save(file_name) {#save_file_name_4}


```
 save(file_name) 
```

Αποθηκεύει σε νέο αρχείο επειδή το αρχικό είναι κλειδωμένο για αλλαγές

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_name | string | Πλήρες όνομα του αρχείου προορισμού |

### Method: save(file_name, format) {#save_file_name_format_5}


```
 save(file_name, format) 
```

Αποθηκεύει σε νέο αρχείο επειδή το αρχικό είναι κλειδωμένο για αλλαγές

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| file_name | string | Πλήρες όνομα του αρχείου προορισμού |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | Καθορίζει τη μορφή για αποθήκευση |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

Αποθήκευση αλλαγών σε ξεχωριστή ροή

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Ροή προορισμού |

### Method: save(stream, format) {#save_stream_format_7}


```
 save(stream, format) 
```

Αποθήκευση αλλαγών σε ξεχωριστή ροή

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom | Ροή προορισμού |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | Καθορίζει τη μορφή για αποθήκευση |

### Method: set_artist(artist) {#set_artist_artist_8}


```
 set_artist(artist) 
```

Αποθήκευση της ετικέτας EXIF Artist, προσθήκη ή αντικατάσταση των δεδομένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| καλλιτέχνης | string | Ο καλλιτέχνης. |

### Method: set_description(description) {#set_description_description_9}


```
 set_description(description) 
```

Αποθήκευση της ετικέτας EXIF ImageDescription, προσθήκη ή αντικατάσταση των δεδομένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| περιγραφή | string | Η περιγραφή. |

### Method: set_geo_location(latitude, longitude) {#set_geo_location_latitude_longitude_10}


```
 set_geo_location(latitude, longitude) 
```

Αποθήκευση των ετικετών EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude και GPSLongitude, προσθήκη ή αντικατάσταση των δεδομένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| γεωγραφικό πλάτος | double | Το γεωγραφικό πλάτος. |
| γεωγραφικό μήκος | double | Το γεωγραφικό μήκος. |

### Method: set_image_size(width, height) {#set_image_size_width_height_11}


```
 set_image_size(width, height) 
```

Αποθήκευση των ετικετών EXIF ImageWidth και ImageHeight, προσθήκη ή αντικατάσταση των δεδομένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| width | int | Το πλάτος. |
| ύψος | int | Το ύψος. |

### Method: set_modify_date(modify_date) {#set_modify_date_modify_date_12}


```
 set_modify_date(modify_date) 
```

Αποθήκευση της ετικέτας EXIF ModifyDate (DataTime), προσθήκη ή αντικατάσταση των δεδομένων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| modify_date | datetime | Η ημερομηνία τροποποίησης. |

### Method: try_get_artist(artist) {#try_get_artist_artist_13}


```
 try_get_artist(artist) 
```

Προσπαθεί να βρει την ετικέτα EXIF Artist, εάν η ετικέτα δεν βρεθεί επιστρέφει null

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| καλλιτέχνης | Συμβολοσειρά | Ο καλλιτέχνης. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αληθές εάν είναι επιτυχές |


### Method: try_get_description(description) {#try_get_description_description_14}


```
 try_get_description(description) 
```

Προσπαθεί να βρει την ετικέτα EXIF ImageDescription, εάν η ετικέτα δεν βρεθεί επιστρέφει null

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| περιγραφή | Συμβολοσειρά | Η περιγραφή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αληθές εάν είναι επιτυχές |


### Method: try_get_geo_location(geo_location) {#try_get_geo_location_geo_location_15}


```
 try_get_geo_location(geo_location) 
```

Προσπαθεί να βρει το σύνολο ετικετών EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude, GPSLongitude, εάν οι ετικέτες δεν εμφανιστούν επιστρέφει null

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| geo_location | [GeoLocation[]](/psd/python-net/aspose.gis.imagemetadata/geolocation) | Η γεωγραφική θέση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αληθές εάν είναι επιτυχές |


### Method: try_get_image_size(image_size) {#try_get_image_size_image_size_16}


```
 try_get_image_size(image_size) 
```

Προσπαθεί να βρει το σύνολο ετικετών EXIF ImageWidth και ImageHeight, εάν οι ετικέτες δεν εμφανιστούν επιστρέφει null

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| image_size | [ImageSize[]](/psd/python-net/aspose.gis.imagemetadata/imagesize) | Μέγεθος της εικόνας. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αληθές εάν είναι επιτυχές |


### Method: try_get_modify_date(modify_date) {#try_get_modify_date_modify_date_17}


```
 try_get_modify_date(modify_date) 
```

Προσπαθεί να βρει την ετικέτα EXIF ModifyDate (DataTime), εάν η ετικέτα δεν βρεθεί επιστρέφει την προεπιλεγμένη τιμή DataTime

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| modify_date | datetime[] | Η ημερομηνία τροποποίησης. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Αληθές εάν είναι επιτυχές |


