---
title: "GeocentricSpatialReferenceSystemParameters クラス"
type: docs
weight: 60
url: /ja/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/
---

**Summary:** Parameters to create geocentric SRS.<br/>            Parameters have reasonable defaults, so you will have to assign only some of them.<br/>            If you assign <see langword="null" /> to any parameter, a default value will be used.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeocentricSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [GeocentricSpatialReferenceSystemParameters()](#GeocentricSpatialReferenceSystemParameters__1) | GeocentricSpatialReferenceSystemParameters クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| axises_order | [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder) | r/w | 軸の順序。デフォルトは [GeocentricAxisesOrder.XYZ](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/) です。 |
| datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r/w | ジオセントリック SRS のデータム。デフォルトは [GeographicDatum.wgs84](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/) です。 |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | この SRS で使用される単位。デフォルトは [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/) です。 |
| 名前 | string | 読み/書き | ジオセントリック SRS の名前。デフォルトは "Unnamed" です。 |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r/w | この SRS の本初子午線。デフォルトは [PrimeMeridian.greenwich](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/) です。 |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | ジオセントリック SRS の 'X' 次元を表す軸（本初子午線を指す軸）。 |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | ジオセントリック SRS の 'Y' 次元を表す軸（赤道平面上で X 軸の左または右を指す軸）。<br/>            デフォルトは [AxisDirection.EAST](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) 方向の軸です。 |
| z_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | ジオセントリック SRS の 'Z' 次元を表す軸（北極または南極を指す軸）。<br/>            デフォルトは [AxisDirection.NORTH](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) 方向の軸です。 |


### Constructor: GeocentricSpatialReferenceSystemParameters() {#GeocentricSpatialReferenceSystemParameters__1}


```
 GeocentricSpatialReferenceSystemParameters() 
```

GeocentricSpatialReferenceSystemParameters クラスの新しいインスタンスを初期化します。

