---
title: "FileDriver.OpenDataset"
second_title: "Aspose.GIS for .NET API 参考"
description: "FileDriver 方法。打开数据集"
type: docs
weight: 80
url: /zh/net/aspose.gis/filedriver/opendataset/
---
## OpenDataset(string) {#opendataset_2}

打开数据集。

```csharp
public Dataset OpenDataset(string path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 数据集的路径。 |

### 返回值

一个 [`Dataset`](../../dataset/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 读取数据集时出错。 |
| IOException | 发生 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开数据集（参见 [`CanOpenDatasets`](../canopendatasets/)）。 |

### 另见

* class [Dataset](../../dataset/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## OpenDataset(AbstractPath) {#opendataset}

打开数据集。

```csharp
public Dataset OpenDataset(AbstractPath path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 数据集的路径。 |

### 返回值

一个 [`Dataset`](../../dataset/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 读取数据集时出错。 |
| IOException | 发生 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开数据集（参见 [`CanOpenDatasets`](../canopendatasets/)）。 |

### 另见

* class [Dataset](../../dataset/)
* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## OpenDataset(string, DriverOptions) {#opendataset_3}

打开数据集。

```csharp
public Dataset OpenDataset(string path, DriverOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 数据集的路径。 |
| options | DriverOptions | 驱动程序特定的选项。 |

### 返回值

一个 [`Dataset`](../../dataset/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 读取数据集时出错。 |
| IOException | 发生 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开数据集（参见 [`CanOpenDatasets`](../canopendatasets/)）。 |

### 另见

* class [Dataset](../../dataset/)
* class [DriverOptions](../../driveroptions/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## OpenDataset(AbstractPath, DriverOptions) {#opendataset_1}

打开数据集。

```csharp
public virtual Dataset OpenDataset(AbstractPath path, DriverOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 数据集的路径。 |
| options | DriverOptions | 驱动程序特定的选项。 |

### 返回值

一个 [`Dataset`](../../dataset/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 读取数据集时出错。 |
| IOException | 发生 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开数据集（参见 [`CanOpenDatasets`](../canopendatasets/)）。 |

### 另见

* class [Dataset](../../dataset/)
* class [AbstractPath](../../abstractpath/)
* class [DriverOptions](../../driveroptions/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)


