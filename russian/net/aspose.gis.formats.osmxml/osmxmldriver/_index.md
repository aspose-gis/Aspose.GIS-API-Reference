---
title: Class OsmXmlDriver
second_title: Справочник по Aspose.GIS for .NET API
description: Aspose.Gis.Formats.OsmXml.OsmXmlDriver сорт. Драйвер для формата OSM XML.
type: docs
weight: 620
url: /ru/net/aspose.gis.formats.osmxml/osmxmldriver/
---
## OsmXmlDriver class

Драйвер для формата OSM XML.

```csharp
public sealed class OsmXmlDriver : FileDriver
```

## Характеристики

| Имя | Описание |
| --- | --- |
| override [CanCreateDatasets](../../aspose.gis.formats.osmxml/osmxmldriver/cancreatedatasets/) { get; } | Получает значение, указывающее, может ли этот драйвер создавать наборы данных. |
| override [CanCreateLayers](../../aspose.gis.formats.osmxml/osmxmldriver/cancreatelayers/) { get; } | Получает значение, указывающее, может ли этот драйвер создавать векторные слои. |
| virtual [CanOpenDatasets](../../aspose.gis/filedriver/canopendatasets/) { get; } | Получает значение, указывающее, может ли этот драйвер открывать наборы данных. |
| override [CanOpenLayers](../../aspose.gis.formats.osmxml/osmxmldriver/canopenlayers/) { get; } | Получает значение, указывающее, может ли этот драйвер открывать векторные слои. |

## Методы

| Имя | Описание |
| --- | --- |
| [CreateDataset](../../aspose.gis/filedriver/createdataset/)(AbstractPath) | Создает набор данных. |
| [CreateDataset](../../aspose.gis/filedriver/createdataset/)(string) | Создает набор данных. |
| virtual [CreateDataset](../../aspose.gis/filedriver/createdataset/)(AbstractPath, DriverOptions) | Создает набор данных. |
| [CreateDataset](../../aspose.gis/filedriver/createdataset/)(string, DriverOptions) | Создает набор данных. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(AbstractPath) | Создает слой и открывает его для добавления. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(string) | Создает слой и открывает его для добавления. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(AbstractPath, DriverOptions) | Создает слой и открывает его для добавления. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(AbstractPath, SpatialReferenceSystem) | Создает слой и открывает его для добавления. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(string, DriverOptions) | Создает слой и открывает его для добавления. |
| [CreateLayer](../../aspose.gis.formats.osmxml/osmxmldriver/createlayer/#createlayer_7)(string, OsmXmlOptions) | Создает слой и открывает его для добавления новых объектов. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(string, SpatialReferenceSystem) | Создает слой и открывает его для добавления. |
| override [CreateLayer](../../aspose.gis.formats.osmxml/osmxmldriver/createlayer/#createlayer_2)(AbstractPath, DriverOptions, SpatialReferenceSystem) | Создает слой и открывает его для добавления новых объектов. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(string, DriverOptions, SpatialReferenceSystem) | Создает слой и открывает его для добавления. |
| [CreateLayer](../../aspose.gis.formats.osmxml/osmxmldriver/createlayer/#createlayer_8)(string, OsmXmlOptions, SpatialReferenceSystem) | Создает слой и открывает его для добавления новых объектов. |
| virtual [EditLayer](../../aspose.gis/filedriver/editlayer/)(AbstractPath, DriverOptions) | Открывает слой для редактирования. |
| [EditLayer](../../aspose.gis/filedriver/editlayer/)(string, DriverOptions) | Открывает слой для редактирования. |
| [OpenDataset](../../aspose.gis/filedriver/opendataset/)(AbstractPath) | Открывает набор данных. |
| [OpenDataset](../../aspose.gis/filedriver/opendataset/)(string) | Открывает набор данных. |
| virtual [OpenDataset](../../aspose.gis/filedriver/opendataset/)(AbstractPath, DriverOptions) | Открывает набор данных. |
| [OpenDataset](../../aspose.gis/filedriver/opendataset/)(string, DriverOptions) | Открывает набор данных. |
| [OpenLayer](../../aspose.gis/filedriver/openlayer/)(AbstractPath) | Открывает слой для чтения. |
| [OpenLayer](../../aspose.gis/filedriver/openlayer/)(string) | Открывает слой для чтения. |
| override [OpenLayer](../../aspose.gis.formats.osmxml/osmxmldriver/openlayer/#openlayer_1)(AbstractPath, DriverOptions) | Открывает слой для чтения. |
| [OpenLayer](../../aspose.gis.formats.osmxml/osmxmldriver/openlayer/#openlayer_2)(AbstractPath, OsmXmlOptions) | Открывает слой для чтения. |
| [OpenLayer](../../aspose.gis/filedriver/openlayer/)(string, DriverOptions) | Открывает слой для чтения. |
| [OpenLayer](../../aspose.gis.formats.osmxml/osmxmldriver/openlayer/#openlayer_5)(string, OsmXmlOptions) | Открывает слой для чтения. |
| override [SupportsSpatialReferenceSystem](../../aspose.gis.formats.osmxml/osmxmldriver/supportsspatialreferencesystem/)(SpatialReferenceSystem) | Определяет, поддерживается ли драйвером указанная система пространственной привязки. |

### Смотрите также

* class [FileDriver](../../aspose.gis/filedriver/)
* пространство имен [Aspose.Gis.Formats.OsmXml](../../aspose.gis.formats.osmxml/)
* сборка [Aspose.GIS](../../)


