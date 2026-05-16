---
title: "GeographicSpatialReferenceSystemParameters 클래스"
type: docs
weight: 90
url: /ko/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters/
---

**Summary:** Parameters to create geographic SRS.<br/>            Parameters have reasonable defaults, so you will have to assign only some of them.<br/>            If you assign <see langword="null" /> to any parameter, a default value will be used.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GeographicSpatialReferenceSystemParameters()](#GeographicSpatialReferenceSystemParameters__1) | GeographicSpatialReferenceSystemParameters 클래스의 새 인스턴스를 초기화합니다 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| angular_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | 이 SRS에서 사용할 단위. 기본값은 [Unit.degree](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| axises_order | [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder) | r/w | 축 순서. 기본값은 [GeographicAxisesOrder.LONGITUDE_LATITUDE](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/). |
| datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r/w | 지리 SRS의 기준점. 기본값은 [GeographicDatum.wgs84](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/). |
| latitude_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | 위도를 나타내는 축. 기본값은 북쪽 방향의 축입니다. |
| longitude_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | 경도를 나타내는 축. 기본값은 동쪽 방향의 축입니다. |
| 이름 | string | r/w | 지리 SRS의 이름. 기본값은 "Unnamed". |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r/w | 이 SRS의 기본 자오선. 기본값은 [PrimeMeridian.greenwich](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/)입니다. |


### Constructor: GeographicSpatialReferenceSystemParameters() {#GeographicSpatialReferenceSystemParameters__1}


```
 GeographicSpatialReferenceSystemParameters() 
```

GeographicSpatialReferenceSystemParameters 클래스의 새 인스턴스를 초기화합니다

