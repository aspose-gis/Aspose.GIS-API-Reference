---
title: "NumericFormat Κλάση"
type: docs
weight: 2870
url: /el/python-net/aspose.gis/numericformat/
---

**Summary:** [NumericFormat](/psd/python-net/aspose.gis/numericformat/) are used to format common numeric types in text.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.NumericFormat

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| round_trip [static] | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | r | Μετατρέπει και προσπαθεί να διασφαλίσει ότι μια αριθμητική τιμή που μετατρέπεται σε<br/>            συμβολοσειρά αναλύεται ξανά στην ίδια αριθμητική τιμή. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [flat(significant_digits)](#flat_significant_digits_1) | Μετατρέπει έναν αριθμό σε κείμενο σταθερής υποδιαστολής χωρίς επιστημονική σημειογραφία. |
| [general(precision)](#general_precision_2) | Μετατρέπει έναν αριθμό στην πιο συμπαγή μορφή, είτε σταθερής υποδιαστολής είτε επιστημονική σημειογραφία,<br/>            ανάλογα με τον τύπο του αριθμού και το αν υπάρχει προσδιοριστής ακρίβειας. Συνιστάται η χρήση. |


### Method: flat(significant_digits)  [static] {#flat_significant_digits_1}


```
 flat(significant_digits) 
```

Μετατρέπει έναν αριθμό σε κείμενο σταθερής υποδιαστολής χωρίς επιστημονική σημειογραφία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| significant_digits | int | Αριθμός σημαντικών ψηφίων. Η μέγιστη διαθέσιμη ακρίβεια είναι "308" |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Ο Προσδιοριστής Ακρίβειας Στρογγυλοποίησης. |


### Method: general(precision)  [static] {#general_precision_2}


```
 general(precision) 
```

Μετατρέπει έναν αριθμό στην πιο συμπαγή μορφή, είτε σταθερής υποδιαστολής είτε επιστημονική σημειογραφία,<br/>            ανάλογα με τον τύπο του αριθμού και το αν υπάρχει προσδιοριστής ακρίβειας. Συνιστάται η χρήση.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| precision | int | Η ακρίβεια ορίζει τον μέγιστο αριθμό σημαντικών ψηφίων που μπορούν να εμφανιστούν στη συμβολοσειρά αποτελέσματος.<br/>            Εάν η ακρίβεια είναι μηδέν, χρησιμοποιείται η τιμή "15". Η μέγιστη διαθέσιμη ακρίβεια είναι "17". |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Ο Γενικός Προσδιοριστής Μορφής. |


