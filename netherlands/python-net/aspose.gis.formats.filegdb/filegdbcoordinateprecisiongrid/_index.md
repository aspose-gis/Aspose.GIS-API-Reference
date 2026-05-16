---
title: "FileGdbCoordinatePrecisionGrid-klasse"
type: docs
weight: 10
url: /nl/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/
---

**Summary:** A coordinate precision grid inside a FileGDB layer.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbCoordinatePrecisionGrid

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid()](#FileGdbCoordinatePrecisionGrid__1) | Initialiseert een nieuw exemplaar van de FileGdbCoordinatePrecisionGrid-klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| m_origin | Nullable<double> | r/w | Haalt de oorsprong van de M-coördinaat op of stelt deze in. Als ingesteld op <see langword=\"null\" /> wordt de standaardwaarde gebruikt. |
| m_scale | Nullable<double> | r/w | Haalt de schaal van de M-coördinaat op of stelt deze in. Als ingesteld op <see langword=\"null\" /> wordt de standaardwaarde gebruikt. |
| x_origin | Nullable<double> | r/w | Haalt de oorsprong van de X-coördinaat op of stelt deze in. Als ingesteld op <see langword="null" /> wordt de standaardwaarde gebruikt. |
| xy_scale | Nullable<double> | r/w | Haalt de schaal van X- en Y-coördinaten op of stelt deze in. Als ingesteld op <see langword="null" /> wordt de standaardwaarde gebruikt. |
| y_origin | Nullable<double> | r/w | Haalt de oorsprong van de Y-coördinaat op of stelt deze in. Als ingesteld op <see langword="null" /> wordt de standaardwaarde gebruikt. |
| z_origin | Nullable<double> | r/w | Haalt de oorsprong van de Z-coördinaat op of stelt deze in. Als ingesteld op <see langword="null" /> wordt de standaardwaarde gebruikt. |
| z_scale | Nullable<double> | r/w | Haalt de schaal van de Z-coördinaat op of stelt deze in. Als ingesteld op <see langword="null" /> wordt de standaardwaarde gebruikt. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [create_from_rectangle(p1, p2)](#create_from_rectangle_p1_p2_1) | Maakt een nieuw <c>FileGdbCoordinatePrecisionGrid</c> aan zodat alle waarden binnen een rechthoek representabel zijn. |


### Constructor: FileGdbCoordinatePrecisionGrid() {#FileGdbCoordinatePrecisionGrid__1}


```
 FileGdbCoordinatePrecisionGrid() 
```

Initialiseert een nieuw exemplaar van de FileGdbCoordinatePrecisionGrid-klasse

### Method: create_from_rectangle(p1, p2)  [static] {#create_from_rectangle_p1_p2_1}


```
 create_from_rectangle(p1, p2) 
```

Maakt een nieuw <c>FileGdbCoordinatePrecisionGrid</c> aan zodat alle waarden binnen een rechthoek representabel zijn.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| p1 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Eén hoek van de rechthoek. |
| p2 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | De tegenoverliggende hoek van de rechthoek. Moet dezelfde afmetingen hebben als <paramref name="p1" />. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid](/psd/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid) | De <c>FileGdbCoordinatePrecisionGrid</c> zodat alle waarden binnen een rechthoek representabel zijn.<br/>            Waarden buiten de rechthoek zijn niet representabel, dus alle coördinaten die naar de FileGDB-laag worden geschreven<br/>            moeten binnen de rechthoek liggen. |


