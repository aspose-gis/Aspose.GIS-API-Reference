---
title: "Κλάση FromDefinitionDataSourceBuilder"
type: docs
weight: 10
url: /el/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/
---

**Summary:** Provides the ability to configure a data source object

**Module:** [aspose.gis.formats.database.fromdefinition](/psd/python-net/aspose.gis.formats.database.fromdefinition/)

**Full Name:** aspose.gis.formats.database.fromdefinition.FromDefinitionDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | Ρυθμίζει το όνομα του πεδίου που θα περιέχει πληροφορίες για το χαρακτηριστικό του στοιχείου. |
| [build()](#build__2) | Η μέθοδος ανακτά μια υλοποίηση του [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) |
| [geometry_field(name)](#geometry_field_name_3) | Ρυθμίζει το όνομα του πεδίου από το οποίο θα εξαχθεί η γεωμετρία. |
| [identity_attribute(name, overwrite_same_key)](#identity_attribute_name_overwrite_same_key_4) | Υποχρεωτική ρύθμιση που επιτρέπει την παρακολούθηση αλλαγών. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

Ρυθμίζει το όνομα του πεδίου που θα περιέχει πληροφορίες για το χαρακτηριστικό του στοιχείου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Όνομα του πεδίου βάσης δεδομένων για το χαρακτηριστικό. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Τύπος δεδομένων στον οποίο πρέπει να μετατραπούν τα δεδομένα από τη βάση δεδομένων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: build() {#build__2}


```
 build() 
```

Η μέθοδος ανακτά μια υλοποίηση του [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/)

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource) | Υλοποίηση του [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) |


### Method: geometry_field(name) {#geometry_field_name_3}


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
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: identity_attribute(name, overwrite_same_key) {#identity_attribute_name_overwrite_same_key_4}


```
 identity_attribute(name, overwrite_same_key) 
```

Υποχρεωτική ρύθμιση που επιτρέπει την παρακολούθηση αλλαγών.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Ένα χαρακτηριστικό ενός στοιχείου που θα θεωρείται ως μοναδική ταυτοποίηση του στοιχείου. |
| overwrite_same_key | bool | Εάν αυτή η σημαία οριστεί σε true, τότε τα πρόσφατα προστιθέμενα στοιχεία με μοναδικό αναγνωριστικό το ίδιο με αυτό που υπάρχει ήδη στο επίπεδο, <br/>            το τρέχον θα αντικατασταθεί, και τα δεδομένα θα θεωρηθούν ενημερωμένα εάν βρεθούν διαφορές.<br/>            Διαφορετικά, θα ριχτεί μια εξαίρεση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


