---
title: "MeasuredLine Kelas"
type: docs
weight: 60
url: /id/python-net/aspose.gis.labeling.line/measuredline/
---

**Summary:** 

**Module:** [aspose.gis.labeling.line](/psd/python-net/aspose.gis.labeling.line/)

**Full Name:** aspose.gis.labeling.line.MeasuredLine

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [MeasuredLine(line)](#MeasuredLine_line_1) | Menginisialisasi sebuah instance baru dari kelas MeasuredLine |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| distance_to_segment | System.Collections.Generic.IReadOnlyList<double> | r |  |
| is_closed | bool | r |  |
| line | System.Collections.Generic.IReadOnlyList<Aspose.Gis.Common.Coordinate> | r |  |
| middle_of_line | double | r |  |
| segment_lengths | System.Collections.Generic.IReadOnlyList<double> | r |  |
| total_line_length | double | r |  |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_point_by_distance(distance_along_line)](#get_point_by_distance_distance_along_line_1) |    |
| [get_segment_index(distance_along_line)](#get_segment_index_distance_along_line_2) |    |


### Constructor: MeasuredLine(line) {#MeasuredLine_line_1}


```
 MeasuredLine(line) 
```

Menginisialisasi sebuah instance baru dari kelas MeasuredLine

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| line | System.Collections.Generic.IReadOnlyList<Aspose.Gis.Common.Coordinate> |  |

### Method: get_point_by_distance(distance_along_line) {#get_point_by_distance_distance_along_line_1}


```
 get_point_by_distance(distance_along_line) 
```

  

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| distance_along_line | double |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) |  |


### Method: get_segment_index(distance_along_line) {#get_segment_index_distance_along_line_2}


```
 get_segment_index(distance_along_line) 
```

  

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| distance_along_line | double |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int |  |


