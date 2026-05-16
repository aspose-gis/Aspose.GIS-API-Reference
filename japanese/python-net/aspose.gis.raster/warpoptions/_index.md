---
title: "WarpOptions クラス"
type: docs
weight: 100
url: /ja/python-net/aspose.gis.raster/warpoptions/
---

**Summary:** Options for raster warping.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.WarpOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [WarpOptions()](#WarpOptions__1) | WarpOptions クラスの新しいインスタンスを初期化します |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| cell_height | double | r/w | ラスタセルの新しい高さ（対象のジオリファレンス単位）を指定します。<br/>            値が 0 に設定されている場合、[WarpOptions.cell_height](/psd/python-net/aspose.gis.raster/warpoptions/) は自動的に計算されます。デフォルト値は "0" です。 |
| cell_width | double | r/w | ラスタセルの新しい幅（対象のジオリファレンス単位）を指定します。<br/>            値が 0 に設定されている場合、[WarpOptions.cell_width](/psd/python-net/aspose.gis.raster/warpoptions/) は自動的に計算されます。デフォルト値は "0" です。 |
| default_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | ソース空間参照が欠落している場合の値を指定します。 |
| 高さ | int | 読み/書き | 出力ラスタの高さ（ピクセルと列）を指定します。<br/>            値が 0 に設定されている場合、高さは自動的に計算されます。デフォルト値は "0" です。 |
| target_extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | ワープ対象のラスタレイヤの境界を指定します。<br/>            <see langword="null" /> に設定された場合、ワープ中にラスタのすべてのセルを含むように範囲が計算されます。 |
| target_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | 対象の空間参照を指定します。<br/>            <see langword="null" /> に設定された場合、デフォルトまたはソースの空間参照が使用されます。 |
| width | int | 読み/書き | 出力ラスタの幅（ピクセルと列）を指定します。<br/>            値が 0 に設定されている場合、幅は自動的に計算されます。デフォルト値は "0" です。 |


### Constructor: WarpOptions() {#WarpOptions__1}


```
 WarpOptions() 
```

WarpOptions クラスの新しいインスタンスを初期化します

