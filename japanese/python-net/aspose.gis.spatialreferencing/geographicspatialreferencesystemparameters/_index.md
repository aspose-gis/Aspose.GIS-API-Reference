---
title: "GeographicSpatialReferenceSystemParameters クラス"
type: docs
weight: 90
url: /ja/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters/
---

**Summary:** Parameters to create geographic SRS.<br/>            Parameters have reasonable defaults, so you will have to assign only some of them.<br/>            If you assign <see langword="null" /> to any parameter, a default value will be used.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [GeographicSpatialReferenceSystemParameters()](#GeographicSpatialReferenceSystemParameters__1) | GeographicSpatialReferenceSystemParameters クラスの新しいインスタンスを初期化します |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| angular_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | この SRS で使用される単位。デフォルトは [Unit.degree](/psd/python-net/aspose.gis.spatialreferencing/unit/) です。 |
| axises_order | [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder) | r/w | 軸の順序。デフォルトは [GeographicAxisesOrder.LONGITUDE_LATITUDE](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/) です。 |
| datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r/w | 地理的 SRS の基準。デフォルトは [GeographicDatum.wgs84](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/) です。 |
| latitude_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | 緯度を表す軸。デフォルトは北方向の軸です。 |
| longitude_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | 経度を表す軸。デフォルトは東方向の軸です。 |
| 名前 | string | 読み/書き | 地理的 SRS の名前。デフォルトは "Unnamed" です。 |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r/w | この SRS の本初子午線。デフォルトは [PrimeMeridian.greenwich](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/) です。 |


### Constructor: GeographicSpatialReferenceSystemParameters() {#GeographicSpatialReferenceSystemParameters__1}


```
 GeographicSpatialReferenceSystemParameters() 
```

GeographicSpatialReferenceSystemParameters クラスの新しいインスタンスを初期化します

