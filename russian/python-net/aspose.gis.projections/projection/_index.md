---
title: "Класс Projection"
type: docs
weight: 20
url: /ru/python-net/aspose.gis.projections/projection/
---

**Summary:** 

**Module:** [aspose.gis.projections](/psd/python-net/aspose.gis.projections/)

**Full Name:** aspose.gis.projections.Projection

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [create(projection_method_id, parameters)](#create_projection_method_id_parameters_1) |    |
| [to_geographic(easting, northing, longitude, latitude)](#to_geographic_easting_northing_longitude_latitude_2) |    |
| [to_projected(longitude, latitude, easting, northing)](#to_projected_longitude_latitude_easting_northing_3) |    |


### Method: create(projection_method_id, parameters)  [static] {#create_projection_method_id_parameters_1}


```
 create(projection_method_id, parameters) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| projection_method_id | [ProjectionMethodIdentifier](/psd/python-net/aspose.gis.projections/projectionmethodidentifier) |  |
| parameters | [ProjectionParameters](/psd/python-net/aspose.gis.projections/projectionparameters) |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection) |  |


### Method: to_geographic(easting, northing, longitude, latitude) {#to_geographic_easting_northing_longitude_latitude_2}


```
 to_geographic(easting, northing, longitude, latitude) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| смещение по востоку | double |  |
| смещение по северу | double |  |
| долгота | float[] |  |
| широта | float[] |  |

**Returns**

| Тип | Описание |
| :- | :- |
| bool |  |


### Method: to_projected(longitude, latitude, easting, northing) {#to_projected_longitude_latitude_easting_northing_3}


```
 to_projected(longitude, latitude, easting, northing) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| долгота | double |  |
| широта | double |  |
| смещение по востоку | float[] |  |
| смещение по северу | float[] |  |

**Returns**

| Тип | Описание |
| :- | :- |
| bool |  |


