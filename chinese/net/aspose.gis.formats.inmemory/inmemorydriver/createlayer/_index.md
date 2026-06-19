---
title: "InMemoryDriver.CreateLayer"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "InMemoryDriver 方法。创建图层并打开以添加新要素"
type: docs
weight: 40
url: /zh/net/aspose.gis.formats.inmemory/inmemorydriver/createlayer/
---
## CreateLayer(AbstractPath, DriverOptions, SpatialReferenceSystem) {#createlayer_3}

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
* class [InMemoryDriver](../)
* namespace [Aspose.Gis.Formats.InMemory](../../inmemorydriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(FeaturesSequence) {#createlayer_5}

从要素序列创建图层并打开以添加新要素。

```csharp
public VectorLayer CreateLayer(FeaturesSequence featuresSequence)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| featuresSequence | FeaturesSequence | 要素序列。 |

### 返回值

[`VectorLayer`](../../../aspose.gis/vectorlayer/) 的实例。

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [FeaturesSequence](../../../aspose.gis/featuressequence/)
* class [InMemoryDriver](../)
* namespace [Aspose.Gis.Formats.InMemory](../../inmemorydriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(SpatialReferenceSystem) {#createlayer_6}

创建图层并以添加新要素的方式打开它。

```csharp
public VectorLayer CreateLayer(SpatialReferenceSystem spatialReferenceSystem)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| spatialReferenceSystem | SpatialReferenceSystem | 空间参考系统。 |

### 返回值

[`VectorLayer`](../../../aspose.gis/vectorlayer/) 的实例。

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [InMemoryDriver](../)
* namespace [Aspose.Gis.Formats.InMemory](../../inmemorydriver/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer() {#createlayer}

创建图层并以添加新要素的方式打开它。

```csharp
public VectorLayer CreateLayer()
```

### 返回值

[`VectorLayer`](../../../aspose.gis/vectorlayer/) 的实例。

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [InMemoryDriver](../)
* namespace [Aspose.Gis.Formats.InMemory](../../inmemorydriver/)
* assembly [Aspose.GIS](../../../)


