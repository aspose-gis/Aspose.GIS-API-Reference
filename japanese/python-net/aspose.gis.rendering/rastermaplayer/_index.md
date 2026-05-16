---
title: "RasterMapLayer クラス"
type: docs
weight: 250
url: /ja/python-net/aspose.gis.rendering/rastermaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a raster layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.RasterMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [RasterMapLayer(layer, colorizer, keep_open)](#RasterMapLayer_layer_colorizer_keep_open_1) | 新しいインスタンスを作成します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | r/w | ラスタのセルを描画するために使用するカラーライザーです。 |
| 不透明度 | double | 読み/書き | レイヤーの不透明度です。 |
| resampling | [RasterMapResampling](/psd/python-net/aspose.gis.rendering/rastermapresampling) | r/w | マップ上のレイヤーのワープオプションを指定します。 |


### Constructor: RasterMapLayer(layer, colorizer, keep_open) {#RasterMapLayer_layer_colorizer_keep_open_1}


```
 RasterMapLayer(layer, colorizer, keep_open) 
```

新しいインスタンスを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | ラスタレイヤー。 |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | レイヤーを描画するために使用するシンボライザーです。<see langword="null" /> の場合、デフォルトのカラーライザーが使用されます。 |
| keep_open | bool | <see langword="true" /> は、[VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) オブジェクトが破棄された後もレイヤーを開いたままにします。そうでない場合は、<see langword="false" />。 |

