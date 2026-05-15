---
title: "Κλάση XyzTiles"
type: docs
weight: 20
url: /el/python-net/aspose.gis.formats.xyztile/xyztiles/
---

**Summary:** A XyzTiles provide access to [XyzTile](/psd/python-net/aspose.gis.formats.xyztile/xyztile/) objects.

**Module:** [aspose.gis.formats.xyztile](/psd/python-net/aspose.gis.formats.xyztile/)

**Full Name:** aspose.gis.formats.xyztile.XyzTiles

**Inheritance:** WebTiles

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XyzTiles(connection)](#XyzTiles_connection_1) | Δημιουργήστε μια παρουσία του [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_tile(zoom, x, y)](#get_tile_zoom_x_y_1) | Φορτώνει το καθορισμένο πλακίδιο. |
| [get_tile(zoom, x, y, tile_size)](#get_tile_zoom_x_y_tile_size_2) | Φορτώνει το καθορισμένο πλακίδιο. |
| [get_tiles(zoom, extent)](#get_tiles_zoom_extent_3) | Φορτώνει πλακίδια με βάση το χωρικό πλαίσιο και το επίπεδο ζουμ. |
| [get_tiles(zoom, extent, tile_size)](#get_tiles_zoom_extent_tile_size_4) | Φορτώνει πλακίδια με βάση το χωρικό πλαίσιο και το επίπεδο ζουμ. |


### Constructor: XyzTiles(connection) {#XyzTiles_connection_1}


```
 XyzTiles(connection) 
```

Δημιουργήστε μια παρουσία του [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/).

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| connection | [XyzConnection](/psd/python-net/aspose.gis.formats.xyztile/xyzconnection) | Μια σύνδεση που περιέχει επιλογές web. |

### Method: get_tile(zoom, x, y) {#get_tile_zoom_x_y_1}


```
 get_tile(zoom, x, y) 
```

Φορτώνει το καθορισμένο πλακίδιο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| zoom | int | Το επίπεδο ζουμ για τη φόρτωση των πλακιδίων. Το υψηλότερο επίπεδο ζουμ είναι 0. Οι περισσότεροι πάροχοι πλακιδίων έχουν περίπου 22 μέγιστα επίπεδα ζουμ. |
| x | int | Μία στήλη x ενός πλακιδίου. |
| y | int | Μία σειρά y ενός πλακιδίου. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | Το web πλακίδιο. |


### Method: get_tile(zoom, x, y, tile_size) {#get_tile_zoom_x_y_tile_size_2}


```
 get_tile(zoom, x, y, tile_size) 
```

Φορτώνει το καθορισμένο πλακίδιο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| zoom | int | Το επίπεδο ζουμ για τη φόρτωση των πλακιδίων. Το υψηλότερο επίπεδο ζουμ είναι 0. Οι περισσότεροι πάροχοι πλακιδίων έχουν περίπου 22 μέγιστα επίπεδα ζουμ. |
| x | int | Μία στήλη x ενός πλακιδίου. |
| y | int | Μία σειρά y ενός πλακιδίου. |
| tile_size | int | Μέγεθος των πλακιδίων, εξ ορισμού είναι 256 (είναι το πρότυπο μέγεθος πλακιδίων). |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | Το web πλακίδιο. |


### Method: get_tiles(zoom, extent) {#get_tiles_zoom_extent_3}


```
 get_tiles(zoom, extent) 
```

Φορτώνει πλακίδια με βάση το χωρικό πλαίσιο και το επίπεδο ζουμ.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| zoom | int | Το επίπεδο ζουμ για τη φόρτωση των πλακιδίων. Το υψηλότερο επίπεδο ζουμ είναι 0. Οι περισσότεροι πάροχοι πλακιδίων έχουν περίπου 22 μέγιστα επίπεδα ζουμ. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Το πλαίσιο περιορισμού για τη φόρτωση των πλακιδίων. Η χωρική αναφορά Wgs84 θα χρησιμοποιηθεί εάν λείπει. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | Τα πλακίδια ιστού. |


### Method: get_tiles(zoom, extent, tile_size) {#get_tiles_zoom_extent_tile_size_4}


```
 get_tiles(zoom, extent, tile_size) 
```

Φορτώνει πλακίδια με βάση το χωρικό πλαίσιο και το επίπεδο ζουμ.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| zoom | int | Το επίπεδο ζουμ για τη φόρτωση των πλακιδίων. Το υψηλότερο επίπεδο ζουμ είναι 0. Οι περισσότεροι πάροχοι πλακιδίων έχουν περίπου 22 μέγιστα επίπεδα ζουμ. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Το πλαίσιο περιορισμού για τη φόρτωση των πλακιδίων. Η χωρική αναφορά Wgs84 θα χρησιμοποιηθεί εάν λείπει. |
| tile_size | int | Μέγεθος των πλακιδίων, εξ ορισμού είναι 256 (είναι το πρότυπο μέγεθος πλακιδίων). |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | Τα πλακίδια ιστού. |


