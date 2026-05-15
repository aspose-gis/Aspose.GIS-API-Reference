---
title: "FileGdbCoordinatePrecisionGrid Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/
---

**Summary:** A coordinate precision grid inside a FileGDB layer.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbCoordinatePrecisionGrid

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid()](#FileGdbCoordinatePrecisionGrid__1) | Initialisiert eine neue Instanz der FileGdbCoordinatePrecisionGrid-Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| m_origin | Nullable<double> | r/w | Liest oder setzt den Ursprung der M-Koordinate. Wenn auf <see langword=\"null\" /> gesetzt, wird der Standardwert verwendet. |
| m_scale | Nullable<double> | r/w | Liest oder setzt die Skalierung der M-Koordinate. Wenn auf <see langword=\"null\" /> gesetzt, wird der Standardwert verwendet. |
| x_origin | Nullable<double> | r/w | Liest oder setzt den Ursprung der X-Koordinate. Wenn auf <see langword="null" /> gesetzt, wird der Standardwert verwendet. |
| xy_scale | Nullable<double> | r/w | Liest oder setzt den Maßstab von X- und Y-Koordinaten. Wenn auf <see langword="null" /> gesetzt, wird der Standardwert verwendet. |
| y_origin | Nullable<double> | r/w | Liest oder setzt den Ursprung der Y-Koordinate. Wenn auf <see langword="null" /> gesetzt, wird der Standardwert verwendet. |
| z_origin | Nullable<double> | r/w | Liest oder setzt den Ursprung der Z-Koordinate. Wenn auf <see langword="null" /> gesetzt, wird der Standardwert verwendet. |
| z_scale | Nullable<double> | r/w | Liest oder setzt den Maßstab der Z-Koordinate. Wenn auf <see langword="null" /> gesetzt, wird der Standardwert verwendet. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [create_from_rectangle(p1, p2)](#create_from_rectangle_p1_p2_1) | Erstellt ein neues <c>FileGdbCoordinatePrecisionGrid</c>, sodass alle Werte innerhalb eines Rechtecks darstellbar sind. |


### Constructor: FileGdbCoordinatePrecisionGrid() {#FileGdbCoordinatePrecisionGrid__1}


```
 FileGdbCoordinatePrecisionGrid() 
```

Initialisiert eine neue Instanz der FileGdbCoordinatePrecisionGrid-Klasse

### Method: create_from_rectangle(p1, p2)  [static] {#create_from_rectangle_p1_p2_1}


```
 create_from_rectangle(p1, p2) 
```

Erstellt ein neues <c>FileGdbCoordinatePrecisionGrid</c>, sodass alle Werte innerhalb eines Rechtecks darstellbar sind.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| p1 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Eine Ecke des Rechtecks. |
| p2 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Gegenüberliegende Ecke des Rechtecks. Muss dieselben Abmessungen wie <paramref name="p1" /> haben. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid](/psd/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid) | Das <c>FileGdbCoordinatePrecisionGrid</c>, sodass alle Werte innerhalb eines Rechtecks darstellbar sind.<br/>            Werte außerhalb des Rechtecks sind nicht darstellbar, daher müssen alle Koordinaten, die in das FileGDB-Layer geschrieben werden,<br/>            innerhalb des Rechtecks liegen. |


