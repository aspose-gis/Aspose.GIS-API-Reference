---
title: "KmlIconStyle クラス"
type: docs
weight: 60
url: /ja/python-net/aspose.gis.formats.kml.styles/kmliconstyle/
---

**Summary:** Specifies how icons for kml:Placemarks and kml:PhotoOverlay with a kml:Point geometry are drawn<br/>            in an earth browser's list and geographic views.

**Module:** [aspose.gis.formats.kml.styles](/psd/python-net/aspose.gis.formats.kml.styles/)

**Full Name:** aspose.gis.formats.kml.styles.KmlIconStyle

**Inheritance:** KmlAbstractColorStyle

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [KmlIconStyle()](#KmlIconStyle__1) | KmlIconStyle クラスの新しいインスタンスを初期化します |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| 色 | System.Drawing.Color | 読み/書き | グラフィック要素の色を指定します。デフォルト値は .です。 |
| color_mode | [KmlColorModes](/psd/python-net/aspose.gis.formats.kml.styles/kmlcolormodes) | r/w | グラフィック要素のカラーモードを指定します。デフォルト値: normal。 |
| 見出し | double | 読み/書き | 方向（北、南、東、西）、十進法の度数で表します。値は 0（北）から 360 度までです。デフォルト値は '0' です。 |
| hot_spot | [KmlCoordinate](/psd/python-net/aspose.gis.formats.kml.styles/kmlcoordinate) | r/w | アイコン上の参照点の位置を指定します。この参照点は Placemark で指定された Point にアンカーされます。<br/>            デフォルト値は <see langword="null" /> で、HotSpot が欠落していることを意味します。 |
| resource | [KmlIconResource](/psd/python-net/aspose.gis.formats.kml.styles/kmliconresource) | r/w | リソースの場所を指定します。デフォルト値は <see langword="null" /> で、Icon が欠落していることを意味します。 |
| スケール | double | 読み/書き | グラフィック要素に適用されるスケール係数を指定します。デフォルト値は '1' です。 |


### Constructor: KmlIconStyle() {#KmlIconStyle__1}


```
 KmlIconStyle() 
```

KmlIconStyle クラスの新しいインスタンスを初期化します

