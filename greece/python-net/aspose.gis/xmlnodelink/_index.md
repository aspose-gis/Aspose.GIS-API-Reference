---
title: "XmlNodeLink Κλάση"
type: docs
weight: 4340
url: /el/python-net/aspose.gis/xmlnodelink/
---

**Summary:** XML Node-Based links to parts of sources

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.XmlNodeLink

**Inheritance:** NodeLink

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| children | [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | r | Λαμβάνει τα παιδιά. |
| name_without_prefix | string | r | Λαμβάνει το όνομα χωρίς πρόθεμα. |
| node_name | string | r/w | Λαμβάνει ή ορίζει το όνομα. |
| node_value | string | r/w | Λαμβάνει ή ορίζει την τιμή. |
| πρόθεμα | string | r | Λαμβάνει το πρόθεμα. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_child(child)](#add_child_child_1) | Προσθέτει το παιδί. |
| [as_bool()](#as_bool__2) | Επιστρέφει την τιμή μετατρεπόμενη σε bool |
| [as_double()](#as_double__3) | Επιστρέφει την τιμή μετατρεπόμενη σε double. |
| [as_int()](#as_int__4) | Επιστρέφει την τιμή μετατρεπόμενη σε int. |
| [find_nodes_by_name(name)](#find_nodes_by_name_name_5) | Βρίσκει τους κόμβους XML με το όνομα |
| [get_node_by_name(name)](#get_node_by_name_name_6) | Λαμβάνει τον κόμβο με βάση το όνομα. Παρακαλώ σημειώστε ότι αυτή η μέθοδος θα επιστρέψει τον πρώτο βρεθέντα Node.<br/>            Δεν έχει σημασία σε ποιο επίπεδο θα βρεθεί |
| [get_node_content()](#get_node_content__7) | Λαμβάνει το περιεχόμενο του κόμβου. |
| [get_nodes_by_name(names)](#get_nodes_by_name_names_8) | Λαμβάνει όλους τους κόμβους με το καθορισμένο όνομα. <br/>            Δεν έχει σημασία σε ποιο επίπεδο θα βρεθούν |


### Method: add_child(child) {#add_child_child_1}


```
 add_child(child) 
```

Προσθέτει το παιδί.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| child | [NodeLink](/psd/python-net/aspose.gis/nodelink) | Το παιδί. |

### Method: as_bool() {#as_bool__2}


```
 as_bool() 
```

Επιστρέφει την τιμή μετατρεπόμενη σε bool

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Η λογική τιμή (bool) του κόμβου |


### Method: as_double() {#as_double__3}


```
 as_double() 
```

Επιστρέφει την τιμή μετατρεπόμενη σε double.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| double | Η τιμή double του κόμβου |


### Method: as_int() {#as_int__4}


```
 as_int() 
```

Επιστρέφει την τιμή μετατρεπόμενη σε int.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Η τιμή int του κόμβου |


### Method: find_nodes_by_name(name) {#find_nodes_by_name_name_5}


```
 find_nodes_by_name(name) 
```

Βρίσκει τους κόμβους XML με το όνομα

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Το όνομα του κόμβου |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | Πίνακας κόμβων XML κατά όνομα |


### Method: get_node_by_name(name) {#get_node_by_name_name_6}


```
 get_node_by_name(name) 
```

Λαμβάνει τον κόμβο με βάση το όνομα. Παρακαλώ σημειώστε ότι αυτή η μέθοδος θα επιστρέψει τον πρώτο βρεθέντα Node.<br/>            Δεν έχει σημασία σε ποιο επίπεδο θα βρεθεί

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Το όνομα του κόμβου που θέλετε να βρείτε. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | Ο βρεθείς κόμβος με το NodeLink API |


### Method: get_node_content() {#get_node_content__7}


```
 get_node_content() 
```

Λαμβάνει το περιεχόμενο του κόμβου.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Το περιεχόμενο του κόμβου |


### Method: get_nodes_by_name(names) {#get_nodes_by_name_names_8}


```
 get_nodes_by_name(names) 
```

Λαμβάνει όλους τους κόμβους με το καθορισμένο όνομα. <br/>            Δεν έχει σημασία σε ποιο επίπεδο θα βρεθούν

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ονόματα | string | Τα ονόματα. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | Ο πίνακας των βρεθέντων κόμβων. |


