---
title: "Κλάση VectorMapLayer"
type: docs
weight: 390
url: /el/python-net/aspose.gis.rendering/vectormaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a vector layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.VectorMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [VectorMapLayer(features_sequence)](#VectorMapLayer_features_sequence_1) | Δημιουργεί νέα παρουσία με προεπιλεγμένο συμβολιστή. |
| [VectorMapLayer(features_sequence, symbolizer)](#VectorMapLayer_features_sequence_symbolizer_2) | Δημιουργεί νέα παρουσία με προεπιλεγμένο συμβολιστή. |
| [VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system)](#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3) | Δημιουργεί νέα παρουσία με προεπιλεγμένο συμβολιστή. |
| [VectorMapLayer(layer, keep_open)](#VectorMapLayer_layer_keep_open_4) | Δημιουργεί νέα παρουσία με προεπιλεγμένο συμβολιστή. |
| [VectorMapLayer(layer, symbolizer, keep_open)](#VectorMapLayer_layer_symbolizer_keep_open_5) | Δημιουργεί νέο αντικείμενο. |
| [VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6) | Δημιουργεί νέο αντικείμενο. |
| [VectorMapLayer(layer, symbolizer, labeling, keep_open)](#VectorMapLayer_layer_symbolizer_labeling_keep_open_7) | Δημιουργεί νέο αντικείμενο. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | r | Η ακολουθία χαρακτηριστικών που αντιπροσωπεύεται από αυτό το <c>VectorMapLayer</c>. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | r/w | Καθορίζει επιλογές παραμόρφωσης του επιπέδου χάρτη. |
| opacity | double | r/w | Διαφάνεια του στρώματος. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | r/w | Συμβολιστής για χρήση στην απόδοση των χαρακτηριστικών του επιπέδου. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [import_sld(path, options)](#import_sld_path_options_1) | Εισάγει στυλ από το αρχείο Styled Layer Descriptor που βρίσκεται στη συγκεκριμένη διαδρομή. |
| [import_sld(path, options)](#import_sld_path_options_2) | Εισάγει στυλ από το αρχείο Styled Layer Descriptor που βρίσκεται στη συγκεκριμένη διαδρομή. |
| [import_sld_from_string(sld, options)](#import_sld_from_string_sld_options_3) | Εισάγει στυλ από το καθορισμένο κείμενο Styled Layer Descriptor. |


### Constructor: VectorMapLayer(features_sequence) {#VectorMapLayer_features_sequence_1}


```
 VectorMapLayer(features_sequence) 
```

Δημιουργεί νέα παρουσία με προεπιλεγμένο συμβολιστή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Σειρά χαρακτηριστικών. |

### Constructor: VectorMapLayer(features_sequence, symbolizer) {#VectorMapLayer_features_sequence_symbolizer_2}


```
 VectorMapLayer(features_sequence, symbolizer) 
```

Δημιουργεί νέα παρουσία με προεπιλεγμένο συμβολιστή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Σειρά χαρακτηριστικών. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Συμβολιστής για χρήση στην απόδοση του επιπέδου. Εάν <see langword="null" />, θα χρησιμοποιηθεί ο προεπιλεγμένος συμβολιστής. |

### Constructor: VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) {#VectorMapLayer_features_sequence_symbolizer_labeling_default_reference_system_3}


```
 VectorMapLayer(features_sequence, symbolizer, labeling, default_reference_system) 
```

Δημιουργεί νέα παρουσία με προεπιλεγμένο συμβολιστή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Σειρά χαρακτηριστικών. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Συμβολιστής για χρήση στην απόδοση του επιπέδου. Εάν <see langword="null" />, θα χρησιμοποιηθεί ο προεπιλεγμένος συμβολιστής. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Ετικετοποίηση για χρήση στην επισήμανση χαρακτηριστικών στο επίπεδο. Εάν <see langword="null" />, θα χρησιμοποιηθεί το προεπιλεγμένο [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Καθορίζει μια τιμή για μια πηγή χωρικής αναφοράς (layer\sequence) εάν λείπει. Θα χρησιμοποιηθεί το προεπιλεγμένο null. |

### Constructor: VectorMapLayer(layer, keep_open) {#VectorMapLayer_layer_keep_open_4}


```
 VectorMapLayer(layer, keep_open) 
```

Δημιουργεί νέα παρουσία με προεπιλεγμένο συμβολιστή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Διανυσματικό επίπεδο. |
| keep_open | bool | <see langword="true" /> για να αφήσετε το στρώμα ανοιχτό μετά την απελευθέρωση του αντικειμένου [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/); διαφορετικά, <see langword="false" />. |

### Constructor: VectorMapLayer(layer, symbolizer, keep_open) {#VectorMapLayer_layer_symbolizer_keep_open_5}


```
 VectorMapLayer(layer, symbolizer, keep_open) 
```

Δημιουργεί νέο αντικείμενο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Διανυσματικό επίπεδο. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Συμβολιστής για χρήση στην απόδοση του επιπέδου. Εάν <see langword="null" />, θα χρησιμοποιηθεί ο προεπιλεγμένος συμβολιστής. |
| keep_open | bool | <see langword="true" /> για να αφήσετε το στρώμα ανοιχτό μετά την απελευθέρωση του αντικειμένου [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/); διαφορετικά, <see langword="false" />. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_default_reference_system_keep_open_6}


```
 VectorMapLayer(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

Δημιουργεί νέο αντικείμενο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Διανυσματικό επίπεδο. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Συμβολιστής για χρήση στην απόδοση του επιπέδου. Εάν <see langword="null" />, θα χρησιμοποιηθεί ο προεπιλεγμένος συμβολιστής. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Ετικετοποίηση για χρήση στην επισήμανση χαρακτηριστικών στο επίπεδο. Εάν <see langword="null" />, θα χρησιμοποιηθεί το προεπιλεγμένο [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Καθορίζει μια τιμή για μια πηγή χωρικής αναφοράς (layer\sequence) εάν λείπει. Θα χρησιμοποιηθεί το προεπιλεγμένο null. |
| keep_open | bool | <see langword="true" /> για να αφήσετε το στρώμα ανοιχτό μετά την απελευθέρωση του αντικειμένου [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/); διαφορετικά, <see langword="false" />. |

### Constructor: VectorMapLayer(layer, symbolizer, labeling, keep_open) {#VectorMapLayer_layer_symbolizer_labeling_keep_open_7}


```
 VectorMapLayer(layer, symbolizer, labeling, keep_open) 
```

Δημιουργεί νέο αντικείμενο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Διανυσματικό επίπεδο. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Συμβολιστής για χρήση στην απόδοση του επιπέδου. Εάν <see langword="null" />, θα χρησιμοποιηθεί ο προεπιλεγμένος συμβολιστής. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Ετικετοποίηση για χρήση στην επισήμανση χαρακτηριστικών στο επίπεδο. Εάν <see langword="null" />, θα χρησιμοποιηθεί το προεπιλεγμένο [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |
| keep_open | bool | <see langword="true" /> για να αφήσετε το στρώμα ανοιχτό μετά την απελευθέρωση του αντικειμένου [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/); διαφορετικά, <see langword="false" />. |

### Method: import_sld(path, options) {#import_sld_path_options_1}


```
 import_sld(path, options) 
```

Εισάγει στυλ από το αρχείο Styled Layer Descriptor που βρίσκεται στη συγκεκριμένη διαδρομή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string | Διαδρομή προς το αρχείο Styled Layer Descriptor. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Επιλογές εισαγωγής. |

### Method: import_sld(path, options) {#import_sld_path_options_2}


```
 import_sld(path, options) 
```

Εισάγει στυλ από το αρχείο Styled Layer Descriptor που βρίσκεται στη συγκεκριμένη διαδρομή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το αρχείο Styled Layer Descriptor. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Επιλογές εισαγωγής. |

### Method: import_sld_from_string(sld, options) {#import_sld_from_string_sld_options_3}


```
 import_sld_from_string(sld, options) 
```

Εισάγει στυλ από το καθορισμένο κείμενο Styled Layer Descriptor.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| sld | string | Περιγραφέας Στυλιζαρισμένου Στρώματος. |
| options | [SldImportOptions](/psd/python-net/aspose.gis.rendering.sld/sldimportoptions/) | Επιλογές εισαγωγής. |

