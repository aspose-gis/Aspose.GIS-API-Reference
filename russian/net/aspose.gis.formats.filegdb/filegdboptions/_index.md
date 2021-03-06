---
title: FileGdbOptions
second_title: Справочник по Aspose.GIS for .NET API
description: Опции драйвера для формата FileGDB.
type: docs
weight: 240
url: /ru/net/aspose.gis.formats.filegdb/filegdboptions/
---
## FileGdbOptions class

Опции драйвера для формата FileGDB.

```csharp
public sealed class FileGdbOptions : DriverOptions
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [FileGdbOptions](filegdboptions)() | Создать новый экземпляр. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring) { get; set; } | Определяет, закрывается ли незамкнутыйLinearRingв каждой геометрии. По умолчанию`false`. |
| [CoordinatePrecisionGrid](../../aspose.gis.formats.filegdb/filegdboptions/coordinateprecisiongrid) { get; set; } | Сетка точности координат для использования в новом слое. |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints) { get; set; } | Определяет, добавлять ли новую точку посередине к каждому сегменту геометрии. По умолчанию`false`. |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints) { get; set; } | Определяет, удалять ли ближайшие точки в каждой геометрии. По умолчанию`false`. |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance) { get; set; } | Определяет расстояние для[`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints). По умолчанию`0`. |
| [EnsureValidCoordinatesRange](../../aspose.gis.formats.filegdb/filegdboptions/ensurevalidcoordinatesrange) { get; set; } | Должны ли координаты находиться в допустимом диапазоне. |
| [GeometryFieldName](../../aspose.gis.formats.filegdb/filegdboptions/geometryfieldname) { get; set; } | Имя поля геометрии. |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance) { get; set; } | Допуск, используемый для линеаризации геометрии кривых. |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel) { get; set; } | A[`PrecisionModel`](../../aspose.gis/precisionmodel)который будет применен к координате M при добавлении геометрии к[`VectorLayer`](../../aspose.gis/vectorlayer)или когда они читаются из[`VectorLayer`](../../aspose.gis/vectorlayer). Значение по умолчанию:[`Exact`](../../aspose.gis/precisionmodel/exact). |
| [MTolerance](../../aspose.gis.formats.filegdb/filegdboptions/mtolerance) { get; set; } | Допуск привязки M. |
| [ObjectIdFieldName](../../aspose.gis.formats.filegdb/filegdboptions/objectidfieldname) { get; set; } | Имя поля идентификатора объекта. |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments) { get; set; } | Определяет, удаляются ли точки, лежащие на одном сегменте в каждой геометрии. По умолчанию`false`. |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance) { get; set; } | Определяет расстояние для[`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments). По умолчанию`0`. |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite) { get; set; } | Определяет, следует ли проверять геометрию при ее добавлении в слой. Если установлено значение`true`,[`IsValid`](../../aspose.gis.geometries/geometry/isvalid)вызывается для каждого геометрия, когда она добавляется к слою, и если проверка не пройдена ([`IsValid`](../../aspose.gis.geometries/geometry/isvalid)is`false`),TВыбрасывается:Aspose.Gis.GisException. |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines) { get; set; } | Определяет, разрешено ли преобразование полигона или мультиполигона в строку. По умолчанию`false`. |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel) { get; set; } | A[`PrecisionModel`](../../aspose.gis/precisionmodel)который будет применяться к координатам X и Y когда геометрия добавляются в[`VectorLayer`](../../aspose.gis/vectorlayer)или когда они считываются из[`VectorLayer`](../../aspose.gis/vectorlayer). Значение по умолчанию:[`Exact`](../../aspose.gis/precisionmodel/exact). |
| [XYTolerance](../../aspose.gis.formats.filegdb/filegdboptions/xytolerance) { get; set; } | Допуск привязки X и Y. |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel) { get; set; } | A[`PrecisionModel`](../../aspose.gis/precisionmodel)который будет применен к координате Z при добавлении геометрии к[`VectorLayer`](../../aspose.gis/vectorlayer)или когда они читаются из[`VectorLayer`](../../aspose.gis/vectorlayer). Значение по умолчанию:[`Exact`](../../aspose.gis/precisionmodel/exact). |
| [ZTolerance](../../aspose.gis.formats.filegdb/filegdboptions/ztolerance) { get; set; } | Допуск привязки Z. |

### Смотрите также

* class [DriverOptions](../../aspose.gis/driveroptions)
* пространство имен [Aspose.Gis.Formats.FileGdb](../../aspose.gis.formats.filegdb)
* сборка [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
