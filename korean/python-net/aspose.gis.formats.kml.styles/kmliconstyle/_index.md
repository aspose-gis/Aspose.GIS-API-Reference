---
title: "KmlIconStyle 클래스"
type: docs
weight: 60
url: /ko/python-net/aspose.gis.formats.kml.styles/kmliconstyle/
---

**Summary:** Specifies how icons for kml:Placemarks and kml:PhotoOverlay with a kml:Point geometry are drawn<br/>            in an earth browser's list and geographic views.

**Module:** [aspose.gis.formats.kml.styles](/psd/python-net/aspose.gis.formats.kml.styles/)

**Full Name:** aspose.gis.formats.kml.styles.KmlIconStyle

**Inheritance:** KmlAbstractColorStyle

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [KmlIconStyle()](#KmlIconStyle__1) | KmlIconStyle 클래스의 새 인스턴스를 초기화합니다 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| color | System.Drawing.Color | r/w | 그래픽 요소의 색상을 지정합니다. 기본값은 . |
| color_mode | [KmlColorModes](/psd/python-net/aspose.gis.formats.kml.styles/kmlcolormodes) | r/w | 그래픽 요소의 색상 모드를 지정합니다. 기본값: normal. |
| 제목 | double | r/w | 방향(북, 남, 동, 서), 십진수 도 단위. 값은 0(북)에서 360도까지 범위입니다. 기본값은 '0'입니다. |
| hot_spot | [KmlCoordinate](/psd/python-net/aspose.gis.formats.kml.styles/kmlcoordinate) | r/w | Placemark에 지정된 Point에 고정되는 아이콘의 기준점 위치를 지정합니다.<br/>            기본값은 <see langword="null" />이며, 이는 HotSpot이 누락됨을 의미합니다. |
| resource | [KmlIconResource](/psd/python-net/aspose.gis.formats.kml.styles/kmliconresource) | r/w | 리소스 위치를 지정합니다. 기본값은 <see langword="null" />이며, 이는 아이콘이 누락됨을 의미합니다. |
| scale | double | r/w | 그래픽 요소에 적용될 배율 인자를 지정합니다. 기본값은 '1'입니다. |


### Constructor: KmlIconStyle() {#KmlIconStyle__1}


```
 KmlIconStyle() 
```

KmlIconStyle 클래스의 새 인스턴스를 초기화합니다

