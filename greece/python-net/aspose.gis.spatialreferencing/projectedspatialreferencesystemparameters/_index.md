---
title: "Κλάση ProjectedSpatialReferenceSystemParameters"
type: docs
weight: 160
url: /el/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/
---

**Summary:** Parameters to create projected SRS. Some of parameters have defaults.<br/>            Some parameters have reasonable defaults, so you don't have to assign only them.<br/>            If you assign <see langword="null" /> to those parameters, a default value will be used.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) and [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) don't have defaults -<br/>            you have to assign some non <see langword="null" /> value to this properties.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.ProjectedSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ProjectedSpatialReferenceSystemParameters()](#ProjectedSpatialReferenceSystemParameters__1) | Δημιουργεί νέο αντικείμενο. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| axises_order | [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder) | r/w | Σειρά αξόνων. Προεπιλογή είναι [ProjectedAxisesOrder.XY](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/). |
| base | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r/w | Βασικό γεωγραφικό SRS (SRS στο οποίο εφαρμόζεται η προβολή).<br/>            ΠΡΕΠΕΙ να ορίσετε αυτήν την ιδιότητα σε τιμή διαφορετική από <see langword="null" /> για να δημιουργήσετε έγκυρο SRS,<br/>            αυτή η ιδιότητα δεν έχει προεπιλογή. |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | Μονάδες που θα χρησιμοποιηθούν σε αυτό το SRS. Η προεπιλογή είναι [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| όνομα | string | r/w | Όνομα του προβλεπόμενου SRS. Η προεπιλογή είναι "Unnamed". |
| projection_method_identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r/w | Αναγνωριστικό της μεθόδου προβολής. Δεν υπάρχει προεπιλεγμένη τιμή, μπορείτε να ορίσετε αυτήν την παράμετρο σε τιμή διαφορετική από <see langword="null" />,<br/>            εάν θέλετε να συνημψετε αναγνωριστικό στην προβολή. Εάν το κάνετε αυτό - εξαρτάται από εσάς να διασφαλίσετε ότι το αναγνωριστικό είναι συνεπές με τη μέθοδο προβολής<br/>            όνομα (το όνομα της μεθόδου προβολής δεν θα αλλάξει όταν ορίσετε αυτήν την ιδιότητα). |
| projection_method_name | string | r/w | Όνομα της μεθόδου προβολής. Δεν υπάρχει προεπιλογή και ΠΡΕΠΕΙ να ορίσετε αυτήν την παράμετρο σε μη <see langword="null" /> τιμή, επειδή<br/>            το προβλεπόμενο SRS χωρίς όνομα προβολής είναι άχρηστο. |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Άξονας που περιγράφει τη διάσταση X (οριζόντια). Προεπιλογή είναι ο άξονας με κατεύθυνση ανατολής. |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Άξονας που περιγράφει τη διάσταση Y (κατακόρυφα). Προεπιλογή είναι ο άξονας με κατεύθυνση βορρά. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_projection_parameter(parameter_name, value)](#add_projection_parameter_parameter_name_value_1) | Προσθέτει παράμετρο προβολής σε αυτό το SRS. Εάν μια παράμετρος με αυτό το όνομα έχει ήδη προστεθεί - ενημερώστε την. |
| [get_projection_parameter(parameter_name)](#get_projection_parameter_parameter_name_2) | Λαμβάνει την παράμετρο προβολής με το καθορισμένο όνομα. |


### Constructor: ProjectedSpatialReferenceSystemParameters() {#ProjectedSpatialReferenceSystemParameters__1}


```
 ProjectedSpatialReferenceSystemParameters() 
```

Δημιουργεί νέο αντικείμενο.

### Method: add_projection_parameter(parameter_name, value) {#add_projection_parameter_parameter_name_value_1}


```
 add_projection_parameter(parameter_name, value) 
```

Προσθέτει παράμετρο προβολής σε αυτό το SRS. Εάν μια παράμετρος με αυτό το όνομα έχει ήδη προστεθεί - ενημερώστε την.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| parameter_name | string | Όνομα της παραμέτρου προβολής. |
| value | double | Τιμή της παραμέτρου. Η μονάδα της τιμής πρέπει να είναι στο [ProjectedSpatialReferenceSystemParameters.linear_unit](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/)<br/>            ή στο [GeographicSpatialReferenceSystem.angular_unit](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) του [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/). |

### Method: get_projection_parameter(parameter_name) {#get_projection_parameter_parameter_name_2}


```
 get_projection_parameter(parameter_name) 
```

Λαμβάνει την παράμετρο προβολής με το καθορισμένο όνομα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| parameter_name | string | Όνομα της παραμέτρου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| double | Τιμή παραμέτρου προβολής. |


