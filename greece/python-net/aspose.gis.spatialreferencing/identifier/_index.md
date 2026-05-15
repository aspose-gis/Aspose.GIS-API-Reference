---
title: "Identifier Κλάση"
type: docs
weight: 110
url: /el/python-net/aspose.gis.spatialreferencing/identifier/
---

**Summary:** Represents an identifier - a reference to external description of an object.<br/>            If you create a SRS from WKT, [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) corresponds to "AUTHORITY" keyword.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Identifier

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Identifier(authority_name, authority_unique_identifier)](#Identifier_authority_name_authority_unique_identifier_1) | Δημιουργήστε νέα παρουσία. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| authority_name | string | r | Ένα όνομα αρχής, που έδωσε ένα [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
| authority_unique_identifier | string | r | Ένας μοναδικός τρόπος για να αναπαραστήσετε ένα αντικείμενο εντός ενός [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [epsg(epsg_code)](#epsg_epsg_code_1) | Δημιουργεί νέο Identifier που αντιπροσωπεύει το αναγνωριστικό EPSG με κώδικα <paramref name="epsgCode" />. |
| [get_epsg_code()](#get_epsg_code__2) | Εάν αυτό το αντικείμενο αντιπροσωπεύει ένα έγκυρο αναγνωριστικό EPSG (π.χ. - το όνομα αρχής είναι "EPSG" και το μοναδικό αναγνωριστικό αρχής είναι ακέραιος) -<br/>            επιστρέψτε το. Διαφορετικά - επιστρέψτε -1. |


### Constructor: Identifier(authority_name, authority_unique_identifier) {#Identifier_authority_name_authority_unique_identifier_1}


```
 Identifier(authority_name, authority_unique_identifier) 
```

Δημιουργήστε νέα παρουσία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| authority_name | string | [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
| authority_unique_identifier | string | [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |

### Method: epsg(epsg_code)  [static] {#epsg_epsg_code_1}


```
 epsg(epsg_code) 
```

Δημιουργεί νέο Identifier που αντιπροσωπεύει το αναγνωριστικό EPSG με κώδικα <paramref name="epsgCode" />.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| epsg_code | int | Κωδικός EPSG. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Νέο αναγνωριστικό με [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/) "EPSG" και [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) <paramref name=\"epsgCode\" />.<br/>            Εάν <paramref name=\"epsgCode\" /> είναι μικρότερο από 0 - επιστρέφει <see langword=\"null\" />; |


### Method: get_epsg_code() {#get_epsg_code__2}


```
 get_epsg_code() 
```

Εάν αυτό το αντικείμενο αντιπροσωπεύει ένα έγκυρο αναγνωριστικό EPSG (π.χ. - το όνομα αρχής είναι "EPSG" και το μοναδικό αναγνωριστικό αρχής είναι ακέραιος) -<br/>            επιστρέψτε το. Διαφορετικά - επιστρέψτε -1.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int | Αναγνωριστικό EPSG που αντιπροσωπεύεται από αυτό το αντικείμενο. Εάν αυτό το αντικείμενο δεν αντιπροσωπεύει αναγνωριστικό EPSG - επιστρέφει -1. |


