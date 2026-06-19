---
title: "GmlDriver.CreateLayer"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "GmlDriver 方法。创建一个图层并打开以添加新要素。"
type: docs
weight: 40
url: /zh/net/aspose.gis.formats.gml/gmldriver/createlayer/
---
## CreateLayer(string, GmlOptions) {#createlayer_7}

创建图层并以添加新要素的方式打开它。

```csharp
public VectorLayer CreateLayer(string path, GmlOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | 字符串 | 文件的路径。 |
| options | GmlOptions | 驱动程序特定的选项。 |

### 返回值

[`VectorLayer`](../../../aspose.gis/vectorlayer/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 图层已存在。 |

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [GmlOptions](../../gmloptions/)
* class [GmlDriver](../)
* namespace [Aspose.Gis.Formats.Gml](../../gmldriver/)
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
* class [GmlDriver](../)
* namespace [Aspose.Gis.Formats.Gml](../../gmldriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(string, GmlOptions, SpatialReferenceSystem) {#createlayer_8}

创建图层并以添加新要素的方式打开它。

```csharp
public VectorLayer CreateLayer(string path, GmlOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | 字符串 | 文件的路径。 |
| options | GmlOptions | 驱动程序特定的选项。 |
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
* class [GmlOptions](../../gmloptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [GmlDriver](../)
* namespace [Aspose.Gis.Formats.Gml](../../gmldriver/)
* assembly [Aspose.GIS](../../../)


