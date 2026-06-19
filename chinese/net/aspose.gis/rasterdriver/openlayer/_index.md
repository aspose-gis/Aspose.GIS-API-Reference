---
title: "RasterDriver.OpenLayer"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "RasterDriver 方法。打开图层进行读取"
type: docs
weight: 20
url: /zh/net/aspose.gis/rasterdriver/openlayer/
---
## OpenLayer(AbstractPath, RasterDriverOptions) {#openlayer_1}

打开该图层进行读取。

```csharp
public abstract RasterLayer OpenLayer(AbstractPath path, RasterDriverOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 文件的路径。 |
| options | RasterDriverOptions | 驱动程序特定的选项。 |

### 返回值

[`RasterLayer`](../../../aspose.gis.raster/rasterlayer/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开栅格图层（参见 [`CanOpenLayers`](../canopenlayers/)）。 |

### 另见

* class [RasterLayer](../../../aspose.gis.raster/rasterlayer/)
* class [AbstractPath](../../abstractpath/)
* class [RasterDriverOptions](../../rasterdriveroptions/)
* class [RasterDriver](../)
* namespace [Aspose.Gis](../../rasterdriver/)
* assembly [Aspose.GIS](../../../)

---

## OpenLayer(string) {#openlayer_2}

打开该图层进行读取。

```csharp
public RasterLayer OpenLayer(string path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | 字符串 | 文件的路径。 |

### 返回值

[`RasterLayer`](../../../aspose.gis.raster/rasterlayer/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 路径为 `null`。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开栅格图层（参见 [`CanOpenLayers`](../canopenlayers/)）。 |

### 另见

* class [RasterLayer](../../../aspose.gis.raster/rasterlayer/)
* class [RasterDriver](../)
* namespace [Aspose.Gis](../../rasterdriver/)
* assembly [Aspose.GIS](../../../)

---

## OpenLayer(AbstractPath) {#openlayer}

打开该图层进行读取。

```csharp
public RasterLayer OpenLayer(AbstractPath path)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 文件的路径。 |

### 返回值

[`RasterLayer`](../../../aspose.gis.raster/rasterlayer/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 路径为 `null`。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开栅格图层（参见 [`CanOpenLayers`](../canopenlayers/)）。 |

### 另见

* class [RasterLayer](../../../aspose.gis.raster/rasterlayer/)
* class [AbstractPath](../../abstractpath/)
* class [RasterDriver](../)
* namespace [Aspose.Gis](../../rasterdriver/)
* assembly [Aspose.GIS](../../../)

---

## OpenLayer(string, RasterDriverOptions) {#openlayer_3}

打开该图层进行读取。

```csharp
public RasterLayer OpenLayer(string path, RasterDriverOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | 字符串 | 文件的路径。 |
| options | RasterDriverOptions | 驱动程序特定的选项。 |

### 返回值

[`RasterLayer`](../../../aspose.gis.raster/rasterlayer/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开栅格图层（参见 [`CanOpenLayers`](../canopenlayers/)）。 |

### 另见

* class [RasterLayer](../../../aspose.gis.raster/rasterlayer/)
* class [RasterDriverOptions](../../rasterdriveroptions/)
* class [RasterDriver](../)
* namespace [Aspose.Gis](../../rasterdriver/)
* assembly [Aspose.GIS](../../../)


