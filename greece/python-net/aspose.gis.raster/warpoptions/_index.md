---
title: "WarpOptions Κλάση"
type: docs
weight: 100
url: /el/python-net/aspose.gis.raster/warpoptions/
---

**Summary:** Options for raster warping.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.WarpOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WarpOptions()](#WarpOptions__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης WarpOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cell_height | double | r/w | Καθορίζει νέο ύψος του κελιού raster (σε μονάδες γεωαναφοράς στόχου).<br/>            Εάν η τιμή οριστεί σε 0, το [WarpOptions.cell_height](/psd/python-net/aspose.gis.raster/warpoptions/) υπολογίζεται αυτόματα. Η προεπιλεγμένη τιμή είναι "0". |
| cell_width | double | r/w | Καθορίζει νέο πλάτος του κελιού raster (σε μονάδες γεωαναφοράς στόχου).<br/>            Εάν η τιμή οριστεί σε 0, το [WarpOptions.cell_width](/psd/python-net/aspose.gis.raster/warpoptions/) υπολογίζεται αυτόματα. Η προεπιλεγμένη τιμή είναι "0". |
| default_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Καθορίζει μια τιμή για την πηγή χωρικής αναφοράς εάν αυτή λείπει. |
| ύψος | int | r/w | Καθορίζει το ύψος εξόδου raster σε εικονοστοιχεία και στήλες.<br/>            Εάν η τιμή οριστεί σε 0, το ύψος υπολογίζεται αυτόματα. Η προεπιλεγμένη τιμή είναι "0". |
| target_extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | Καθορίζει τα όρια του στρώματος raster για παραμόρφωση.<br/>            Εάν οριστεί σε <see langword="null" />, η έκταση υπολογίζεται κατά τη διάρκεια της παραμόρφωσης ώστε να περιλαμβάνει όλα τα κελιά από το raster. |
| target_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Καθορίζει την στοχευμένη χωρική αναφορά.<br/>            Εάν οριστεί σε <see langword="null" />, χρησιμοποιείται η προεπιλεγμένη ή η πηγή χωρικής αναφοράς. |
| width | int | r/w | Καθορίζει το πλάτος εξόδου raster σε εικονοστοιχεία και στήλες.<br/>            Εάν η τιμή οριστεί σε 0, το πλάτος υπολογίζεται αυτόματα. Η προεπιλεγμένη τιμή είναι "0". |


### Constructor: WarpOptions() {#WarpOptions__1}


```
 WarpOptions() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης WarpOptions

