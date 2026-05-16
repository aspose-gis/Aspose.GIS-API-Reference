---
title: "MapOptions 클래스"
type: docs
weight: 30
url: /ko/python-net/aspose.gis.geotools.layersmap/mapoptions/
---

**Summary:** Map Options for creating maps using [LayersMapBuilder](/psd/python-net/aspose.gis.geotools.layersmap/layersmapbuilder/)

**Module:** [aspose.gis.geotools.layersmap](/psd/python-net/aspose.gis.geotools.layersmap/)

**Full Name:** aspose.gis.geotools.layersmap.MapOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MapOptions()](#MapOptions__1) | MapOptions 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | r/w | 지도의 배경 색상. 기본값은 System.Drawing.Color.Transparent입니다. |
| height | int | r/w | 지도의 시각적 높이. 기본값은 400입니다. [MapSizeModes.CUSTOM](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/)인 경우에 사용됩니다. |
| layers | [MapLayerOptions[]](/psd/python-net/aspose.gis.geotools.layersmap/maplayeroptions) | r/w | Aspose.Gis.GeoTools.LayersMap.MapLayerOptions에 의해 표현되는 벡터 레이어 옵션 모음. |
| rasters | [MapRasterOptions[]](/psd/python-net/aspose.gis.geotools.layersmap/maprasteroptions) | r/w | Aspose.Gis.GeoTools.LayersMap.MapRasterOptions에 의해 표현되는 래스터 레이어 옵션 모음. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | r/w | 사용할 렌더러. 기본값은 Aspose.Gis.Rendering.Renders.Jpeg입니다. |
| size_mode | [MapSizeModes](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes) | r/w | 크기 모드. 기본값은 [MapSizeModes.AUTO](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/)입니다. |
| spatial_reference | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | 공간 참조. 기본값은 Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.WebMercator입니다. |
| tiles | [MapTilesOptions](/psd/python-net/aspose.gis.geotools.layersmap/maptilesoptions) | r/w | 타일 옵션. |
| width | int | r/w | 지도의 시각적 너비. 기본값은 400입니다. [MapSizeModes.CUSTOM](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/)인 경우에 사용됩니다. |


### Constructor: MapOptions() {#MapOptions__1}


```
 MapOptions() 
```

MapOptions 클래스의 새 인스턴스를 초기화합니다.

