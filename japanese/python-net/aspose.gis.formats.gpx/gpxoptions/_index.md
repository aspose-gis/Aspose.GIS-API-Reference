---
title: "GpxOptions クラス"
type: docs
weight: 20
url: /ja/python-net/aspose.gis.formats.gpx/gpxoptions/
---

**Summary:** Driver-specific options for GPX format.

**Module:** [aspose.gis.formats.gpx](/psd/python-net/aspose.gis.formats.gpx/)

**Full Name:** aspose.gis.formats.gpx.GpxOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [GpxOptions()](#GpxOptions__1) | 新しいインスタンスを作成します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | 各ジオメトリで未閉じの [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) を閉じるかどうかを判定します。デフォルトは <see langword="false" /> です。 |
| create_midpoints | bool | 読み/書き | ジオメトリの各セグメントの中間に新しい点を追加するかどうかを判定します。デフォルトは <see langword="false" /> です。 |
| delete_near_points | bool | 読み/書き | 各ジオメトリで近接点を削除するかどうかを判定します。デフォルトは <see langword="false" /> です。 |
| delete_near_points_distance | double | r/w | [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/) の距離を決定します。デフォルトは <see langword=\"0\" />です。 |
| linearization_tolerance | double | 読み/書き | 曲線ジオメトリを直線化するために使用する許容値です。 |
| m_attribute | string | r/w | どの GPX 属性がウェイポイント、ルートポイント、トラックポイントの 'M' 座標としてエクスポートされるかを決定します。<br/>            動作は [GpxOptions.z_attribute](/psd/python-net/aspose.gis.formats.gpx/gpxoptions/) と同じで、デフォルトは <see langword=\"null\" /> です。 |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | ジオメトリが [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) に追加されるとき、または [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) から読み込まれるときに M 座標に適用される [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)です。<br/>デフォルト値は [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/) です。 |
| nested_attribute_separator | string | r | ネストされた属性名とそのインデックスを区切る文字列です。デフォルトは二重アンダースコア \"__\" です。 |
| read_nested_attributes | bool | 読み/書き | GPX ポイント（例: 'trkpt' や 'rtept'）が内部属性を含むか、そしてそれを読み取るかどうかを決定します。デフォルトは <see langword=\"false\" /> です。 |
| simplify_segments | bool | 読み/書き | 各ジオメトリの同じセグメント上にあるポイントを削除するかどうかを決定します。デフォルトは <see langword=\"false\" />です。 |
| simplify_segments_distance | double | r/w | [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/) の距離を決定します。デフォルトは <see langword=\"0\" />です。 |
| validate_geometries_on_write | bool | r/w | ジオメトリがレイヤーに追加されるときに検証すべきかどうかを決定します。<br/>            <see langword=\"true\" /> に設定されている場合、ジオメトリがレイヤーに追加されるたびに [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) が呼び出され、検証が失敗した場合（[Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) が <see langword=\"false\" />）、[GisException](/psd/python-net/aspose.gis/gisexception/) がスローされます。 |
| write_polygons_as_lines | bool | 読み/書き | ポリゴンまたはマルチポリゴンをラインストリングに変換できるかどうかを決定します。デフォルトは <see langword=\"false\" />です。 |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | ジオメトリが [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) に追加されるとき、または [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) から読み込まれるときに X および Y 座標に適用される [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)です。<br/>デフォルト値は [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/) です。 |
| z_attribute | string | 読み/書き | どの GPX 属性がウェイポイント、ルートポイント、トラックポイントの 'Z' 座標としてエクスポートされるかを決定します。<br/>            <see langword=\"null\" /> の場合、'Z' 座標としてエクスポートされる属性はありません。<br/>            デフォルトは \"ele\" です。<br/>            可能な値は、double として表現できるすべての GPX XML 属性名（例: \"speed\", \"magvar\", \"geoidheight\" など）です。 |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | ジオメトリが [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) に追加されるとき、または [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) から読み込まれるときに Z 座標に適用される [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)です。<br/>デフォルト値は [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/) です。 |


### Constructor: GpxOptions() {#GpxOptions__1}


```
 GpxOptions() 
```

新しいインスタンスを作成します。

