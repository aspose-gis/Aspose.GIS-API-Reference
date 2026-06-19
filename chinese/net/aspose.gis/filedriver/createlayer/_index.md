---
title: "FileDriver.CreateLayer"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "FileDriver 方法。创建图层并打开以追加"
type: docs
weight: 60
url: /zh/net/aspose.gis/filedriver/createlayer/
---
## CreateLayer(string) {#createlayer_4}

创建图层并以追加方式打开它。

```csharp
public VectorLayer CreateLayer(string path)
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
| [GisException](../../gisexception/) | 写入要素到文件时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序无法创建矢量图层（参见 [`CanCreateLayers`](../cancreatelayers/)）。 |

### 另见

* class [VectorLayer](../../vectorlayer/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath) {#createlayer}

创建图层并以追加方式打开它。

```csharp
public VectorLayer CreateLayer(AbstractPath path)
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
| [GisException](../../gisexception/) | 写入要素到文件时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序无法创建矢量图层（参见 [`CanCreateLayers`](../cancreatelayers/)）。 |

### 另见

* class [VectorLayer](../../vectorlayer/)
* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(string, DriverOptions) {#createlayer_5}

创建图层并以追加方式打开它。

```csharp
public VectorLayer CreateLayer(string path, DriverOptions options)
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
| ArgumentNullException | 路径为 `null`。 |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| [GisException](../../gisexception/) | 写入要素到文件时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序无法创建矢量图层（参见 [`CanCreateLayers`](../cancreatelayers/)）。 |

### 另见

* class [VectorLayer](../../vectorlayer/)
* class [DriverOptions](../../driveroptions/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath, DriverOptions) {#createlayer_1}

创建图层并以追加方式打开它。

```csharp
public VectorLayer CreateLayer(AbstractPath path, DriverOptions options)
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
| ArgumentNullException | 路径为 `null`。 |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| [GisException](../../gisexception/) | 写入要素到文件时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序无法创建矢量图层（参见 [`CanCreateLayers`](../cancreatelayers/)）。 |

### 另见

* class [VectorLayer](../../vectorlayer/)
* class [AbstractPath](../../abstractpath/)
* class [DriverOptions](../../driveroptions/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(string, SpatialReferenceSystem) {#createlayer_7}

创建图层并以追加方式打开它。

```csharp
public VectorLayer CreateLayer(string path, SpatialReferenceSystem spatialReferenceSystem)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | 字符串 | 文件的路径。 |
| spatialReferenceSystem | SpatialReferenceSystem | 空间参考系统。 |

### 返回值

[`VectorLayer`](../../vectorlayer/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 写入要素到文件时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序不支持空间参考系统。使用 [`SupportsSpatialReferenceSystem`](../supportsspatialreferencesystem/) 检查是否支持空间参考系统。 |

### 另见

* class [VectorLayer](../../vectorlayer/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath, SpatialReferenceSystem) {#createlayer_3}

创建图层并以追加方式打开它。

```csharp
public VectorLayer CreateLayer(AbstractPath path, SpatialReferenceSystem spatialReferenceSystem)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 文件的路径。 |
| spatialReferenceSystem | SpatialReferenceSystem | 空间参考系统。 |

### 返回值

[`VectorLayer`](../../vectorlayer/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 写入要素到文件时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序不支持空间参考系统。使用 [`SupportsSpatialReferenceSystem`](../supportsspatialreferencesystem/) 检查是否支持空间参考系统。 |

### 另见

* class [VectorLayer](../../vectorlayer/)
* class [AbstractPath](../../abstractpath/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(string, DriverOptions, SpatialReferenceSystem) {#createlayer_6}

创建图层并以追加方式打开它。

```csharp
public VectorLayer CreateLayer(string path, DriverOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | 字符串 | 文件的路径。 |
| options | DriverOptions | 驱动程序特定的选项。 |
| spatialReferenceSystem | SpatialReferenceSystem | 空间参考系统。 |

### 返回值

[`VectorLayer`](../../vectorlayer/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 路径为 `null`。 |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| [GisException](../../gisexception/) | 写入要素到文件时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序不支持空间参考系统。使用 [`SupportsSpatialReferenceSystem`](../supportsspatialreferencesystem/) 检查是否支持空间参考系统。 |
| NotSupportedException | 驱动程序无法创建矢量图层（参见 [`CanCreateLayers`](../cancreatelayers/)）。 |

### 另见

* class [VectorLayer](../../vectorlayer/)
* class [DriverOptions](../../driveroptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath, DriverOptions, SpatialReferenceSystem) {#createlayer_2}

创建图层并以追加方式打开它。

```csharp
public abstract VectorLayer CreateLayer(AbstractPath path, DriverOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 文件的路径。 |
| options | DriverOptions | 驱动程序特定的选项。 |
| spatialReferenceSystem | SpatialReferenceSystem | 空间参考系统。 |

### 返回值

[`VectorLayer`](../../vectorlayer/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 路径为 `null`。 |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| [GisException](../../gisexception/) | 写入要素到文件时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序不支持空间参考系统。使用 [`SupportsSpatialReferenceSystem`](../supportsspatialreferencesystem/) 检查是否支持空间参考系统。 |
| NotSupportedException | 驱动程序无法创建矢量图层（参见 [`CanCreateLayers`](../cancreatelayers/)）。 |

### 另见

* class [VectorLayer](../../vectorlayer/)
* class [AbstractPath](../../abstractpath/)
* class [DriverOptions](../../driveroptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)


