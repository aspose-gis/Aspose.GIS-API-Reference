---
title: "Kelas Projection"
type: docs
weight: 20
url: /id/python-net/aspose.gis.projections/projection/
---

**Summary:** 

**Module:** [aspose.gis.projections](/psd/python-net/aspose.gis.projections/)

**Full Name:** aspose.gis.projections.Projection

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [create(projection_method_id, parameters)](#create_projection_method_id_parameters_1) |    |
| [to_geographic(easting, northing, longitude, latitude)](#to_geographic_easting_northing_longitude_latitude_2) |    |
| [to_projected(longitude, latitude, easting, northing)](#to_projected_longitude_latitude_easting_northing_3) |    |


### Method: create(projection_method_id, parameters)  [static] {#create_projection_method_id_parameters_1}


```
 create(projection_method_id, parameters) 
```

  

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| projection_method_id | [ProjectionMethodIdentifier](/psd/python-net/aspose.gis.projections/projectionmethodidentifier) |  |
| parameters | [ProjectionParameters](/psd/python-net/aspose.gis.projections/projectionparameters) |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection) |  |


### Method: to_geographic(easting, northing, longitude, latitude) {#to_geographic_easting_northing_longitude_latitude_2}


```
 to_geographic(easting, northing, longitude, latitude) 
```

  

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| easting | double |  |
| northing | double |  |
| longitude | float[] |  |
| latitude | float[] |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool |  |


### Method: to_projected(longitude, latitude, easting, northing) {#to_projected_longitude_latitude_easting_northing_3}


```
 to_projected(longitude, latitude, easting, northing) 
```

  

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| longitude | double |  |
| latitude | double |  |
| easting | float[] |  |
| northing | float[] |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool |  |


