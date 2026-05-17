---
title: "MapTransform-klass"
type: docs
weight: 70
url: /sv/python-net/aspose.gis.common.formats.mapinfo.tabformat.map/maptransform/
---

**Summary:** 

**Module:** [aspose.gis.common.formats.mapinfo.tabformat.map](/psd/python-net/aspose.gis.common.formats.mapinfo.tabformat.map/)

**Full Name:** aspose.gis.common.formats.mapinfo.tabformat.map.MapTransform

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [MapTransform(x_displacement, y_displacement, x_scale, y_scale, coordinates_origin_quadrant)](#MapTransform_x_displacement_y_displacement_x_scale_y_scale_coordinates_origin_quadrant_1) | Initierar en ny instans av MapTransform-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| coordinates_origin_quadrant | [Quadrant](/psd/python-net/aspose.gis.common/quadrant) | r |    |
| koordinater_ursprung_kvadrant_byte | byte | r |  |
| x_förskjutning | double | r |  |
| x_scale | double | r |  |
| y_förskjutning | double | r |  |
| y_scale | double | r |  |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [apply(ix, iy)](#apply_ix_iy_1) |    |
| to_int_coordinate(coordinate, n_x, n_y) |  |


### Constructor: MapTransform(x_displacement, y_displacement, x_scale, y_scale, coordinates_origin_quadrant) {#MapTransform_x_displacement_y_displacement_x_scale_y_scale_coordinates_origin_quadrant_1}


```
 MapTransform(x_displacement, y_displacement, x_scale, y_scale, coordinates_origin_quadrant) 
```

Initierar en ny instans av MapTransform-klassen

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x_förskjutning | double |  |
| y_förskjutning | double |  |
| x_scale | double |  |
| y_scale | double |  |
| coordinates_origin_quadrant | [Quadrant](/psd/python-net/aspose.gis.common/quadrant) |  |

### Method: apply(ix, iy) {#apply_ix_iy_1}


```
 apply(ix, iy) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ix | int |  |
| iy | int |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


