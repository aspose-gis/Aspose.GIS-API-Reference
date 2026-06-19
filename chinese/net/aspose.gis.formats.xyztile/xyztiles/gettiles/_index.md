---
title: "XyzTiles.GetTiles"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "XyzTiles 方法。根据空间边界框和缩放级别加载瓦片"
type: docs
weight: 40
url: /zh/net/aspose.gis.formats.xyztile/xyztiles/gettiles/
---
## XyzTiles.GetTiles method

按空间边界框和缩放级别加载瓦片。

```csharp
public IEnumerable<WebTile> GetTiles(int zoom, Extent extent)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 缩放 | Int32 | 用于加载瓦片的缩放级别。最高缩放级别为 0。大多数瓦片提供商的最大缩放级别约为 22。 |
| 范围 | 范围 | 用于加载瓦片的边界框。如果未提供，将使用 Wgs84 空间参考。 |

### 返回值

网络瓦片。

### 另见

* class [WebTile](../../../aspose.gis.raster.web/webtile/)
* class [Extent](../../../aspose.gis/extent/)
* class [XyzTiles](../)
* namespace [Aspose.Gis.Formats.XyzTile](../../xyztiles/)
* assembly [Aspose.GIS](../../../)


