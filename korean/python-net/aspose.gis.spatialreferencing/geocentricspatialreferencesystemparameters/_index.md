---
title: "GeocentricSpatialReferenceSystemParameters 클래스"
type: docs
weight: 60
url: /ko/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/
---

**Summary:** Parameters to create geocentric SRS.<br/>            Parameters have reasonable defaults, so you will have to assign only some of them.<br/>            If you assign <see langword="null" /> to any parameter, a default value will be used.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeocentricSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GeocentricSpatialReferenceSystemParameters()](#GeocentricSpatialReferenceSystemParameters__1) | GeocentricSpatialReferenceSystemParameters 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| axises_order | [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder) | r/w | 축 순서. 기본값은 [GeocentricAxisesOrder.XYZ](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/)입니다. |
| datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r/w | 지구 중심 SRS의 데이터. 기본값은 [GeographicDatum.wgs84](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/)입니다. |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | 이 SRS에서 사용할 단위. 기본값은 [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/)입니다. |
| 이름 | string | r/w | 지구 중심 SRS의 이름. 기본값은 "Unnamed"입니다. |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r/w | 이 SRS의 기본 자오선. 기본값은 [PrimeMeridian.greenwich](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/)입니다. |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | 지구 중심 SRS의 'X' 차원을 설명하는 축(기본 자오선을 가리키는 축). |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | 지구 중심 SRS의 'Y' 차원을 설명하는 축(적도면에서 X 축의 왼쪽 또는 오른쪽을 가리키는 축).<br/>            기본값은 [AxisDirection.EAST](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) 방향의 축입니다. |
| z_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | 지구 중심 SRS의 'Z' 차원을 설명하는 축(북극 또는 남극을 가리키는 축).<br/>            기본값은 [AxisDirection.NORTH](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) 방향의 축입니다. |


### Constructor: GeocentricSpatialReferenceSystemParameters() {#GeocentricSpatialReferenceSystemParameters__1}


```
 GeocentricSpatialReferenceSystemParameters() 
```

GeocentricSpatialReferenceSystemParameters 클래스의 새 인스턴스를 초기화합니다.

