---
title: "类 FileDriver"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.FileDriver 类。特定基于文件的格式的驱动程序"
type: docs
weight: 1670
url: /zh/net/aspose.gis/filedriver/
---
## FileDriver class

特定文件格式的驱动程序。

```csharp
public abstract class FileDriver : Driver
```

## 属性

| 名称 | 描述 |
| --- | --- |
| abstract [CanCreateDatasets](../../aspose.gis/filedriver/cancreatedatasets/) { get; } | 获取一个值，指示此驱动程序是否可以创建数据集。 |
| abstract [CanCreateLayers](../../aspose.gis/filedriver/cancreatelayers/) { get; } | 获取一个值，指示此驱动程序是否可以创建矢量图层。 |
| virtual [CanOpenDatasets](../../aspose.gis/filedriver/canopendatasets/) { get; } | 获取一个值，指示此驱动程序是否可以打开数据集。 |
| abstract [CanOpenLayers](../../aspose.gis/filedriver/canopenlayers/) { get; } | 获取一个值，指示此驱动程序是否可以打开矢量图层。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CreateDataset](../../aspose.gis/filedriver/createdataset/#createdataset)(AbstractPath) | 创建一个数据集。 |
| [CreateDataset](../../aspose.gis/filedriver/createdataset/#createdataset_2)(string) | 创建一个数据集。 |
| virtual [CreateDataset](../../aspose.gis/filedriver/createdataset/#createdataset_1)(AbstractPath, DriverOptions) | 创建一个数据集。 |
| [CreateDataset](../../aspose.gis/filedriver/createdataset/#createdataset_3)(string, DriverOptions) | 创建一个数据集。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/#createlayer)(AbstractPath) | 创建图层并以追加方式打开它。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/#createlayer_4)(string) | 创建图层并以追加方式打开它。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/#createlayer_1)(AbstractPath, DriverOptions) | 创建图层并以追加方式打开它。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/#createlayer_3)(AbstractPath, SpatialReferenceSystem) | 创建图层并以追加方式打开它。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/#createlayer_5)(string, DriverOptions) | 创建图层并以追加方式打开它。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/#createlayer_7)(string, SpatialReferenceSystem) | 创建图层并以追加方式打开它。 |
| abstract [CreateLayer](../../aspose.gis/filedriver/createlayer/#createlayer_2)(AbstractPath, DriverOptions, SpatialReferenceSystem) | 创建图层并以追加方式打开它。 |
| [CreateLayer](../../aspose.gis/filedriver/createlayer/#createlayer_6)(string, DriverOptions, SpatialReferenceSystem) | 创建图层并以追加方式打开它。 |
| virtual [EditLayer](../../aspose.gis/filedriver/editlayer/#editlayer)(AbstractPath, DriverOptions) | 以编辑模式打开图层。 |
| [EditLayer](../../aspose.gis/filedriver/editlayer/#editlayer_1)(string, DriverOptions) | 以编辑模式打开图层。 |
| [OpenDataset](../../aspose.gis/filedriver/opendataset/#opendataset)(AbstractPath) | 打开数据集。 |
| [OpenDataset](../../aspose.gis/filedriver/opendataset/#opendataset_2)(string) | 打开数据集。 |
| virtual [OpenDataset](../../aspose.gis/filedriver/opendataset/#opendataset_1)(AbstractPath, DriverOptions) | 打开数据集。 |
| [OpenDataset](../../aspose.gis/filedriver/opendataset/#opendataset_3)(string, DriverOptions) | 打开数据集。 |
| [OpenLayer](../../aspose.gis/filedriver/openlayer/#openlayer)(AbstractPath) | 打开该图层进行读取。 |
| [OpenLayer](../../aspose.gis/filedriver/openlayer/#openlayer_2)(string) | 打开该图层进行读取。 |
| abstract [OpenLayer](../../aspose.gis/filedriver/openlayer/#openlayer_1)(AbstractPath, DriverOptions) | 打开该图层进行读取。 |
| [OpenLayer](../../aspose.gis/filedriver/openlayer/#openlayer_3)(string, DriverOptions) | 打开该图层进行读取。 |
| abstract [SupportsSpatialReferenceSystem](../../aspose.gis/filedriver/supportsspatialreferencesystem/)(SpatialReferenceSystem) | 确定指定的空间参考系统是否受此驱动程序支持。 |

### 另见

* class [Driver](../driver/)
* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


