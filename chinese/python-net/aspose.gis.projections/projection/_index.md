---
title: "投影类"
type: docs
weight: 20
url: /zh/python-net/aspose.gis.projections/projection/
---

**Summary:** 

**Module:** [aspose.gis.projections](/psd/python-net/aspose.gis.projections/)

**Full Name:** aspose.gis.projections.Projection

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create(projection_method_id, parameters)](#create_projection_method_id_parameters_1) |    |
| [to_geographic(easting, northing, longitude, latitude)](#to_geographic_easting_northing_longitude_latitude_2) |    |
| [to_projected(longitude, latitude, easting, northing)](#to_projected_longitude_latitude_easting_northing_3) |    |


### Method: create(projection_method_id, parameters)  [static] {#create_projection_method_id_parameters_1}


```
 create(projection_method_id, parameters) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| projection_method_id | [ProjectionMethodIdentifier](/psd/python-net/aspose.gis.projections/projectionmethodidentifier) |  |
| parameters | [ProjectionParameters](/psd/python-net/aspose.gis.projections/projectionparameters) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection) |  |


### Method: to_geographic(easting, northing, longitude, latitude) {#to_geographic_easting_northing_longitude_latitude_2}


```
 to_geographic(easting, northing, longitude, latitude) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 东向坐标 | double |  |
| 北向坐标 | double |  |
| 经度 | float[] |  |
| 纬度 | float[] |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool |  |


### Method: to_projected(longitude, latitude, easting, northing) {#to_projected_longitude_latitude_easting_northing_3}


```
 to_projected(longitude, latitude, easting, northing) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 经度 | double |  |
| 纬度 | double |  |
| 东向坐标 | float[] |  |
| 北向坐标 | float[] |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool |  |


