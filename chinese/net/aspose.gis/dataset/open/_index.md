---
title: "Dataset.Open"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Dataset 方法。打开数据集"
type: docs
weight: 20
url: /zh/net/aspose.gis/dataset/open/
---
## Open(string, FileDriver) {#open_3}

打开数据集。

```csharp
public static Dataset Open(string path, FileDriver driver)
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
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 读取数据集时出错。 |
| IOException | 发生了 I/O 错误。 |

### 另见

* class [FileDriver](../../filedriver/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)

---

## Open(AbstractPath, FileDriver) {#open}

打开数据集。

```csharp
public static Dataset Open(AbstractPath path, FileDriver driver)
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
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 读取数据集时出错。 |
| IOException | 发生了 I/O 错误。 |

### 另见

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)

---

## Open(string, FileDriver, DriverOptions) {#open_4}

打开数据集。

```csharp
public static Dataset Open(string path, FileDriver driver, DriverOptions options)
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
| [GisException](../../gisexception/) | 读取数据集时出错。 |
| IOException | 发生了 I/O 错误。 |

### 另见

* class [FileDriver](../../filedriver/)
* class [DriverOptions](../../driveroptions/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)

---

## Open(AbstractPath, FileDriver, DriverOptions) {#open_1}

打开数据集。

```csharp
public static Dataset Open(AbstractPath path, FileDriver driver, DriverOptions options)
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
| [GisException](../../gisexception/) | 读取数据集时出错。 |
| IOException | 发生了 I/O 错误。 |

### 另见

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [DriverOptions](../../driveroptions/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)

---

## Open(IDbConnection, DatabaseDriver) {#open_2}

打开数据集。

```csharp
public static Dataset Open(IDbConnection connection, DatabaseDriver driver)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 连接 | IDbConnection | 已打开到数据库的连接。 |
| 驱动程序 | DatabaseDriver | 要使用的驱动程序。 |

### 返回值

一个 [`Dataset`](../) 实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 读取数据集时出错。 |
| IOException | 发生了 I/O 错误。 |

### 另见

* class [DatabaseDriver](../../databasedriver/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)


