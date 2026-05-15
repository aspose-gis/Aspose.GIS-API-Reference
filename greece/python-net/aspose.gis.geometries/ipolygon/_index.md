---
title: "Κλάση IPolygon"
type: docs
weight: 210
url: /el/python-net/aspose.gis.geometries/ipolygon/
---

**Summary:** A [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) whose boundaries are defined by linear rings.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.IPolygon

**Inheritance:** ICurvePolygon, ISurface, IGeometry

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | Λαμβάνει τη τοπολογική διάσταση αυτής της [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/).<br/>            Εάν η διάσταση είναι άγνωστη (π.χ. για μια κενή GEOMETRYCOLLECTION) επιστρέφεται το [GeometryDimension.POINT](/psd/python-net/aspose.gis.geometries/geometrydimension/). |
| exterior_ring | [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring) | r | Λαμβάνει το εξωτερικό δακτύλιο. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | Λαμβάνει τον τύπο της γεωμετρίας. |
| has_curve_geometry | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η γεωμετρία είναι ή περιέχει καμπύλη (μη γραμμική) γεωμετρία. |
| has_m | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει συντεταγμένη M. |
| has_z | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει συντεταγμένη Z. |
| interior_rings_count | int | r | Λαμβάνει τον αριθμό των εσωτερικών δακτυλίων. |
| is_empty | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι κενή (αντιπροσωπεύει το κενό σύνολο σημείων). |
| is_simple | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι απλή από την άποψη του SFA. |
| is_valid | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι έγκυρη. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Λαμβάνει το SpatialReferenceSystem αυτού του αντικειμένου.<br/>            Αυτή η ιδιότητα μπορεί να είναι <see langword="null" />, εάν το SpatialReferenceSystem είναι άγνωστο. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [as_binary()](#as_binary__1) | Μετατρέπει αυτή τη γεωμετρία στην αναπαράστασή της Well-Known Binary. |
| [as_binary(variant)](#as_binary_variant_2) | Μετατρέπει αυτή τη γεωμετρία στην αναπαράστασή της Well-Known Binary. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_3) | Εξάγει αυτή τη γεωμετρία σε αναπαράσταση εικόνας. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_4) | Εξάγει αυτή τη γεωμετρία σε αναπαράσταση εικόνας. |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_5) | Εξάγει αυτή τη γεωμετρία σε αναπαράσταση εικόνας. |
| [as_text()](#as_text__6) | Μετατρέπει αυτή τη γεωμετρία στην αναπαράστασή της Well-Known Text. |
| [as_text(variant)](#as_text_variant_7) | Μετατρέπει αυτή τη γεωμετρία στην αναπαράστασή της Well-Known Text. |
| [as_text(variant, format)](#as_text_variant_format_8) | Μετατρέπει αυτή τη γεωμετρία στην αναπαράστασή της Well-Known Text. |
| [clone()](#clone__9) | Κλωνοποιεί αυτό το παράδειγμα. |
| [covered_by(other)](#covered_by_other_10) | Καθορίζει εάν αυτή η γεωμετρία καλύπτεται από μια καθορισμένη γεωμετρία. |
| [covers(other)](#covers_other_11) | Καθορίζει εάν αυτή η γεωμετρία καλύπτει μια καθορισμένη γεωμετρία. |
| [crosses(other)](#crosses_other_12) | Καθορίζει εάν αυτή η γεωμετρία και μια καθορισμένη γεωμετρία διασχίζουν. |
| [difference(other)](#difference_other_13) | Αφαιρεί μια καθορισμένη γεωμετρία από αυτή τη γεωμετρία. |
| [disjoint(other)](#disjoint_other_14) | Καθορίζει εάν αυτή η γεωμετρία είναι διακριτή από μια καθορισμένη γεωμετρία. |
| [get_area()](#get_area__15) | Υπολογίζει το εμβαδόν αυτής της γεωμετρίας. |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_16) | Υπολογίζει μια περιοχή buffer γύρω από αυτή τη γεωμετρία. |
| [get_centroid()](#get_centroid__17) | Υπολογίζει το κέντρο μάζας αυτής της γεωμετρίας. |
| [get_convex_hull()](#get_convex_hull__18) | Υπολογίζει το κυρτό περίβλημα αυτής της γεωμετρίας. |
| [get_distance_to(other)](#get_distance_to_other_19) | Υπολογίζει την ελάχιστη απόσταση μεταξύ αυτής της γεωμετρίας και μιας καθορισμένης γεωμετρίας. |
| [get_extent()](#get_extent__20) | Υπολογίζει και επιστρέφει το περιβάλλον όριο αυτής της γεωμετρίας. |
| [get_interior_ring(index)](#get_interior_ring_index_21) | Λαμβάνει τον εσωτερικό δακτύλιο με βάση τον δείκτη του. |
| [get_length()](#get_length__22) | Υπολογίζει το μήκος αυτής της γεωμετρίας. |
| [get_point_on_surface()](#get_point_on_surface__23) | Βρίσκει ένα σημείο που είναι εγγυημένα πάνω σε αυτή την επιφάνεια. |
| [intersection(other)](#intersection_other_24) | Δημιουργεί μια τομή μεταξύ αυτής της γεωμετρίας και μιας καθορισμένης γεωμετρίας. |
| [intersects(extent)](#intersects_extent_25) | Καθορίζει εάν αυτή η γεωμετρία τέμνει ένα καθορισμένο εύρος. |
| [intersects(other)](#intersects_other_26) | Καθορίζει εάν αυτή η γεωμετρία και μια καθορισμένη γεωμετρία τέμνονται. |
| [overlaps(other)](#overlaps_other_27) | Καθορίζει εάν αυτή η γεωμετρία επικαλύπτεται με μια καθορισμένη γεωμετρία. |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_28) | Καθορίζει εάν ο πίνακας τομής DE-9IM αυτής της γεωμετρίας και μιας καθορισμένης γεωμετρίας ταιριάζει με το παρεχόμενο μοτίβο. |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__29) | Λαμβάνει τα πολύγωνα που αναπαρίστανται ως γραμμές αυτής της γεωμετρίας. |
| [spatially_contains(other)](#spatially_contains_other_30) | Καθορίζει εάν αυτή η γεωμετρία χωρικά περιέχει μια καθορισμένη γεωμετρία. |
| [spatially_equals(other)](#spatially_equals_other_31) | Καθορίζει εάν αυτή η γεωμετρία είναι χωρικά ίση με μια καθορισμένη γεωμετρία. |
| [sym_difference(other)](#sym_difference_other_32) | Δημιουργεί τη συμμετρική διαφορά μεταξύ αυτού του γεωμετρικού αντικειμένου και ενός καθορισμένου γεωμετρικού αντικειμένου. |
| [to_editable()](#to_editable__33) | Λαμβάνει ένα επεξεργάσιμο αντίγραφο αυτού του γεωμετρικού αντικειμένου. |
| [to_linear_geometry()](#to_linear_geometry__34) | Λαμβάνει μια προσεγγιστική ή ισοδύναμη μη-καμπυλική έκδοση αυτού του γεωμετρικού αντικειμένου χρησιμοποιώντας την προεπιλεγμένη <c>tolerance</c>. |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_35) | Λαμβάνει μια προσεγγιστική ή ισοδύναμη μη-καμπυλική έκδοση αυτού του γεωμετρικού αντικειμένου χρησιμοποιώντας την καθορισμένη <c>tolerance</c>. |
| [touches(other)](#touches_other_36) | Καθορίζει εάν αυτό το γεωμετρικό αντικείμενο και ένα καθορισμένο γεωμετρικό αντικείμενο αγγίζουν. |
| [union(other)](#union_other_37) | Ενώνει αυτό το γεωμετρικό αντικείμενο και ένα καθορισμένο γεωμετρικό αντικείμενο. |
| [union(other)](#union_other_38) | Ενώνει αυτό το γεωμετρικό αντικείμενο και ένα καθορισμένο γεωμετρικό αντικείμενο. |
| [within(extent)](#within_extent_39) | Καθορίζει εάν αυτό το γεωμετρικό αντικείμενο βρίσκεται εντός ενός καθορισμένου εύρους. |
| [within(other)](#within_other_40) | Καθορίζει εάν αυτό το γεωμετρικό αντικείμενο βρίσκεται εντός ενός καθορισμένου γεωμετρικού αντικειμένου. |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

Μετατρέπει αυτή τη γεωμετρία στην αναπαράστασή της Well-Known Binary.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| byte | Αναπαράσταση Well-Known Binary αυτού του γεωμετρικού αντικειμένου. |


### Method: as_binary(variant) {#as_binary_variant_2}


```
 as_binary(variant) 
```

Μετατρέπει αυτή τη γεωμετρία στην αναπαράστασή της Well-Known Binary.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| variant | [WkbVariant](/psd/python-net/aspose.gis.geometries/wkbvariant) | Παραλλαγή Well-Known Binary προς χρήση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| byte | Αναπαράσταση Well-Known Binary αυτού του γεωμετρικού αντικειμένου. |


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_3}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

Εξάγει αυτή τη γεωμετρία σε αναπαράσταση εικόνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Διαδρομή προς την εικόνα εξόδου. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Πλάτος του χάρτη. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Ύψος του χάρτη. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Renderer προς χρήση. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Ένας symbolizer προς χρήση για την απόδοση. Εάν <see langword=\"null\" />, χρησιμοποιείται ο προεπιλεγμένος symbolizer. |

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_4}


```
 as_image(output_path, width, height, renderer, symbolizer) 
```

Εξάγει αυτή τη γεωμετρία σε αναπαράσταση εικόνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| output_path | string | Διαδρομή προς την εικόνα εξόδου. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Πλάτος του χάρτη. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Ύψος του χάρτη. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Renderer προς χρήση. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Ένας symbolizer προς χρήση για την απόδοση. Εάν <see langword=\"null\" />, χρησιμοποιείται ο προεπιλεγμένος symbolizer. |

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_5}


```
 as_image(width, height, renderer, symbolizer) 
```

Εξάγει αυτή τη γεωμετρία σε αναπαράσταση εικόνας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Πλάτος του χάρτη. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement/) | Ύψος του χάρτη. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | Renderer προς χρήση. |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Ένας symbolizer προς χρήση για την απόδοση. Εάν <see langword=\"null\" />, χρησιμοποιείται ο προεπιλεγμένος symbolizer. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| _io.BufferedRandom | Η εικόνα ως ροή |


### Method: as_text() {#as_text__6}


```
 as_text() 
```

Μετατρέπει αυτή τη γεωμετρία στην αναπαράστασή της Well-Known Text.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Αναπαράσταση Well-Known Text αυτού του γεωμετρικού αντικειμένου. |


### Method: as_text(variant) {#as_text_variant_7}


```
 as_text(variant) 
```

Μετατρέπει αυτή τη γεωμετρία στην αναπαράστασή της Well-Known Text.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | Παραλλαγή Well-Known Text προς χρήση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Αναπαράσταση Well-Known Text αυτού του γεωμετρικού αντικειμένου. |


### Method: as_text(variant, format) {#as_text_variant_format_8}


```
 as_text(variant, format) 
```

Μετατρέπει αυτή τη γεωμετρία στην αναπαράστασή της Well-Known Text.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| variant | [WktVariant](/psd/python-net/aspose.gis.geometries/wktvariant) | Παραλλαγή Well-Known Text προς χρήση. |
| format | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Μορφή συντεταγμένων για μετατροπή σε συμβολοσειρά. Δείτε το [NumericFormat](/psd/python-net/aspose.gis/numericformat/) για να το λάβετε. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Αναπαράσταση Well-Known Text αυτού του γεωμετρικού αντικειμένου. |


### Method: clone() {#clone__9}


```
 clone() 
```

Κλωνοποιεί αυτό το παράδειγμα.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | Το κλώνο αυτής της παρουσίας |


### Method: covered_by(other) {#covered_by_other_10}


```
 covered_by(other) 
```

Καθορίζει εάν αυτή η γεωμετρία καλύπτεται από μια καθορισμένη γεωμετρία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Ένα γεωμετρικό αντικείμενο. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <see langword=\"true\" /> εάν αυτό το γεωμετρικό αντικείμενο είναι \"spatially covered by\" ένα άλλο γεωμετρικό αντικείμενο. <see langword=\"false\" /> διαφορετικά. |


### Method: covers(other) {#covers_other_11}


```
 covers(other) 
```

Καθορίζει εάν αυτή η γεωμετρία καλύπτει μια καθορισμένη γεωμετρία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Ένα γεωμετρικό αντικείμενο. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <see langword=\"true\" /> εάν αυτό το γεωμετρικό αντικείμενο \"spatially covers\" ένα άλλο γεωμετρικό αντικείμενο. <see langword=\"false\" /> διαφορετικά. |


### Method: crosses(other) {#crosses_other_12}


```
 crosses(other) 
```

Καθορίζει εάν αυτή η γεωμετρία και μια καθορισμένη γεωμετρία διασχίζουν.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Ένα γεωμετρικό αντικείμενο. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <see langword=\"true\" /> εάν αυτό το γεωμετρικό αντικείμενο \"spatially crosses\" ένα άλλο γεωμετρικό αντικείμενο. <see langword=\"false\" /> διαφορετικά. |


### Method: difference(other) {#difference_other_13}


```
 difference(other) 
```

Αφαιρεί μια καθορισμένη γεωμετρία από αυτή τη γεωμετρία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Μια γεωμετρία για αφαίρεση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Μια γεωμετρία που αντιπροσωπεύει τη διαφορά αυτής της γεωμετρίας και ενός ορίσματος. Η γεωμετρία αποτελέσματος περιέχει<br/>            σύνολο σημείων που υπάρχουν σε αυτή τη γεωμετρία αλλά δεν υπάρχουν στο όρισμα. |


### Method: disjoint(other) {#disjoint_other_14}


```
 disjoint(other) 
```

Καθορίζει εάν αυτή η γεωμετρία είναι διακριτή από μια καθορισμένη γεωμετρία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Ένα γεωμετρικό αντικείμενο. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <see langword="true" /> εάν αυτή η γεωμετρία είναι «χωρισμένη χωρικά» από άλλη γεωμετρία. <see langword="false" /> διαφορετικά. |


### Method: get_area() {#get_area__15}


```
 get_area() 
```

Υπολογίζει το εμβαδόν αυτής της γεωμετρίας.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| double | Η περιοχή αυτής της γεωμετρίας.<br/>            Άθροισμα των περιοχών των στοιχείων αυτής της γεωμετρίας εάν αυτή η γεωμετρία είναι μια [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_16}


```
 get_buffer(distance, quadrant_segments) 
```

Υπολογίζει μια περιοχή buffer γύρω από αυτή τη γεωμετρία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| απόσταση | double | Το πλάτος της περιοχής buffer (σε μονάδες Spatial Reference). |
| quadrant_segments | int | Αριθμός τμημάτων που χρησιμοποιούνται για την προσέγγιση μιας καμπυλότητας 90 μοιρών.<br/>            Όσο μεγαλύτερος είναι αυτός ο αριθμός, τόσο καλύτερη είναι η προσέγγιση των καμπυλών.<br/>            Η προεπιλογή είναι 30. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Μια γεωμετρία που αντιπροσωπεύει όλα τα σημεία που βρίσκονται εντός μιας καθορισμένης απόστασης από<br/>            αυτή τη γεωμετρία.<br/>            Ο τύπος του αποτελέσματος είναι είτε [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/), [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon/) ή [IMultiPolygon](/psd/python-net/aspose.gis.geometries/imultipolygon/). |


### Method: get_centroid() {#get_centroid__17}


```
 get_centroid() 
```

Υπολογίζει το κέντρο μάζας αυτής της γεωμετρίας.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Το κέντρο μάζας (centroid) αυτής της γεωμετρίας. Εάν αυτή η γεωμετρία είναι κενή, επιστρέφεται ένα κενό σημείο.<br/>            Το κέντρο μάζας είναι ίσο με το κέντρο μάζας των γεωμετριών υψηλότερης διάστασης σε αυτή τη γεωμετρία<br/>            (π.χ. εάν η γεωμετρία περιέχει τόσο σημεία όσο και γραμμές, μόνο οι γραμμές συμβάλλουν στο κέντρο μάζας). |


### Method: get_convex_hull() {#get_convex_hull__18}


```
 get_convex_hull() 
```

Υπολογίζει το κυρτό περίβλημα αυτής της γεωμετρίας.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Μια γεωμετρία που αντιπροσωπεύει το κυρτό περίβλημα (convex hull) αυτής της γεωμετρίας.<br/>            Εάν αυτή η γεωμετρία δεν έχει σημεία, τότε το αποτέλεσμα είναι [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/).<br/>            Εάν αυτή η γεωμετρία έχει μόνο ένα σημείο, τότε το αποτέλεσμα είναι αυτό το σημείο.<br/>            Εάν αυτή η γεωμετρία έχει μόνο δύο σημεία, τότε το αποτέλεσμα είναι [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) με τα σημεία.<br/>            Εάν αυτή η γεωμετρία έχει τρία ή περισσότερα σημεία, τότε το αποτέλεσμα είναι [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/) που αντιπροσωπεύει ένα κυρτό<br/>            περίβλημα γύρω από όλα τα σημεία των γεωμετριών. |


### Method: get_distance_to(other) {#get_distance_to_other_19}


```
 get_distance_to(other) 
```

Υπολογίζει την ελάχιστη απόσταση μεταξύ αυτής της γεωμετρίας και μιας καθορισμένης γεωμετρίας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Μια γεωμετρία για την εύρεση απόστασης προς αυτή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| double | Εάν και οι δύο γεωμετρίες δεν είναι [IGeometry.is_empty](/psd/python-net/aspose.gis.geometries/igeometry/) - μια απόσταση μεταξύ των πλησιέστερων σημείων των γεωμετριών.<br/>            Εάν τουλάχιστον μία γεωμετρία είναι κενή, επιστρέφεται -1. |


### Method: get_extent() {#get_extent__20}


```
 get_extent() 
```

Υπολογίζει και επιστρέφει το περιβάλλον όριο αυτής της γεωμετρίας.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Ένα περιοριστικό εύρος (bounding extent) αυτής της γεωμετρίας. |


### Method: get_interior_ring(index) {#get_interior_ring_index_21}


```
 get_interior_ring(index) 
```

Λαμβάνει τον εσωτερικό δακτύλιο με βάση τον δείκτη του.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | int | Ο δείκτης. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring) | Ο εσωτερικός δακτύλιος. |


### Method: get_length() {#get_length__22}


```
 get_length() 
```

Υπολογίζει το μήκος αυτής της γεωμετρίας.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| double | Το μήκος αυτής της γεωμετρίας.<br/>            Περιφέρεια εάν αυτή είναι μια [Polygon](/psd/python-net/aspose.gis.geometries/polygon/).<br/>            Άθροισμα των μηκών των στοιχείων αυτής της γεωμετρίας εάν αυτή η γεωμετρία είναι μια [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: get_point_on_surface() {#get_point_on_surface__23}


```
 get_point_on_surface() 
```

Βρίσκει ένα σημείο που είναι εγγυημένα πάνω σε αυτή την επιφάνεια.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Ένα σημείο σε αυτή την επιφάνεια. Ένα κενό σημείο εάν αυτή η επιφάνεια δεν έχει εσωτερικό. |


### Method: intersection(other) {#intersection_other_24}


```
 intersection(other) 
```

Δημιουργεί μια τομή μεταξύ αυτής της γεωμετρίας και μιας καθορισμένης γεωμετρίας.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Μια γεωμετρία για τον υπολογισμό τομής με αυτή. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Μια γεωμετρία που αντιπροσωπεύει την τομή αυτής της γεωμετρίας και ενός ορίσματος. Η γεωμετρία αποτελέσματος περιέχει<br/>            σύνολο σημείων που υπάρχουν και στην αυτή τη γεωμετρία και στο όρισμα. |


### Method: intersects(extent) {#intersects_extent_25}


```
 intersects(extent) 
```

Καθορίζει εάν αυτή η γεωμετρία τέμνει ένα καθορισμένο εύρος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Το εύρος. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <see langword="true" /> εάν αυτή η γεωμετρία τέμνει το εύρος· <see langword="false" /> διαφορετικά. |


### Method: intersects(other) {#intersects_other_26}


```
 intersects(other) 
```

Καθορίζει εάν αυτή η γεωμετρία και μια καθορισμένη γεωμετρία τέμνονται.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Ένα γεωμετρικό αντικείμενο. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <see langword="true" /> εάν αυτή η γεωμετρία "spatially intersects" άλλη γεωμετρία. <see langword="false" /> διαφορετικά. |


### Method: overlaps(other) {#overlaps_other_27}


```
 overlaps(other) 
```

Καθορίζει εάν αυτή η γεωμετρία επικαλύπτεται με μια καθορισμένη γεωμετρία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Ένα γεωμετρικό αντικείμενο. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <see langword="true" /> εάν αυτή η γεωμετρία είναι "spatially overlaps" άλλη γεωμετρία. <see langword="false" /> διαφορετικά. |


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_28}


```
 relate(other, intersection_pattern_matrix) 
```

Καθορίζει εάν ο πίνακας τομής DE-9IM αυτής της γεωμετρίας και μιας καθορισμένης γεωμετρίας ταιριάζει με το παρεχόμενο μοτίβο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Ένα γεωμετρικό αντικείμενο. |
| intersection_pattern_matrix | string | Ένα μοτίβο για αντιστοίχιση.<br/> Αυτό πρέπει να είναι μια συμβολοσειρά μήκους 9.<br/> Κάθε χαρακτήρας της συμβολοσειράς αντιπροσωπεύει την αναμενόμενη διάσταση μιας τομής:<br/> <ul><br/> <li>χαρακτήρας 0 - μεταξύ εσωτερικών των γεωμετριών.</li><br/> <li>χαρακτήρας 1 - μεταξύ εσωτερικού αυτής της γεωμετρίας και ορίου άλλης γεωμετρίας.</li><br/> <li>χαρακτήρας 2 - μεταξύ εσωτερικού αυτής της γεωμετρίας και εξωτερικού άλλης γεωμετρίας.</li><br/> <li>χαρακτήρας 3 - μεταξύ ορίου αυτής της γεωμετρίας και εσωτερικού άλλης γεωμετρίας.</li><br/> <li>χαρακτήρας 4 - μεταξύ ορίων των γεωμετρικών.</li><br/> <li>χαρακτήρας 5 - μεταξύ ορίου αυτής της γεωμετρίας και εξωτερικού άλλης γεωμετρίας.</li><br/> <li>χαρακτήρας 6 - μεταξύ εξωτερικού αυτής της γεωμετρίας και εσωτερικού άλλης γεωμετρίας.</li><br/> <li>χαρακτήρας 7 - μεταξύ εξωτερικού αυτής της γεωμετρίας και ορίου άλλης γεωμετρίας.</li><br/> <li>χαρακτήρας 8 - μεταξύ εξωτερικών των γεωμετρικών.</li><br/> </ul><br/> Οι πιθανές τιμές κάθε χαρακτήρα είναι:<br/> <ul><br/> <li>* - οποιαδήποτε τιμή;</li><br/> <li>F - καμία τομή;</li><br/> <li>T - οποιαδήποτε τομή;</li><br/> <li>0 - τομή σημείου (π.χ. κοινό σημείο);</li><br/> <li>1 - τομή γραμμής (π.χ. κοινό τμήμα γραμμής);</li><br/> <li>2 - τομή περιοχής (π.χ. κοινό τμήμα πολυγώνου);</li><br/> </ul><br/> Για παράδειγμα, ένα μοτίβο τομής "F0*******" σημαίνει ότι δεν πρέπει να υπάρχει τομή μεταξύ των εσωτερικών των γεωμετριών και η τομή μεταξύ των ορίων των γεωμετριών πρέπει να είναι σημείο.<br/> Δείτε την OpenGIS Simple Features Specification για περισσότερες λεπτομέρειες σχετικά με το μοτίβο του πίνακα τομών. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <see langword="true" /> εάν αυτός ο πίνακας τομών ταιριάζει με το μοτίβο· <see langword="false" /> διαφορετικά. |


### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__29}


```
 replace_polygons_by_lines() 
```

Λαμβάνει τα πολύγωνα που αναπαρίστανται ως γραμμές αυτής της γεωμετρίας.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Μια γεωμετρία που δεν περιέχει γεωμετρίες πολυγώνου. Εφαρμόζονται οι ακόλουθες μετασχηματισμοί:<br/> <ul><br/> <li> [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s γραμμικοποιούνται<br/> (μετατρέπονται σε [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s)</li><br/> <li>[GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s συνδέονται σε [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s</li><br/> </ul> |


### Method: spatially_contains(other) {#spatially_contains_other_30}


```
 spatially_contains(other) 
```

Καθορίζει εάν αυτή η γεωμετρία χωρικά περιέχει μια καθορισμένη γεωμετρία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Ένα γεωμετρικό αντικείμενο. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <see langword="true" /> εάν αυτή η γεωμετρία "spatially contains" άλλη γεωμετρία. <see langword="false" /> διαφορετικά. |


### Method: spatially_equals(other) {#spatially_equals_other_31}


```
 spatially_equals(other) 
```

Καθορίζει εάν αυτή η γεωμετρία είναι χωρικά ίση με μια καθορισμένη γεωμετρία.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Ένα γεωμετρικό αντικείμενο. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <see langword="true" /> εάν αυτή η γεωμετρία "spatially equals" στην καθορισμένη γεωμετρία. <see langword="false" /> διαφορετικά. |


### Method: sym_difference(other) {#sym_difference_other_32}


```
 sym_difference(other) 
```

Δημιουργεί τη συμμετρική διαφορά μεταξύ αυτού του γεωμετρικού αντικειμένου και ενός καθορισμένου γεωμετρικού αντικειμένου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Μια γεωμετρία για τον υπολογισμό της συμμετρικής διαφοράς. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Μια γεωμετρία που αντιπροσωπεύει τη συμμετρική διαφορά αυτής της γεωμετρίας και ενός ορίσματος. Η γεωμετρία αποτελέσματος περιέχει<br/> σύνολο σημείων που εμφανίζονται σε μία από τις γεωμετρίες αλλά όχι και στις δύο. |


### Method: to_editable() {#to_editable__33}


```
 to_editable() 
```

Λαμβάνει ένα επεξεργάσιμο αντίγραφο αυτού του γεωμετρικού αντικειμένου.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Polygon](/psd/python-net/aspose.gis.geometries/polygon) | Ένα επεξεργάσιμο αντίγραφο αυτής της γεωμετρίας. |


### Method: to_linear_geometry() {#to_linear_geometry__34}


```
 to_linear_geometry() 
```

Λαμβάνει μια προσεγγιστική ή ισοδύναμη μη-καμπυλική έκδοση αυτού του γεωμετρικού αντικειμένου χρησιμοποιώντας την προεπιλεγμένη <c>tolerance</c>.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon) | Μια γεωμετρία που δεν έχει γεωμετρίες καμπύλης. Αυτό είναι το ισοδύναμο του <DOM Element: class at 0x2a1791a70d0>.IGeometry.to_linear_geometry()(float) με<br/>            προεπιλεγμένο <c>tolerance</c>. Η προεπιλεγμένη <c>tolerance</c> ορίζεται από το [IGeometry.spatial_reference_system](/psd/python-net/aspose.gis.geometries/igeometry/)<br/>            αυτής της γεωμετρίας:<br/>            <ul><br/>            <li> Για προβλεπόμενο SRS η ανοχή είναι 0.001 μέτρα (σε μονάδες SRS) </li><br/>            <li> Για γεωγραφικό SRS η ανοχή είναι <c>1e-5</c> μοίρες (σε μονάδες SRS) </li><br/>            <li> Για άγνωστο SRS η ανοχή είναι <c>1e-5</c> </li><br/>            </ul><br/>            Για περισσότερες λεπτομέρειες σχετικά με τους εφαρμοζόμενους μετασχηματισμούς, ανατρέξτε στην προδιαγραφή του <DOM Element: class at 0x2a1791a70d0>.IGeometry.to_linear_geometry()(float). |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_35}


```
 to_linear_geometry(tolerance) 
```

Λαμβάνει μια προσεγγιστική ή ισοδύναμη μη-καμπυλική έκδοση αυτού του γεωμετρικού αντικειμένου χρησιμοποιώντας την καθορισμένη <c>tolerance</c>.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ανοχή | double | Η <c>tolerance</c> που θα χρησιμοποιηθεί. Το αποτέλεσμα είναι εγγυημένα μικρότερο από <c>tolerance</c> από την<br/>            καμπυλωτή γεωμετρία, εκτός εάν ο αριθμός των σημείων που απαιτούνται για την εξομάλυνση της γεωμετρίας υπερβαίνει το μέγιστο ανά τεταρτημόριο<br/>            που αυτή τη στιγμή είναι ίσο με 10000 σημεία. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IPolygon](/psd/python-net/aspose.gis.geometries/ipolygon) | Μια γεωμετρία που δεν έχει γεωμετρίες καμπύλης. Εφαρμόζονται οι ακόλουθοι μετασχηματισμοί:<br/>            <ul><br/>            <li> Τα [GeometryType.CIRCULAR_STRING]s μετατρέπονται σε γραμμικές μορφές (μετατρέπονται σε [GeometryType.LINE_STRING]s με καθορισμένο <paramref name="tolerance" />) </li><br/>            <li> Τα [GeometryType.COMPOUND_CURVE]s ενώνται σε <c>LineString</c>s </li><br/>            <li> Τα [GeometryType.CURVE_POLYGON]s μετατρέπονται σε [GeometryType.POLYGON]s </li><br/>            <li> Τα [GeometryType.MULTI_CURVE]s μετατρέπονται σε [GeometryType.MULTI_LINE_STRING]s </li><br/>            <li> Τα [GeometryType.MULTI_SURFACE]s μετατρέπονται σε [GeometryType.MULTI_POLYGON]s </li><br/>            </ul><br/>            Ως αποτέλεσμα, το [IGeometry.has_curve_geometry] είναι <see langword="false" />. |


### Method: touches(other) {#touches_other_36}


```
 touches(other) 
```

Καθορίζει εάν αυτό το γεωμετρικό αντικείμενο και ένα καθορισμένο γεωμετρικό αντικείμενο αγγίζουν.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Ένα γεωμετρικό αντικείμενο. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <see langword="true" /> εάν αυτή η γεωμετρία "spatially touches" άλλη γεωμετρία. <see langword="false" /> διαφορετικά. |


### Method: union(other) {#union_other_37}


```
 union(other) 
```

Ενώνει αυτό το γεωμετρικό αντικείμενο και ένα καθορισμένο γεωμετρικό αντικείμενο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Μια γεωμετρία για ένωση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Μια γεωμετρία που αντιπροσωπεύει την ένωση αυτής της γεωμετρίας και ενός ορίσματος. Η γεωμετρία αποτελέσματος περιέχει<br/> σύνολο σημείων που εμφανίζονται σε αυτή τη γεωμετρία ή σε ένα όρισμα. |


### Method: union(other) {#union_other_38}


```
 union(other) 
```

Ενώνει αυτό το γεωμετρικό αντικείμενο και ένα καθορισμένο γεωμετρικό αντικείμενο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [IGeometry[]](/psd/python-net/aspose.gis.geometries/igeometry) | Μια γεωμετρία για ένωση. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Μια γεωμετρία που αντιπροσωπεύει την ένωση αυτής της γεωμετρίας και ενός ορίσματος. Η γεωμετρία αποτελέσματος περιέχει<br/> σύνολο σημείων που εμφανίζονται σε αυτή τη γεωμετρία ή σε ένα όρισμα. |


### Method: within(extent) {#within_extent_39}


```
 within(extent) 
```

Καθορίζει εάν αυτό το γεωμετρικό αντικείμενο βρίσκεται εντός ενός καθορισμένου εύρους.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Το εύρος. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <see langword="true" /> εάν αυτή η γεωμετρία βρίσκεται εντός της έκτασης· <see langword="false" /> διαφορετικά. |


### Method: within(other) {#within_other_40}


```
 within(other) 
```

Καθορίζει εάν αυτό το γεωμετρικό αντικείμενο βρίσκεται εντός ενός καθορισμένου γεωμετρικού αντικειμένου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Ένα γεωμετρικό αντικείμενο. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | <see langword="true" /> εάν αυτή η γεωμετρία "spatially within" άλλη γεωμετρία. <see langword="false" /> διαφορετικά. |


