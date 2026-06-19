---
title: "FileDriver.CreateDataset"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "FileDriver 方法。创建数据集"
type: docs
weight: 50
url: /zh/net/aspose.gis/filedriver/createdataset/
---
## CreateDataset(string) {#createdataset_2}

创建一个数据集。

```csharp
public Dataset CreateDataset(string path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | 字符串 | 数据集的路径。 |

### 返回值

一个 [`Dataset`](../../dataset/) 实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 创建数据集时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开数据集（参见 [`CanOpenDatasets`](../canopendatasets/)）。 |
| InvalidOperationException | 数据集已存在。 |

### 另见

* class [Dataset](../../dataset/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateDataset(AbstractPath) {#createdataset}

创建一个数据集。

```csharp
public Dataset CreateDataset(AbstractPath path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 数据集的路径。 |

### 返回值

一个 [`Dataset`](../../dataset/) 实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 创建数据集时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开数据集（参见 [`CanOpenDatasets`](../canopendatasets/)）。 |
| InvalidOperationException | 数据集已存在。 |

### 另见

* class [Dataset](../../dataset/)
* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateDataset(string, DriverOptions) {#createdataset_3}

创建一个数据集。

```csharp
public Dataset CreateDataset(string path, DriverOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | 字符串 | 数据集的路径。 |
| options | DriverOptions | 驱动程序特定的选项。 |

### 返回值

一个 [`Dataset`](../../dataset/) 实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 创建数据集时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开数据集（参见 [`CanOpenDatasets`](../canopendatasets/)）。 |
| InvalidOperationException | 数据集已存在。 |

### 另见

* class [Dataset](../../dataset/)
* class [DriverOptions](../../driveroptions/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateDataset(AbstractPath, DriverOptions) {#createdataset_1}

创建一个数据集。

```csharp
public virtual Dataset CreateDataset(AbstractPath path, DriverOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 数据集的路径。 |
| options | DriverOptions | 驱动程序特定的选项。 |

### 返回值

一个 [`Dataset`](../../dataset/) 实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 创建数据集时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开数据集（参见 [`CanOpenDatasets`](../canopendatasets/)）。 |
| InvalidOperationException | 数据集已存在。 |

### 另见

* class [Dataset](../../dataset/)
* class [AbstractPath](../../abstractpath/)
* class [DriverOptions](../../driveroptions/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)


