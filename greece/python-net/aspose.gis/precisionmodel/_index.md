---
title: "PrecisionModel Κλάση"
type: docs
weight: 3200
url: /el/python-net/aspose.gis/precisionmodel/
---

**Summary:** [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) specifies a number of significant digits in a coordinate.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.PrecisionModel

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| exact [static] | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r | Επιστρέφει ένα ακριβές μοντέλο ακρίβειας.<br/>            Σύμφωνα με το ακριβές μοντέλο ακρίβειας, όλα τα ψηφία σε μια τιμή double είναι σημαντικά. |
| is_exact | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το μοντέλο ακρίβειας είναι ακριβές. |
| is_rounding | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτό το μοντέλο ακρίβειας είναι στρογγυλοποιημένο. |
| significant_digits | int | r | Λαμβάνει τον αριθμό των σημαντικών ψηφίων σε ένα μοντέλο ακρίβειας εάν είναι στρογγυλοποιημένο. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [rounding(significant_digits)](#rounding_significant_digits_1) | Επιστρέφει ένα μοντέλο στρογγυλοποίησης ακρίβειας.<br/>            Σύμφωνα με το μοντέλο στρογγυλοποίησης ακρίβειας, μόνο ένας περιορισμένος αριθμός ψηφίων είναι σημαντικός. |


### Method: rounding(significant_digits)  [static] {#rounding_significant_digits_1}


```
 rounding(significant_digits) 
```

Επιστρέφει ένα μοντέλο στρογγυλοποίησης ακρίβειας.<br/>            Σύμφωνα με το μοντέλο στρογγυλοποίησης ακρίβειας, μόνο ένας περιορισμένος αριθμός ψηφίων είναι σημαντικός.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| significant_digits | int | Αριθμός σημαντικών ψηφίων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | Μοντέλο στρογγυλοποίησης Precision. |


