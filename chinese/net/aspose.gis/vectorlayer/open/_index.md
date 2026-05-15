---
title: "VectorLayer.Open"
second_title: "Aspose.GIS for .NET API 参考"
description: "VectorLayer 方法。打开图层进行读取"
type: docs
weight: 20
url: /zh/net/aspose.gis/vectorlayer/open/
---
## Open(string, FileDriver) {#open_2}

打开图层进行读取。

```csharp
public static VectorLayer Open(string path, FileDriver driver)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 文件的路径。 |
| 驱动 | FileDriver | 要使用的驱动。 |

### 返回值

只读图层。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 读取文件中的要素时出错。 |
| IOException | 发生 I/O 错误。 |

### 另见

* class [FileDriver](../../filedriver/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Open(AbstractPath, FileDriver) {#open}

打开图层进行读取。

```csharp
public static VectorLayer Open(AbstractPath path, FileDriver driver)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 文件的路径。 |
| 驱动 | FileDriver | 要使用的驱动。 |

### 返回值

只读图层。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 读取文件中的要素时出错。 |
| IOException | 发生 I/O 错误。 |

### 另见

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Open(string, FileDriver, DriverOptions) {#open_3}

打开图层进行读取。

```csharp
public static VectorLayer Open(string path, FileDriver driver, DriverOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 文件的路径。 |
| 驱动 | FileDriver | 要使用的驱动。 |
| options | DriverOptions | 驱动程序特定的选项。 |

### 返回值

只读图层。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 读取文件中的要素时出错。 |
| IOException | 发生 I/O 错误。 |

### 另见

* class [FileDriver](../../filedriver/)
* class [DriverOptions](../../driveroptions/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Open(AbstractPath, FileDriver, DriverOptions) {#open_1}

打开图层进行读取。

```csharp
public static VectorLayer Open(AbstractPath path, FileDriver driver, DriverOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 文件的路径。 |
| 驱动 | FileDriver | 要使用的驱动。 |
| options | DriverOptions | 驱动程序特定的选项。 |

### 返回值

只读图层。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 读取文件中的要素时出错。 |
| IOException | 发生 I/O 错误。 |

### 另见

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [DriverOptions](../../driveroptions/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)


