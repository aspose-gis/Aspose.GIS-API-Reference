---
title: "FileGdbCoordinatePrecisionGrid klass"
type: docs
weight: 10
url: /sv/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/
---

**Summary:** A coordinate precision grid inside a FileGDB layer.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbCoordinatePrecisionGrid

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid()](#FileGdbCoordinatePrecisionGrid__1) | Initierar en ny instans av klassen FileGdbCoordinatePrecisionGrid |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| m_origin | Nullable<double> | läs/skriv | Hämtar eller anger ursprunget för M-koordinaten. Om den sätts till <see langword="null" /> används standardvärdet. |
| m_scale | Nullable<double> | läs/skriv | Hämtar eller anger skalan för M-koordinaten. Om den sätts till <see langword="null" /> används standardvärdet. |
| x_origin | Nullable<double> | läs/skriv | Hämtar eller anger ursprunget för X-koordinaten. Om den sätts till <see langword=\"null\" /> används standardvärdet. |
| xy_scale | Nullable<double> | läs/skriv | Hämtar eller anger skalan för X- och Y-koordinaterna. Om den sätts till <see langword=\"null\" /> används standardvärdet. |
| y_origin | Nullable<double> | läs/skriv | Hämtar eller anger ursprunget för Y-koordinaten. Om den sätts till <see langword=\"null\" /> används standardvärdet. |
| z_origin | Nullable<double> | läs/skriv | Hämtar eller anger ursprunget för Z-koordinaten. Om den sätts till <see langword=\"null\" /> används standardvärdet. |
| z_scale | Nullable<double> | läs/skriv | Hämtar eller anger skalan för Z-koordinaten. Om den sätts till <see langword=\"null\" /> används standardvärdet. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [create_from_rectangle(p1, p2)](#create_from_rectangle_p1_p2_1) | Skapar en ny <c>FileGdbCoordinatePrecisionGrid</c> så att alla värden inom en rektangel kan representeras. |


### Constructor: FileGdbCoordinatePrecisionGrid() {#FileGdbCoordinatePrecisionGrid__1}


```
 FileGdbCoordinatePrecisionGrid() 
```

Initierar en ny instans av klassen FileGdbCoordinatePrecisionGrid

### Method: create_from_rectangle(p1, p2)  [static] {#create_from_rectangle_p1_p2_1}


```
 create_from_rectangle(p1, p2) 
```

Skapar en ny <c>FileGdbCoordinatePrecisionGrid</c> så att alla värden inom en rektangel kan representeras.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| p1 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Ett hörn av rektangeln. |
| p2 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Motsatt hörn av rektangeln. Måste ha samma dimensioner som <paramref name=\"p1\" />. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid](/psd/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid) | Den <c>FileGdbCoordinatePrecisionGrid</c> så att alla värden inom en rektangel kan representeras.<br/>            Värden utanför rektangeln kan inte representeras, så alla koordinater som kommer att skrivas till FileGDB-lagret<br/>            måste ligga inom rektangeln. |


