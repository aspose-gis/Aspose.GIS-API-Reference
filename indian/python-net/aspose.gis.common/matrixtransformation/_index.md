---
title: "MatrixTransformation क्लास"
type: docs
weight: 670
url: /hi/python-net/aspose.gis.common/matrixtransformation/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.MatrixTransformation

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [MatrixTransformation()](#MatrixTransformation__1) | MatrixTransformation क्लास का नया उदाहरण प्रारंभ करता है |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| dx | double | r/w |  |
| dy | double | r/w |  |
| is_editable | bool | r |  |
| is_null | bool | r |  |
| m11 | double | r/w |  |
| m12 | double | r/w |  |
| m21 | double | r/w |  |
| m22 | double | r/w |  |
| रोटेशन | double | r |  |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [clone()](#clone__1) | वर्तमान इंस्टेंस की एक प्रति बनाकर नया ऑब्जेक्ट बनाता है। |
| lock_from_editing() |  |
| rotate(cos, sin) |  |
| rotate(degrees) |  |
| scale(zoom_x, zoom_y) |  |
| [transform(coordinate)](#transform_coordinate_2) |    |
| [transform(x, y)](#transform_x_y_3) |    |
| translate(c) |  |
| translate(x, y) |  |


### Constructor: MatrixTransformation() {#MatrixTransformation__1}


```
 MatrixTransformation() 
```

MatrixTransformation क्लास का नया उदाहरण प्रारंभ करता है

### Method: clone() {#clone__1}


```
 clone() 
```

वर्तमान इंस्टेंस की एक प्रति बनाकर नया ऑब्जेक्ट बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [MatrixTransformation](/psd/python-net/aspose.gis.common/matrixtransformation) |  |


### Method: transform(coordinate) {#transform_coordinate_2}


```
 transform(coordinate) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| coordinate | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


### Method: transform(x, y) {#transform_x_y_3}


```
 transform(x, y) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | double |  |
| y | double |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


