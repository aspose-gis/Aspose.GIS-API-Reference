---
title: "KmlIconStyle 类"
type: docs
weight: 60
url: /zh/python-net/aspose.gis.formats.kml.styles/kmliconstyle/
---

**Summary:** Specifies how icons for kml:Placemarks and kml:PhotoOverlay with a kml:Point geometry are drawn<br/>            in an earth browser's list and geographic views.

**Module:** [aspose.gis.formats.kml.styles](/psd/python-net/aspose.gis.formats.kml.styles/)

**Full Name:** aspose.gis.formats.kml.styles.KmlIconStyle

**Inheritance:** KmlAbstractColorStyle

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [KmlIconStyle()](#KmlIconStyle__1) | 初始化 KmlIconStyle 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| 颜色 | System.Drawing.Color | r/w | 指定图形元素的颜色。默认值为 . |
| color_mode | [KmlColorModes](/psd/python-net/aspose.gis.formats.kml.styles/kmlcolormodes) | r/w | 指定图形元素的颜色模式。默认值：normal。 |
| 标题 | double | r/w | 方向（北、南、东、西），以十进制度表示。取值范围为 0（北）至 360 度。默认值为 '0'。 |
| hot_spot | [KmlCoordinate](/psd/python-net/aspose.gis.formats.kml.styles/kmlcoordinate) | r/w | 指定锚定在 Placemark 中指定的 Point 上的图标参考点的位置。<br/>            默认值为 <see langword="null" />，表示未设置 HotSpot。 |
| resource | [KmlIconResource](/psd/python-net/aspose.gis.formats.kml.styles/kmliconresource) | r/w | 指定资源位置。默认值为 <see langword="null" />，表示未提供 Icon。 |
| 比例 | double | r/w | 指定应应用于图形元素的缩放因子。默认值为 '1'。 |


### Constructor: KmlIconStyle() {#KmlIconStyle__1}


```
 KmlIconStyle() 
```

初始化 KmlIconStyle 类的新实例

