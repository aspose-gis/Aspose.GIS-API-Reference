---
title: "MatrixTransformation クラス"
type: docs
weight: 670
url: /ja/python-net/aspose.gis.common/matrixtransformation/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.MatrixTransformation

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [MatrixTransformation()](#MatrixTransformation__1) | MatrixTransformation クラスの新しいインスタンスを初期化します |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| dx | double | 読み/書き |  |
| dy | double | 読み/書き |  |
| 編集可能 | bool | r |  |
| nullか | bool | r |  |
| m11 | double | 読み/書き |  |
| m12 | double | 読み/書き |  |
| m21 | double | 読み/書き |  |
| m22 | double | 読み/書き |  |
| 回転 | double | r |  |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [clone()](#clone__1) | 現在のインスタンスのコピーである新しいオブジェクトを作成します。 |
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

MatrixTransformation クラスの新しいインスタンスを初期化します

### Method: clone() {#clone__1}


```
 clone() 
```

現在のインスタンスのコピーである新しいオブジェクトを作成します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [MatrixTransformation](/psd/python-net/aspose.gis.common/matrixtransformation) |  |


### Method: transform(coordinate) {#transform_coordinate_2}


```
 transform(coordinate) 
```

  

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| coordinate | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


### Method: transform(x, y) {#transform_x_y_3}


```
 transform(x, y) 
```

  

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| x | double |  |
| y | double |  |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Coordinate](/psd/python-net/aspose.gis.common/coordinate) |  |


