---
title: "类 OsmXmlDriver"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.Formats.OsmXml.OsmXmlDriver 类。OSM XML 格式的驱动程序。"
type: docs
weight: 2260
url: /zh/net/aspose.gis.formats.osmxml/osmxmldriver/
---
## OsmXmlDriver class

OSM XML 格式的驱动程序。

```csharp
public sealed class OsmXmlDriver : FileDriver
```

## 属性

| 名称 | 描述 |
| --- | --- |
| override [CanCreateDatasets](../../aspose.gis.formats.osmxml/osmxmldriver/cancreatedatasets/) { get; } | 获取一个值，指示此驱动程序是否可以创建数据集。 |
| override [CanCreateLayers](../../aspose.gis.formats.osmxml/osmxmldriver/cancreatelayers/) { get; } | 获取一个值，指示此驱动程序是否可以创建矢量图层。 |
| virtual [CanOpenDatasets](../../aspose.gis/filedriver/canopendatasets/) { get; } | 获取一个值，指示此驱动程序是否可以打开数据集。 |
| override [CanOpenLayers](../../aspose.gis.formats.osmxml/osmxmldriver/canopenlayers/) { get; } | 获取一个值，指示此驱动程序是否可以打开矢量图层。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CreateDataset](../../aspose.gis/filedriver/createdataset/)(AbstractPath) | 创建一个数据集。 |
| [CreateDataset](../../aspose.gis/filedriver/createdataset/)(string) | 创建一个数据集。 |
| virtual [CreateDataset](../../aspose.gis/filedriver/createdataset/)(AbstractPath, DriverOptions) | 创建一个数据集。 |
| [CreateDataset](../../aspose.gis/filedriver/createdataset/)(string, DriverOptions) | 创建一个数据集。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(AbstractPath) | 创建图层并以追加方式打开它。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(string) | 创建图层并以追加方式打开它。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(AbstractPath, DriverOptions) | 创建图层并以追加方式打开它。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(AbstractPath, SpatialReferenceSystem) | 创建图层并以追加方式打开它。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(string, DriverOptions) | 创建图层并以追加方式打开它。 |
| [CreateLayer](../../aspose.gis.formats.osmxml/osmxmldriver/createlayer/#createlayer_8)(string, OsmXmlOptions) | 创建图层并以添加新要素的方式打开它。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(string, SpatialReferenceSystem) | 创建图层并以追加方式打开它。 |
| override [CreateLayer](../../aspose.gis.formats.osmxml/osmxmldriver/createlayer/#createlayer_2)(AbstractPath, DriverOptions, SpatialReferenceSystem) | 创建图层并以添加新要素的方式打开它。 |
| [CreateLayer](../../aspose.gis.formats.osmxml/osmxmldriver/createlayer/#createlayer_3)(AbstractPath, OsmXmlOptions, SpatialReferenceSystem) | 创建图层并以添加新要素的方式打开它。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(string, DriverOptions, SpatialReferenceSystem) | 创建图层并以追加方式打开它。 |
| [CreateLayer](../../aspose.gis.formats.osmxml/osmxmldriver/createlayer/#createlayer_9)(string, OsmXmlOptions, SpatialReferenceSystem) | 创建图层并以添加新要素的方式打开它。 |
| virtual [EditLayer](../../aspose.gis/filedriver/editlayer/)(AbstractPath, DriverOptions) | 以编辑模式打开图层。 |
| [EditLayer](../../aspose.gis/filedriver/editlayer/)(string, DriverOptions) | 以编辑模式打开图层。 |
| [OpenDataset](../../aspose.gis/filedriver/opendataset/)(AbstractPath) | 打开数据集。 |
| [OpenDataset](../../aspose.gis/filedriver/opendataset/)(string) | 打开数据集。 |
| virtual [OpenDataset](../../aspose.gis/filedriver/opendataset/)(AbstractPath, DriverOptions) | 打开数据集。 |
| [OpenDataset](../../aspose.gis/filedriver/opendataset/)(string, DriverOptions) | 打开数据集。 |
| [OpenLayer](../../aspose.gis/filedriver/openlayer/)(AbstractPath) | 打开该图层进行读取。 |
| [OpenLayer](../../aspose.gis/filedriver/openlayer/)(string) | 打开该图层进行读取。 |
| override [OpenLayer](../../aspose.gis.formats.osmxml/osmxmldriver/openlayer/#openlayer_1)(AbstractPath, DriverOptions) | 以读取模式打开图层。 |
| [OpenLayer](../../aspose.gis.formats.osmxml/osmxmldriver/openlayer/#openlayer_2)(AbstractPath, OsmXmlOptions) | 以读取模式打开图层。 |
| [OpenLayer](../../aspose.gis/filedriver/openlayer/)(string, DriverOptions) | 打开该图层进行读取。 |
| [OpenLayer](../../aspose.gis.formats.osmxml/osmxmldriver/openlayer/#openlayer_5)(string, OsmXmlOptions) | 以读取模式打开图层。 |
| override [SupportsSpatialReferenceSystem](../../aspose.gis.formats.osmxml/osmxmldriver/supportsspatialreferencesystem/)(SpatialReferenceSystem) | 确定指定的空间参考系统是否受此驱动程序支持。 |

### 另见

* class [FileDriver](../../aspose.gis/filedriver/)
* namespace [Aspose.Gis.Formats.OsmXml](../../aspose.gis.formats.osmxml/)
* assembly [Aspose.GIS](../../)


