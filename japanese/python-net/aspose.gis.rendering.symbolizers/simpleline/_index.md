---
title: "SimpleLine クラス"
type: docs
weight: 120
url: /ja/python-net/aspose.gis.rendering.symbolizers/simpleline/
---

**Summary:** Simple line symbolizer.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.SimpleLine

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [SimpleLine()](#SimpleLine__1) | 新しいインスタンスを作成します。 |
| [SimpleLine(other)](#SimpleLine_other_2) | [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline/) クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| cap_style | [CapStyle](/psd/python-net/aspose.gis.rendering/capstyle) | r/w | 線の端部がどのように描画されるかを指定します。 |
| 色 | System.Drawing.Color | 読み/書き | 線の色と透明度を指定します。 |
| dash_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 線の開始点から破線パターンの開始までの距離を指定します。 |
| dash_pattern | System.Collections.Generic.IEnumerable<Measurement> | 読み/書き | 破線の線で、交互のダッシュとスペースの長さを指定する距離の配列を指定します。<br/>             |
| line_join | [LineJoin](/psd/python-net/aspose.gis.rendering/linejoin) | r/w | 線分の交点で線がどのように描画されるかを決定します。 |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) は何も描画せず、適用されたジオメトリの描画を実質的にスキップします。 |
| offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 元の線からのオフセットを指定します。<br/>            正の距離の場合、オフセットは入力線の左側（線の方向に対して）に配置されます。<br/>            負の距離の場合、右側に配置されます。 |
| style | [StrokeStyle](/psd/python-net/aspose.gis.rendering/strokestyle) | r/w | シンボルラインの描画方法を指定します。 |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 線の幅を指定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [clone()](#clone__1) | このインスタンスをクローンします。 |


### Constructor: SimpleLine() {#SimpleLine__1}


```
 SimpleLine() 
```

新しいインスタンスを作成します。

### Constructor: SimpleLine(other) {#SimpleLine_other_2}


```
 SimpleLine(other) 
```

[SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline/) クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline) | データをコピーする他の [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline/)。 |

### Method: clone() {#clone__1}


```
 clone() 
```

このインスタンスをクローンします。

**Returns**

| 型 | 説明 |
| :- | :- |
| [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline) | このインスタンスのクローン。 |


