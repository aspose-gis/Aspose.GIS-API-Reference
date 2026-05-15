---
title: "Κατηγορία Map"
type: docs
weight: 100
url: /el/python-net/aspose.gis.rendering/map/
---

**Summary:** Map is a collection of layers that can be rendered on top of each other via [Renderer](/psd/python-net/aspose.gis.rendering/renderer/).

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.Map

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Map()](#Map__1) | Δημιουργεί νέα παρουσία της κλάσης <c>Map</c>. |
| [Map(width, height)](#Map_width_height_2) | Δημιουργεί νέα παρουσία της κλάσης <c>Map</c>. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | r/w | Χρώμα φόντου του χάρτη. Προεπιλογή είναι . |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | Καθορίζει τα όρια του χάρτη για απόδοση.<br/>            Εάν οριστεί σε <see langword="null" />, το εύρος υπολογίζεται κατά την απόδοση ώστε να περιλαμβάνει όλα τα γεωμετρικά στοιχεία σε όλα τα στρώματα. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Οπτικό ύψος του χάρτη. |
| padding | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Καθορίζει το padding που θα προστεθεί στο εύρος. |
| resolution | double | r/w | Ανάλυση που θα χρησιμοποιηθεί για την απόδοση αυτού του χάρτη και για τη μετατροπή μεταξύ [Measurement](/psd/python-net/aspose.gis.rendering/measurement/). Προεπιλογή είναι 96. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [Map.spatial_reference_system](/psd/python-net/aspose.gis.rendering/map/) του χάρτη. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Οπτικό πλάτος του χάρτη. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(features_sequence)](#add_features_sequence_1) | Δημιουργεί και προσθέτει ένα [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) στον χάρτη. Τα στρώματα αποδίδονται με τη σειρά προσθήκης. |
| [add(features_sequence, symbolizer)](#add_features_sequence_symbolizer_2) | Δημιουργεί και προσθέτει ένα [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) στον χάρτη. Τα στρώματα αποδίδονται με τη σειρά προσθήκης. |
| [add(features_sequence, symbolizer, labeling)](#add_features_sequence_symbolizer_labeling_3) | Δημιουργεί και προσθέτει ένα [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) στον χάρτη. Τα στρώματα αποδίδονται με τη σειρά προσθήκης. |
| [add(layer, colorizer, keep_open)](#add_layer_colorizer_keep_open_4) | Δημιουργεί ένα [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) με προεπιλεγμένο colorizer και το προσθέτει στον χάρτη. |
| [add(layer, keep_open)](#add_layer_keep_open_5) | Δημιουργεί ένα [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) με προεπιλεγμένο symbolizer και το προσθέτει στον χάρτη. Τα στρώματα αποδίδονται με τη σειρά προσθήκης. |
| [add(layer, symbolizer, keep_open)](#add_layer_symbolizer_keep_open_6) | Δημιουργεί και προσθέτει ένα [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) στον χάρτη. Τα στρώματα αποδίδονται με τη σειρά προσθήκης. |
| [add(layer, symbolizer, labeling, default_reference_system, keep_open)](#add_layer_symbolizer_labeling_default_reference_system_keep_open_7) | Δημιουργεί και προσθέτει ένα [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) στον χάρτη. Τα στρώματα αποδίδονται με τη σειρά προσθήκης. |
| [add(layer, symbolizer, labeling, keep_open)](#add_layer_symbolizer_labeling_keep_open_8) | Δημιουργεί και προσθέτει ένα [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) στον χάρτη. Τα στρώματα αποδίδονται με τη σειρά προσθήκης. |
| [add(map_layer)](#add_map_layer_9) | Προσθέτει ένα επίπεδο στον χάρτη. Τα επίπεδα αποδίδονται με τη σειρά προσθήκης. |
| [render(output_path, renderer)](#render_output_path_renderer_10) | Αποδίδει τον χάρτη σε ένα αρχείο. |
| [render(output_path, renderer)](#render_output_path_renderer_11) | Αποδίδει τον χάρτη σε ένα αρχείο. |


### Constructor: Map() {#Map__1}


```
 Map() 
```

Δημιουργεί νέα παρουσία της κλάσης <c>Map</c>.

### Constructor: Map(width, height) {#Map_width_height_2}


```
 Map(width, height) 
```

Δημιουργεί νέα παρουσία της κλάσης <c>Map</c>.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Πλάτος του χάρτη. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Ύψος του χάρτη. |

### Method: add(features_sequence) {#add_features_sequence_1}


```
 add(features_sequence) 
```

Δημιουργεί και προσθέτει ένα [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) στον χάρτη. Τα στρώματα αποδίδονται με τη σειρά προσθήκης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Μια ακολουθία χαρακτηριστικών για αναπαράσταση από το [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |

### Method: add(features_sequence, symbolizer) {#add_features_sequence_symbolizer_2}


```
 add(features_sequence, symbolizer) 
```

Δημιουργεί και προσθέτει ένα [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) στον χάρτη. Τα στρώματα αποδίδονται με τη σειρά προσθήκης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Μια ακολουθία χαρακτηριστικών για αναπαράσταση από το [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Ένας symbolizer προς χρήση για την απόδοση. Εάν <see langword=\"null\" />, χρησιμοποιείται ο προεπιλεγμένος symbolizer. |

### Method: add(features_sequence, symbolizer, labeling) {#add_features_sequence_symbolizer_labeling_3}


```
 add(features_sequence, symbolizer, labeling) 
```

Δημιουργεί και προσθέτει ένα [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) στον χάρτη. Τα στρώματα αποδίδονται με τη σειρά προσθήκης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Μια ακολουθία χαρακτηριστικών για αναπαράσταση από το [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Ένας συμβολιστής για χρήση στην απόδοση. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Ετικετοποίηση για χρήση στην επισήμανση χαρακτηριστικών στο επίπεδο. Εάν <see langword="null" />, θα χρησιμοποιηθεί το [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |

### Method: add(layer, colorizer, keep_open) {#add_layer_colorizer_keep_open_4}


```
 add(layer, colorizer, keep_open) 
```

Δημιουργεί ένα [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) με προεπιλεγμένο colorizer και το προσθέτει στον χάρτη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | Ένα διανυσματικό επίπεδο για αναπαράσταση από το [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/). |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | Ένας χρωματιστής για χρήση στην απόδοση. Εάν <see langword="null" />, χρησιμοποιείται ο προεπιλεγμένος χρωματιστής. |
| keep_open | bool | <see langword="true" /> για να αφήσετε το raster επίπεδο ανοιχτό μετά την απελευθέρωση του αντικειμένου [Map](/psd/python-net/aspose.gis.rendering/map/);<br/>            <see langword="false" /> για να απελευθερώσετε το επίπεδο. |

### Method: add(layer, keep_open) {#add_layer_keep_open_5}


```
 add(layer, keep_open) 
```

Δημιουργεί ένα [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) με προεπιλεγμένο symbolizer και το προσθέτει στον χάρτη. Τα στρώματα αποδίδονται με τη σειρά προσθήκης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ένα διανυσματικό επίπεδο για αναπαράσταση από το [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| keep_open | bool | <see langword="true" /> για να αφήσετε το διανυσματικό επίπεδο ανοιχτό μετά την απελευθέρωση του αντικειμένου [Map](/psd/python-net/aspose.gis.rendering/map/);<br/>            <see langword="false" /> για να απελευθερώσετε το επίπεδο. |

### Method: add(layer, symbolizer, keep_open) {#add_layer_symbolizer_keep_open_6}


```
 add(layer, symbolizer, keep_open) 
```

Δημιουργεί και προσθέτει ένα [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) στον χάρτη. Τα στρώματα αποδίδονται με τη σειρά προσθήκης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ένα διανυσματικό επίπεδο για αναπαράσταση από το [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Ένας symbolizer προς χρήση για την απόδοση. Εάν <see langword=\"null\" />, χρησιμοποιείται ο προεπιλεγμένος symbolizer. |
| keep_open | bool | <see langword="true" /> για να αφήσετε το διανυσματικό επίπεδο ανοιχτό μετά την απελευθέρωση του αντικειμένου [Map](/psd/python-net/aspose.gis.rendering/map/);<br/>            <see langword="false" /> για να απελευθερώσετε το επίπεδο. |

### Method: add(layer, symbolizer, labeling, default_reference_system, keep_open) {#add_layer_symbolizer_labeling_default_reference_system_keep_open_7}


```
 add(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

Δημιουργεί και προσθέτει ένα [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) στον χάρτη. Τα στρώματα αποδίδονται με τη σειρά προσθήκης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ένα διανυσματικό επίπεδο για αναπαράσταση από το [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Ένας symbolizer προς χρήση για την απόδοση. Εάν <see langword=\"null\" />, χρησιμοποιείται ο προεπιλεγμένος symbolizer. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Ετικετοποίηση για χρήση στην επισήμανση χαρακτηριστικών στο επίπεδο. Εάν <see langword="null" />, θα χρησιμοποιηθεί το προεπιλεγμένο [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Καθορίζει μια τιμή για μια πηγή χωρικής αναφοράς (layer\sequence) εάν λείπει. Θα χρησιμοποιηθεί το προεπιλεγμένο null. |
| keep_open | bool | <see langword="true" /> για να αφήσετε το επίπεδο ανοιχτό μετά την απελευθέρωση του αντικειμένου [Map](/psd/python-net/aspose.gis.rendering/map/); διαφορετικά, <see langword="false" />. |

### Method: add(layer, symbolizer, labeling, keep_open) {#add_layer_symbolizer_labeling_keep_open_8}


```
 add(layer, symbolizer, labeling, keep_open) 
```

Δημιουργεί και προσθέτει ένα [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) στον χάρτη. Τα στρώματα αποδίδονται με τη σειρά προσθήκης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ένα διανυσματικό επίπεδο για αναπαράσταση από το [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Ένας symbolizer προς χρήση για την απόδοση. Εάν <see langword=\"null\" />, χρησιμοποιείται ο προεπιλεγμένος symbolizer. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Ετικετοποίηση για χρήση στην επισήμανση χαρακτηριστικών στο επίπεδο. Εάν <see langword="null" />, θα χρησιμοποιηθεί το προεπιλεγμένο [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |
| keep_open | bool | <see langword="true" /> για να αφήσετε το επίπεδο ανοιχτό μετά την απελευθέρωση του αντικειμένου [Map](/psd/python-net/aspose.gis.rendering/map/); διαφορετικά, <see langword="false" />. |

### Method: add(map_layer) {#add_map_layer_9}


```
 add(map_layer) 
```

Προσθέτει ένα επίπεδο στον χάρτη. Τα επίπεδα αποδίδονται με τη σειρά προσθήκης.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| map_layer | [MapLayer](/psd/python-net/aspose.gis.rendering/maplayer) | Το επίπεδο που θα προστεθεί. |

### Method: render(output_path, renderer) {#render_output_path_renderer_10}


```
 render(output_path, renderer) 
```

Αποδίδει τον χάρτη σε ένα αρχείο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| output_path | string | Διαδρομή προς το αρχείο εξόδου. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | Renderer προς χρήση. |

### Method: render(output_path, renderer) {#render_output_path_renderer_11}


```
 render(output_path, renderer) 
```

Αποδίδει τον χάρτη σε ένα αρχείο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς το αρχείο εξόδου. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | Renderer προς χρήση. |

