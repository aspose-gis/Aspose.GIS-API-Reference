---
title: Class GeoJsonDriver
second_title: Aspose.GIS for .NET API 参考
description: Aspose.Gis.Formats.GeoJson.GeoJsonDriver 班级. GeoJSON 格式的驱动程序
type: docs
weight: 300
url: /zh/net/aspose.gis.formats.geojson/geojsondriver/
---
## GeoJsonDriver class

GeoJSON 格式的驱动程序。

```csharp
public sealed class GeoJsonDriver : FileDriver
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| override [CanCreateDatasets](../../aspose.gis.formats.geojson/geojsondriver/cancreatedatasets/) { get; } | 获取一个值，指示此驱动程序是否可以创建数据集。 |
| override [CanCreateLayers](../../aspose.gis.formats.geojson/geojsondriver/cancreatelayers/) { get; } | 获取一个值，指示此驱动程序是否可以创建矢量图层。 |
| virtual [CanOpenDatasets](../../aspose.gis/filedriver/canopendatasets/) { get; } | 获取一个值，指示此驱动程序是否可以打开数据集。 |
| override [CanOpenLayers](../../aspose.gis.formats.geojson/geojsondriver/canopenlayers/) { get; } | 获取一个值，指示此驱动程序是否可以打开矢量图层。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| [CreateDataset](../../aspose.gis/filedriver/createdataset/)(AbstractPath) | 创建数据集。 |
| [CreateDataset](../../aspose.gis/filedriver/createdataset/)(string) | 创建数据集。 |
| virtual [CreateDataset](../../aspose.gis/filedriver/createdataset/)(AbstractPath, DriverOptions) | 创建数据集。 |
| [CreateDataset](../../aspose.gis/filedriver/createdataset/)(string, DriverOptions) | 创建数据集。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(AbstractPath) | 创建图层并打开它以进行附加。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(string) | 创建图层并打开它以进行附加。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(AbstractPath, DriverOptions) | 创建图层并打开它以进行附加。 |
| [CreateLayer](../../aspose.gis.formats.geojson/geojsondriver/createlayer/#createlayer_3)(AbstractPath, GeoJsonOptions) | 创建图层并打开它以添加新功能。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(AbstractPath, SpatialReferenceSystem) | 创建图层并打开它以进行附加。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(string, DriverOptions) | 创建图层并打开它以进行附加。 |
| [CreateLayer](../../aspose.gis.formats.geojson/geojsondriver/createlayer/#createlayer_9)(string, GeoJsonOptions) | 创建图层并打开它以添加新功能。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(string, SpatialReferenceSystem) | 创建图层并打开它以进行附加。 |
| override [CreateLayer](../../aspose.gis.formats.geojson/geojsondriver/createlayer/#createlayer_2)(AbstractPath, DriverOptions, SpatialReferenceSystem) | 创建图层并打开它以添加新功能。 |
| [CreateLayer](../../aspose.gis.formats.geojson/geojsondriver/createlayer/#createlayer_4)(AbstractPath, GeoJsonOptions, SpatialReferenceSystem) | 创建图层并打开它以添加新功能。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/)(string, DriverOptions, SpatialReferenceSystem) | 创建图层并打开它以进行附加。 |
| virtual [EditLayer](../../aspose.gis/filedriver/editlayer/)(AbstractPath, DriverOptions) | 打开图层进行编辑。 |
| [EditLayer](../../aspose.gis/filedriver/editlayer/)(string, DriverOptions) | 打开图层进行编辑。 |
| [OpenDataset](../../aspose.gis/filedriver/opendataset/)(AbstractPath) | 打开数据集。 |
| [OpenDataset](../../aspose.gis/filedriver/opendataset/)(string) | 打开数据集。 |
| virtual [OpenDataset](../../aspose.gis/filedriver/opendataset/)(AbstractPath, DriverOptions) | 打开数据集。 |
| [OpenDataset](../../aspose.gis/filedriver/opendataset/)(string, DriverOptions) | 打开数据集。 |
| [OpenLayer](../../aspose.gis/filedriver/openlayer/)(AbstractPath) | 打开图层进行读取。 |
| [OpenLayer](../../aspose.gis/filedriver/openlayer/)(string) | 打开图层进行读取。 |
| override [OpenLayer](../../aspose.gis.formats.geojson/geojsondriver/openlayer/#openlayer_1)(AbstractPath, DriverOptions) | 开启一层读取。 |
| [OpenLayer](../../aspose.gis.formats.geojson/geojsondriver/openlayer/#openlayer_2)(AbstractPath, GeoJsonOptions) | 开启一层读取。 |
| [OpenLayer](../../aspose.gis/filedriver/openlayer/)(string, DriverOptions) | 打开图层进行读取。 |
| [OpenLayer](../../aspose.gis.formats.geojson/geojsondriver/openlayer/#openlayer_5)(string, GeoJsonOptions) | 开启一层读取。 |
| override [SupportsSpatialReferenceSystem](../../aspose.gis.formats.geojson/geojsondriver/supportsspatialreferencesystem/)(SpatialReferenceSystem) | 确定驱动程序是否支持指定的空间参考系统。 |

### 也可以看看

* class [FileDriver](../../aspose.gis/filedriver/)
* 命名空间 [Aspose.Gis.Formats.GeoJson](../../aspose.gis.formats.geojson/)
* 部件 [Aspose.GIS](../../)


