---
title: "RasterImageMarker クラス"
type: docs
weight: 80
url: /ja/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/
---

**Summary:** This symbolizer renders a provided raster image.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.RasterImageMarker

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [RasterImageMarker(image_path)](#RasterImageMarker_image_path_1) | 新しい [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) クラスのインスタンスを初期化します。 |
| [RasterImageMarker(image_path)](#RasterImageMarker_image_path_2) | 新しい [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) クラスのインスタンスを初期化します。 |
| [RasterImageMarker(other)](#RasterImageMarker_other_3) | 新しい [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | マーカーの高さを指定します。 |
| horizontal_anchor_point | [HorizontalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/horizontalanchor) | r/w | マーカー形状のどの側がポイント位置と水平に揃えるかを指定します。 |
| horizontal_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | ポイント位置から形状アンカーポイントへの水平オフセットを指定します。 |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) は何も描画せず、適用されたジオメトリの描画を実質的にスキップします。 |
| 不透明度 | double | 読み/書き | レイヤーの不透明度です。デフォルト値は 1.0 です。 |
| 回転 | double | 読み/書き | シンボルを中心点の周りで回転させる角度（十進法の度数）を指定します。<br/>            正の値は時計回りの回転を示し、負の値は反時計回りの回転を示します。 |
| vertical_anchor_point | [VerticalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/verticalanchor) | r/w | マーカー形状のどの側がポイント位置と垂直に揃えるかを指定します。 |
| vertical_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | ポイント位置から形状アンカーポイントへの垂直オフセットを指定します。 |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | マーカーの幅を指定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [clone()](#clone__1) | このインスタンスをクローンします。 |


### Constructor: RasterImageMarker(image_path) {#RasterImageMarker_image_path_1}


```
 RasterImageMarker(image_path) 
```

新しい [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| image_path | string | ファイルへのパス。 |

### Constructor: RasterImageMarker(image_path) {#RasterImageMarker_image_path_2}


```
 RasterImageMarker(image_path) 
```

新しい [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| image_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | ファイルへのパス。 |

### Constructor: RasterImageMarker(other) {#RasterImageMarker_other_3}


```
 RasterImageMarker(other) 
```

新しい [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker) | データをコピーする他の [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/)。 |

### Method: clone() {#clone__1}


```
 clone() 
```

このインスタンスをクローンします。

**Returns**

| 型 | 説明 |
| :- | :- |
| [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker) | このインスタンスのクローン。 |


