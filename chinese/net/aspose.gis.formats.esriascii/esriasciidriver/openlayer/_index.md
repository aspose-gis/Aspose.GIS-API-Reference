---
title: "EsriAsciiDriver.OpenLayer"
second_title: "Aspose.GIS for .NET API 参考"
description: "EsriAsciiDriver 方法。打开图层进行读取"
type: docs
weight: 20
url: /zh/net/aspose.gis.formats.esriascii/esriasciidriver/openlayer/
---
## OpenLayer(AbstractPath, RasterDriverOptions) {#openlayer_2}

打开该图层进行读取。

```csharp
public override RasterLayer OpenLayer(AbstractPath path, RasterDriverOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 文件的路径。 |
| options | RasterDriverOptions | 驱动程序特定的选项。 |

### 返回值

一个 [`RasterLayer`](../../../aspose.gis.raster/rasterlayer/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| IOException | 发生 I/O 错误。 |
| NotSupportedException | 驱动程序无法打开栅格图层（参见 [`CanOpenLayers`](../canopenlayers/)）。 |

### 另见

* class [RasterLayer](../../../aspose.gis.raster/rasterlayer/)
* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [RasterDriverOptions](../../../aspose.gis/rasterdriveroptions/)
* class [EsriAsciiDriver](../)
* namespace [Aspose.Gis.Formats.EsriAscii](../../esriasciidriver/)
* assembly [Aspose.GIS](../../../)

---

## OpenLayer(string, EsriAsciiOptions) {#openlayer_4}

打开图层进行读取。

```csharp
public RasterLayer OpenLayer(string path, EsriAsciiOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 文件的路径。 |
| options | EsriAsciiOptions | 驱动程序特定的选项。 |

### 返回值

一个 [`RasterLayer`](../../../aspose.gis.raster/rasterlayer/) 的实例。

### 另见

* class [RasterLayer](../../../aspose.gis.raster/rasterlayer/)
* class [EsriAsciiOptions](../../esriasciioptions/)
* class [EsriAsciiDriver](../)
* namespace [Aspose.Gis.Formats.EsriAscii](../../esriasciidriver/)
* assembly [Aspose.GIS](../../../)

---

## OpenLayer(AbstractPath, EsriAsciiOptions) {#openlayer_1}

打开图层进行读取。

```csharp
public RasterLayer OpenLayer(AbstractPath path, EsriAsciiOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 文件的路径。 |
| options | EsriAsciiOptions | 驱动程序特定的选项。 |

### 返回值

一个 [`RasterLayer`](../../../aspose.gis.raster/rasterlayer/) 的实例。

### 另见

* class [RasterLayer](../../../aspose.gis.raster/rasterlayer/)
* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [EsriAsciiOptions](../../esriasciioptions/)
* class [EsriAsciiDriver](../)
* namespace [Aspose.Gis.Formats.EsriAscii](../../esriasciidriver/)
* assembly [Aspose.GIS](../../../)


