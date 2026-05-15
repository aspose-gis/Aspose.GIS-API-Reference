---
title: "Κλάση Extent"
type: docs
weight: 820
url: /el/python-net/aspose.gis/extent/
---

**Summary:** A two-dimensional spatial bounding box.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Extent

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Extent()](#Extent__1) | Δημιουργεί νέο αντικείμενο. |
| [Extent(srs)](#Extent_srs_2) | Δημιουργεί νέο αντικείμενο. |
| [Extent(x_min, y_min, x_max, y_max, srs)](#Extent_x_min_y_min_x_max_y_max_srs_3) | Δημιουργεί νέο αντικείμενο. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| center | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | r | Κέντρο του extent. |
| ύψος | double | r | Ύψος του extent. |
| is_valid | bool | r | Καθορίζει αν αυτό το [Extent](/psd/python-net/aspose.gis/extent/) είναι έγκυρο. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) που σχετίζεται με αυτό το extent.<br/>            Μπορεί να είναι <see langword="null" /> εάν το [Extent.spatial_reference_system](/psd/python-net/aspose.gis/extent/) είναι άγνωστο.<br/>            Χρησιμοποιήστε Aspose.Gis.Extent.GetTransformed(Aspose.Gis.SpatialReferencing.SpatialReferenceSystem)<br/>            προκειμένου να μετασχηματίσετε το extent μεταξύ διαφορετικών συστημάτων αναφοράς χώρου. |
| width | double | r | Πλάτος του extent. |
| x_max | double | r/w | Μέγιστη τιμή του συντεταγμένου X. |
| x_min | double | r/w | Ελάχιστη τιμή του συντεταγμένου X. |
| y_max | double | r/w | Μέγιστη τιμή του συντεταγμένου Y. |
| y_min | double | r/w | Ελάχιστη τιμή του συντεταγμένου Y. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Κλωνοποιεί αυτό το παράδειγμα. |
| [contains(extent)](#contains_extent_2) | Καθορίζει εάν αυτό το εύρος περιέχει το όρισμα. |
| [contains(geometry)](#contains_geometry_3) | Καθορίζει εάν αυτό το εύρος περιέχει το όρισμα. |
| [contains(x, y)](#contains_x_y_4) | Καθορίζει εάν αυτό το εύρος περιέχει ένα συντεταγμένο που ορίζεται από τα ορίσματα. |
| [get_transformed(target_srs)](#get_transformed_target_srs_5) | Επιστρέφει νέο εύρος σε καθορισμένο [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) που περιέχει αυτό το εύρος. |
| [grow(extent)](#grow_extent_6) | Μεγαλώνει αυτό το εύρος ώστε να περιλαμβάνει το όρισμα. |
| [grow(x, y)](#grow_x_y_7) | Μεγαλώνει αυτό το εύρος ώστε να περιλαμβάνει το καθορισμένο σημείο. |
| [grow_x(value)](#grow_x_value_8) | Μεγαλώνει αυτό το εύρος κατά τον άξονα X ώστε να περιλαμβάνει την καθορισμένη τιμή. |
| [grow_y(value)](#grow_y_value_9) | Μεγαλώνει αυτό το εύρος κατά τον άξονα Y ώστε να περιλαμβάνει την καθορισμένη τιμή. |
| [intersects(extent)](#intersects_extent_10) | Καθορίζει εάν αυτό το εύρος τέμνει το όρισμα. |
| [intersects(geometry)](#intersects_geometry_11) | Καθορίζει εάν αυτό το εύρος τέμνει το όρισμα. |
| normalize() | Ανταλλάσσει [Extent.x_min](/psd/python-net/aspose.gis/extent/) με [Extent.x_max](/psd/python-net/aspose.gis/extent/) εάν το [Extent.width](/psd/python-net/aspose.gis/extent/) είναι αρνητικό και<br/>            [Extent.y_min](/psd/python-net/aspose.gis/extent/) με [Extent.y_max](/psd/python-net/aspose.gis/extent/) εάν το [Extent.height](/psd/python-net/aspose.gis/extent/) είναι αρνητικό. |
| [to_polygon()](#to_polygon__12) | Μετατρέπει αυτό το εύρος σε ένα ορθογώνιο πολύγωνο που το αντιπροσωπεύει. |


### Constructor: Extent() {#Extent__1}


```
 Extent() 
```

Δημιουργεί νέο αντικείμενο.

### Constructor: Extent(srs) {#Extent_srs_2}


```
 Extent(srs) 
```

Δημιουργεί νέο αντικείμενο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) συσχετισμένο με αυτό το εύρος.<br/>            Μπορεί να είναι <see langword="null" /> για να υποδείξει ότι το SRS είναι άγνωστο. |

### Constructor: Extent(x_min, y_min, x_max, y_max, srs) {#Extent_x_min_y_min_x_max_y_max_srs_3}


```
 Extent(x_min, y_min, x_max, y_max, srs) 
```

Δημιουργεί νέο αντικείμενο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x_min | double | Ελάχιστη τιμή X. |
| y_min | double | Ελάχιστη τιμή Y. |
| x_max | double | Μέγιστη τιμή X. |
| y_max | double | Μέγιστη τιμή Y. |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) συσχετισμένο με αυτό το εύρος.<br/>            Μπορεί να είναι <see langword="null" /> για να υποδείξει ότι το SRS είναι άγνωστο. |

### Method: clone() {#clone__1}


```
 clone() 
```

Κλωνοποιεί αυτό το παράδειγμα.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Αντίγραφο αυτού του αντικειμένου. |


### Method: contains(extent) {#contains_extent_2}


```
 contains(extent) 
```

Καθορίζει εάν αυτό το εύρος περιέχει το όρισμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Άλλο εύρος. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Τιμή, που υποδεικνύει εάν αυτό το εύρος περιέχει το όρισμα. |


### Method: contains(geometry) {#contains_geometry_3}


```
 contains(geometry) 
```

Καθορίζει εάν αυτό το εύρος περιέχει το όρισμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Ένα γεωμετρικό σχήμα για δοκιμή περιεχομένου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Τιμή, που υποδεικνύει εάν αυτό το εύρος περιέχει το όρισμα. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Καθορίζει εάν αυτό το εύρος περιέχει ένα συντεταγμένο που ορίζεται από τα ορίσματα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | double | X του συντεταγμένου. |
| y | double | Y του συντεταγμένου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Τιμή, που υποδεικνύει εάν το συντεταγμένο βρίσκεται εντός του πλαισίου. |


### Method: get_transformed(target_srs) {#get_transformed_target_srs_5}


```
 get_transformed(target_srs) 
```

Επιστρέφει νέο εύρος σε καθορισμένο [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) που περιέχει αυτό το εύρος.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) για μετασχηματισμό. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Το αποτέλεσμα της μετατροπής αυτού του εύρους στο καθορισμένο SRS. |


### Method: grow(extent) {#grow_extent_6}


```
 grow(extent) 
```

Μεγαλώνει αυτό το εύρος ώστε να περιλαμβάνει το όρισμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Άλλο εύρος. |

### Method: grow(x, y) {#grow_x_y_7}


```
 grow(x, y) 
```

Μεγαλώνει αυτό το εύρος ώστε να περιλαμβάνει το καθορισμένο σημείο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | double | Συντεταγμένη X για συμπερίληψη. |
| y | double | Συντεταγμένη Y για συμπερίληψη. |

### Method: grow_x(value) {#grow_x_value_8}


```
 grow_x(value) 
```

Μεγαλώνει αυτό το εύρος κατά τον άξονα X ώστε να περιλαμβάνει την καθορισμένη τιμή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| value | double | Τιμή για συμπερίληψη. |

### Method: grow_y(value) {#grow_y_value_9}


```
 grow_y(value) 
```

Μεγαλώνει αυτό το εύρος κατά τον άξονα Y ώστε να περιλαμβάνει την καθορισμένη τιμή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| value | double | Τιμή για συμπερίληψη. |

### Method: intersects(extent) {#intersects_extent_10}


```
 intersects(extent) 
```

Καθορίζει εάν αυτό το εύρος τέμνει το όρισμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Άλλο εύρος. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Τιμή, η οποία υποδεικνύει αν αυτό το εύρος τέμνει το όρισμα. |


### Method: intersects(geometry) {#intersects_geometry_11}


```
 intersects(geometry) 
```

Καθορίζει εάν αυτό το εύρος τέμνει το όρισμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Γεωμετρία για δοκιμή τομής |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool | Τιμή, η οποία υποδεικνύει αν αυτό το εύρος τέμνει το όρισμα. |


### Method: to_polygon() {#to_polygon__12}


```
 to_polygon() 
```

Μετατρέπει αυτό το εύρος σε ένα ορθογώνιο πολύγωνο που το αντιπροσωπεύει.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Ένα ορθογώνιο [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) που αντιπροσωπεύει αυτό το εύρος. Για μη έγκυρα εύρη<br/>            επιστρέφεται ένα κενό πολύγωνο. |


