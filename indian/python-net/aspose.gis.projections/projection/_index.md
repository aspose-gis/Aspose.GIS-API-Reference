---
title: "Projection क्लास"
type: docs
weight: 20
url: /hi/python-net/aspose.gis.projections/projection/
---

**Summary:** 

**Module:** [aspose.gis.projections](/psd/python-net/aspose.gis.projections/)

**Full Name:** aspose.gis.projections.Projection

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [create(projection_method_id, parameters)](#create_projection_method_id_parameters_1) |    |
| [to_geographic(easting, northing, longitude, latitude)](#to_geographic_easting_northing_longitude_latitude_2) |    |
| [to_projected(longitude, latitude, easting, northing)](#to_projected_longitude_latitude_easting_northing_3) |    |


### Method: create(projection_method_id, parameters)  [static] {#create_projection_method_id_parameters_1}


```
 create(projection_method_id, parameters) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| projection_method_id | [ProjectionMethodIdentifier](/psd/python-net/aspose.gis.projections/projectionmethodidentifier) |  |
| parameters | [ProjectionParameters](/psd/python-net/aspose.gis.projections/projectionparameters) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection) |  |


### Method: to_geographic(easting, northing, longitude, latitude) {#to_geographic_easting_northing_longitude_latitude_2}


```
 to_geographic(easting, northing, longitude, latitude) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| पूर्वनिर्देश | double |  |
| उत्तरीनिर्देश | double |  |
| देशांतर | float[] |  |
| अक्षांश | float[] |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool |  |


### Method: to_projected(longitude, latitude, easting, northing) {#to_projected_longitude_latitude_easting_northing_3}


```
 to_projected(longitude, latitude, easting, northing) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| देशांतर | double |  |
| अक्षांश | double |  |
| पूर्वनिर्देश | float[] |  |
| उत्तरीनिर्देश | float[] |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool |  |


