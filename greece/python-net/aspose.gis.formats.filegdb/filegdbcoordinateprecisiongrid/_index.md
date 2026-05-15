---
title: "FileGdbCoordinatePrecisionGrid Κλάση"
type: docs
weight: 10
url: /el/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/
---

**Summary:** A coordinate precision grid inside a FileGDB layer.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbCoordinatePrecisionGrid

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid()](#FileGdbCoordinatePrecisionGrid__1) | Αρχικοποιεί μια νέα παρουσία της κλάσης FileGdbCoordinatePrecisionGrid |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| m_origin | Nullable<double> | r/w | Λαμβάνει ή ορίζει την προέλευση του συντεταγμένου M. Εάν οριστεί σε <see langword=\"null\" /> η προεπιλογή χρησιμοποιείται. |
| m_scale | Nullable<double> | r/w | Λαμβάνει ή ορίζει την κλίμακα του συντεταγμένου M. Εάν οριστεί σε <see langword=\"null\" /> η προεπιλογή χρησιμοποιείται. |
| x_origin | Nullable<double> | r/w | Λαμβάνει ή ορίζει την αρχή της συντεταγμένης X. Εάν οριστεί σε <see langword=\"null\" />, χρησιμοποιείται η προεπιλογή. |
| xy_scale | Nullable<double> | r/w | Λαμβάνει ή ορίζει την κλίμακα των συντεταγμένων X και Y. Εάν οριστεί σε <see langword=\"null\" />, χρησιμοποιείται η προεπιλογή. |
| y_origin | Nullable<double> | r/w | Λαμβάνει ή ορίζει την αρχή της συντεταγμένης Y. Εάν οριστεί σε <see langword=\"null\" />, χρησιμοποιείται η προεπιλογή. |
| z_origin | Nullable<double> | r/w | Λαμβάνει ή ορίζει την αρχή της συντεταγμένης Z. Εάν οριστεί σε <see langword=\"null\" />, χρησιμοποιείται η προεπιλογή. |
| z_scale | Nullable<double> | r/w | Λαμβάνει ή ορίζει την κλίμακα της συντεταγμένης Z. Εάν οριστεί σε <see langword=\"null\" />, χρησιμοποιείται η προεπιλογή. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_rectangle(p1, p2)](#create_from_rectangle_p1_p2_1) | Δημιουργεί νέο <c>FileGdbCoordinatePrecisionGrid</c> έτσι ώστε όλες οι τιμές μέσα σε ένα ορθογώνιο να είναι αναπαραγώγιμες. |


### Constructor: FileGdbCoordinatePrecisionGrid() {#FileGdbCoordinatePrecisionGrid__1}


```
 FileGdbCoordinatePrecisionGrid() 
```

Αρχικοποιεί μια νέα παρουσία της κλάσης FileGdbCoordinatePrecisionGrid

### Method: create_from_rectangle(p1, p2)  [static] {#create_from_rectangle_p1_p2_1}


```
 create_from_rectangle(p1, p2) 
```

Δημιουργεί νέο <c>FileGdbCoordinatePrecisionGrid</c> έτσι ώστε όλες οι τιμές μέσα σε ένα ορθογώνιο να είναι αναπαραγώγιμες.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| p1 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Μία γωνία του ορθογωνίου. |
| p2 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Αντίθετη γωνία του ορθογωνίου. Πρέπει να έχει τις ίδιες διαστάσεις με <paramref name=\"p1\" />. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid](/psd/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid) | Το <c>FileGdbCoordinatePrecisionGrid</c> έτσι ώστε όλες οι τιμές μέσα σε ένα ορθογώνιο να είναι αναπαραγώγιμες.<br/>            Οι τιμές εκτός του ορθογωνίου δεν είναι αναπαραγώγιμες, έτσι όλες οι συντεταγμένες που θα γραφούν στο επίπεδο FileGDB<br/>            πρέπει να βρίσκονται μέσα στο ορθογώνιο. |


