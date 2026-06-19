---
title: "Dataset.Create"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Dataset 方法。创建数据集"
type: docs
weight: 10
url: /zh/net/aspose.gis/dataset/create/
---
## Create(string, FileDriver) {#create_2}

创建一个数据集。

```csharp
public static Dataset Create(string path, FileDriver driver)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | 字符串 | 数据集的路径。 |
| 驱动程序 | FileDriver | 要使用的驱动程序。 |

### 返回值

一个 [`Dataset`](../) 实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 创建数据集时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开数据集。 |
| InvalidOperationException | 数据集已存在。 |

### 另见

* class [FileDriver](../../filedriver/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)

---

## Create(AbstractPath, FileDriver) {#create}

创建一个数据集。

```csharp
public static Dataset Create(AbstractPath path, FileDriver driver)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 数据集的路径。 |
| 驱动程序 | FileDriver | 要使用的驱动程序。 |

### 返回值

一个 [`Dataset`](../) 实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 创建数据集时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开数据集。 |
| InvalidOperationException | 数据集已存在。 |

### 另见

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)

---

## Create(string, FileDriver, DriverOptions) {#create_3}

创建一个数据集。

```csharp
public static Dataset Create(string path, FileDriver driver, DriverOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | 字符串 | 数据集的路径。 |
| 驱动程序 | FileDriver | 要使用的驱动程序。 |
| options | DriverOptions | 驱动程序特定的选项。 |

### 返回值

一个 [`Dataset`](../) 实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 创建数据集时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开数据集。 |
| InvalidOperationException | 数据集已存在。 |

### 另见

* class [FileDriver](../../filedriver/)
* class [DriverOptions](../../driveroptions/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)

---

## Create(AbstractPath, FileDriver, DriverOptions) {#create_1}

创建一个数据集。

```csharp
public static Dataset Create(AbstractPath path, FileDriver driver, DriverOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 数据集的路径。 |
| 驱动程序 | FileDriver | 要使用的驱动程序。 |
| options | DriverOptions | 驱动程序特定的选项。 |

### 返回值

一个 [`Dataset`](../) 实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 创建数据集时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开数据集。 |
| InvalidOperationException | 数据集已存在。 |

### 另见

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [DriverOptions](../../driveroptions/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)


