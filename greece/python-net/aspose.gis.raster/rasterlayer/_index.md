---
title: "RasterLayer Κλάση"
type: docs
weight: 70
url: /el/python-net/aspose.gis.raster/rasterlayer/
---

**Summary:** Represents a raster layer.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.RasterLayer

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| band_count | int | r | Λαμβάνει τον αριθμό των ζωνών στο επίπεδο raster. |
| bounds | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | r | Λαμβάνει τα όρια του raster. |
| cell_size | [IRasterCellSize](/psd/python-net/aspose.gis.raster/irastercellsize) | r | Λαμβάνει το μέγεθος του κελιού ή του pixel του raster. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Λαμβάνει το [RasterLayer.driver](/psd/python-net/aspose.gis.raster/rasterlayer/) που δημιούργησε αυτό το επίπεδο. |
| ύψος | int | r | Λαμβάνει το ύψος του raster σε pixel. Επίσης είναι γνωστό ως αριθμός γραμμών. |
| no_data_values | [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | r | Λαμβάνει τις τιμές που αντιπροσωπεύουν το φόντο ή το 'χωρίς δεδομένα' του raster. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Λαμβάνει ένα σύστημα αναφοράς χώρου του raster.<br/>            Μπορεί να είναι <see langword="null" /> αν είναι άγνωστο. |
| upper_left_x | double | r | Λαμβάνει τη συντεταγμένη x της επάνω αριστερής γωνίας του raster. |
| upper_left_y | double | r | Λαμβάνει τη συντεταγμένη y της επάνω αριστερής γωνίας του raster. |
| width | int | r | Λαμβάνει το πλάτος του raster σε pixel. Επίσης είναι γνωστό ως αριθμός στηλών. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [crop(geometry, masks)](#crop_geometry_masks_1) | Κόβει το επίπεδο raster χρησιμοποιώντας μια μορφή σχήματος (και μάσκα ζώνης). |
| [crop(masks)](#crop_masks_2) | Κόβει το επίπεδο raster χρησιμοποιώντας μάσκα ζώνης). |
| [get_band(index)](#get_band_index_3) | Λαμβάνει μια ζώνη με το καθορισμένο δείκτη. |
| [get_extent()](#get_extent__4) | Υπολογίζει το χωρικό εύρος αυτού του επιπέδου. |
| [get_spatial_point(cell_x, cell_y)](#get_spatial_point_cell_x_cell_y_5) | Μετατρέπει τη συγκεκριμένη στήλη και γραμμή σε χωρική συντεταγμένη. |
| [get_statistics(band_index, exclude_nodata_value)](#get_statistics_band_index_exclude_nodata_value_6) | Υπολογίζει συνοπτικά στατιστικά που περιλαμβάνουν αριθμό, άθροισμα, μέσο, ελάχιστο, μέγιστο. |
| [get_values(cell_x, cell_y)](#get_values_cell_x_cell_y_7) | Αναγνώνει τις τιμές στο καθορισμένο κελί. |
| [get_values_dump(rect)](#get_values_dump_rect_8) | Αναγνώνει τις τιμές στο καθορισμένο μπλοκ ως μονοδιάστατο πίνακα. |
| [warp(options)](#warp_options_9) | Παραμορφώνει το επίπεδο raster σε άλλο. |


### Method: crop(geometry, masks) {#crop_geometry_masks_1}


```
 crop(geometry, masks) 
```

Κόβει το επίπεδο raster χρησιμοποιώντας μια μορφή σχήματος (και μάσκα ζώνης).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Η γεωμετρία αντιπροσωπεύει τη μορφή σχήματος. |
| μάσκες | double | Μάσκα για στρώση περικοπής |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Το περικομμένο raster στρώμα. Εάν δεν βρεθούν τομές, επιστρέφει <see langword="null" />. |


### Method: crop(masks) {#crop_masks_2}


```
 crop(masks) 
```

Κόβει το επίπεδο raster χρησιμοποιώντας μάσκα ζώνης).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| μάσκες | double | Μάσκα για στρώση περικοπής |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Το περικομμένο raster στρώμα. Εάν δεν βρεθούν τομές, επιστρέφει <see langword="null" />. |


### Method: get_band(index) {#get_band_index_3}


```
 get_band(index) 
```

Λαμβάνει μια ζώνη με το καθορισμένο δείκτη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | int | Οι αριθμοί ζώνης ξεκινούν από 0 και η ζώνη θεωρείται 0 εάν δεν καθοριστεί. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IRasterBand](/psd/python-net/aspose.gis.raster/irasterband) | Επιστρέφει βασικά μεταδεδομένα για μια raster ζώνη. |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

Υπολογίζει το χωρικό εύρος αυτού του επιπέδου.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Μια χωρική έκταση αυτού του επιπέδου. |


### Method: get_spatial_point(cell_x, cell_y) {#get_spatial_point_cell_x_cell_y_5}


```
 get_spatial_point(cell_x, cell_y) 
```

Μετατρέπει τη συγκεκριμένη στήλη και γραμμή σε χωρική συντεταγμένη.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cell_x | int | Η τιμή για τη στήλη (συντεταγμένη x). Η αρίθμηση ξεκινά από 0. |
| cell_y | int | Η τιμή για τη γραμμή (συντεταγμένη y). Η αρίθμηση ξεκινά από 0. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Επιστρέφει τη συντεταγμένη x της πάνω αριστερής γωνίας δεδομένης μιας στήλης και γραμμής. |


### Method: get_statistics(band_index, exclude_nodata_value) {#get_statistics_band_index_exclude_nodata_value_6}


```
 get_statistics(band_index, exclude_nodata_value) 
```

Υπολογίζει συνοπτικά στατιστικά που περιλαμβάνουν αριθμό, άθροισμα, μέσο, ελάχιστο, μέγιστο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| band_index | int | Ο δείκτης της ζώνης. Η αρίθμηση ξεκινά από το 0. |
| exclude_nodata_value | bool | Επιτρέπει την εξαίρεση τιμών 'nodata'. Εάν το 'excludeNodataValue' οριστεί σε false, τότε όλα τα pixel λαμβάνονται υπόψη. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [RasterStatistics](/psd/python-net/aspose.gis.raster/rasterstatistics) | Οι συνοπτικές στατιστικές. |


### Method: get_values(cell_x, cell_y) {#get_values_cell_x_cell_y_7}


```
 get_values(cell_x, cell_y) 
```

Αναγνώνει τις τιμές στο καθορισμένο κελί.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cell_x | int | Η τιμή για τη στήλη (συντεταγμένη x). Η αρίθμηση ξεκινά από 0. |
| cell_y | int | Η τιμή για τη γραμμή (συντεταγμένη y). Η αρίθμηση ξεκινά από 0. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | Οι τιμές raster. |


### Method: get_values_dump(rect) {#get_values_dump_rect_8}


```
 get_values_dump(rect) 
```

Αναγνώνει τις τιμές στο καθορισμένο μπλοκ ως μονοδιάστατο πίνακα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rect | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | Μπλοκ κελιών raster από όπου διαβάζεται το dump. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IRasterValues[]](/psd/python-net/aspose.gis.raster/irastervalues) | Η dump τιμών. |


### Method: warp(options) {#warp_options_9}


```
 warp(options) 
```

Παραμορφώνει το επίπεδο raster σε άλλο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| options | [WarpOptions](/psd/python-net/aspose.gis.raster/warpoptions) | Επιλογές για τη διαδικασία επαναπροβολής. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Το warp raster στρώμα. |


