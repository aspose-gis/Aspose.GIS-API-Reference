---
title: "Measurement 类"
type: docs
weight: 150
url: /zh/python-net/aspose.gis.rendering/measurement/
---

**Summary:** A number that indicates a render measurement.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.Measurement

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Measurement()](#Measurement__1) | 初始化 Measurement 类的新实例 |
| [Measurement(value, unit)](#Measurement_value_unit_2) | 创建新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | 计量单位。 |
| value | double | r | 指示测量长度的数值。 |
| zero [static] | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r | 零长度的测量。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [inches(value)](#inches_value_1) | 返回一个新的 <c>Measurement</c> 实例，表示英寸长度。 |
| [map_units(value)](#map_units_value_2) | 返回一个新的 <c>Measurement</c> 实例，表示地图空间参考单位的长度。 |
| [meters_on_earth(value)](#meters_on_earth_value_3) | 返回一个新的 <c>Measurement</c> 实例，表示地球上的米长度。 |
| [millimeters(value)](#millimeters_value_4) | 返回一个新的 <c>Measurement</c> 实例，表示毫米长度。 |
| [pixels(value)](#pixels_value_5) | 返回一个新的 <c>Measurement</c> 实例，表示像素长度。 |
| [points(value)](#points_value_6) | 返回一个新的 <c>Measurement</c> 实例，表示点长度。 |


### Constructor: Measurement() {#Measurement__1}


```
 Measurement() 
```

初始化 Measurement 类的新实例

### Constructor: Measurement(value, unit) {#Measurement_value_unit_2}


```
 Measurement(value, unit) 
```

创建新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | double | 指示测量长度的数值。 |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | 计量单位。 |

### Method: inches(value)  [static] {#inches_value_1}


```
 inches(value) 
```

返回一个新的 <c>Measurement</c> 实例，表示英寸长度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | double | 英寸数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | 新的 <c>Measurement</c> 类实例。 |


### Method: map_units(value)  [static] {#map_units_value_2}


```
 map_units(value) 
```

返回一个新的 <c>Measurement</c> 实例，表示地图空间参考单位的长度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | double | 单位数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | 新的 <c>Measurement</c> 类实例。 |


### Method: meters_on_earth(value)  [static] {#meters_on_earth_value_3}


```
 meters_on_earth(value) 
```

返回一个新的 <c>Measurement</c> 实例，表示地球上的米长度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | double | 米数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | 新的 <c>Measurement</c> 类实例。 |


### Method: millimeters(value)  [static] {#millimeters_value_4}


```
 millimeters(value) 
```

返回一个新的 <c>Measurement</c> 实例，表示毫米长度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | double | 毫米数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | 新的 <c>Measurement</c> 类实例。 |


### Method: pixels(value)  [static] {#pixels_value_5}


```
 pixels(value) 
```

返回一个新的 <c>Measurement</c> 实例，表示像素长度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | double | 像素数。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | 新的 <c>Measurement</c> 类实例。 |


### Method: points(value)  [static] {#points_value_6}


```
 points(value) 
```

返回一个新的 <c>Measurement</c> 实例，表示点长度。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| value | double | 点的数量。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | 新的 <c>Measurement</c> 类实例。 |


