---
title: "MapTransform Klasse"
type: docs
weight: 70
url: /de/python-net/aspose.gis.common.formats.mapinfo.tabformat.map/maptransform/
---

**Summary:** 

**Module:** [aspose.gis.common.formats.mapinfo.tabformat.map](/psd/python-net/aspose.gis.common.formats.mapinfo.tabformat.map/)

**Full Name:** aspose.gis.common.formats.mapinfo.tabformat.map.MapTransform

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [MapTransform(x_displacement, y_displacement, x_scale, y_scale, coordinates_origin_quadrant)](#MapTransform_x_displacement_y_displacement_x_scale_y_scale_coordinates_origin_quadrant_1) | Initialisiert eine neue Instanz der MapTransform-Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| coordinates_origin_quadrant | [Quadrant](/psd/python-net/aspose.gis.common/quadrant) | r |    |
| koordinaten_ursprung_quadrant_byte | byte | r |  |
| x_verschiebung | double | r |  |
| x_scale | double | r |  |
| y_verschiebung | double | r |  |
| y_scale | double | r |  |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [apply(ix, iy)](#apply_ix_iy_1) |    |
| to_int_coordinate(coordinate, n_x, n_y) |  |


### Constructor: MapTransform(x_displacement, y_displacement, x_scale, y_scale, coordinates_origin_quadrant) {#MapTransform_x_displacement_y_displacement_x_scale_y_scale_coordinates_origin_quadrant_1}


```
 MapTransform(x_displacement, y_displacement, x_scale, y_scale, coordinates_origin_quadrant) 
```

Initialisiert eine neue Instanz der MapTransform-Klasse

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x_verschiebung | double |  |
| y_verschiebung | double |  |
| x_scale | double |  |
| y_scale | double |  |
| coordinates_origin_quadrant | [Quadrant](/psd/python-net/aspose.gis.common/quadrant) |  |

### Method: apply(ix, iy) {#apply_ix_iy_1}


```
 apply(ix, iy) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| ix | int |  |
| iy | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


