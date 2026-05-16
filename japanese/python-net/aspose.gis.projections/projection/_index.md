---
title: "投影クラス"
type: docs
weight: 20
url: /ja/python-net/aspose.gis.projections/projection/
---

**Summary:** 

**Module:** [aspose.gis.projections](/psd/python-net/aspose.gis.projections/)

**Full Name:** aspose.gis.projections.Projection

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **説明** |
| :- | :- |
| [create(projection_method_id, parameters)](#create_projection_method_id_parameters_1) |    |
| [to_geographic(easting, northing, longitude, latitude)](#to_geographic_easting_northing_longitude_latitude_2) |    |
| [to_projected(longitude, latitude, easting, northing)](#to_projected_longitude_latitude_easting_northing_3) |    |


### Method: create(projection_method_id, parameters)  [static] {#create_projection_method_id_parameters_1}


```
 create(projection_method_id, parameters) 
```

  

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| projection_method_id | [ProjectionMethodIdentifier](/psd/python-net/aspose.gis.projections/projectionmethodidentifier) |  |
| parameters | [ProjectionParameters](/psd/python-net/aspose.gis.projections/projectionparameters) |  |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection) |  |


### Method: to_geographic(easting, northing, longitude, latitude) {#to_geographic_easting_northing_longitude_latitude_2}


```
 to_geographic(easting, northing, longitude, latitude) 
```

  

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| イースティング | double |  |
| ノーシング | double |  |
| 経度 | float[] |  |
| 緯度 | float[] |  |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool |  |


### Method: to_projected(longitude, latitude, easting, northing) {#to_projected_longitude_latitude_easting_northing_3}


```
 to_projected(longitude, latitude, easting, northing) 
```

  

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 経度 | double |  |
| 緯度 | double |  |
| イースティング | float[] |  |
| ノーシング | float[] |  |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool |  |


