---
title: "VectorLayer.Create"
second_title: "Aspose.GIS for .NET API 参考"
description: "VectorLayer 方法。创建图层并打开以添加新要素。"
type: docs
weight: 10
url: /zh/net/aspose.gis/vectorlayer/create/
---
## Create(string, FileDriver) {#create_4}

创建图层并打开以添加新特征。

```csharp
public static VectorLayer Create(string path, FileDriver driver)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 文件的路径。 |
| 驱动 | FileDriver | 要使用的驱动。 |

### 返回值

只写图层。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 路径为 `null`。 |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| [GisException](../../gisexception/) | 写入要素到文件时出错。 |
| IOException | 发生 I/O 错误。 |

### 另见

* class [FileDriver](../../filedriver/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Create(string, FileDriver, DriverOptions) {#create_5}

创建图层并打开以添加新特征。

```csharp
public static VectorLayer Create(string path, FileDriver driver, DriverOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 文件的路径。 |
| 驱动 | FileDriver | 要使用的驱动。 |
| options | DriverOptions | 驱动程序特定的选项。 |

### 返回值

只写图层。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 路径为 `null`。 |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| [GisException](../../gisexception/) | 写入要素到文件时出错。 |
| IOException | 发生 I/O 错误。 |

### 另见

* class [FileDriver](../../filedriver/)
* class [DriverOptions](../../driveroptions/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Create(AbstractPath, FileDriver) {#create}

创建图层并打开以添加新特征。

```csharp
public static VectorLayer Create(AbstractPath path, FileDriver driver)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 文件的路径。 |
| 驱动 | FileDriver | 要使用的驱动。 |

### 返回值

只写图层。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 路径为 `null`。 |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| [GisException](../../gisexception/) | 写入要素到文件时出错。 |
| IOException | 发生 I/O 错误。 |

### 另见

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Create(AbstractPath, FileDriver, DriverOptions) {#create_1}

创建图层并打开以添加新特征。

```csharp
public static VectorLayer Create(AbstractPath path, FileDriver driver, DriverOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 文件的路径。 |
| 驱动 | FileDriver | 要使用的驱动。 |
| options | DriverOptions | 驱动程序特定的选项。 |

### 返回值

只写图层。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 路径为 `null`。 |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| [GisException](../../gisexception/) | 写入要素到文件时出错。 |
| IOException | 发生 I/O 错误。 |

### 另见

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [DriverOptions](../../driveroptions/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Create(string, FileDriver, SpatialReferenceSystem) {#create_7}

创建图层并以追加方式打开它。

```csharp
public static VectorLayer Create(string path, FileDriver driver, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 文件的路径。 |
| 驱动 | FileDriver | 要使用的驱动。 |
| spatialReferenceSystem | SpatialReferenceSystem | 空间参考系统。 |

### 返回值

`[`VectorLayer`](../)` 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 读取或写入要素时出错（从/到文件）。 |
| IOException | 发生 I/O 错误。 |
| NotSupportedException | 驱动程序不支持该空间参考系统。使用 [`SupportsSpatialReferenceSystem`](../../filedriver/supportsspatialreferencesystem/) 检查是否支持该空间参考系统。 |

### 另见

* class [FileDriver](../../filedriver/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Create(AbstractPath, FileDriver, SpatialReferenceSystem) {#create_3}

创建图层并以追加方式打开它。

```csharp
public static VectorLayer Create(AbstractPath path, FileDriver driver, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 文件的路径。 |
| 驱动 | FileDriver | 要使用的驱动。 |
| spatialReferenceSystem | SpatialReferenceSystem | 空间参考系统。 |

### 返回值

`[`VectorLayer`](../)` 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 读取或写入要素时出错（从/到文件）。 |
| IOException | 发生 I/O 错误。 |
| NotSupportedException | 驱动程序不支持该空间参考系统。使用 [`SupportsSpatialReferenceSystem`](../../filedriver/supportsspatialreferencesystem/) 检查是否支持该空间参考系统。 |

### 另见

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Create(string, FileDriver, DriverOptions, SpatialReferenceSystem) {#create_6}

创建图层并以追加方式打开它。

```csharp
public static VectorLayer Create(string path, FileDriver driver, DriverOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 文件的路径。 |
| 驱动 | FileDriver | 要使用的驱动。 |
| options | DriverOptions | 驱动程序特定的选项。 |
| spatialReferenceSystem | SpatialReferenceSystem | 空间参考系统。 |

### 返回值

`[`VectorLayer`](../)` 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 路径为 `null`。 |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| [GisException](../../gisexception/) | 读取或写入要素时出错（从/到文件）。 |
| IOException | 发生 I/O 错误。 |
| NotSupportedException | 驱动程序不支持该空间参考系统。使用 [`SupportsSpatialReferenceSystem`](../../filedriver/supportsspatialreferencesystem/) 检查是否支持该空间参考系统。 |

### 另见

* class [FileDriver](../../filedriver/)
* class [DriverOptions](../../driveroptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Create(AbstractPath, FileDriver, DriverOptions, SpatialReferenceSystem) {#create_2}

创建图层并以追加方式打开它。

```csharp
public static VectorLayer Create(AbstractPath path, FileDriver driver, DriverOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 文件的路径。 |
| 驱动 | FileDriver | 要使用的驱动。 |
| options | DriverOptions | 驱动程序特定的选项。 |
| spatialReferenceSystem | SpatialReferenceSystem | 空间参考系统。 |

### 返回值

`[`VectorLayer`](../)` 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 路径为 `null`。 |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| [GisException](../../gisexception/) | 读取或写入要素时出错（从/到文件）。 |
| IOException | 发生 I/O 错误。 |
| NotSupportedException | 驱动程序不支持该空间参考系统。使用 [`SupportsSpatialReferenceSystem`](../../filedriver/supportsspatialreferencesystem/) 检查是否支持该空间参考系统。 |

### 另见

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [DriverOptions](../../driveroptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)


