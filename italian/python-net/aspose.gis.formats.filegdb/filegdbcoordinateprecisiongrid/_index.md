---
title: "Classe FileGdbCoordinatePrecisionGrid"
type: docs
weight: 10
url: /it/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/
---

**Summary:** A coordinate precision grid inside a FileGDB layer.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbCoordinatePrecisionGrid

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid()](#FileGdbCoordinatePrecisionGrid__1) | Inizializza una nuova istanza della classe FileGdbCoordinatePrecisionGrid |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| m_origin | Nullable<double> | r/w | Ottiene o imposta l'origine della coordinata M. Se impostato a <see langword="null" /> viene utilizzato il valore predefinito. |
| m_scale | Nullable<double> | r/w | Ottiene o imposta la scala della coordinata M. Se impostato a <see langword="null" /> viene utilizzato il valore predefinito. |
| x_origin | Nullable<double> | r/w | Ottiene o imposta l'origine della coordinata X. Se impostato su <see langword="null" /> viene utilizzato il valore predefinito. |
| xy_scale | Nullable<double> | r/w | Ottiene o imposta la scala delle coordinate X e Y. Se impostato su <see langword="null" /> viene utilizzato il valore predefinito. |
| y_origin | Nullable<double> | r/w | Ottiene o imposta l'origine della coordinata Y. Se impostato su <see langword="null" /> viene utilizzato il valore predefinito. |
| z_origin | Nullable<double> | r/w | Ottiene o imposta l'origine della coordinata Z. Se impostato su <see langword="null" /> viene utilizzato il valore predefinito. |
| z_scale | Nullable<double> | r/w | Ottiene o imposta la scala della coordinata Z. Se impostato su <see langword="null" /> viene utilizzato il valore predefinito. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [create_from_rectangle(p1, p2)](#create_from_rectangle_p1_p2_1) | Crea un nuovo <c>FileGdbCoordinatePrecisionGrid</c> in modo che tutti i valori all'interno di un rettangolo siano rappresentabili. |


### Constructor: FileGdbCoordinatePrecisionGrid() {#FileGdbCoordinatePrecisionGrid__1}


```
 FileGdbCoordinatePrecisionGrid() 
```

Inizializza una nuova istanza della classe FileGdbCoordinatePrecisionGrid

### Method: create_from_rectangle(p1, p2)  [static] {#create_from_rectangle_p1_p2_1}


```
 create_from_rectangle(p1, p2) 
```

Crea un nuovo <c>FileGdbCoordinatePrecisionGrid</c> in modo che tutti i valori all'interno di un rettangolo siano rappresentabili.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| p1 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Un angolo del rettangolo. |
| p2 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Angolo opposto del rettangolo. Deve avere le stesse dimensioni di <paramref name="p1" />. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid](/psd/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid) | Il <c>FileGdbCoordinatePrecisionGrid</c> in modo che tutti i valori all'interno di un rettangolo siano rappresentabili.<br/>            I valori al di fuori del rettangolo non sono rappresentabili, quindi tutte le coordinate che saranno scritte nel layer FileGDB<br/>            devono trovarsi all'interno del rettangolo. |


