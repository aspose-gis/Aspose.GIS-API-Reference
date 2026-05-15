---
title: "Κλάση Ellipsoid"
type: docs
weight: 40
url: /el/python-net/aspose.gis.spatialreferencing/ellipsoid/
---

**Summary:** Ellipsoid represents an ellipsoid, which approximates earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Ellipsoid

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Ellipsoid(name, semi_major_axis, inverse_flattening, identifier)](#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1) | Δημιουργεί νέο Ellipsoid. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| airy [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ελλειψοειδές Airy. |
| epsg_code | int | r | Εάν το αναγνωριστικό αυτού του αντικειμένου είναι αναγνωριστικό EPSG - επιστρέφει τον κωδικό του. Διαφορετικά - επιστρέφει -1. |
| grs80 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ελλειψοειδές GRS 1980. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Αναγνωριστικό αυτού του αναγνωρίσιμου αντικειμένου. |
| inverse_flattening | double | r | Αντίστροφη επίπεδωση του ελλειψοειδούς. 0 εάν αυτό είναι σφαίρα. |
| is_sphere | bool | r | Ανιχνεύει εάν αυτό το ελλειψοειδές είναι σφαίρα. |
| is_valid | bool | r | Ανιχνεύει εάν το ελλειψοειδές είναι έγκυρο: η μισή κύρια άξονας είναι μεγαλύτερη από 0 και η αντίστροφη επίπεδωση είναι θετική ή ίση με 0. |
| όνομα | string | r | Όνομα αυτού του αντικειμένου. |
| semi_major_axis | double | r | Μισή κύρια άξονας του ελλειψοειδούς. |
| semi_minor_axis | double | r | Μισή δευτερεύουσα άξονας του ελλειψοειδούς. Ισούται με τη μισή κύρια άξονα εάν αυτό είναι σφαίρα. |
| wgs72 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ελλειψοειδές WGS 72. |
| wgs84 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ελλειψοειδές WGS 84. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [is_equivalent(ellipsoid1, ellipsoid2)](#is_equivalent_ellipsoid1_ellipsoid2_1) | Καθορίζει εάν δύο ελλειψοειδή είναι ισοδύναμα.<br/>            Εάν το ελλειψοειδές A είναι ισοδύναμο με το ελλειψοειδές B, τότε έχουν την ίδια μισή κύρια άξονα και αντίστροφη επίπεδωση. |
| [is_equivalent(other)](#is_equivalent_other_2) | Καθορίζει εάν δύο ελλειψοειδή είναι ισοδύναμα.<br/>            Εάν το ελλειψοειδές A είναι ισοδύναμο με το ελλειψοειδές B, τότε έχουν την ίδια μισή κύρια άξονα και αντίστροφη επίπεδωση. |


### Constructor: Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) {#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1}


```
 Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) 
```

Δημιουργεί νέο Ellipsoid.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Όνομα του ελλειψοειδούς. |
| semi_major_axis | double | Μισή κύρια άξονας του ελλειψοειδούς. |
| inverse_flattening | double | Αντίστροφη επίπεδωση του ελλειψοειδούς. Πρέπει να είναι 0 για τη δημιουργία σφαιροειδούς. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Αναγνωριστικό του ελλειψοειδούς. |

### Method: is_equivalent(ellipsoid1, ellipsoid2)  [static] {#is_equivalent_ellipsoid1_ellipsoid2_1}


```
 is_equivalent(ellipsoid1, ellipsoid2) 
```

Καθορίζει εάν δύο ελλειψοειδή είναι ισοδύναμα.<br/>            Εάν το ελλειψοειδές A είναι ισοδύναμο με το ελλειψοειδές B, τότε έχουν την ίδια μισή κύρια άξονα και αντίστροφη επίπεδωση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ellipsoid1 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Πρώτο ελλειψοειδές. |
| ellipsoid2 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Δεύτερο ελλειψοειδές. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Τιμή bool, που υποδεικνύει εάν δύο ελλειψοειδή είναι ισοδύναμα. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

Καθορίζει εάν δύο ελλειψοειδή είναι ισοδύναμα.<br/>            Εάν το ελλειψοειδές A είναι ισοδύναμο με το ελλειψοειδές B, τότε έχουν την ίδια μισή κύρια άξονα και αντίστροφη επίπεδωση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Άλλο ελλειψοειδές. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Τιμή bool, που υποδεικνύει εάν δύο ελλειψοειδή είναι ισοδύναμα. |


