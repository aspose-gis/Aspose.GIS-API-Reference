---
title: "MapOptions クラス"
type: docs
weight: 30
url: /ja/python-net/aspose.gis.geotools.layersmap/mapoptions/
---

**Summary:** Map Options for creating maps using [LayersMapBuilder](/psd/python-net/aspose.gis.geotools.layersmap/layersmapbuilder/)

**Module:** [aspose.gis.geotools.layersmap](/psd/python-net/aspose.gis.geotools.layersmap/)

**Full Name:** aspose.gis.geotools.layersmap.MapOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [MapOptions()](#MapOptions__1) | MapOptions クラスの新しいインスタンスを初期化します |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | 読み/書き | マップの背景色。デフォルトは System.Drawing.Color.Transparent です。 |
| height | int | r/w | マップの視覚的な高さ。デフォルトは 400 です。[MapSizeModes.CUSTOM](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/) の場合に使用されます。 |
| layers | [MapLayerOptions[]](/psd/python-net/aspose.gis.geotools.layersmap/maplayeroptions) | r/w | Aspose.Gis.GeoTools.LayersMap.MapLayerOptions によって表現されるベクトルレイヤーのオプションのコレクション。 |
| rasters | [MapRasterOptions[]](/psd/python-net/aspose.gis.geotools.layersmap/maprasteroptions) | r/w | Aspose.Gis.GeoTools.LayersMap.MapRasterOptions によって表現されるラスターレイヤーのオプションのコレクション。 |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | r/w | 使用するレンダラー。デフォルトは Aspose.Gis.Rendering.Renders.Jpeg です。 |
| size_mode | [MapSizeModes](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes) | r/w | サイズモード。デフォルトは [MapSizeModes.AUTO](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/) です。 |
| spatial_reference | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | 空間参照。デフォルトは Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.WebMercator です。 |
| tiles | [MapTilesOptions](/psd/python-net/aspose.gis.geotools.layersmap/maptilesoptions) | r/w | タイルオプション。 |
| width | int | r/w | マップの視覚的な幅。デフォルトは 400 です。[MapSizeModes.CUSTOM](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/) の場合に使用されます。 |


### Constructor: MapOptions() {#MapOptions__1}


```
 MapOptions() 
```

MapOptions クラスの新しいインスタンスを初期化します

