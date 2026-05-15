---
title: "Tetragon Klasse"
type: docs
weight: 190
url: /de/python-net/aspose.gis.labeling/tetragon/
---

**Summary:** 

**Module:** [aspose.gis.labeling](/psd/python-net/aspose.gis.labeling/)

**Full Name:** aspose.gis.labeling.Tetragon

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [Tetragon()](#Tetragon__1) | Initialisiert eine neue Instanz der Tetragon Klasse |
| [Tetragon(rectangle, angle)](#Tetragon_rectangle_angle_2) | Initialisiert eine neue Instanz der Tetragon Klasse |
| [Tetragon(x, y, width, height, angle)](#Tetragon_x_y_width_height_angle_3) | Initialisiert eine neue Instanz der Tetragon Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| Winkel | double | r |  |
| bounding_rectangle | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle/) | r |    |
| c0 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
| c1 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
| c2 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
| c3 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [intersects(tetragon)](#intersects_tetragon_1) |    |
| [translate(delta)](#translate_delta_2) |    |


### Constructor: Tetragon() {#Tetragon__1}


```
 Tetragon() 
```

Initialisiert eine neue Instanz der Tetragon Klasse

### Constructor: Tetragon(rectangle, angle) {#Tetragon_rectangle_angle_2}


```
 Tetragon(rectangle, angle) 
```

Initialisiert eine neue Instanz der Tetragon Klasse

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.gis.common/rectangle/) |  |
| Winkel | double |  |

### Constructor: Tetragon(x, y, width, height, angle) {#Tetragon_x_y_width_height_angle_3}


```
 Tetragon(x, y, width, height, angle) 
```

Initialisiert eine neue Instanz der Tetragon Klasse

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | double |  |
| y | double |  |
| width | double |  |
| Höhe | double |  |
| Winkel | double |  |

### Method: intersects(tetragon) {#intersects_tetragon_1}


```
 intersects(tetragon) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| tetragon | [Tetragon](/psd/python-net/aspose.gis.labeling/tetragon) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool |  |


### Method: translate(delta) {#translate_delta_2}


```
 translate(delta) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| delta | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Tetragon](/psd/python-net/aspose.gis.labeling/tetragon) |  |


