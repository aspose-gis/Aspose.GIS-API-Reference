---
title: "SimpleLabeling クラス"
type: docs
weight: 80
url: /ja/python-net/aspose.gis.rendering.labelings/simplelabeling/
---

**Summary:** A simple labeling places label on every feature.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.SimpleLabeling

**Inheritance:** Labeling

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [SimpleLabeling()](#SimpleLabeling__1) | 新しい [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) クラスのインスタンスを初期化します。 |
| [SimpleLabeling(label_attribute)](#SimpleLabeling_label_attribute_2) | 新しい [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) クラスのインスタンスを初期化します。 |
| [SimpleLabeling(other)](#SimpleLabeling_other_3) | 新しい [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| font_color | System.Drawing.Color | 読み/書き | テキストの色を決定します。 |
| font_family | string | 読み/書き | テキストを描画するために使用するフォントファミリ。デフォルトはシステム依存の値です。 |
| font_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | テキストのサイズ。 |
| font_style | [FontStyle](/psd/python-net/aspose.gis.rendering.labelings/fontstyle) | r/w | テキストに適用するスタイル。 |
| halo_color | System.Drawing.Color | 読み/書き | テキスト周囲のハロー（ストローク）の色。 |
| halo_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | テキスト周囲のハロー（ストローク）のサイズ。 |
| label_attribute | string | r/w | ラベルのソースとして使用する属性名。[None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) が設定されている場合は無視されます。<br/> いずれかの [SimpleLabeling.label_attribute](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) または [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) がレンダリング前に設定されている必要があります。<br/> それ以外の場合は InvalidOperationException がスローされます。 |
| multipart_mode | [MultipartMode](/psd/python-net/aspose.gis.rendering.labelings/multipartmode) | r/w | マルチパートジオメトリのレンダリング動作を指定します。デフォルトは [MultipartMode.ALL](/psd/python-net/aspose.gis.rendering.labelings/multipartmode/) です。 |
| null [static] | [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling) | r | [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) のインスタンスを取得します。 |
| placement | [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | r/w | ラベル配置は、ラベルがフィーチャのジオメトリに対してどのように相対的に配置されるかを指定します。 |
| 優先度 | int | 読み/書き | このラベルが他のラベルと重なる場合の優先度を示します。優先度が低いラベルはレンダリングされません。<br/> デフォルトは 1000 です。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [clone()](#clone__1) | このインスタンスをクローンします。 |


### Constructor: SimpleLabeling() {#SimpleLabeling__1}


```
 SimpleLabeling() 
```

新しい [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) クラスのインスタンスを初期化します。

### Constructor: SimpleLabeling(label_attribute) {#SimpleLabeling_label_attribute_2}


```
 SimpleLabeling(label_attribute) 
```

新しい [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| label_attribute | string | ラベルのソースとして使用する属性名。 |

### Constructor: SimpleLabeling(other) {#SimpleLabeling_other_3}


```
 SimpleLabeling(other) 
```

新しい [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | データをコピー元とする他の [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/)。 |

### Method: clone() {#clone__1}


```
 clone() 
```

このインスタンスをクローンします。

**Returns**

| 型 | 説明 |
| :- | :- |
| [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | このインスタンスのクローン。 |


