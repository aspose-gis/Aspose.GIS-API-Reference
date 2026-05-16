---
title: "GeoJsonOptions クラス"
type: docs
weight: 20
url: /ja/python-net/aspose.gis.formats.geojson/geojsonoptions/
---

**Summary:** Driver-specific options for GeoJSON format.

**Module:** [aspose.gis.formats.geojson](/psd/python-net/aspose.gis.formats.geojson/)

**Full Name:** aspose.gis.formats.geojson.GeoJsonOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [GeoJsonOptions()](#GeoJsonOptions__1) | 新しいインスタンスを作成します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| array_as_string | bool | 読み/書き | 文字列、整数、実数の JSon 配列を文字列として公開するかどうか。 |
| attributes_skip | bool | 読み/書き | 属性の変換を制御します: yes - すべての属性をスキップ |
| auto_id | [AutoIds](/psd/python-net/aspose.gis/autoids) | r/w | ID を自動生成 |
| close_linear_ring | bool | r/w | 各ジオメトリで未閉じの [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) を閉じるかどうかを判定します。デフォルトは <see langword="false" /> です。 |
| create_midpoints | bool | 読み/書き | ジオメトリの各セグメントの中間に新しい点を追加するかどうかを判定します。デフォルトは <see langword="false" /> です。 |
| date_as_string | bool | 読み/書き | JSon の日付/時刻/日時を文字列として公開するかどうか。 |
| delete_near_points | bool | 読み/書き | 各ジオメトリで近接点を削除するかどうかを判定します。デフォルトは <see langword="false" /> です。 |
| delete_near_points_distance | double | r/w | [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/) の距離を決定します。デフォルトは <see langword=\"0\" />です。 |
| 説明 | string | 読み/書き | レイヤー作成用のフィーチャコレクションレベルの説明 |
| geometry_as_collection | bool | 読み/書き | ジオメトリの変換を制御します: yes - ジオメトリを GeometryCollection 型でラップします。 |
| linearization_tolerance | double | 読み/書き | 曲線ジオメトリを直線化するために使用する許容値です。 |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | ジオメトリが [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) に追加されるとき、または [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) から読み込まれるときに M 座標に適用される [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)です。<br/>デフォルト値は [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/) です。 |
| 名前 | string | 読み/書き | レイヤー作成用のフィーチャコレクションレベルの名前 |
| nested_properties_separator | string | 読み/書き | 入れ子属性のコンポーネントを区切るために使用される文字列を取得または設定します。<br/>デフォルトは \"_\" です。 |
| read_bounding_boxes | bool | r/w | バウンディングボックス（'bbox'）を属性として 'bbox_0'、'bbox_1' などの名前で読み取るかどうかを決定します。<br/>            デフォルト値は <see langword=\"false\" /> です。<br/>            [GeoJsonOptions.nested_properties_separator](/psd/python-net/aspose.gis.formats.geojson/geojsonoptions/) 文字列は bbox_0、bbox_1、... の名前で使用されます。 |
| simplify_segments | bool | 読み/書き | 各ジオメトリの同じセグメント上にあるポイントを削除するかどうかを決定します。デフォルトは <see langword=\"false\" />です。 |
| simplify_segments_distance | double | r/w | [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/) の距離を決定します。デフォルトは <see langword=\"0\" />です。 |
| validate_geometries_on_write | bool | r/w | ジオメトリがレイヤーに追加されるときに検証すべきかどうかを決定します。<br/>            <see langword=\"true\" /> に設定されている場合、ジオメトリがレイヤーに追加されるたびに [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) が呼び出され、検証が失敗した場合（[Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) が <see langword=\"false\" />）、[GisException](/psd/python-net/aspose.gis/gisexception/) がスローされます。 |
| write_bounding_boxes | bool | 読み/書き | GeoJSON オブジェクトにそのジオメトリの座標範囲に関する情報を含めるかどうかを決定します。<br/>            <see langword=\"true\" /> に設定すると、レイヤーに追加される各ジオメトリ（null でない）に対してメンバー \"bbox\" が生成されます。<br/>            デフォルト値は <see langword=\"false\" /> です。 |
| write_polygons_as_lines | bool | 読み/書き | ポリゴンまたはマルチポリゴンをラインストリングに変換できるかどうかを決定します。デフォルトは <see langword=\"false\" />です。 |
| write_unset_attribute | bool | 読み/書き | 未設定属性を書き込む際に 'null' 値を追加するかどうか |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | ジオメトリが [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) に追加されるとき、または [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) から読み込まれるときに X および Y 座標に適用される [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)です。<br/>デフォルト値は [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/) です。 |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | ジオメトリが [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) に追加されるとき、または [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) から読み込まれるときに Z 座標に適用される [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)です。<br/>デフォルト値は [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/) です。 |


### Constructor: GeoJsonOptions() {#GeoJsonOptions__1}


```
 GeoJsonOptions() 
```

新しいインスタンスを作成します。

