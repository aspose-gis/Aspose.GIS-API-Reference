---
title: "Κλάση CompoundCurve"
type: docs
weight: 20
url: /el/python-net/aspose.gis.geometries/compoundcurve/
---

**Summary:** A curve that represents a sequence of contiguous curves such that adjacent curves are joined at their end points.

**Module:** [aspose.gis.geometries](/psd/python-net/aspose.gis.geometries/)

**Full Name:** aspose.gis.geometries.CompoundCurve

**Inheritance:** IGeometry, ICurve, ICompoundCurve, Curve

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [CompoundCurve()](#CompoundCurve__1) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [CompoundCurve](/psd/python-net/aspose.gis.geometries/compoundcurve/). |
| [CompoundCurve(curves)](#CompoundCurve_curves_2) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [CompoundCurve](/psd/python-net/aspose.gis.geometries/compoundcurve/). |
| [CompoundCurve(other)](#CompoundCurve_other_3) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [CompoundCurve](/psd/python-net/aspose.gis.geometries/compoundcurve/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| coordinate_dimension | int | r | Λαμβάνει τον αριθμό των διαστάσεων συντεταγμένων για αυτή τη [Γεωμετρία](/psd/python-net/aspose.gis.geometries/geometry/). |
| count | int | r | Λαμβάνει τον αριθμό των καμπυλών στο [ICompoundCurve](/psd/python-net/aspose.gis.geometries/icompoundcurve/). |
| dimension | [GeometryDimension](/psd/python-net/aspose.gis.geometries/geometrydimension) | r | Λαμβάνει τη τοπολογική διάσταση αυτής της [Γεωμετρία](/psd/python-net/aspose.gis.geometries/geometry/). |
| end_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | Επιστρέφει ένα αντίγραφο του τελικού σημείου της καμπύλης. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype) | r | Λαμβάνει τον τύπο της γεωμετρίας. |
| has_curve_geometry | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η γεωμετρία είναι ή περιέχει καμπύλη (μη γραμμική) γεωμετρία. |
| has_m | bool | r/w | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει συντεταγμένη M. |
| has_z | bool | r/w | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία έχει συντεταγμένη Z. |
| is_closed | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν μια καμπύλη είναι κλειστή. <br/>            Μια καμπύλη είναι κλειστή εάν το αρχικό της σημείο είναι ίσο με το τελικό σημείο. |
| is_empty | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι κενή. |
| is_simple | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι απλή από την άποψη του SFA. |
| is_valid | bool | r | Λαμβάνει μια τιμή που υποδεικνύει εάν αυτή η παρουσία είναι έγκυρη. |
| null [static] | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | r | Λαμβάνει μια παρουσία μηδενικής γεωμετρίας. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Λαμβάνει το SpatialReferenceSystem αυτής της παρουσίασης.<br/>            Αυτή η ιδιότητα μπορεί να είναι <see langword="null" />, εάν το SpatialReferenceSystem δεν έχει οριστεί.<br/>            Η ανάθεση νέου SpatialReferenceSystem δεν θα εκτελέσει καμία μετασχηματισμό συντεταγμένων, μόνο η αναφορά θα αλλάξει. |
| start_point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | r | Επιστρέφει ένα αντίγραφο του αρχικού σημείου της καμπύλης. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_curve(curve)](#add_curve_curve_1) | Προσθέτει μια καμπύλη στο τέλος αυτού του [CompoundCurve](/psd/python-net/aspose.gis.geometries/compoundcurve/). |
| [as_binary()](#as_binary__2) | Μετατρέπει αυτή τη γεωμετρία στην αναπαράστασή της Well-Known Binary. |
| [as_binary(variant)](#as_binary_variant_3) | Μετατρέπει αυτή τη γεωμετρία στην αναπαράστασή της Well-Known Binary. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_4) | Εξάγει αυτή τη γεωμετρία σε αναπαράσταση εικόνας. |
| [as_image(output_path, width, height, renderer, symbolizer)](#as_image_output_path_width_height_renderer_symbolizer_5) | Εξάγει αυτή τη γεωμετρία σε αναπαράσταση εικόνας. |
| [as_image(width, height, renderer, symbolizer)](#as_image_width_height_renderer_symbolizer_6) | Εξάγει αυτή τη γεωμετρία σε αναπαράσταση εικόνας. |
| [as_text()](#as_text__7) | Μετατρέπει αυτή τη γεωμετρία στην αναπαράστασή της Well-Known Text. |
| [as_text(variant)](#as_text_variant_8) | Μετατρέπει αυτή τη γεωμετρία στην αναπαράστασή της Well-Known Text. |
| [as_text(variant, format)](#as_text_variant_format_9) | Μετατρέπει αυτή τη γεωμετρία στην αναπαράστασή της Well-Known Text. |
| [clone()](#clone__10) | Κλωνοποιεί αυτό το παράδειγμα. |
| [covered_by(other)](#covered_by_other_11) | Καθορίζει εάν αυτή η γεωμετρία καλύπτεται από μια καθορισμένη γεωμετρία. |
| [covers(other)](#covers_other_12) | Καθορίζει εάν αυτή η γεωμετρία καλύπτει μια καθορισμένη γεωμετρία. |
| [crosses(other)](#crosses_other_13) | Καθορίζει εάν αυτή η γεωμετρία και μια καθορισμένη γεωμετρία διασχίζουν. |
| [difference(other)](#difference_other_14) | Αφαιρεί μια καθορισμένη γεωμετρία από αυτή τη γεωμετρία. |
| [disjoint(other)](#disjoint_other_15) | Καθορίζει εάν αυτή η γεωμετρία είναι διακριτή από μια καθορισμένη γεωμετρία. |
| [from_binary(wkb)](#from_binary_wkb_16) | Δημιουργεί μια γεωμετρία από την αναπαράστασή της σε Well-Known Binary. |
| [from_binary(wkb, spatial_reference_system)](#from_binary_wkb_spatial_reference_system_17) | Δημιουργεί μια γεωμετρία από την αναπαράστασή της σε Well-Known Binary. |
| [from_text(wkt)](#from_text_wkt_18) | Δημιουργεί μια γεωμετρία από την αναπαράστασή της σε Well-Known Text. |
| [from_text(wkt, spatial_reference_system)](#from_text_wkt_spatial_reference_system_19) | Δημιουργεί μια γεωμετρία από την αναπαράστασή της σε Well-Known Text. |
| [get_area()](#get_area__20) | Υπολογίζει το εμβαδόν αυτής της γεωμετρίας. |
| [get_buffer(distance, quadrant_segments)](#get_buffer_distance_quadrant_segments_21) | Υπολογίζει μια περιοχή buffer γύρω από αυτή τη γεωμετρία. |
| [get_centroid()](#get_centroid__22) | Υπολογίζει το κέντρο μάζας αυτής της γεωμετρίας. |
| [get_convex_hull()](#get_convex_hull__23) | Υπολογίζει το κυρτό περίβλημα αυτής της γεωμετρίας. |
| [get_distance_to(other)](#get_distance_to_other_24) | Υπολογίζει την ελάχιστη απόσταση μεταξύ αυτής της γεωμετρίας και μιας καθορισμένης γεωμετρίας. |
| [get_extent()](#get_extent__25) | Υπολογίζει και επιστρέφει το περιβάλλον όριο αυτής της γεωμετρίας. |
| [get_length()](#get_length__26) | Υπολογίζει το μήκος αυτής της γεωμετρίας. |
| [intersection(other)](#intersection_other_27) | Δημιουργεί μια τομή μεταξύ αυτής της γεωμετρίας και μιας καθορισμένης γεωμετρίας. |
| [intersects(extent)](#intersects_extent_28) | Καθορίζει εάν αυτή η γεωμετρία τέμνει ένα καθορισμένο εύρος. |
| [intersects(other)](#intersects_other_29) | Καθορίζει εάν αυτή η γεωμετρία και μια καθορισμένη γεωμετρία τέμνονται. |
| [overlaps(other)](#overlaps_other_30) | Καθορίζει εάν αυτή η γεωμετρία επικαλύπτεται με μια καθορισμένη γεωμετρία. |
| [relate(other, intersection_pattern_matrix)](#relate_other_intersection_pattern_matrix_31) | Καθορίζει εάν ο πίνακας τομής DE-9IM αυτής της γεωμετρίας και μιας καθορισμένης γεωμετρίας ταιριάζει με το παρεχόμενο μοτίβο. |
| [replace_polygons_by_lines()](#replace_polygons_by_lines__32) | Λαμβάνει τα πολύγωνα που αναπαρίστανται ως γραμμές αυτής της γεωμετρίας. |
| reverse() | Αναστρέφει αυτό το [CompoundCurve](/psd/python-net/aspose.gis.geometries/compoundcurve/). Δηλαδή - αντιστρέφει τη σειρά των καμπυλών και κάθε καμπύλη μέσα σε αυτή τη σύνθετη καμπύλη. |
| [round_m(digits)](#round_m_digits_33) | Στρογγυλοποιεί την συντεταγμένη M σε καθορισμένο αριθμό δεκαδικών ψηφίων. |
| [round_xy(digits)](#round_xy_digits_34) | Στρογγυλοποιεί τις συντεταγμένες X και Y σε καθορισμένο αριθμό δεκαδικών ψηφίων. |
| [round_z(digits)](#round_z_digits_35) | Στρογγυλοποιεί τη συντεταγμένη Z σε καθορισμένο αριθμό δεκαδικών ψηφίων. |
| set_empty() | Κάνει αυτή τη [Geometry](/psd/python-net/aspose.gis.geometries/geometry/) κενή. |
| [spatially_contains(other)](#spatially_contains_other_36) | Καθορίζει εάν αυτή η γεωμετρία χωρικά περιέχει μια καθορισμένη γεωμετρία. |
| [spatially_equals(other)](#spatially_equals_other_37) | Καθορίζει εάν αυτή η γεωμετρία είναι χωρικά ίση με μια καθορισμένη γεωμετρία. |
| [sym_difference(other)](#sym_difference_other_38) | Δημιουργεί τη συμμετρική διαφορά μεταξύ αυτού του γεωμετρικού αντικειμένου και ενός καθορισμένου γεωμετρικού αντικειμένου. |
| [to_editable()](#to_editable__39) | Λαμβάνει ένα επεξεργάσιμο αντίγραφο αυτού του γεωμετρικού αντικειμένου. |
| [to_linear_geometry()](#to_linear_geometry__40) | Λαμβάνει μια προσεγγιστική ή ισοδύναμη μη-καμπυλική έκδοση αυτού του γεωμετρικού αντικειμένου χρησιμοποιώντας την προεπιλεγμένη <c>tolerance</c>. |
| [to_linear_geometry(tolerance)](#to_linear_geometry_tolerance_41) | Λαμβάνει μια προσεγγιστική ή ισοδύναμη μη-καμπυλική έκδοση αυτού του γεωμετρικού αντικειμένου χρησιμοποιώντας την καθορισμένη <c>tolerance</c>. |
| [to_svg(extent)](#to_svg_extent_42) | Μετατρέπει αυτό το γεωμετρικό αντικείμενο σε αναπαράσταση Svg. |
| [touches(other)](#touches_other_43) | Καθορίζει εάν αυτό το γεωμετρικό αντικείμενο και ένα καθορισμένο γεωμετρικό αντικείμενο αγγίζουν. |
| [union(other)](#union_other_44) | Ενώνει αυτό το γεωμετρικό αντικείμενο και ένα καθορισμένο γεωμετρικό αντικείμενο. |
| [union(other)](#union_other_45) | Ενώνει αυτό το γεωμετρικό αντικείμενο και ένα καθορισμένο γεωμετρικό αντικείμενο. |
| [within(extent)](#within_extent_46) | Καθορίζει εάν αυτό το γεωμετρικό αντικείμενο βρίσκεται εντός ενός καθορισμένου εύρους. |
| [within(other)](#within_other_47) | Καθορίζει εάν αυτό το γεωμετρικό αντικείμενο βρίσκεται εντός ενός καθορισμένου γεωμετρικού αντικειμένου. |


### Constructor: CompoundCurve() {#CompoundCurve__1}


```
 CompoundCurve() 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [CompoundCurve](/psd/python-net/aspose.gis.geometries/compoundcurve/).

### Constructor: CompoundCurve(curves) {#CompoundCurve_curves_2}


```
 CompoundCurve(curves) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [CompoundCurve](/psd/python-net/aspose.gis.geometries/compoundcurve/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| καμπύλες | System.Collections.Generic.IEnumerable<ICurve> | Η συλλογή των καμπυλών. |

### Constructor: CompoundCurve(other) {#CompoundCurve_other_3}


```
 CompoundCurve(other) 
```

Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [CompoundCurve](/psd/python-net/aspose.gis.geometries/compoundcurve/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| other | [ICompoundCurve](/psd/python-net/aspose.gis.geometries/icompoundcurve) | Η άλλη γραμμή από την οποία θα αντιγραφούν τα δεδομένα. |

### Method: add_curve(curve) {#add_curve_curve_1}


```
 add_curve(curve) 
```

Προσθέτει μια καμπύλη στο τέλος αυτού του [CompoundCurve](/psd/python-net/aspose.gis.geometries/compoundcurve/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| curve | [ICurve](/psd/python-net/aspose.gis.geometries/icurve) | Καμπύλη προς προσθήκη. |

### Method: as_binary() {#as_binary__2}


```
 as_binary() 
```

Μετατρέπει αυτή τη γεωμετρία στην αναπαράστασή της Well-Known Binary.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| byte | Αναπαράσταση Well-Known Binary αυτού του γεωμετρικού αντικειμένου. |


### Method: as_binary(variant) {#as_binary_variant_3}


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


### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_4}


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

### Method: as_image(output_path, width, height, renderer, symbolizer) {#as_image_output_path_width_height_renderer_symbolizer_5}


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

### Method: as_image(width, height, renderer, symbolizer) {#as_image_width_height_renderer_symbolizer_6}


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


### Method: as_text() {#as_text__7}


```
 as_text() 
```

Μετατρέπει αυτή τη γεωμετρία στην αναπαράστασή της Well-Known Text.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Αναπαράσταση Well-Known Text αυτού του γεωμετρικού αντικειμένου. |


### Method: as_text(variant) {#as_text_variant_8}


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


### Method: as_text(variant, format) {#as_text_variant_format_9}


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


### Method: clone() {#clone__10}


```
 clone() 
```

Κλωνοποιεί αυτό το παράδειγμα.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Geometry](/psd/python-net/aspose.gis.geometries/geometry) | Το κλώνο αυτής της παρουσίας |


### Method: covered_by(other) {#covered_by_other_11}


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


### Method: covers(other) {#covers_other_12}


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


### Method: crosses(other) {#crosses_other_13}


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


### Method: difference(other) {#difference_other_14}


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


### Method: disjoint(other) {#disjoint_other_15}


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


### Method: from_binary(wkb)  [static] {#from_binary_wkb_16}


```
 from_binary(wkb) 
```

Δημιουργεί μια γεωμετρία από την αναπαράστασή της σε Well-Known Binary.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| wkb | byte | Αναπαράσταση Well-Known Binary μιας γεωμετρίας. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Μια γεωμετρία που αναπαρίσταται από το όρισμα. |


### Method: from_binary(wkb, spatial_reference_system)  [static] {#from_binary_wkb_spatial_reference_system_17}


```
 from_binary(wkb, spatial_reference_system) 
```

Δημιουργεί μια γεωμετρία από την αναπαράστασή της σε Well-Known Binary.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| wkb | byte | Αναπαράσταση Well-Known Binary μιας γεωμετρίας. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Σύστημα Αναφοράς Χώρου που θα εκχωρηθεί στη γεωμετρία. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Μια γεωμετρία που αναπαρίσταται από το όρισμα. |


### Method: from_text(wkt)  [static] {#from_text_wkt_18}


```
 from_text(wkt) 
```

Δημιουργεί μια γεωμετρία από την αναπαράστασή της σε Well-Known Text.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| wkt | string | Αναπαράσταση Well-Known Text μιας γεωμετρίας. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Μια γεωμετρία που αναπαρίσταται από το όρισμα. |


### Method: from_text(wkt, spatial_reference_system)  [static] {#from_text_wkt_spatial_reference_system_19}


```
 from_text(wkt, spatial_reference_system) 
```

Δημιουργεί μια γεωμετρία από την αναπαράστασή της σε Well-Known Text.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| wkt | string | Αναπαράσταση Well-Known Text μιας γεωμετρίας. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Σύστημα Αναφοράς Χώρου που θα εκχωρηθεί στη γεωμετρία. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Μια γεωμετρία που αναπαρίσταται από το όρισμα. |


### Method: get_area() {#get_area__20}


```
 get_area() 
```

Υπολογίζει το εμβαδόν αυτής της γεωμετρίας.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| double | Η περιοχή αυτής της γεωμετρίας.<br/>            Άθροισμα των περιοχών των στοιχείων αυτής της γεωμετρίας εάν αυτή η γεωμετρία είναι μια [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: get_buffer(distance, quadrant_segments) {#get_buffer_distance_quadrant_segments_21}


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


### Method: get_centroid() {#get_centroid__22}


```
 get_centroid() 
```

Υπολογίζει το κέντρο μάζας αυτής της γεωμετρίας.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint) | Το κέντρο μάζας (centroid) αυτής της γεωμετρίας. Εάν αυτή η γεωμετρία είναι κενή, επιστρέφεται ένα κενό σημείο.<br/>            Το κέντρο μάζας είναι ίσο με το κέντρο μάζας των γεωμετριών υψηλότερης διάστασης σε αυτή τη γεωμετρία<br/>            (π.χ. εάν η γεωμετρία περιέχει τόσο σημεία όσο και γραμμές, μόνο οι γραμμές συμβάλλουν στο κέντρο μάζας). |


### Method: get_convex_hull() {#get_convex_hull__23}


```
 get_convex_hull() 
```

Υπολογίζει το κυρτό περίβλημα αυτής της γεωμετρίας.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Μια γεωμετρία που αντιπροσωπεύει το κυρτό περίβλημα (convex hull) αυτής της γεωμετρίας.<br/>            Εάν αυτή η γεωμετρία δεν έχει σημεία, τότε το αποτέλεσμα είναι [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/).<br/>            Εάν αυτή η γεωμετρία έχει μόνο ένα σημείο, τότε το αποτέλεσμα είναι αυτό το σημείο.<br/>            Εάν αυτή η γεωμετρία έχει μόνο δύο σημεία, τότε το αποτέλεσμα είναι [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) με τα σημεία.<br/>            Εάν αυτή η γεωμετρία έχει τρία ή περισσότερα σημεία, τότε το αποτέλεσμα είναι [ILinearRing](/psd/python-net/aspose.gis.geometries/ilinearring/) που αντιπροσωπεύει ένα κυρτό<br/>            περίβλημα γύρω από όλα τα σημεία των γεωμετριών. |


### Method: get_distance_to(other) {#get_distance_to_other_24}


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


### Method: get_extent() {#get_extent__25}


```
 get_extent() 
```

Υπολογίζει και επιστρέφει το περιβάλλον όριο αυτής της γεωμετρίας.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Ένα περιοριστικό εύρος (bounding extent) αυτής της γεωμετρίας. |


### Method: get_length() {#get_length__26}


```
 get_length() 
```

Υπολογίζει το μήκος αυτής της γεωμετρίας.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| double | Το μήκος αυτής της γεωμετρίας.<br/>            Περιφέρεια εάν αυτή είναι μια [Polygon](/psd/python-net/aspose.gis.geometries/polygon/).<br/>            Άθροισμα των μηκών των στοιχείων αυτής της γεωμετρίας εάν αυτή η γεωμετρία είναι μια [GeometryCollection](/psd/python-net/aspose.gis.geometries/geometrycollection/). |


### Method: intersection(other) {#intersection_other_27}


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


### Method: intersects(extent) {#intersects_extent_28}


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


### Method: intersects(other) {#intersects_other_29}


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


### Method: overlaps(other) {#overlaps_other_30}


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


### Method: relate(other, intersection_pattern_matrix) {#relate_other_intersection_pattern_matrix_31}


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


### Method: replace_polygons_by_lines() {#replace_polygons_by_lines__32}


```
 replace_polygons_by_lines() 
```

Λαμβάνει τα πολύγωνα που αναπαρίστανται ως γραμμές αυτής της γεωμετρίας.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry) | Μια γεωμετρία που δεν περιέχει γεωμετρίες πολυγώνου. Εφαρμόζονται οι ακόλουθες μετασχηματισμοί:<br/> <ul><br/> <li> [GeometryType.POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s γραμμικοποιούνται<br/> (μετατρέπονται σε [GeometryType.LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s)</li><br/> <li>[GeometryType.MULTI_POLYGON](/psd/python-net/aspose.gis.geometries/geometrytype/)s συνδέονται σε [GeometryType.MULTI_LINE_STRING](/psd/python-net/aspose.gis.geometries/geometrytype/)s</li><br/> </ul> |


### Method: round_m(digits) {#round_m_digits_33}


```
 round_m(digits) 
```

Στρογγυλοποιεί την συντεταγμένη M σε καθορισμένο αριθμό δεκαδικών ψηφίων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ψηφία | int | Αριθμός δεκαδικών ψηφίων. |

### Method: round_xy(digits) {#round_xy_digits_34}


```
 round_xy(digits) 
```

Στρογγυλοποιεί τις συντεταγμένες X και Y σε καθορισμένο αριθμό δεκαδικών ψηφίων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ψηφία | int | Αριθμός δεκαδικών ψηφίων. |

### Method: round_z(digits) {#round_z_digits_35}


```
 round_z(digits) 
```

Στρογγυλοποιεί τη συντεταγμένη Z σε καθορισμένο αριθμό δεκαδικών ψηφίων.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ψηφία | int | Αριθμός δεκαδικών ψηφίων. |

### Method: spatially_contains(other) {#spatially_contains_other_36}


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


### Method: spatially_equals(other) {#spatially_equals_other_37}


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


### Method: sym_difference(other) {#sym_difference_other_38}


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


### Method: to_editable() {#to_editable__39}


```
 to_editable() 
```

Λαμβάνει ένα επεξεργάσιμο αντίγραφο αυτού του γεωμετρικού αντικειμένου.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [CompoundCurve](/psd/python-net/aspose.gis.geometries/compoundcurve) | Ένα επεξεργάσιμο αντίγραφο αυτής της γεωμετρίας. |


### Method: to_linear_geometry() {#to_linear_geometry__40}


```
 to_linear_geometry() 
```

Λαμβάνει μια προσεγγιστική ή ισοδύναμη μη-καμπυλική έκδοση αυτού του γεωμετρικού αντικειμένου χρησιμοποιώντας την προεπιλεγμένη <c>tolerance</c>.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | Ένα [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) που προσεγγίζει ή είναι ισοδύναμο με αυτήν την καμπύλη.<br/>            Αυτή είναι η ισοδυναμία του <DOM Element: class at 0x2a1791540d0>.ICurve.to_linear_geometry()(float) με<br/>            προεπιλεγμένο <c>tolerance</c>. Η προεπιλεγμένη τιμή του <c>tolerance</c> εξαρτάται από το [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)<br/>            αυτής της γεωμετρίας:<br/>            <ul><br/>            <li> Για προβλεπόμενο SRS η ανοχή είναι 0.001 μέτρα (σε μονάδες SRS) </li><br/>            <li> Για γεωγραφικό SRS η ανοχή είναι <c>1e-5</c> μοίρες (σε μονάδες SRS) </li><br/>            <li> Για άγνωστο SRS η ανοχή είναι <c>1e-5</c> </li><br/>            </ul><br/>            Για περισσότερες λεπτομέρειες σχετικά με τις μετασχηματισμούς που εφαρμόζονται, ανατρέξτε στην προδιαγραφή του <DOM Element: class at 0x2a1791540d0>.ICurve.to_linear_geometry()(float). |


### Method: to_linear_geometry(tolerance) {#to_linear_geometry_tolerance_41}


```
 to_linear_geometry(tolerance) 
```

Λαμβάνει μια προσεγγιστική ή ισοδύναμη μη-καμπυλική έκδοση αυτού του γεωμετρικού αντικειμένου χρησιμοποιώντας την καθορισμένη <c>tolerance</c>.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ανοχή | double | Η <c>tolerance</c> που θα χρησιμοποιηθεί. Το αποτέλεσμα εγγυάται ότι θα είναι μικρότερο από <c>tolerance</c> από την<br/> καμπυλωτή γεωμετρία, εκτός εάν ο αριθμός των σημείων που απαιτούνται για τη γραμμικοποίηση της γεωμετρίας υπερβεί το μέγιστο ανά τεταρτημόριο,<br/> το οποίο αυτή τη στιγμή είναι ίσο με 10000 σημεία. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring) | Ένα [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) που προσεγγίζει ή είναι ισοδύναμο με αυτήν την καμπύλη:<br/>             <ul><br/>             Αν αυτό το αντικείμενο είναι [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/) το ίδιο, το αποτέλεσμα είναι ισοδύναμο με αυτό το αντικείμενο<br/>             Αν αυτό το αντικείμενο είναι [ICircularString](/psd/python-net/aspose.gis.geometries/icircularstring/) το αποτέλεσμα είναι η κυκλική συμβολοσειρά γραμμικοποιημένη με το καθορισμένο <paramref name="tolerance" /><br/>             Αν αυτό το αντικείμενο είναι [ICompoundCurve](/psd/python-net/aspose.gis.geometries/icompoundcurve/) - όλες οι καμπύλες από αυτό γραμμικοποιούνται και στη συνέχεια ενώνται σε [ILineString](/psd/python-net/aspose.gis.geometries/ilinestring/)<br/>            </ul> |


### Method: to_svg(extent) {#to_svg_extent_42}


```
 to_svg(extent) 
```

Μετατρέπει αυτό το γεωμετρικό αντικείμενο σε αναπαράσταση Svg.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Έκταση για τη μετάφραση αυτής της γεωμετρίας σε Svg |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Η αναπαράσταση Svg. |


### Method: touches(other) {#touches_other_43}


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


### Method: union(other) {#union_other_44}


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


### Method: union(other) {#union_other_45}


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


### Method: within(extent) {#within_extent_46}


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


### Method: within(other) {#within_other_47}


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


