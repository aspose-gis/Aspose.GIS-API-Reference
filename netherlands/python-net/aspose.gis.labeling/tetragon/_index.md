---
title: "Tetragon Klasse"
type: docs
weight: 190
url: /nl/python-net/aspose.gis.labeling/tetragon/
---

**Summary:** 

**Module:** [aspose.gis.labeling](/psd/python-net/aspose.gis.labeling/)

**Full Name:** aspose.gis.labeling.Tetragon

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [Tetragon()](#Tetragon__1) | Initialiseert een nieuw exemplaar van de Tetragon klasse |
| [Tetragon(rectangle, angle)](#Tetragon_rectangle_angle_2) | Initialiseert een nieuw exemplaar van de Tetragon klasse |
| [Tetragon(x, y, width, height, angle)](#Tetragon_x_y_width_height_angle_3) | Initialiseert een nieuw exemplaar van de Tetragon klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| hoek | double | r |  |
| bounding_rectangle | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle/) | r |    |
| c0 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
| c1 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
| c2 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
| c3 | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) | r |    |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [intersects(tetragon)](#intersects_tetragon_1) |    |
| [translate(delta)](#translate_delta_2) |    |


### Constructor: Tetragon() {#Tetragon__1}


```
 Tetragon() 
```

Initialiseert een nieuw exemplaar van de Tetragon klasse

### Constructor: Tetragon(rectangle, angle) {#Tetragon_rectangle_angle_2}


```
 Tetragon(rectangle, angle) 
```

Initialiseert een nieuw exemplaar van de Tetragon klasse

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rectangle | [Rectangle](/psd/python-net/aspose.gis.common/rectangle/) |  |
| hoek | double |  |

### Constructor: Tetragon(x, y, width, height, angle) {#Tetragon_x_y_width_height_angle_3}


```
 Tetragon(x, y, width, height, angle) 
```

Initialiseert een nieuw exemplaar van de Tetragon klasse

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | double |  |
| y | double |  |
| width | double |  |
| hoogte | double |  |
| hoek | double |  |

### Method: intersects(tetragon) {#intersects_tetragon_1}


```
 intersects(tetragon) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| tetragon | [Tetragon](/psd/python-net/aspose.gis.labeling/tetragon) |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool |  |


### Method: translate(delta) {#translate_delta_2}


```
 translate(delta) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| delta | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Tetragon](/psd/python-net/aspose.gis.labeling/tetragon) |  |


