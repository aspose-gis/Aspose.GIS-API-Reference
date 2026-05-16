---
title: "EsriAsciiOptions クラス"
type: docs
weight: 20
url: /ja/python-net/aspose.gis.formats.esriascii/esriasciioptions/
---

**Summary:** Driver-specific options for EsriAscii format.

**Module:** [aspose.gis.formats.esriascii](/psd/python-net/aspose.gis.formats.esriascii/)

**Full Name:** aspose.gis.formats.esriascii.EsriAsciiOptions

**Inheritance:** RasterDriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [EsriAsciiOptions()](#EsriAsciiOptions__1) | 新しいインスタンスを作成します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | 各ジオメトリで未閉じの [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) を閉じるかどうかを判定します。デフォルトは <see langword="false" /> です。 |
| create_midpoints | bool | 読み/書き | ジオメトリの各セグメントの中間に新しい点を追加するかどうかを判定します。デフォルトは <see langword="false" /> です。 |
| delete_near_points | bool | 読み/書き | 各ジオメトリで近接点を削除するかどうかを判定します。デフォルトは <see langword="false" /> です。 |
| delete_near_points_distance | double | r/w | [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/) の距離を決定します。デフォルトは <see langword=\"0\" />です。 |
| linearization_tolerance | double | 読み/書き | 曲線ジオメトリを直線化するために使用する許容値です。 |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | ジオメトリが [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) に追加されるとき、または [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) から読み込まれるときに M 座標に適用される [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)です。<br/>デフォルト値は [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/) です。 |
| simplify_segments | bool | 読み/書き | 各ジオメトリの同じセグメント上にあるポイントを削除するかどうかを決定します。デフォルトは <see langword=\"false\" />です。 |
| simplify_segments_distance | double | r/w | [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/) の距離を決定します。デフォルトは <see langword=\"0\" />です。 |
| validate_geometries_on_write | bool | r/w | ジオメトリがレイヤーに追加されるときに検証すべきかどうかを決定します。<br/>            <see langword=\"true\" /> に設定されている場合、ジオメトリがレイヤーに追加されるたびに [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) が呼び出され、検証が失敗した場合（[Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) が <see langword=\"false\" />）、[GisException](/psd/python-net/aspose.gis/gisexception/) がスローされます。 |
| write_polygons_as_lines | bool | 読み/書き | ポリゴンまたはマルチポリゴンをラインストリングに変換できるかどうかを決定します。デフォルトは <see langword=\"false\" />です。 |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | ジオメトリが [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) に追加されるとき、または [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) から読み込まれるときに X および Y 座標に適用される [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)です。<br/>デフォルト値は [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/) です。 |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | ジオメトリが [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) に追加されるとき、または [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) から読み込まれるときに Z 座標に適用される [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/)です。<br/>デフォルト値は [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/) です。 |


### Constructor: EsriAsciiOptions() {#EsriAsciiOptions__1}


```
 EsriAsciiOptions() 
```

新しいインスタンスを作成します。

