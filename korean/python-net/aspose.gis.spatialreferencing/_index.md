---
title: "aspose.gis.spatialreferencing"
type: docs
weight: 790
url: /ko/python-net/aspose.gis.spatialreferencing/
---




## **Classes**
| **Class** | **Description** |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) | 축은 SRS의 한 차원을 설명합니다. |
| [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/) | 다른 기준점으로 변환하기 위한 Bursa-Wolf 공식의 매개변수를 포함하는 클래스입니다. |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) | 복합 SRS는 두 개의 기본 SRS를 결합하지만, 그 중 어느 것도 복합일 수 없습니다. |
| [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid/) | Ellipsoid는 지구를 근사하는 타원체를 나타냅니다. |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/) | 지오센트릭 SRS는 지구 중심을 원점으로 하는 3차원 직교 SRS입니다. |
| [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/) | 지오센트릭 SRS를 생성하기 위한 매개변수입니다.<br/>            매개변수는 합리적인 기본값을 가지고 있으므로 일부만 지정하면 됩니다.<br/>            어떤 매개변수에 <see langword="null" />을 할당하면 기본값이 사용됩니다. |
| [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/) | 지리 기준점은 경도와 위도를 지구상의 특정 위치와 연결합니다. |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) | 지리적 SRS는 경도와 위도를 기반으로 하는 SRS입니다.<br/>            지리적 SRS는 2차원일 수도 있고 3차원일 수도 있습니다.<br/>            지리적 SRS가 3차원인 경우, 실제로는 2차원 SRS와 수직 SRS로 구성된 복합 SRS입니다. |
| [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters/) | 지리적 SRS를 생성하기 위한 매개변수입니다.<br/>            매개변수는 합리적인 기본값을 가지고 있으므로 일부만 지정하면 됩니다.<br/>            어떤 매개변수에 <see langword="null" />을 할당하면 기본값이 사용됩니다. |
| [IdentifiableObject](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/) | EPSG 코드와 이름을 가질 수 있는 객체를 나타냅니다. |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) | 식별자를 나타냅니다 - 객체의 외부 설명에 대한 참조입니다.<br/>            WKT에서 SRS를 생성하면, [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/)가 "AUTHORITY" 키워드에 해당합니다. |
| [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum/) | 지역 공간 기준 시스템에서 측정에 사용되는 방법을 나타냅니다. |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/) | 지역 SRS와 관련된 좌표는 지구가 아니라 특정 객체에 대한 것입니다. |
| [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/) | PrimeMeridian은 경도가 0으로 정의되는 자오선을 나타냅니다. |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/) | Projected SRS는 지리적 SRS에 투영을 적용한 결과입니다.<br/>            Projected SRS는 2차원 또는 3차원일 수 있습니다.<br/>            Projected SRS가 3차원인 경우, 실제로는 2차원 투영 SRS와 1차원 수직 SRS로 구성된 복합 SRS입니다. |
| [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) | Projected SRS를 생성하기 위한 매개변수입니다. 일부 매개변수에는 기본값이 있습니다.<br/>            일부 매개변수는 합리적인 기본값을 가지고 있으므로 해당 값만 지정하면 됩니다.<br/>            해당 매개변수에 <see langword="null" />을 할당하면 기본값이 사용됩니다.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) 및 [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/)에는 기본값이 없으며 -<br/>            이 속성에 <see langword="null" />이 아닌 값을 할당해야 합니다. |
| [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/) | 매개변수를 갖는 투영 방법을 나타내며, (경도, 위도)를 (x, y)로 변환합니다. |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 공간 기준 시스템은 좌표를 지구상의 위치에 매핑합니다.<br/>            다양한 유형의 SRS가 있으며, [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)을 참조하십시오.<br/>            또한, SRS 유형이 [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) 또는<br/>            [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/)인 경우, SRS는 복합 또는 단일일 수 있으며, [SpatialReferenceSystem.is_compound](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)을 참조하십시오. |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) | 공간 기준 시스템 변환은 기하학 객체를 소스 공간 기준 시스템에서 대상 공간 기준 시스템으로 변환합니다. |
| [TransformationException](/psd/python-net/aspose.gis.spatialreferencing/transformationexception/) | 좌표 변환 중 또는 변환 생성 중 오류가 발생하면 변환 예외가 발생합니다. |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) | 측정 단위를 나타냅니다. |
| [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum/) | 수직 측정에 사용되는 방법을 나타냅니다. |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/) | Vertical SRS는 높이 좌표를 설명하는 1차원 SRS입니다. |
## **Enumerations**
| **Enumeration** | **Description** |
| :- | :- |
| [AxisDirection](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) | 축 방향은 축이 가리키는 방향을 정의합니다. |
| [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/) | 지구 중심 SRS에서 축의 순서를 나타냅니다. |
| [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/) | 지리적 SRS에서 축의 순서를 나타냅니다. |
| [ParameterType](/psd/python-net/aspose.gis.spatialreferencing/parametertype/) | [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/)에서 매개변수 유형을 결정합니다. |
| [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/) | 지리적 SRS에서 축의 순서를 나타냅니다. |
| [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) | 공간 기준 시스템의 유형을 나타냅니다. |
