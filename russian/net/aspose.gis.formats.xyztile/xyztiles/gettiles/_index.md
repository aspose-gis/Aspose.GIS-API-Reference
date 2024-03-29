---
title: XyzTiles.GetTiles
second_title: Справочник по Aspose.GIS for .NET API
description: XyzTiles метод. Загружает плитки по пространственной ограничивающей рамке и уровню масштабирования.
type: docs
weight: 40
url: /ru/net/aspose.gis.formats.xyztile/xyztiles/gettiles/
---
## XyzTiles.GetTiles method

Загружает плитки по пространственной ограничивающей рамке и уровню масштабирования.

```csharp
public IEnumerable<WebTile> GetTiles(int zoom, Extent extent)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| zoom | Int32 | Уровень масштабирования для загрузки тайлов. Самый высокий уровень масштабирования равен 0. Большинство поставщиков плиток имеют около 22 максимальных уровней масштабирования. |
| extent | Extent | Ограничивающая рамка для загрузки тайлов. Пространственная привязка Wgs84 будет использоваться, если она отсутствует. |

### Возвращаемое значение

Веб-плитки.

### Смотрите также

* class [WebTile](../../../aspose.gis.raster.web/webtile/)
* class [Extent](../../../aspose.gis/extent/)
* class [XyzTiles](../)
* пространство имен [Aspose.Gis.Formats.XyzTile](../../xyztiles/)
* сборка [Aspose.GIS](../../../)


