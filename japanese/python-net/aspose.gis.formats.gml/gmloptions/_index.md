---
title: "GmlOptions クラス"
type: docs
weight: 20
url: /ja/python-net/aspose.gis.formats.gml/gmloptions/
---

**Summary:** Driver-specific options for GML format.

**Module:** [aspose.gis.formats.gml](/psd/python-net/aspose.gis.formats.gml/)

**Full Name:** aspose.gis.formats.gml.GmlOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [GmlOptions()](#GmlOptions__1) | 新しいインスタンスを作成します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| application_namespace | string | 読み/書き | これは、gml ドキュメントを生成するために使用されるアプリケーション名前空間として使用されるカスタム名前空間を指定します。 |
| close_linear_ring | bool | r/w | 各ジオメトリで未閉じの [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) を閉じるかどうかを判定します。デフォルトは <see langword="false" /> です。 |
| create_midpoints | bool | 読み/書き | ジオメトリの各セグメントの中間に新しい点を追加するかどうかを判定します。デフォルトは <see langword="false" /> です。 |
| delete_near_points | bool | 読み/書き | 各ジオメトリで近接点を削除するかどうかを判定します。デフォルトは <see langword="false" /> です。 |
| delete_near_points_distance | double | r/w | [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/) の距離を決定します。デフォルトは <see langword=\"0\" />です。 |
| linearization_tolerance | double | 読み/書き | 曲線ジオメトリを直線化するために使用する許容値です。 |
| load_schemas_from_internet | bool | 読み/書き | Aspose.GIS がインターネットから XML スキーマをロードできるかどうかを決定します。<br/>            <see langword=\"false\" /> に設定された場合、'file://' で始まらない絶対 URI を持つスキーマはロードされません。<br/>            デフォルトは <see langword=\"false\" /> です。 |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | ジオメトリが [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) に追加されるとき、または [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) から読み込まれるときに M 座標に適用される [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)です。<br/>デフォルト値は [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/) です。 |
| nested_properties_separator | string | 読み/書き | 入れ子属性のコンポーネントを区切るために使用される文字列を取得または設定します。<br/>デフォルトは \"_\" です。 |
| restore_schema | bool | 読み/書き | Aspose.GIS が XML スキーマが欠落しているかロードできない Gml ファイル内の属性を解析できるかどうかを決定します。<br/>            <see langword=\"true\" /> に設定された場合、Aspose.GIS リーダーは XML スキーマの存在を必要としません。<br/>            デフォルトは <see langword=\"false\" /> です。 |
| schema_location | string | r/w | スペースで区切られた URI ペアのリストです。各ペアの最初の URI は名前空間の URI で、2 番目の URI は名前空間の XML スキーマへのパスです。<br/>            <see langword=\"null\" /> に設定された場合、[GmlDriver](/psd/python-net/aspose.gis.formats.gml/gmldriver/) はドキュメントのルート要素から schemaLocation を読み取ろうとします。<br/>            デフォルトは <see langword=\"null\" /> です。 |
| simplify_segments | bool | 読み/書き | 各ジオメトリの同じセグメント上にあるポイントを削除するかどうかを決定します。デフォルトは <see langword=\"false\" />です。 |
| simplify_segments_distance | double | r/w | [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/) の距離を決定します。デフォルトは <see langword=\"0\" />です。 |
| validate_geometries_on_write | bool | r/w | ジオメトリがレイヤーに追加されるときに検証すべきかどうかを決定します。<br/>            <see langword=\"true\" /> に設定されている場合、ジオメトリがレイヤーに追加されるたびに [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) が呼び出され、検証が失敗した場合（[Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) が <see langword=\"false\" />）、[GisException](/psd/python-net/aspose.gis/gisexception/) がスローされます。 |
| write_polygons_as_lines | bool | 読み/書き | ポリゴンまたはマルチポリゴンをラインストリングに変換できるかどうかを決定します。デフォルトは <see langword=\"false\" />です。 |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | ジオメトリが [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) に追加されるとき、または [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) から読み込まれるときに X および Y 座標に適用される [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)です。<br/>デフォルト値は [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/) です。 |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | ジオメトリが [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) に追加されるとき、または [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) から読み込まれるときに Z 座標に適用される [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)です。<br/>デフォルト値は [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/) です。 |


### Constructor: GmlOptions() {#GmlOptions__1}


```
 GmlOptions() 
```

新しいインスタンスを作成します。

