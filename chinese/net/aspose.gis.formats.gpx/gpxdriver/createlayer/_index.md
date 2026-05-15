---
title: "GpxDriver.CreateLayer"
second_title: "Aspose.GIS for .NET API 参考"
description: "GpxDriver 方法。创建一个图层并打开以添加新要素"
type: docs
weight: 40
url: /zh/net/aspose.gis.formats.gpx/gpxdriver/createlayer/
---
## CreateLayer(string, GpxOptions) {#createlayer_9}

创建图层并以添加新要素的方式打开它。

```csharp
public VectorLayer CreateLayer(string path, GpxOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 文件的路径。 |
| options | GpxOptions | 驱动程序特定的选项。 |

### 返回值

[`VectorLayer`](../../../aspose.gis/vectorlayer/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 图层已存在。 |

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [GpxOptions](../../gpxoptions/)
* class [GpxDriver](../)
* namespace [Aspose.Gis.Formats.Gpx](../../gpxdriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath, GpxOptions) {#createlayer_3}

创建图层并以添加新要素的方式打开它。

```csharp
public VectorLayer CreateLayer(AbstractPath path, GpxOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 文件的路径。 |
| options | GpxOptions | 驱动程序特定的选项。 |

### 返回值

[`VectorLayer`](../../../aspose.gis/vectorlayer/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 图层已存在。 |

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [GpxOptions](../../gpxoptions/)
* class [GpxDriver](../)
* namespace [Aspose.Gis.Formats.Gpx](../../gpxdriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath, DriverOptions, SpatialReferenceSystem) {#createlayer_2}

创建图层并以添加新要素的方式打开它。

```csharp
public override VectorLayer CreateLayer(AbstractPath path, DriverOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 文件的路径。 |
| options | DriverOptions | 驱动程序特定的选项。 |
| spatialReferenceSystem | SpatialReferenceSystem | 空间参考系统。 |

### 返回值

[`VectorLayer`](../../../aspose.gis/vectorlayer/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 图层已存在。 |

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [DriverOptions](../../../aspose.gis/driveroptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [GpxDriver](../)
* namespace [Aspose.Gis.Formats.Gpx](../../gpxdriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath, GpxOptions, SpatialReferenceSystem) {#createlayer_4}

创建图层并以添加新要素的方式打开它。

```csharp
public VectorLayer CreateLayer(AbstractPath path, GpxOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 文件的路径。 |
| options | GpxOptions | 驱动程序特定的选项。 |
| spatialReferenceSystem | SpatialReferenceSystem | 空间参考系统。 |

### 返回值

[`VectorLayer`](../../../aspose.gis/vectorlayer/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 图层已存在。 |
| NotSupportedException | 驱动程序不支持空间参考系统。 |

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [GpxOptions](../../gpxoptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [GpxDriver](../)
* namespace [Aspose.Gis.Formats.Gpx](../../gpxdriver/)
* assembly [Aspose.GIS](../../../)


