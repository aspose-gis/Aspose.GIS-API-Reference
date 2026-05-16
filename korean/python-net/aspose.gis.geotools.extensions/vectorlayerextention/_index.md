---
title: "VectorLayerExtention 클래스"
type: docs
weight: 10
url: /ko/python-net/aspose.gis.geotools.extensions/vectorlayerextention/
---

**Summary:** Vector Layer Extention.

**Module:** [aspose.gis.geotools.extensions](/psd/python-net/aspose.gis.geotools.extensions/)

**Full Name:** aspose.gis.geotools.extensions.VectorLayerExtention

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_features(layer, geometries)](#add_features_layer_geometries_1) | 일반 리스트를 사용하여 피처를 추가합니다. |
| [read_geometries(layer)](#read_geometries_layer_2) | 레이어에서 기하 도형만 읽습니다. |


### Method: add_features(layer, geometries)  [static] {#add_features_layer_geometries_1}


```
 add_features(layer, geometries) 
```

일반 리스트를 사용하여 피처를 추가합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 추가할 레이어. |
| 기하 도형 | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IGeometry> | 입력 기하 도형. |

### Method: read_geometries(layer)  [static] {#read_geometries_layer_2}


```
 read_geometries(layer) 
```

레이어에서 기하 도형만 읽습니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 읽을 레이어. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IGeometry> | 기능들. |


