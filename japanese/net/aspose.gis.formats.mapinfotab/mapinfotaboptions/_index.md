---
title: Class MapInfoTabOptions
second_title: Aspose.GIS for .NET API リファレンス
description: Aspose.Gis.Formats.MapInfoTab.MapInfoTabOptions クラス. MapInfo タブ形式のドライバー固有のオプション.
type: docs
weight: 610
url: /ja/net/aspose.gis.formats.mapinfotab/mapinfotaboptions/
---
## MapInfoTabOptions class

MapInfo タブ形式のドライバー固有のオプション.

```csharp
public class MapInfoTabOptions : DriverOptions
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [MapInfoTabOptions](mapinfotaboptions/)() | 新しいインスタンスを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [BlockSize](../../aspose.gis.formats.mapinfotab/mapinfotaboptions/blocksize/) { get; set; } | '*.map' ファイルのブロック サイズ (512 の倍数)。デフォルトは 16384 です。有効な値: 512 ～ 32256. |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring/) { get; set; } | 閉じていないものを閉じるかどうかを決定しますLinearRing各ジオメトリで。デフォルトは`false` . |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints/) { get; set; } | ジオメトリの各セグメントの中間に新しいポイントを追加するかどうかを決定します。デフォルトは`false` . |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints/) { get; set; } | 各ジオメトリの近くのポイントを削除するかどうかを決定します。デフォルトは`false` . |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance/) { get; set; } | の距離を決定します[`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints/).デフォルトは`0` . |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance/) { get; set; } | 曲線ジオメトリを線形化するために使用する許容差. |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel/) { get; set; } | A[`PrecisionModel`](../../aspose.gis/precisionmodel/)ジオメトリが[`VectorLayer`](../../aspose.gis/vectorlayer/)またはそれらが[`VectorLayer`](../../aspose.gis/vectorlayer/). デフォルト値は[`Exact`](../../aspose.gis/precisionmodel/exact/) . |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments/) { get; set; } | 各ジオメトリの同じセグメントにあるポイントを削除するかどうかを決定します。デフォルトは`false` . |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance/) { get; set; } | の距離を決定します[`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments/).デフォルトは`0` . |
| [TextStringAttribute](../../aspose.gis.formats.mapinfotab/mapinfotaboptions/textstringattribute/) { get; set; } | 「テキスト」グラフィカル オブジェクトのテキストを表す属性の名前を指定します。 |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite/) { get; set; } | レイヤーにジオメトリを追加するときにジオメトリを検証する必要があるかどうかを決定します. に設定されている場合`true`、[`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) each ジオメトリがレイヤーに追加されたときに呼び出され、検証が失敗した場合 ([`IsValid`](../../aspose.gis.geometries/geometry/isvalid/)は`false`)、[`GisException`](../../aspose.gis/gisexception/)スローされます. |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines/) { get; set; } | ポリゴンまたはマルチポリゴンから折れ線への変換を許可するかどうかを決定します。デフォルトは`false` . |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel/) { get; set; } | A[`PrecisionModel`](../../aspose.gis/precisionmodel/)ジオメトリが[`VectorLayer`](../../aspose.gis/vectorlayer/)またはそれらが[`VectorLayer`](../../aspose.gis/vectorlayer/). デフォルト値は[`Exact`](../../aspose.gis/precisionmodel/exact/) . |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel/) { get; set; } | A[`PrecisionModel`](../../aspose.gis/precisionmodel/)ジオメトリが[`VectorLayer`](../../aspose.gis/vectorlayer/)またはそれらが[`VectorLayer`](../../aspose.gis/vectorlayer/). デフォルト値は[`Exact`](../../aspose.gis/precisionmodel/exact/) . |

### 関連項目

* class [DriverOptions](../../aspose.gis/driveroptions/)
* 名前空間 [Aspose.Gis.Formats.MapInfoTab](../../aspose.gis.formats.mapinfotab/)
* 組み立て [Aspose.GIS](../../)

