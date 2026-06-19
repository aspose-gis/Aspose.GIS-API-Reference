---
title: "FileDriver.OpenLayer"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "FileDriver 方法。打开图层进行读取"
type: docs
weight: 90
url: /zh/net/aspose.gis/filedriver/openlayer/
---
## OpenLayer(string) {#openlayer_2}

打开该图层进行读取。

```csharp
public VectorLayer OpenLayer(string path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | 字符串 | 文件的路径。 |

### 返回值

[`VectorLayer`](../../vectorlayer/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 从文件读取要素时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开矢量图层（参见 [`CanOpenLayers`](../canopenlayers/)）。 |

### 另见

* class [VectorLayer](../../vectorlayer/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## OpenLayer(AbstractPath) {#openlayer}

打开该图层进行读取。

```csharp
public VectorLayer OpenLayer(AbstractPath path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 文件的路径。 |

### 返回值

[`VectorLayer`](../../vectorlayer/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 从文件读取要素时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开矢量图层（参见 [`CanOpenLayers`](../canopenlayers/)）。 |

### 另见

* class [VectorLayer](../../vectorlayer/)
* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## OpenLayer(string, DriverOptions) {#openlayer_3}

打开该图层进行读取。

```csharp
public VectorLayer OpenLayer(string path, DriverOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | 字符串 | 文件的路径。 |
| options | DriverOptions | 驱动程序特定的选项。 |

### 返回值

[`VectorLayer`](../../vectorlayer/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 从文件读取要素时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开矢量图层（参见 [`CanOpenLayers`](../canopenlayers/)）。 |

### 另见

* class [VectorLayer](../../vectorlayer/)
* class [DriverOptions](../../driveroptions/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## OpenLayer(AbstractPath, DriverOptions) {#openlayer_1}

打开该图层进行读取。

```csharp
public abstract VectorLayer OpenLayer(AbstractPath path, DriverOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 文件的路径。 |
| options | DriverOptions | 驱动程序特定的选项。 |

### 返回值

[`VectorLayer`](../../vectorlayer/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 从文件读取要素时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开矢量图层（参见 [`CanOpenLayers`](../canopenlayers/)）。 |

### 另见

* class [VectorLayer](../../vectorlayer/)
* class [AbstractPath](../../abstractpath/)
* class [DriverOptions](../../driveroptions/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)


