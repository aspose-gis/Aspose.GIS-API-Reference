---
title: "LineLabelPlacement クラス"
type: docs
weight: 40
url: /ja/python-net/aspose.gis.rendering.labelings/linelabelplacement/
---

**Summary:** Line label placement places labels along line.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LineLabelPlacement

**Inheritance:** LabelPlacement

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [LineLabelPlacement()](#LineLabelPlacement__1) | 新しいインスタンスを作成します。 |
| [LineLabelPlacement(other)](#LineLabelPlacement_other_2) | 新しいインスタンスを作成します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| alignment | [LineLabelAlignment](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment) | r/w | ラベルが線形パスに対してどのように揃えられるかを指定します。デフォルトは [LineLabelAlignment.PARALLEL](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment/) です。 |
| max_angle_delta | double | r/w | [LineLabelAlignment.CURVED](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment/) と併用する場合、曲線ラベル内の 2 つの<br/>            連続文字間の最大角度（度）を設定します。デフォルトは 25 です。 |
| offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 線形パスからのオフセットです。<br/>            正の値は線の左側に、負の値は右側にオフセットします。デフォルトは 0 です。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [clone()](#clone__1) | このインスタンスをクローンします。 |


### Constructor: LineLabelPlacement() {#LineLabelPlacement__1}


```
 LineLabelPlacement() 
```

新しいインスタンスを作成します。

### Constructor: LineLabelPlacement(other) {#LineLabelPlacement_other_2}


```
 LineLabelPlacement(other) 
```

新しいインスタンスを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [LineLabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/linelabelplacement) | データをコピーする元となる別の [LineLabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/linelabelplacement/)。 |

### Method: clone() {#clone__1}


```
 clone() 
```

このインスタンスをクローンします。

**Returns**

| 型 | 説明 |
| :- | :- |
| [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | このインスタンスのクローン。 |


