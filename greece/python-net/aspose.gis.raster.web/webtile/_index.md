---
title: "WebTile Κλάση"
type: docs
weight: 10
url: /el/python-net/aspose.gis.raster.web/webtile/
---

**Summary:** Abstract Web Tile Model.

**Module:** [aspose.gis.raster.web](/psd/python-net/aspose.gis.raster.web/)

**Full Name:** aspose.gis.raster.web.WebTile

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cell_x | int | r | Η στήλη X ενός πλακιδίου. |
| cell_y | int | r | Η γραμμή Y ενός πλακιδίου. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [as_binary()](#as_binary__1) | Επιστρέφει τη σειρά byte της εικόνας |
| [as_path()](#as_path__2) | Παρουσιάζει το περιεχόμενο του πλακιδίου ως URL ή διαδρομή προς ένα αρχείο. |
| [as_raster()](#as_raster__3) | Παρουσιάζει το περιεχόμενο του πλακιδίου ως στρώση Raster. |
| [get_extent()](#get_extent__4) | Παρουσιάζει το χωρικό εύρος αυτού του στρώματος. |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

Επιστρέφει τη σειρά byte της εικόνας

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| byte | Ακολουθία byte |


### Method: as_path() {#as_path__2}


```
 as_path() 
```

Παρουσιάζει το περιεχόμενο του πλακιδίου ως URL ή διαδρομή προς ένα αρχείο.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string | Url ή Διαδρομή σε αρχείο |


### Method: as_raster() {#as_raster__3}


```
 as_raster() 
```

Παρουσιάζει το περιεχόμενο του πλακιδίου ως στρώση Raster.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Το Raster. |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

Παρουσιάζει το χωρικό εύρος αυτού του στρώματος.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Μια χωρική έκταση αυτού του επιπέδου. |


