---
title: "MapTransform 类"
type: docs
weight: 70
url: /zh/python-net/aspose.gis.common.formats.mapinfo.tabformat.map/maptransform/
---

**Summary:** 

**Module:** [aspose.gis.common.formats.mapinfo.tabformat.map](/psd/python-net/aspose.gis.common.formats.mapinfo.tabformat.map/)

**Full Name:** aspose.gis.common.formats.mapinfo.tabformat.map.MapTransform

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [MapTransform(x_displacement, y_displacement, x_scale, y_scale, coordinates_origin_quadrant)](#MapTransform_x_displacement_y_displacement_x_scale_y_scale_coordinates_origin_quadrant_1) | 初始化 MapTransform 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| coordinates_origin_quadrant | [Quadrant](/psd/python-net/aspose.gis.common/quadrant) | r |    |
| coordinates_origin_quadrant_byte | byte | r |  |
| x_displacement | double | r |  |
| x_scale | double | r |  |
| y_displacement | double | r |  |
| y_scale | double | r |  |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [apply(ix, iy)](#apply_ix_iy_1) |    |
| to_int_coordinate(coordinate, n_x, n_y) |  |


### Constructor: MapTransform(x_displacement, y_displacement, x_scale, y_scale, coordinates_origin_quadrant) {#MapTransform_x_displacement_y_displacement_x_scale_y_scale_coordinates_origin_quadrant_1}


```
 MapTransform(x_displacement, y_displacement, x_scale, y_scale, coordinates_origin_quadrant) 
```

初始化 MapTransform 类的新实例

**Parameters:**

| 参数 | 类型 | 描述 |
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

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| ix | int |  |
| iy | int |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


