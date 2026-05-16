---
title: "WarpOptions 클래스"
type: docs
weight: 100
url: /ko/python-net/aspose.gis.raster/warpoptions/
---

**Summary:** Options for raster warping.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.WarpOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WarpOptions()](#WarpOptions__1) | WarpOptions 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cell_height | double | r/w | 래스터 셀의 새로운 높이를 지정합니다(대상 지리 참조 단위 기준).<br/>            값이 0으로 설정되면 [WarpOptions.cell_height](/psd/python-net/aspose.gis.raster/warpoptions/)가 자동으로 계산됩니다. 기본값은 "0"입니다. |
| cell_width | double | r/w | 래스터 셀의 새로운 너비를 지정합니다(대상 지리 참조 단위 기준).<br/>            값이 0으로 설정되면 [WarpOptions.cell_width](/psd/python-net/aspose.gis.raster/warpoptions/)가 자동으로 계산됩니다. 기본값은 "0"입니다. |
| default_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | 소스 공간 참조가 없을 경우 값을 지정합니다. |
| 높이 | int | r/w | 출력 래스터 높이를 픽셀 및 열 단위로 지정합니다.<br/>            값이 0으로 설정되면 높이가 자동으로 계산됩니다. 기본값은 "0"입니다. |
| target_extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | 래스터 레이어를 워핑할 경계를 지정합니다.<br/>            <see langword="null" />으로 설정하면 워핑 중에 래스터의 모든 셀을 포함하도록 범위가 계산됩니다. |
| target_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | 대상 공간 참조를 지정합니다.<br/>            <see langword="null" />으로 설정하면 기본값 또는 소스 공간 참조가 사용됩니다. |
| width | int | r/w | 출력 래스터 너비를 픽셀 및 열 단위로 지정합니다.<br/>            값이 0으로 설정하면 너비가 자동으로 계산됩니다. 기본값은 "0"입니다. |


### Constructor: WarpOptions() {#WarpOptions__1}


```
 WarpOptions() 
```

WarpOptions 클래스의 새 인스턴스를 초기화합니다.

