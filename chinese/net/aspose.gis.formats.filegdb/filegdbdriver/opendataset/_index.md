---
title: "FileGdbDriver.OpenDataset"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "FileGdbDriver 方法。打开数据集"
type: docs
weight: 80
url: /zh/net/aspose.gis.formats.filegdb/filegdbdriver/opendataset/
---
## OpenDataset(string, FileGdbOptions) {#opendataset_5}

打开数据集。

```csharp
public Dataset OpenDataset(string path, FileGdbOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | 字符串 | 数据集的路径。 |
| options | FileGdbOptions | 驱动程序特定的选项。 |

### 返回值

一个 [`Dataset`](../../../aspose.gis/dataset/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../../aspose.gis/gisexception/) | 读取数据集中的图层时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开数据集（参见 [`CanOpenDatasets`](../canopendatasets/)）。 |

### 另见

* class [Dataset](../../../aspose.gis/dataset/)
* class [FileGdbOptions](../../filegdboptions/)
* class [FileGdbDriver](../)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdbdriver/)
* assembly [Aspose.GIS](../../../)

---

## OpenDataset(AbstractPath, DriverOptions) {#opendataset_1}

打开数据集。

```csharp
public override Dataset OpenDataset(AbstractPath path, DriverOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 数据集的路径。 |
| options | DriverOptions | 驱动程序特定的选项。 |

### 返回值

一个 [`Dataset`](../../../aspose.gis/dataset/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../../aspose.gis/gisexception/) | 读取数据集中的图层时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开数据集（参见 [`CanOpenDatasets`](../canopendatasets/)）。 |

### 另见

* class [Dataset](../../../aspose.gis/dataset/)
* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [DriverOptions](../../../aspose.gis/driveroptions/)
* class [FileGdbDriver](../)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdbdriver/)
* assembly [Aspose.GIS](../../../)

---

## OpenDataset(AbstractPath, FileGdbOptions) {#opendataset_2}

打开数据集。

```csharp
public Dataset OpenDataset(AbstractPath path, FileGdbOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 数据集的路径。 |
| options | FileGdbOptions | 驱动程序特定的选项。 |

### 返回值

一个 [`Dataset`](../../../aspose.gis/dataset/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../../aspose.gis/gisexception/) | 读取数据集中的图层时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开数据集（参见 [`CanOpenDatasets`](../canopendatasets/)）。 |

### 另见

* class [Dataset](../../../aspose.gis/dataset/)
* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [FileGdbOptions](../../filegdboptions/)
* class [FileGdbDriver](../)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdbdriver/)
* assembly [Aspose.GIS](../../../)


