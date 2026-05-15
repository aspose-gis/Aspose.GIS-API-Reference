---
title: "GeoConvert Κλάση"
type: docs
weight: 1140
url: /el/python-net/aspose.gis/geoconvert/
---

**Summary:** Converts coordinates to/from the different formats.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.GeoConvert

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [as_point_text(latitude, longitude, format)](#as_point_text_latitude_longitude_format_1) | Επιστρέφει τη υπολογισμένη θέση ως συμβολοσειρά στην καθορισμένη μορφή. |
| [as_point_text(point, format)](#as_point_text_point_format_2) | Επιστρέφει τη υπολογισμένη θέση ως συμβολοσειρά στην καθορισμένη μορφή. |
| [parse_point_text(text)](#parse_point_text_text_3) | Μετατρέπει τη συμβολοσειρά που περιέχει συντεταγμένες σε αντικείμενο IPoint. |
| [try_parse_point_text(text, point)](#try_parse_point_text_text_point_4) | Μετατρέπει τη συμβολοσειρά που περιέχει συντεταγμένες σε αντικείμενο IPoint. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε. |


### Method: as_point_text(latitude, longitude, format)  [static] {#as_point_text_latitude_longitude_format_1}


```
 as_point_text(latitude, longitude, format) 
```

Επιστρέφει τη υπολογισμένη θέση ως συμβολοσειρά στην καθορισμένη μορφή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| γεωγραφικό πλάτος | double | Γεωγραφικό πλάτος θέσης. |
| γεωγραφικό μήκος | double | Γεωγραφικό μήκος θέσης. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | Μορφή του αποτελέσματος. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Θέση ως συμβολοσειρά. |


### Method: as_point_text(point, format)  [static] {#as_point_text_point_format_2}


```
 as_point_text(point, format) 
```

Επιστρέφει τη υπολογισμένη θέση ως συμβολοσειρά στην καθορισμένη μορφή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Αντικείμενο IPoint. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | Μορφή του αποτελέσματος. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Θέση ως συμβολοσειρά. |


### Method: parse_point_text(text)  [static] {#parse_point_text_text_3}


```
 parse_point_text(text) 
```

Μετατρέπει τη συμβολοσειρά που περιέχει συντεταγμένες σε αντικείμενο IPoint.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| text | string | Μια συμβολοσειρά που περιέχει συντεταγμένες προς μετατροπή.<br/>            Η συμβολοσειρά πρέπει να περιέχει τόσο το γεωγραφικό πλάτος όσο και το γεωγραφικό μήκος.<br/>            Οι συντεταγμένες πρέπει να διαχωρίζονται με κενό, με κόμμα ή με ερωτηματικό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Αντικείμενο IPoint με συντεταγμένες που είναι ισοδύναμες με τη συμβολοσειρά εισόδου. |


### Method: try_parse_point_text(text, point)  [static] {#try_parse_point_text_text_point_4}


```
 try_parse_point_text(text, point) 
```

Μετατρέπει τη συμβολοσειρά που περιέχει συντεταγμένες σε αντικείμενο IPoint. Μια τιμή επιστροφής υποδεικνύει εάν η μετατροπή πέτυχε ή απέτυχε.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| text | string | Μια συμβολοσειρά που περιέχει συντεταγμένες προς μετατροπή.<br/>            Η συμβολοσειρά πρέπει να περιέχει τόσο το γεωγραφικό πλάτος όσο και το γεωγραφικό μήκος.<br/>            Οι συντεταγμένες πρέπει να διαχωρίζονται με κενό, με κόμμα ή με ερωτηματικό. |
| point | [IPoint[]](/psd/python-net/aspose.gis.geometries/ipoint/) | Όταν αυτή η μέθοδος επιστρέψει, περιέχει το αντικείμενο IPoint με τις αναλυμένες συντεταγμένες, εάν η μετατροπή πέτυχε, ή null εάν η μετατροπή απέτυχε. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | True εάν το κείμενο αναλύθηκε επιτυχώς, διαφορετικά False. |


