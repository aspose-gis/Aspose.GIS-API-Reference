---
title: "Extent 类"
type: docs
weight: 820
url: /zh/python-net/aspose.gis/extent/
---

**Summary:** A two-dimensional spatial bounding box.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Extent

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [Extent()](#Extent__1) | 创建新实例。 |
| [Extent(srs)](#Extent_srs_2) | 创建新实例。 |
| [Extent(x_min, y_min, x_max, y_max, srs)](#Extent_x_min_y_min_x_max_y_max_srs_3) | 创建新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| center | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | r | 范围的中心。 |
| height | double | r | 范围的高度。 |
| is_valid | bool | r | 确定此 [Extent](/psd/python-net/aspose.gis/extent/) 是否有效。 |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) 与此范围关联。<br/>如果 [Extent.spatial_reference_system](/psd/python-net/aspose.gis/extent/) 未知，则可以为 <see langword="null" />。<br/>使用 Aspose.Gis.Extent.GetTransformed(Aspose.Gis.SpatialReferencing.SpatialReferenceSystem)<br/>以在不同空间参考系统之间转换范围。 |
| width | double | r | 范围的宽度。 |
| x_max | double | r/w | X 坐标的最大值。 |
| x_min | double | r/w | X 坐标的最小值。 |
| y_max | double | r/w | Y 坐标的最大值。 |
| y_min | double | r/w | Y 坐标的最小值。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 克隆此实例。 |
| [contains(extent)](#contains_extent_2) | 确定此范围是否包含参数。 |
| [contains(geometry)](#contains_geometry_3) | 确定此范围是否包含参数。 |
| [contains(x, y)](#contains_x_y_4) | 确定此范围是否包含由参数定义的坐标。 |
| [get_transformed(target_srs)](#get_transformed_target_srs_5) | 返回在指定的 [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) 中包含此范围的新范围。 |
| [grow(extent)](#grow_extent_6) | 扩展此范围以包含参数。 |
| [grow(x, y)](#grow_x_y_7) | 扩展此范围以包含指定的点。 |
| [grow_x(value)](#grow_x_value_8) | 沿 X 轴扩展此范围，使其包含指定的值。 |
| [grow_y(value)](#grow_y_value_9) | 沿 Y 轴扩展此范围，使其包含指定的值。 |
| [intersects(extent)](#intersects_extent_10) | 确定此范围是否与参数相交。 |
| [intersects(geometry)](#intersects_geometry_11) | 确定此范围是否与参数相交。 |
| normalize() | 如果 [Extent.width](/psd/python-net/aspose.gis/extent/) 为负，则交换 [Extent.x_min](/psd/python-net/aspose.gis/extent/) 与 [Extent.x_max](/psd/python-net/aspose.gis/extent/)，并且<br/>            如果 [Extent.height](/psd/python-net/aspose.gis/extent/) 为负，则交换 [Extent.y_min](/psd/python-net/aspose.gis/extent/) 与 [Extent.y_max](/psd/python-net/aspose.gis/extent/)。 |
| [to_polygon()](#to_polygon__12) | 将此范围转换为表示它的矩形多边形。 |


### Constructor: Extent() {#Extent__1}


```
 Extent() 
```

创建新实例。

### Constructor: Extent(srs) {#Extent_srs_2}


```
 Extent(srs) 
```

创建新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) 与此范围关联。<br/>            可以为 <see langword=\"null\" />，表示 SRS 未知。 |

### Constructor: Extent(x_min, y_min, x_max, y_max, srs) {#Extent_x_min_y_min_x_max_y_max_srs_3}


```
 Extent(x_min, y_min, x_max, y_max, srs) 
```

创建新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x_min | double | X 的最小值。 |
| y_min | double | Y 的最小值。 |
| x_max | double | X 的最大值。 |
| y_max | double | Y 的最大值。 |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) 与此范围关联。<br/>            可以为 <see langword=\"null\" />，表示 SRS 未知。 |

### Method: clone() {#clone__1}


```
 clone() 
```

克隆此实例。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | 此实例的克隆。 |


### Method: contains(extent) {#contains_extent_2}


```
 contains(extent) 
```

确定此范围是否包含参数。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 另一个范围。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 值，指示此范围是否包含参数。 |


### Method: contains(geometry) {#contains_geometry_3}


```
 contains(geometry) 
```

确定此范围是否包含参数。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 用于测试包含性的几何体。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 值，指示此范围是否包含参数。 |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

确定此范围是否包含由参数定义的坐标。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | double | 坐标的 X。 |
| y | double | 坐标的 Y。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 值，指示坐标是否在边界框内。 |


### Method: get_transformed(target_srs) {#get_transformed_target_srs_5}


```
 get_transformed(target_srs) 
```

返回在指定的 [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) 中包含此范围的新范围。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 要转换到的 [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | 此范围转换到指定 SRS 的结果。 |


### Method: grow(extent) {#grow_extent_6}


```
 grow(extent) 
```

扩展此范围以包含参数。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 其他范围。 |

### Method: grow(x, y) {#grow_x_y_7}


```
 grow(x, y) 
```

扩展此范围以包含指定的点。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| x | double | 要包含的 X 坐标。 |
| y | double | 要包含的 Y 坐标。 |

### Method: grow_x(value) {#grow_x_value_8}


```
 grow_x(value) 
```

沿 X 轴扩展此范围，使其包含指定的值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | double | 要包含的值。 |

### Method: grow_y(value) {#grow_y_value_9}


```
 grow_y(value) 
```

沿 Y 轴扩展此范围，使其包含指定的值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | double | 要包含的值。 |

### Method: intersects(extent) {#intersects_extent_10}


```
 intersects(extent) 
```

确定此范围是否与参数相交。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 另一个范围。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 值，指示此范围是否与参数相交。 |


### Method: intersects(geometry) {#intersects_geometry_11}


```
 intersects(geometry) 
```

确定此范围是否与参数相交。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 用于测试相交的几何体 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 值，指示此范围是否与参数相交。 |


### Method: to_polygon() {#to_polygon__12}


```
 to_polygon() 
```

将此范围转换为表示它的矩形多边形。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | 表示此范围的矩形[Polygon](/psd/python-net/aspose.gis.geometries/polygon/)。对于无效范围<br/>            将返回空多边形。 |


