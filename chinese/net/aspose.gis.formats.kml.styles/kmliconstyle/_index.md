---
title: "类 KmlIconStyle"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.Formats.Kml.Styles.KmlIconStyle 类。指定带有 kmlPoint 几何的 kmlPlacemarks 和 kmlPhotoOverlay 的图标在地球浏览器列表和地理视图中的绘制方式"
type: docs
weight: 2130
url: /zh/net/aspose.gis.formats.kml.styles/kmliconstyle/
---
## KmlIconStyle class

指定在地球浏览器的列表和地理视图中，如何绘制针对 kml:Placemarks 和 kml:PhotoOverlay（使用 kml:Point 几何）的图标。

```csharp
public class KmlIconStyle : KmlAbstractColorStyle
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [KmlIconStyle](kmliconstyle/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Color](../../aspose.gis.formats.kml.styles/kmlabstractcolorstyle/color/) { get; set; } | 指定图形元素的颜色。 默认值 白色。 |
| [ColorMode](../../aspose.gis.formats.kml.styles/kmlabstractcolorstyle/colormode/) { get; set; } | 指定图形元素的颜色模式。 默认值： 正常。 |
| [Heading](../../aspose.gis.formats.kml.styles/kmliconstyle/heading/) { get; set; } | 方向（北、南、东、西），以十进制度表示。取值范围为 0（北）至 360 度。默认值为 '0'。 |
| [HotSpot](../../aspose.gis.formats.kml.styles/kmliconstyle/hotspot/) { get; set; } | 指定锚定在 Placemark 中指定的 Point 上的图标参考点位置。默认值为 `null` 表示缺少 HotSpot。 |
| [Resource](../../aspose.gis.formats.kml.styles/kmliconstyle/resource/) { get; set; } | 指定资源位置。默认值为 `null` 表示缺少 Icon。 |
| [Scale](../../aspose.gis.formats.kml.styles/kmliconstyle/scale/) { get; set; } | 指定应应用于图形元素的缩放因子。默认值为 '1'。 |

### 另见

* class [KmlAbstractColorStyle](../kmlabstractcolorstyle/)
* namespace [Aspose.Gis.Formats.Kml.Styles](../../aspose.gis.formats.kml.styles/)
* assembly [Aspose.GIS](../../)


