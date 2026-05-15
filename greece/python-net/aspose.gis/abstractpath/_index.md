---
title: "Κλάση AbstractPath"
type: docs
weight: 10
url: /el/python-net/aspose.gis/abstractpath/
---

**Summary:** An <c>AbstractPath</c> is a base class for classes that specify a unique location in an environment similar to a filesystem,<br/>            like a local filesystem, a remote file storage or a ZIP archive, among others.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.AbstractPath

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| τοποθεσία | string | r | Λαμβάνει μια αναπαράσταση συμβολοσειράς της τοποθεσίας αυτού του <c>AbstractPath</c>. |
| separator | char | r | Λαμβάνει έναν χαρακτήρα διαχωριστή που χρησιμοποιείται για το διαχωρισμό επιπέδων καταλόγου της συμβολοσειράς [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [combine(location)](#combine_location_1) | Συνδυάζει αυτό το [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) με τα καθορισμένα στοιχεία διαδρομής. |
| delete() | Διαγράφει ένα αρχείο που δείχνει αυτή η διαδρομή. |
| [from_local_path(path)](#from_local_path_path_2) | Δημιουργεί ένα [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) που αντιπροσωπεύει μια τοποθεσία στο τοπικό σύστημα αρχείων. |
| [from_stream(stream)](#from_stream_stream_3) | Δημιουργεί ένα [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) από μια ροή. |
| [get_extension()](#get_extension__4) | Επιστρέφει την επέκταση αυτού του [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |
| [get_file_name()](#get_file_name__5) | Επιστρέφει το όνομα αρχείου και την επέκταση αυτού του [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |
| [get_file_name_without_extension()](#get_file_name_without_extension__6) | Επιστρέφει το όνομα αρχείου αυτού του [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) χωρίς την επέκταση. |
| [is_file()](#is_file__7) | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η διαδρομή δείχνει σε ένα υπάρχον αρχείο που μπορεί να ανοιχτεί για ανάγνωση. |
| [list_directory()](#list_directory__8) | Επιστρέφει διαδρομές που βρίσκονται μέσα σε αυτό το <c>AbstractPath</c>, εάν είναι κατάλογος. |
| [open(access)](#open_access_9) | Ανοίγει αυτό το <c>AbstractPath</c> ως αρχείο. |
| [with_extension(new_extension)](#with_extension_new_extension_10) | Επιστρέφει ένα νέο [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) με την επέκταση αρχείου να έχει αλλάξει στην καθορισμένη τιμή. |


### Method: combine(location) {#combine_location_1}


```
 combine(location) 
```

Συνδυάζει αυτό το [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) με τα καθορισμένα στοιχεία διαδρομής.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| location | string | Ένα στοιχείο διαδρομής για προσθήκη σε αυτό το [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ένα νέο [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) που δείχνει σε ένα [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) το οποίο είναι συνδυασμός των τοποθεσιών αυτού του [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) και<br/>            του ορίσματος. |


### Method: from_local_path(path)  [static] {#from_local_path_path_2}


```
 from_local_path(path) 
```

Δημιουργεί ένα [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) που αντιπροσωπεύει μια τοποθεσία στο τοπικό σύστημα αρχείων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Μια διαδρομή στο τοπικό σύστημα αρχείων, όπως <c>\"C:\\\\file.shp\"</c> ή <c>\"D:\\\\directory\\\"</c>. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ένα [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) που αντιπροσωπεύει τη θέση που ορίζεται από το <paramref name=\"path\" />. |


### Method: from_stream(stream)  [static] {#from_stream_stream_3}


```
 from_stream(stream) 
```

Δημιουργεί ένα [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) από μια ροή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| stream | _io.BufferedRandom | Μια ροή για δημιουργία ενός [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) από. <c>Aspose.GIS</c> δεν απελευθερώνει τη ροή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Μια παρουσία του [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) με τη συγκεκριμένη ροή ως περιεχόμενό της. |


### Method: get_extension() {#get_extension__4}


```
 get_extension() 
```

Επιστρέφει την επέκταση αυτού του [AbstractPath](/psd/python-net/aspose.gis/abstractpath/).

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Η επέκταση αυτού του [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) (συμπεριλαμβανομένου του σημείου \".\") ή<br/>            μια κενή συμβολοσειρά εάν το [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) δεν έχει επέκταση. |


### Method: get_file_name() {#get_file_name__5}


```
 get_file_name() 
```

Επιστρέφει το όνομα αρχείου και την επέκταση αυτού του [AbstractPath](/psd/python-net/aspose.gis/abstractpath/).

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Οι χαρακτήρες μετά τον τελευταίο χαρακτήρα [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) στο [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/). Εάν το<br/>            τελευταίο χαρακτήρα είναι ο χαρακτήρας [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/), επιστρέφεται μια κενή συμβολοσειρά. Εάν δεν υπάρχουν<br/>            χαρακτήρες [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) στο [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/), επιστρέφεται το ίδιο το [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/). |


### Method: get_file_name_without_extension() {#get_file_name_without_extension__6}


```
 get_file_name_without_extension() 
```

Επιστρέφει το όνομα αρχείου αυτού του [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) χωρίς την επέκταση.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Η συμβολοσειρά που επιστρέφεται από το [AbstractPath.get_file_name()](/psd/python-net/aspose.gis/abstractpath/) μείον το τελευταίο σημείο και όλους τους χαρακτήρες που την ακολουθούν. |


### Method: is_file() {#is_file__7}


```
 is_file() 
```

Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η διαδρομή δείχνει σε ένα υπάρχον αρχείο που μπορεί να ανοιχτεί για ανάγνωση.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <see langword=\"true\" /> εάν η θέση δείχνει σε αρχείο· <see langword=\"false\" /> διαφορετικά. |


### Method: list_directory() {#list_directory__8}


```
 list_directory() 
```

Επιστρέφει διαδρομές που βρίσκονται μέσα σε αυτό το <c>AbstractPath</c>, εάν είναι κατάλογος.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPath> | Διαδρομές που βρίσκονται μέσα σε αυτό το <c>AbstractPath</c>. |


### Method: open(access) {#open_access_9}


```
 open(access) 
```

Ανοίγει αυτό το <c>AbstractPath</c> ως αρχείο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| πρόσβαση | System.IO.FileAccess | Καθορίζει ένα υποσύνολο των λειτουργιών που μπορούν να εκτελεστούν σε μια ροή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| _io.BufferedRandom | Μία ροή ανοιχτή με το καθορισμένο FileAccess. |


### Method: with_extension(new_extension) {#with_extension_new_extension_10}


```
 with_extension(new_extension) 
```

Επιστρέφει ένα νέο [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) με την επέκταση αρχείου να έχει αλλάξει στην καθορισμένη τιμή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_extension | string | Μια νέα επέκταση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ένα νέο [AbstractPath](/psd/python-net/aspose.gis/abstractpath/), που δείχνει σε ένα αρχείο στον ίδιο φάκελο, αλλά με νέα επέκταση. |


