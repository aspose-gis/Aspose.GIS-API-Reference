---
title: "Κλάση DynamicFeature"
type: docs
weight: 650
url: /el/python-net/aspose.gis/dynamicfeature/
---

**Summary:** A geographic feature composed of a geometry and user-defined attributes.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.DynamicFeature

**Inheritance:** Feature

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | r/w | Λαμβάνει ή ορίζει τη γεωμετρία του χαρακτηριστικού.<br/>            Δεν μπορεί να είναι <see langword="null" />, χρησιμοποιήστε [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/) για να υποδείξετε έλλειψη γεωμετρίας. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [copy_values(input_feature)](#copy_values_input_feature_1) | Αντιγράφει τις τιμές των χαρακτηριστικών από ένα άλλο χαρακτηριστικό. |
| [get_as_node()](#get_as_node__2) | Αποκτά το χαρακτηριστικό ως κόμβο. Αυτό μπορεί να είναι χρήσιμο για τα προσαρμοσμένα δεδομένα |
| [get_value(attribute_name)](#get_value_attribute_name_3) | Λαμβάνει την τιμή ενός χαρακτηριστικού. |
| [get_value_or_default(attribute_name, default_value)](#get_value_or_default_attribute_name_default_value_4) | Λαμβάνει την τιμή ενός χαρακτηριστικού, ή [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/) εάν η τιμή δεν έχει οριστεί ή είναι <c>null</c>. |
| [get_values(values, default_value)](#get_values_values_default_value_5) | Επιστρέφει τις τιμές για όλα τα χαρακτηριστικά σε έναν πίνακα. |
| [get_values(values_count, default_value)](#get_values_values_count_default_value_6) | Επιστρέφει τις τιμές για όλα τα χαρακτηριστικά σε έναν πίνακα. |
| [get_values_dump(default_value)](#get_values_dump_default_value_7) | Επιστρέφει τις τιμές για όλα τα χαρακτηριστικά σε έναν πίνακα.<br/>            Σκεφτείτε να χρησιμοποιήσετε τη μέθοδο Aspose.Gis.DynamicFeature.GetValues(System.Object,System.Object) για να αποφύγετε πρόσθετη κατανομή μνήμης. |
| [get_values_list(attribute_name, separator, count)](#get_values_list_attribute_name_separator_count_8) | Αποκτά τις τιμές μιας ακολουθίας χαρακτηριστικών ως λίστα. |
| [is_value_null(attribute_name)](#is_value_null_attribute_name_9) | Καθορίζει εάν το καθορισμένο χαρακτηριστικό έχει οριστεί ρητά σε τιμή <c>null</c>. |
| [is_value_set(attribute_name)](#is_value_set_attribute_name_10) | Ελέγχει εάν η τιμή του χαρακτηριστικού έχει οριστεί σε αυτό το χαρακτηριστικό. |
| [set_value(attribute_name, value)](#set_value_attribute_name_value_11) | Ορίζει μια νέα τιμή ενός χαρακτηριστικού. |
| [set_value_null(attribute_name)](#set_value_null_attribute_name_12) | Ορίζει την τιμή του χαρακτηριστικού σε <c>null</c>. |
| [set_values(values)](#set_values_values_13) | Ορίζει νέες τιμές για όλα τα χαρακτηριστικά.<br/>            Επίσης, σκεφτείτε να χρησιμοποιήσετε τη μέθοδο [DynamicFeature.copy_values(input_feature)](/psd/python-net/aspose.gis/dynamicfeature/) για να απλοποιήσετε τον ορισμό τιμών σε μία κλήση. |
| [unset_value(attribute_name)](#unset_value_attribute_name_14) | Αφαιρεί την τιμή του χαρακτηριστικού από αυτό το χαρακτηριστικό. |


### Method: copy_values(input_feature) {#copy_values_input_feature_1}


```
 copy_values(input_feature) 
```

Αντιγράφει τις τιμές των χαρακτηριστικών από ένα άλλο χαρακτηριστικό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| input_feature | [Feature](/psd/python-net/aspose.gis/feature) | Το χαρακτηριστικό από το οποίο θα αντιγραφούν οι τιμές. |

### Method: get_as_node() {#get_as_node__2}


```
 get_as_node() 
```

Αποκτά το χαρακτηριστικό ως κόμβο. Αυτό μπορεί να είναι χρήσιμο για τα προσαρμοσμένα δεδομένα

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | Ο NodeLink στο χαρακτηριστικό |


### Method: get_value(attribute_name) {#get_value_attribute_name_3}


```
 get_value(attribute_name) 
```

Λαμβάνει την τιμή ενός χαρακτηριστικού.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| attribute_name | string | Όνομα του χαρακτηριστικού. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| object | Τιμή του χαρακτηριστικού. |


### Method: get_value_or_default(attribute_name, default_value) {#get_value_or_default_attribute_name_default_value_4}


```
 get_value_or_default(attribute_name, default_value) 
```

Λαμβάνει την τιμή ενός χαρακτηριστικού, ή [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/) εάν η τιμή δεν έχει οριστεί ή είναι <c>null</c>.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| attribute_name | string | Όνομα του χαρακτηριστικού. |
| default_value | object | Η τιμή που θα επιστραφεί εάν λείπει η τιμή του χαρακτηριστικού. Η προεπιλεγμένη τιμή είναι <see langword=\"null\" />. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| object | Τιμή του χαρακτηριστικού. |


### Method: get_values(values, default_value) {#get_values_values_default_value_5}


```
 get_values(values, default_value) 
```

Επιστρέφει τις τιμές για όλα τα χαρακτηριστικά σε έναν πίνακα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| values | object | Ο πίνακας στον οποίο θα αντιγράψετε τις τιμές των χαρακτηριστικών. |
| default_value | object | Η τιμή που θα επιστραφεί εάν λείπει (μη ορισμένη) η τιμή του χαρακτηριστικού. Η προεπιλεγμένη τιμή είναι <see langword=\"null\" />.<br/>            Σκεφτείτε να χρησιμοποιήσετε το '.Value' για να διαχωρίσετε τις τιμές 'μη ορισμένη' και '<see langword=\"null\" />'. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Αριθμός αντιγραμμένων χαρακτηριστικών. |


### Method: get_values(values_count, default_value) {#get_values_values_count_default_value_6}


```
 get_values(values_count, default_value) 
```

Επιστρέφει τις τιμές για όλα τα χαρακτηριστικά σε έναν πίνακα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| values_count | int | Ο αριθμός των τιμών. |
| default_value | object | Η τιμή που θα επιστραφεί εάν λείπει (μη ορισμένη) η τιμή του χαρακτηριστικού. Η προεπιλεγμένη τιμή είναι <see langword=\"null\" />.<br/>            Σκεφτείτε να χρησιμοποιήσετε το '.Value' για να διαχωρίσετε τις τιμές 'μη ορισμένη' και '<see langword=\"null\" />'. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| object | Αριθμός αντιγραμμένων χαρακτηριστικών. |


### Method: get_values_dump(default_value) {#get_values_dump_default_value_7}


```
 get_values_dump(default_value) 
```

Επιστρέφει τις τιμές για όλα τα χαρακτηριστικά σε έναν πίνακα.<br/>            Σκεφτείτε να χρησιμοποιήσετε τη μέθοδο Aspose.Gis.DynamicFeature.GetValues(System.Object,System.Object) για να αποφύγετε πρόσθετη κατανομή μνήμης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| default_value | object | Η τιμή που θα επιστραφεί εάν λείπει (μη ορισμένη) η τιμή του χαρακτηριστικού. Η προεπιλεγμένη τιμή είναι <see langword=\"null\" />.<br/>            Σκεφτείτε να χρησιμοποιήσετε το '.Value' για να διαχωρίσετε τις τιμές 'μη ορισμένη' και '<see langword=\"null\" />'. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| object | Ένας νέος πίνακας στον οποίο θα αντιγραφούν οι τιμές των χαρακτηριστικών. |


### Method: get_values_list(attribute_name, separator, count) {#get_values_list_attribute_name_separator_count_8}


```
 get_values_list(attribute_name, separator, count) 
```

Αποκτά τις τιμές μιας ακολουθίας χαρακτηριστικών ως λίστα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| attribute_name | string | Όνομα του χαρακτηριστικού. |
| separator | string | Μια συμβολοσειρά που χρησιμοποιείται για το διαχωρισμό του ονόματος του χαρακτηριστικού και της τιμής του δείκτη της ακολουθίας. |
| count | int | Αριθμός τιμών που θα επιστραφούν (η ελλιπής τιμή συμπληρώνεται ως null) |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| object | Λίστα τιμών των χαρακτηριστικών των οποίων τα ονόματα διαφέρουν ανάλογα με την τιμή του δείκτη ακολουθίας. |


### Method: is_value_null(attribute_name) {#is_value_null_attribute_name_9}


```
 is_value_null(attribute_name) 
```

Καθορίζει εάν το καθορισμένο χαρακτηριστικό έχει οριστεί ρητά σε τιμή <c>null</c>.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| attribute_name | string | Όνομα του χαρακτηριστικού. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <see langword=\"true\" /> εάν η τιμή του χαρακτηριστικού είναι <c>null</c>; διαφορετικά, <see langword=\"false\" />. |


### Method: is_value_set(attribute_name) {#is_value_set_attribute_name_10}


```
 is_value_set(attribute_name) 
```

Ελέγχει εάν η τιμή του χαρακτηριστικού έχει οριστεί σε αυτό το χαρακτηριστικό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| attribute_name | string | Όνομα του χαρακτηριστικού. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <see langword=\"true\" /> εάν η τιμή για το καθορισμένο χαρακτηριστικό έχει οριστεί; διαφορετικά, <see langword=\"false\" />. |


### Method: set_value(attribute_name, value) {#set_value_attribute_name_value_11}


```
 set_value(attribute_name, value) 
```

Ορίζει μια νέα τιμή ενός χαρακτηριστικού.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| attribute_name | string | Το όνομα του χαρακτηριστικού. |
| value | object | Η τιμή του χαρακτηριστικού. |

### Method: set_value_null(attribute_name) {#set_value_null_attribute_name_12}


```
 set_value_null(attribute_name) 
```

Ορίζει την τιμή του χαρακτηριστικού σε <c>null</c>.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| attribute_name | string | Το όνομα του χαρακτηριστικού. |

### Method: set_values(values) {#set_values_values_13}


```
 set_values(values) 
```

Ορίζει νέες τιμές για όλα τα χαρακτηριστικά.<br/>            Επίσης, σκεφτείτε να χρησιμοποιήσετε τη μέθοδο [DynamicFeature.copy_values(input_feature)](/psd/python-net/aspose.gis/dynamicfeature/) για να απλοποιήσετε τον ορισμό τιμών σε μία κλήση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| values | object | Ο πίνακας των νέων τιμών. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Ο αριθμός των τιμών χαρακτηριστικού που έχουν οριστεί. |


### Method: unset_value(attribute_name) {#unset_value_attribute_name_14}


```
 unset_value(attribute_name) 
```

Αφαιρεί την τιμή του χαρακτηριστικού από αυτό το χαρακτηριστικό.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| attribute_name | string | Όνομα του χαρακτηριστικού. |

