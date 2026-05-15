---
title: "Dataset.CreateLayer"
second_title: "Aspose.GIS for .NET API 参考"
description: "Dataset 方法。创建一个新的矢量图层并以追加方式打开它"
type: docs
weight: 70
url: /zh/net/aspose.gis/dataset/createlayer/
---
## CreateLayer() {#createlayer}

创建一个新的矢量图层并以追加模式打开它。

```csharp
public virtual VectorLayer CreateLayer()
```

### 返回值

已打开用于写入的 [`VectorLayer`](../../vectorlayer/)。

### 另见

* class [VectorLayer](../../vectorlayer/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(SpatialReferenceSystem) {#createlayer_2}

创建一个新的矢量图层并以追加模式打开它。

```csharp
public virtual VectorLayer CreateLayer(SpatialReferenceSystem spatialReferenceSystem)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| spatialReferenceSystem | SpatialReferenceSystem | 新图层的空间参考系统。 |

### 返回值

已打开用于写入的 [`VectorLayer`](../../vectorlayer/)。

### 另见

* class [VectorLayer](../../vectorlayer/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(DriverOptions, SpatialReferenceSystem) {#createlayer_1}

创建一个新的矢量图层并以追加模式打开它。

```csharp
public virtual VectorLayer CreateLayer(DriverOptions options, 
    SpatialReferenceSystem spatialReferenceSystem = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | DriverOptions | 打开选项。 |
| spatialReferenceSystem | SpatialReferenceSystem | 新图层的空间参考系统。 |

### 返回值

已打开用于写入的 [`VectorLayer`](../../vectorlayer/)。

### 异常

| 异常 | 条件 |
| --- | --- |
| NotSupportedException | 此数据集不支持创建图层。 |
| IOException | 发生 I/O 错误。 |
| [GisException](../../gisexception/) | 创建图层时出错。 |

### 另见

* class [VectorLayer](../../vectorlayer/)
* class [DriverOptions](../../driveroptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(string, SpatialReferenceSystem) {#createlayer_4}

创建一个具有指定名称的新矢量图层并以追加模式打开它。

```csharp
public virtual VectorLayer CreateLayer(string name, 
    SpatialReferenceSystem spatialReferenceSystem = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | String | 图层名称。 |
| spatialReferenceSystem | SpatialReferenceSystem | 新图层的空间参考系统。 |

### 返回值

已打开用于写入的 [`VectorLayer`](../../vectorlayer/)。

### 异常

| 异常 | 条件 |
| --- | --- |
| NotSupportedException | 此数据集不支持创建图层。 |
| IOException | 发生 I/O 错误。 |
| [GisException](../../gisexception/) | 创建图层时出错。 |

### 另见

* class [VectorLayer](../../vectorlayer/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)

---

## CreateLayer(string, DriverOptions, SpatialReferenceSystem) {#createlayer_3}

创建一个具有指定名称的新矢量图层并以追加模式打开它。

```csharp
public virtual VectorLayer CreateLayer(string name, DriverOptions options, 
    SpatialReferenceSystem spatialReferenceSystem = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | String | 图层名称。 |
| options | DriverOptions | 打开选项。 |
| spatialReferenceSystem | SpatialReferenceSystem | 新图层的空间参考系统。 |

### 返回值

已打开用于写入的 [`VectorLayer`](../../vectorlayer/)。

### 异常

| 异常 | 条件 |
| --- | --- |
| NotSupportedException | 此数据集不支持创建图层。 |
| IOException | 发生 I/O 错误。 |
| [GisException](../../gisexception/) | 创建图层时出错。 |

### 另见

* class [VectorLayer](../../vectorlayer/)
* class [DriverOptions](../../driveroptions/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)


