---
title: "MeasuredLine 클래스"
type: docs
weight: 60
url: /ko/python-net/aspose.gis.labeling.line/measuredline/
---

**Summary:** 

**Module:** [aspose.gis.labeling.line](/psd/python-net/aspose.gis.labeling.line/)

**Full Name:** aspose.gis.labeling.line.MeasuredLine

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MeasuredLine(line)](#MeasuredLine_line_1) | MeasuredLine 클래스의 새 인스턴스를 초기화합니다 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| distance_to_segment | System.Collections.Generic.IReadOnlyList<double> | r |  |
| is_closed | bool | r |  |
| line | System.Collections.Generic.IReadOnlyList<Aspose.Gis.Common.Coordinate> | r |  |
| middle_of_line | double | r |  |
| segment_lengths | System.Collections.Generic.IReadOnlyList<double> | r |  |
| total_line_length | double | r |  |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_point_by_distance(distance_along_line)](#get_point_by_distance_distance_along_line_1) |    |
| [get_segment_index(distance_along_line)](#get_segment_index_distance_along_line_2) |    |


### Constructor: MeasuredLine(line) {#MeasuredLine_line_1}


```
 MeasuredLine(line) 
```

MeasuredLine 클래스의 새 인스턴스를 초기화합니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| line | System.Collections.Generic.IReadOnlyList<Aspose.Gis.Common.Coordinate> |  |

### Method: get_point_by_distance(distance_along_line) {#get_point_by_distance_distance_along_line_1}


```
 get_point_by_distance(distance_along_line) 
```

  

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| distance_along_line | double |  |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) |  |


### Method: get_segment_index(distance_along_line) {#get_segment_index_distance_along_line_2}


```
 get_segment_index(distance_along_line) 
```

  

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| distance_along_line | double |  |

**Returns**

| 형식 | 설명 |
| :- | :- |
| int |  |


