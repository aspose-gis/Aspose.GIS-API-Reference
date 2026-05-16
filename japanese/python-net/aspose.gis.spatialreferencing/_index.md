---
title: "aspose.gis.spatialreferencing"
type: docs
weight: 790
url: /ja/python-net/aspose.gis.spatialreferencing/
---




## **Classes**
| **クラス** | **説明** |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) | 軸は SRS の 1 次元を表します。 |
| [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/) | 別の測地系に変換するための Bursa-Wolf 公式のパラメータを含むクラスです。 |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) | Compound SRS は 2 つの基礎 SRS を結合しますが、どちらもコンパウンドにできません。 |
| [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid/) | Ellipsoid は地球を近似する楕円体を表します。 |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/) | Geocentric SRS は、地球中心を原点とする 3 次元デカルト SRS です。 |
| [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/) | ジオセントリック SRS を作成するためのパラメータです。<br/>            パラメータには妥当なデフォルトが設定されているため、いくつかだけを割り当てればよいです。<br/>            任意のパラメータに <see langword=\"null\" /> を割り当てた場合、デフォルト値が使用されます。 |
| [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/) | 測地系は経度と緯度を地球上の特定の場所に関連付けます。 |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) | Geographic SRS は経度と緯度に基づく SRS です。<br/>            Geographic SRS は 2 次元または 3 次元にすることができます。<br/>            3 次元の Geographic SRS は、実際には 2 次元 SRS と垂直 SRS からなるコンパウンド SRS です。 |
| [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters/) | Geographic SRS を作成するためのパラメータです。<br/>            パラメータには妥当なデフォルトが設定されているため、いくつかだけを割り当てればよいです。<br/>            任意のパラメータに <see langword=\"null\" /> を割り当てた場合、デフォルト値が使用されます。 |
| [IdentifiableObject](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/) | EPSG コードと名前を持つ可能性があるオブジェクトを表します。 |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) | 識別子を表します。これはオブジェクトの外部記述への参照です。<br/>            WKT から SRS を作成する場合、[Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) は \"AUTHORITY\" キーワードに対応します。 |
| [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum/) | ローカル空間参照系で測定に使用される方法を示します。 |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/) | ローカルSRSは地球ではなく、あるオブジェクトに関連する座標です。 |
| [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/) | プライム・メリディアンは経度が0と定義される子午線を表します。 |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/) | 投影SRSは、地理的SRSに投影を適用した結果です。<br/>            投影SRSは2次元または3次元になる可能性があります。<br/>            投影SRSが3次元の場合、実際には2次元投影SRSと1次元垂直SRSからなる複合SRSです。 |
| [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) | 投影SRSを作成するためのパラメータです。一部のパラメータにはデフォルトがあります。<br/>            いくつかのパラメータは妥当なデフォルトを持つため、必ずしもそれらだけを指定する必要はありません。<br/>            それらのパラメータに <see langword="null" /> を割り当てた場合、デフォルト値が使用されます。<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) と [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) にはデフォルトがありません -<br/>            これらのプロパティには <see langword="null" /> 以外の値を割り当てる必要があります。 |
| [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/) | パラメータ付きの投影法を表し、(経度, 緯度) を (x, y) に変換します。 |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 空間参照系は座標を地球上の場所にマッピングします。<br/>            SRSにはさまざまなタイプがあり、[SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) を参照してください。<br/>            さらに、SRSのタイプが [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) または<br/>            [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) の場合、SRSは複合または単一になり得ます。[SpatialReferenceSystem.is_compound](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) を参照してください。 |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) | 空間参照系変換は、ジオメトリをソース空間参照系からターゲット空間参照系へ変換します。 |
| [TransformationException](/psd/python-net/aspose.gis.spatialreferencing/transformationexception/) | 座標の変換中または変換の作成中にエラーが発生した場合、Transformation例外がスローされます。 |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) | 測定単位を表します。 |
| [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum/) | 垂直測定に使用される方法を示します。 |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/) | 垂直SRSは高さ座標を記述する1次元のSRSです。 |
## **Enumerations**
| **列挙** | **説明** |
| :- | :- |
| [AxisDirection](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) | 軸方向は軸が指す方向を定義します。 |
| [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/) | ジオセントリックSRSにおける軸の順序を表します。 |
| [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/) | 地理的SRSにおける軸の順序を表します。 |
| [ParameterType](/psd/python-net/aspose.gis.spatialreferencing/parametertype/) | [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/) のパラメータのタイプを決定します。 |
| [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/) | 地理的SRSにおける軸の順序を表します。 |
| [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) | 空間参照系のタイプを表します。 |
