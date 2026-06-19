---
title: "KmlDriver.CreateLayer"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "KmlDriver 方法。创建图层并打开以添加新要素"
type: docs
weight: 40
url: /zh/net/aspose.gis.formats.kml/kmldriver/createlayer/
---
## CreateLayer(string, KmlOptions) {#createlayer_9}

创建图层并以添加新要素的方式打开它。

```csharp
public VectorLayer CreateLayer(string path, KmlOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | 字符串 | 文件的路径。 |
| options | KmlOptions | 驱动程序特定的选项。 |

### 返回值

[`VectorLayer`](../../../aspose.gis/vectorlayer/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 图层已存在。 |

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [KmlOptions](../../kmloptions/)
* class [KmlDriver](../)
* namespace [Aspose.Gis.Formats.Kml](../../kmldriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath, KmlOptions) {#createlayer_3}

创建图层并以添加新要素的方式打开它。

```csharp
public VectorLayer CreateLayer(AbstractPath path, KmlOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 文件的路径。 |
| options | KmlOptions | 驱动程序特定的选项。 |

### 返回值

[`VectorLayer`](../../../aspose.gis/vectorlayer/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 图层已存在。 |

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [KmlOptions](../../kmloptions/)
* class [KmlDriver](../)
* namespace [Aspose.Gis.Formats.Kml](../../kmldriver/)
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
* class [KmlDriver](../)
* namespace [Aspose.Gis.Formats.Kml](../../kmldriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath, KmlOptions, SpatialReferenceSystem) {#createlayer_4}

创建图层并以添加新要素的方式打开它。

```csharp
public VectorLayer CreateLayer(AbstractPath path, KmlOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 文件的路径。 |
| options | KmlOptions | 驱动程序特定的选项。 |
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
* class [KmlOptions](../../kmloptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [KmlDriver](../)
* namespace [Aspose.Gis.Formats.Kml](../../kmldriver/)
* assembly [Aspose.GIS](../../../)


