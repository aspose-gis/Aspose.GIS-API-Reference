---
title: "FileGdbCoordinatePrecisionGrid classe"
type: docs
weight: 10
url: /fr/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/
---

**Summary:** A coordinate precision grid inside a FileGDB layer.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbCoordinatePrecisionGrid

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid()](#FileGdbCoordinatePrecisionGrid__1) | Initialise une nouvelle instance de la classe FileGdbCoordinatePrecisionGrid |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| m_origin | Nullable<double> | r/w | Obtient ou définit l'origine de la coordonnée M. Si elle est définie sur <see langword="null" /> la valeur par défaut est utilisée. |
| m_scale | Nullable<double> | r/w | Obtient ou définit l'échelle de la coordonnée M. Si elle est définie sur <see langword="null" /> la valeur par défaut est utilisée. |
| x_origin | Nullable<double> | r/w | Obtient ou définit l'origine de la coordonnée X. Si elle est définie sur <see langword="null" /> la valeur par défaut est utilisée. |
| xy_scale | Nullable<double> | r/w | Obtient ou définit l'échelle des coordonnées X et Y. Si elle est définie sur <see langword="null" /> la valeur par défaut est utilisée. |
| y_origin | Nullable<double> | r/w | Obtient ou définit l'origine de la coordonnée Y. Si elle est définie sur <see langword="null" /> la valeur par défaut est utilisée. |
| z_origin | Nullable<double> | r/w | Obtient ou définit l'origine de la coordonnée Z. Si elle est définie sur <see langword="null" /> la valeur par défaut est utilisée. |
| z_scale | Nullable<double> | r/w | Obtient ou définit l'échelle de la coordonnée Z. Si elle est définie sur <see langword="null" /> la valeur par défaut est utilisée. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_rectangle(p1, p2)](#create_from_rectangle_p1_p2_1) | Crée un nouveau <c>FileGdbCoordinatePrecisionGrid</c> de sorte que toutes les valeurs à l'intérieur d'un rectangle soient représentables. |


### Constructor: FileGdbCoordinatePrecisionGrid() {#FileGdbCoordinatePrecisionGrid__1}


```
 FileGdbCoordinatePrecisionGrid() 
```

Initialise une nouvelle instance de la classe FileGdbCoordinatePrecisionGrid

### Method: create_from_rectangle(p1, p2)  [static] {#create_from_rectangle_p1_p2_1}


```
 create_from_rectangle(p1, p2) 
```

Crée un nouveau <c>FileGdbCoordinatePrecisionGrid</c> de sorte que toutes les valeurs à l'intérieur d'un rectangle soient représentables.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| p1 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Un coin du rectangle. |
| p2 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Coin opposé du rectangle. Doit avoir les mêmes dimensions que <paramref name="p1" />. |

**Returns**

| Type | Description |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid](/psd/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid) | Le <c>FileGdbCoordinatePrecisionGrid</c> de sorte que toutes les valeurs à l'intérieur d'un rectangle soient représentables.<br/>            Les valeurs en dehors du rectangle ne sont pas représentables, donc toutes les coordonnées qui seront écrites dans la couche FileGDB<br/>            doivent être à l'intérieur du rectangle. |


