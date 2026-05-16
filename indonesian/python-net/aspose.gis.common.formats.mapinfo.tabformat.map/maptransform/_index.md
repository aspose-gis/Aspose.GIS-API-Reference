---
title: "MapTransform Kelas"
type: docs
weight: 70
url: /id/python-net/aspose.gis.common.formats.mapinfo.tabformat.map/maptransform/
---

**Summary:** 

**Module:** [aspose.gis.common.formats.mapinfo.tabformat.map](/psd/python-net/aspose.gis.common.formats.mapinfo.tabformat.map/)

**Full Name:** aspose.gis.common.formats.mapinfo.tabformat.map.MapTransform

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [MapTransform(x_displacement, y_displacement, x_scale, y_scale, coordinates_origin_quadrant)](#MapTransform_x_displacement_y_displacement_x_scale_y_scale_coordinates_origin_quadrant_1) | Menginisialisasi sebuah instance baru dari kelas MapTransform |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| coordinates_origin_quadrant | [Quadrant](/psd/python-net/aspose.gis.common/quadrant) | r |    |
| coordinates_origin_quadrant_byte | byte | r |  |
| x_displacement | double | r |  |
| x_scale | double | r |  |
| y_displacement | double | r |  |
| y_scale | double | r |  |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [apply(ix, iy)](#apply_ix_iy_1) |    |
| to_int_coordinate(coordinate, n_x, n_y) |  |


### Constructor: MapTransform(x_displacement, y_displacement, x_scale, y_scale, coordinates_origin_quadrant) {#MapTransform_x_displacement_y_displacement_x_scale_y_scale_coordinates_origin_quadrant_1}


```
 MapTransform(x_displacement, y_displacement, x_scale, y_scale, coordinates_origin_quadrant) 
```

Menginisialisasi sebuah instance baru dari kelas MapTransform

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x_displacement | double |  |
| y_displacement | double |  |
| x_scale | double |  |
| y_scale | double |  |
| coordinates_origin_quadrant | [Quadrant](/psd/python-net/aspose.gis.common/quadrant) |  |

### Method: apply(ix, iy) {#apply_ix_iy_1}


```
 apply(ix, iy) 
```

  

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| ix | int |  |
| iy | int |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


