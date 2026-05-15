---
title: "Κλάση Projection"
type: docs
weight: 170
url: /el/python-net/aspose.gis.spatialreferencing/projection/
---

**Summary:** Represents a projection method with parameters, that transforms (longitude, latitude) to (x, y).

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Projection

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| angular_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Μονάδα που χρησιμοποιείται για γωνιακές παραμέτρους. |
| epsg_code | int | r | Εάν το αναγνωριστικό αυτού του αντικειμένου είναι αναγνωριστικό EPSG - επιστρέφει τον κωδικό του. Διαφορετικά - επιστρέφει -1. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Αναγνωριστικό αυτού του αναγνωρίσιμου αντικειμένου. |
| linear_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Μονάδα που χρησιμοποιείται για γραμμικές παραμέτρους. |
| όνομα | string | r | Όνομα αυτού του αντικειμένου. |
| parameters_names | System.Collections.Generic.IList<string> | r | Λαμβάνει μια επαναληπτική συλλογή ονομάτων παραμέτρων που δίνονται σε αυτήν την προβολή |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_parameter_value(name, type)](#get_parameter_value_name_type_1) | Λαμβάνει την παράμετρο με το συγκεκριμένο όνομα αυτής της προβολής. |
| [is_equivalent(other)](#is_equivalent_other_2) | Καθορίζει εάν δύο προβολές είναι ισοδύναμες. Οι ισοδύναμες προβολές αντιστοιχούν (longitude, latitude) σε (x, y) με τον<br/>            ίδιο τρόπο. |
| [try_get_parameter_value(name, type)](#try_get_parameter_value_name_type_3) | Λαμβάνει την παράμετρο με το συγκεκριμένο όνομα αυτής της προβολής. Εάν δεν υπάρχει τέτοια παράμετρος - επιστρέφει <see langword="null" />. |


### Method: get_parameter_value(name, type) {#get_parameter_value_name_type_1}


```
 get_parameter_value(name, type) 
```

Λαμβάνει την παράμετρο με το συγκεκριμένο όνομα αυτής της προβολής.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string | Όνομα της παραμέτρου. |
