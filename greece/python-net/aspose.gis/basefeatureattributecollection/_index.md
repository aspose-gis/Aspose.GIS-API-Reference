---
title: "BaseFeatureAttributeCollection Κλάση"
type: docs
weight: 90
url: /el/python-net/aspose.gis/basefeatureattributecollection/
---

**Summary:** A [FeatureAttributeCollection](/psd/python-net/aspose.gis/featureattributecollection/) defines what attributes are available for a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.BaseFeatureAttributeCollection

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| count | int | r | Λαμβάνει τον αριθμό των χαρακτηριστικών σε ένα [Feature](/psd/python-net/aspose.gis/feature/). |
| is_locked | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η συλλογή χαρακτηριστικών είναι κλειδωμένη. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(attribute)](#add_attribute_1) | Προσθέτει ένα χαρακτηριστικό στη συλλογή. |
| [contains(name)](#contains_name_2) | Καθορίζει εάν η συλλογή χαρακτηριστικών περιέχει ένα χαρακτηριστικό με το συγκεκριμένο όνομα. |
| [index_of(name)](#index_of_name_3) | Αναζητά το χαρακτηριστικό και επιστρέφει τον μηδενικό δείκτη του. |
| lock() | Κλειδώνει αυτή τη συλλογή χαρακτηριστικών για να αποτρέψει περαιτέρω τροποποιήσεις. |
| [remove(index)](#remove_index_4) | Αφαιρεί το χαρακτηριστικό από τη συλλογή. |
| [remove(name)](#remove_name_5) | Αφαιρεί το χαρακτηριστικό από τη συλλογή. |


### Method: add(attribute) {#add_attribute_1}


```
 add(attribute) 
```

Προσθέτει ένα χαρακτηριστικό στη συλλογή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| attribute | [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute) | Το χαρακτηριστικό προς προσθήκη. |

### Method: contains(name) {#contains_name_2}


```
 contains(name) 
```

Καθορίζει εάν η συλλογή χαρακτηριστικών περιέχει ένα χαρακτηριστικό με το συγκεκριμένο όνομα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Όνομα του χαρακτηριστικού. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <see langword="true" /> εάν η συλλογή χαρακτηριστικών περιέχει ένα χαρακτηριστικό με το συγκεκριμένο όνομα· διαφορετικά, <see langword="false" />. |


### Method: index_of(name) {#index_of_name_3}


```
 index_of(name) 
```

Αναζητά το χαρακτηριστικό και επιστρέφει τον μηδενικό δείκτη του.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Όνομα του χαρακτηριστικού. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Ο μηδενικός δείκτης του χαρακτηριστικού μέσα στη συλλογή, εάν βρεθεί· διαφορετικά, –1. |


### Method: remove(index) {#remove_index_4}


```
 remove(index) 
```

Αφαιρεί το χαρακτηριστικό από τη συλλογή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | int | Δείκτης του χαρακτηριστικού. |

### Method: remove(name) {#remove_name_5}


```
 remove(name) 
```

Αφαιρεί το χαρακτηριστικό από τη συλλογή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Όνομα του χαρακτηριστικού. |

