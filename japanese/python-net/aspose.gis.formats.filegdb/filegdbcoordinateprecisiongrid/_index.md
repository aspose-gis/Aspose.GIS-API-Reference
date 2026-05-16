---
title: "FileGdbCoordinatePrecisionGrid クラス"
type: docs
weight: 10
url: /ja/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/
---

**Summary:** A coordinate precision grid inside a FileGDB layer.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbCoordinatePrecisionGrid

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid()](#FileGdbCoordinatePrecisionGrid__1) | FileGdbCoordinatePrecisionGrid クラスの新しいインスタンスを初期化します |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| m_origin | Nullable<double> | 読み/書き | M 座標の原点を取得または設定します。<see langword=\"null\" /> に設定された場合、既定が使用されます。 |
| m_scale | Nullable<double> | 読み/書き | M 座標のスケールを取得または設定します。<see langword=\"null\" /> に設定された場合、既定が使用されます。 |
| x_origin | Nullable<double> | 読み/書き | X 座標の原点を取得または設定します。<see langword=\"null\" /> に設定した場合、既定が使用されます。 |
| xy_scale | Nullable<double> | 読み/書き | X および Y 座標のスケールを取得または設定します。<see langword=\"null\" /> に設定した場合、既定が使用されます。 |
| y_origin | Nullable<double> | 読み/書き | Y 座標の原点を取得または設定します。<see langword=\"null\" /> に設定した場合、既定が使用されます。 |
| z_origin | Nullable<double> | 読み/書き | Z 座標の原点を取得または設定します。<see langword=\"null\" /> に設定した場合、既定が使用されます。 |
| z_scale | Nullable<double> | 読み/書き | Z 座標のスケールを取得または設定します。<see langword=\"null\" /> に設定した場合、既定が使用されます。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [create_from_rectangle(p1, p2)](#create_from_rectangle_p1_p2_1) | <c>FileGdbCoordinatePrecisionGrid</c> を新規作成し、矩形内のすべての値が表現可能になるようにします。 |


### Constructor: FileGdbCoordinatePrecisionGrid() {#FileGdbCoordinatePrecisionGrid__1}


```
 FileGdbCoordinatePrecisionGrid() 
```

FileGdbCoordinatePrecisionGrid クラスの新しいインスタンスを初期化します

### Method: create_from_rectangle(p1, p2)  [static] {#create_from_rectangle_p1_p2_1}


```
 create_from_rectangle(p1, p2) 
```

<c>FileGdbCoordinatePrecisionGrid</c> を新規作成し、矩形内のすべての値が表現可能になるようにします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| p1 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | 矩形の一つの角。 |
| p2 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | 矩形の反対側の角。<paramref name=\"p1\" /> と同じ寸法である必要があります。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid](/psd/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid) | <c>FileGdbCoordinatePrecisionGrid</c> は、矩形内のすべての値が表現可能になるようにします。<br/>            矩形外の値は表現できないため、FileGDB レイヤーに書き込まれるすべての座標は矩形内にある必要があります。 |


