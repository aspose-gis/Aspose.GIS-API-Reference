---
title: "类 Dataset"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.Dataset 类。数据集是 VectorLayer 实例的集合"
type: docs
weight: 1430
url: /zh/net/aspose.gis/dataset/
---
## Dataset class

数据集是 [`VectorLayer`](../vectorlayer/) 实例的集合。

```csharp
public abstract class Dataset : IDisposable
```

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [CanCreateLayers](../../aspose.gis/dataset/cancreatelayers/) { get; } | 获取一个值，指示此数据集是否可以创建矢量图层。 |
| virtual [CanRemoveLayers](../../aspose.gis/dataset/canremovelayers/) { get; } | 获取一个值，指示此数据集是否可以删除矢量图层。 |
| abstract [Driver](../../aspose.gis/dataset/driver/) { get; } | 获取实例化此数据集的 [`Driver`](./driver/)。 |
| abstract [LayersCount](../../aspose.gis/dataset/layerscount/) { get; } | 获取此数据集中的图层数量。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Create](../../aspose.gis/dataset/create/#create)(AbstractPath, FileDriver) | 创建一个数据集。 |
| static [Create](../../aspose.gis/dataset/create/#create_2)(string, FileDriver) | 创建一个数据集。 |
| static [Create](../../aspose.gis/dataset/create/#create_1)(AbstractPath, FileDriver, DriverOptions) | 创建一个数据集。 |
| static [Create](../../aspose.gis/dataset/create/#create_3)(string, FileDriver, DriverOptions) | 创建一个数据集。 |
| static [Open](../../aspose.gis/dataset/open/#open)(AbstractPath, FileDriver) | 打开数据集。 |
| static [Open](../../aspose.gis/dataset/open/#open_2)(IDbConnection, DatabaseDriver) | 打开数据集。 |
| static [Open](../../aspose.gis/dataset/open/#open_3)(string, FileDriver) | 打开数据集。 |
| static [Open](../../aspose.gis/dataset/open/#open_1)(AbstractPath, FileDriver, DriverOptions) | 打开数据集。 |
| static [Open](../../aspose.gis/dataset/open/#open_4)(string, FileDriver, DriverOptions) | 打开数据集。 |
| virtual [CreateLayer](../../aspose.gis/dataset/createlayer/#createlayer)() | 创建一个新的矢量图层并以追加模式打开它。 |
| virtual [CreateLayer](../../aspose.gis/dataset/createlayer/#createlayer_2)(SpatialReferenceSystem) | 创建一个新的矢量图层并以追加模式打开它。 |
| virtual [CreateLayer](../../aspose.gis/dataset/createlayer/#createlayer_1)(DriverOptions, SpatialReferenceSystem) | 创建一个新的矢量图层并以追加模式打开它。 |
| virtual [CreateLayer](../../aspose.gis/dataset/createlayer/#createlayer_4)(string, SpatialReferenceSystem) | 创建一个具有指定名称的新矢量图层并以追加模式打开它。 |
| virtual [CreateLayer](../../aspose.gis/dataset/createlayer/#createlayer_3)(string, DriverOptions, SpatialReferenceSystem) | 创建一个具有指定名称的新矢量图层并以追加模式打开它。 |
| [Dispose](../../aspose.gis/dataset/dispose/)() | 释放 `Dataset` 使用的资源。 |
| abstract [EditLayer](../../aspose.gis/dataset/editlayer/)(string, DriverOptions, SpatialReferenceSystem) | 以编辑模式打开具有指定名称的图层。 |
| abstract [EditLayerAt](../../aspose.gis/dataset/editlayerat/)(int, DriverOptions, SpatialReferenceSystem) | 以编辑模式打开具有指定名称的图层。 |
| abstract [GetLayerName](../../aspose.gis/dataset/getlayername/)(int) | 获取指定索引处图层的名称。 |
| virtual [HasLayerWithName](../../aspose.gis/dataset/haslayerwithname/)(string) | 检查当前数据集是否拥有具有特定名称的图层 |
| abstract [OpenLayer](../../aspose.gis/dataset/openlayer/)(string, DriverOptions) | 以读取模式打开具有指定名称的图层。 |
| abstract [OpenLayerAt](../../aspose.gis/dataset/openlayerat/)(int, DriverOptions) | 以读取模式打开指定索引处的图层。 |
| virtual [RemoveLayer](../../aspose.gis/dataset/removelayer/)(string) | 删除具有指定名称的矢量图层。 |
| virtual [RemoveLayerAt](../../aspose.gis/dataset/removelayerat/)(int) | 删除指定索引处的矢量图层。 |
| virtual [RenameLayer](../../aspose.gis/dataset/renamelayer/)(string, string) | 重命名数据集中的图层 |

### 另见

* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


