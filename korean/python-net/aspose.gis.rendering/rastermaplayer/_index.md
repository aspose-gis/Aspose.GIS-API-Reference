---
title: "RasterMapLayer 클래스"
type: docs
weight: 250
url: /ko/python-net/aspose.gis.rendering/rastermaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a raster layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.RasterMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RasterMapLayer(layer, colorizer, keep_open)](#RasterMapLayer_layer_colorizer_keep_open_1) | 새 인스턴스를 생성합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | r/w | 래스터 셀을 렌더링하는 데 사용할 컬러라이저. |
| opacity | double | r/w | 레이어의 불투명도. |
| resampling | [RasterMapResampling](/psd/python-net/aspose.gis.rendering/rastermapresampling) | r/w | 지도상의 레이어 왜곡 옵션을 지정합니다. |


### Constructor: RasterMapLayer(layer, colorizer, keep_open) {#RasterMapLayer_layer_colorizer_keep_open_1}


```
 RasterMapLayer(layer, colorizer, keep_open) 
```

새 인스턴스를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | 래스터 레이어. |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | 레이어를 렌더링하는 데 사용할 심볼라이저입니다. <see langword=\"null\" />인 경우 기본 컬러라이저가 사용됩니다. |
| keep_open | bool | <see langword=\"true\" />는 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 객체가 해제된 후 레이어를 열어 둡니다; 그렇지 않으면 <see langword=\"false\" />입니다. |

