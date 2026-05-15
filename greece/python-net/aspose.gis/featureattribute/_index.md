---
title: "FeatureAttribute Κλάση"
type: docs
weight: 840
url: /el/python-net/aspose.gis/featureattribute/
---

**Summary:** An attribute of a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeatureAttribute

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FeatureAttribute(name, data_type)](#FeatureAttribute_name_data_type_1) | Αρχικοποιεί μια νέα παρουσία της κλάσης [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/). |
| [FeatureAttribute(name, data_type, can_be_null)](#FeatureAttribute_name_data_type_can_be_null_2) | Αρχικοποιεί μια νέα παρουσία της κλάσης [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| can_be_null | bool | r/w | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία μπορεί να είναι null. |
| can_be_unset | bool | r/w | Λαμβάνει ή ορίζει μια τιμή που υποδεικνύει εάν η τιμή για αυτό το χαρακτηριστικό μπορεί να παραλειφθεί. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | r/w | Λαμβάνει τον τύπο δεδομένων του χαρακτηριστικού. |
| default_value | object | r/w | Λαμβάνει ή ορίζει μια τιμή για το χαρακτηριστικό, η οποία υποδεικνύει ελλιπή δεδομένα. |
| has_custom_default_value | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν η προ-ορισμένη προεπιλεγμένη τιμή για αυτό το χαρακτηριστικό αντικαταστάθηκε με προσαρμοσμένη τιμή. |
| is_locked | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το χαρακτηριστικό είναι κλειδωμένο. |
| όνομα | string | r/w | Λαμβάνει το όνομα του χαρακτηριστικού. |
| precision | Nullable<int> | r/w | Λαμβάνει ή ορίζει το μέγιστο αριθμό δεκαδικών ψηφίων για αποθήκευση. |
| type_name | string | r/w | Το όνομα τύπου του χαρακτηριστικού. |
| width | Nullable<int> | r/w | Λαμβάνει ή ορίζει το μέγιστο επιτρεπόμενο πλάτος της αναπαράστασης χαρακτήρων του χαρακτηριστικού. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| lock() | Κλειδώνει αυτό το χαρακτηριστικό. |


### Constructor: FeatureAttribute(name, data_type) {#FeatureAttribute_name_data_type_1}


```
 FeatureAttribute(name, data_type) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Το όνομα του χαρακτηριστικού. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Ο τύπος δεδομένων του χαρακτηριστικού. |

### Constructor: FeatureAttribute(name, data_type, can_be_null) {#FeatureAttribute_name_data_type_can_be_null_2}


```
 FeatureAttribute(name, data_type, can_be_null) 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Το όνομα του χαρακτηριστικού. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Ο τύπος δεδομένων του χαρακτηριστικού. |
| can_be_null | bool | <see langword="true" /> εάν αυτή η παρουσία μπορεί να είναι null; διαφορετικά, <see langword="false" />. |

