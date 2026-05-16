---
title: "BoundingBox クラス"
type: docs
weight: 90
url: /ja/python-net/aspose.gis.common/boundingbox/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.BoundingBox

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [BoundingBox()](#BoundingBox__1) | BoundingBox クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| bounding_rectangle | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle) | r |    |
| has_m | bool | r |  |
| has_z | bool | r |  |
| m_center | double | r |  |
| m_length | double | r |  |
| m_max | double | 読み/書き |  |
| m_min | double | 読み/書き |  |
| x_center | double | r |  |
| x_length | double | r |  |
| x_max | double | 読み/書き |  |
| x_min | double | 読み/書き |  |
| xy_center | [Coordinate](/psd/python-net/aspose.gis.common/coordinate) | r |    |
| y_center | double | r |  |
| y_length | double | r |  |
| y_max | double | 読み/書き |  |
| y_min | double | 読み/書き |  |
| z_center | double | r |  |
| z_length | double | r |  |
| z_max | double | 読み/書き |  |
| z_min | double | 読み/書き |  |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| clear() |  |
| [clone()](#clone__1) | 現在のインスタンスのコピーである新しいオブジェクトを作成します。 |
| grow(other, has_z, has_m) |  |
| grow_m(m) |  |
| grow_x(x) |  |
| grow_y(y) |  |
| grow_z(z) |  |
| [has_values()](#has_values__2) |    |


### Constructor: BoundingBox() {#BoundingBox__1}


```
 BoundingBox() 
```

BoundingBox クラスの新しいインスタンスを初期化します。

### Method: clone() {#clone__1}


```
 clone() 
```

現在のインスタンスのコピーである新しいオブジェクトを作成します。

**Returns**

| 型 | 説明 |
| :- | :- |
| [BoundingBox](/psd/python-net/aspose.gis.common/boundingbox) |  |


### Method: has_values() {#has_values__2}


```
 has_values() 
```

  

**Returns**

| 型 | 説明 |
| :- | :- |
| bool |  |


