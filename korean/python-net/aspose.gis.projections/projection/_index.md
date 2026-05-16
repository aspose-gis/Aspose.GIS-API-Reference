---
title: "Projection 클래스"
type: docs
weight: 20
url: /ko/python-net/aspose.gis.projections/projection/
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

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| projection_method_id | [ProjectionMethodIdentifier](/psd/python-net/aspose.gis.projections/projectionmethodidentifier) |  |
| parameters | [ProjectionParameters](/psd/python-net/aspose.gis.projections/projectionparameters) |  |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection) |  |


### Method: to_geographic(easting, northing, longitude, latitude) {#to_geographic_easting_northing_longitude_latitude_2}


```
 to_geographic(easting, northing, longitude, latitude) 
```

  

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 동쪽 좌표 | double |  |
| 북쪽 좌표 | double |  |
| 경도 | float[] |  |
| 위도 | float[] |  |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool |  |


### Method: to_projected(longitude, latitude, easting, northing) {#to_projected_longitude_latitude_easting_northing_3}


```
 to_projected(longitude, latitude, easting, northing) 
```

  

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 경도 | double |  |
| 위도 | double |  |
| 동쪽 좌표 | float[] |  |
| 북쪽 좌표 | float[] |  |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool |  |


