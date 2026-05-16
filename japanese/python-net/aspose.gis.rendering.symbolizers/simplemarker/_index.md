---
title: "SimpleMarker クラス"
type: docs
weight: 130
url: /ja/python-net/aspose.gis.rendering.symbolizers/simplemarker/
---

**Summary:** Simple point symbolizer.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.SimpleMarker

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [SimpleMarker()](#SimpleMarker__1) | [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/) クラスの新しいインスタンスを初期化します。 |
| [SimpleMarker(other)](#SimpleMarker_other_2) | [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/) クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| fill_color | System.Drawing.Color | 読み/書き | 塗りつぶしの色と透明度を指定します。 |
| horizontal_anchor_point | [HorizontalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/horizontalanchor) | r/w | マーカー形状のどの側がポイント位置と水平に揃えるかを指定します。 |
| horizontal_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | ポイント位置から形状アンカーポイントへの水平オフセットを指定します。 |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) は何も描画せず、適用されたジオメトリの描画を実質的にスキップします。 |
| 回転 | double | 読み/書き | シンボルを中心点の周りで回転させる角度（十進法の度数）を指定します。<br/>            正の値は時計回りの回転を示し、負の値は反時計回りの回転を示します。 |
| shape_type | [MarkerShapeType](/psd/python-net/aspose.gis.rendering.symbolizers/markershapetype) | r/w | マーカーの形状を指定します。 |
| size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | マーカーのサイズを指定します。 |
| stroke_color | System.Drawing.Color | 読み/書き | 線の色と透明度を指定します。 |
| stroke_dash_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 線の開始点から破線パターンの開始までの距離を指定します。 |
| stroke_dash_pattern | System.Collections.Generic.IEnumerable<Measurement> | 読み/書き | 破線の線で、交互のダッシュとスペースの長さを指定する距離の配列を指定します。<br/>             |
| stroke_line_join | [LineJoin](/psd/python-net/aspose.gis.rendering/linejoin) | r/w | 線分の交点で線がどのように描画されるかを決定します。 |
| stroke_style | [StrokeStyle](/psd/python-net/aspose.gis.rendering/strokestyle) | r/w | シンボルラインの描画方法を指定します。 |
| stroke_width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 線の幅を指定します。 |
| vertical_anchor_point | [VerticalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/verticalanchor) | r/w | マーカー形状のどの側がポイント位置と垂直に揃えるかを指定します。 |
| vertical_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | ポイント位置から形状アンカーポイントへの垂直オフセットを指定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [clone()](#clone__1) | このインスタンスをクローンします。 |


### Constructor: SimpleMarker() {#SimpleMarker__1}


```
 SimpleMarker() 
```

[SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/) クラスの新しいインスタンスを初期化します。

### Constructor: SimpleMarker(other) {#SimpleMarker_other_2}


```
 SimpleMarker(other) 
```

[SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker) | データをコピーする対象となる別の [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/)。 |

### Method: clone() {#clone__1}


```
 clone() 
```

このインスタンスをクローンします。

**Returns**

| 型 | 説明 |
| :- | :- |
| [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker) | このインスタンスのクローン。 |


