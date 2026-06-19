---
title: "VectorMapLayer.VectorMapLayer"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "VectorMapLayer 构造函数。创建具有默认符号器的新实例"
type: docs
weight: 10
url: /zh/net/aspose.gis.rendering/vectormaplayer/vectormaplayer/
---
## VectorMapLayer(FeaturesSequence) {#constructor}

使用默认符号器创建新实例。

```csharp
public VectorMapLayer(FeaturesSequence featuresSequence)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| featuresSequence | FeaturesSequence | 要素序列。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |

### 另见

* class [FeaturesSequence](../../../aspose.gis/featuressequence/)
* class [VectorMapLayer](../)
* namespace [Aspose.Gis.Rendering](../../vectormaplayer/)
* assembly [Aspose.GIS](../../../)

---

## VectorMapLayer(FeaturesSequence, VectorSymbolizer) {#constructor_1}

使用默认符号器创建新实例。

```csharp
public VectorMapLayer(FeaturesSequence featuresSequence, VectorSymbolizer symbolizer)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| featuresSequence | FeaturesSequence | 要素序列。 |
| 符号化器 | VectorSymbolizer | 用于渲染图层的符号器。如果 `null`，将使用默认符号器。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |

### 另见

* class [FeaturesSequence](../../../aspose.gis/featuressequence/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [VectorMapLayer](../)
* namespace [Aspose.Gis.Rendering](../../vectormaplayer/)
* assembly [Aspose.GIS](../../../)

---

## VectorMapLayer(FeaturesSequence, VectorSymbolizer, Labeling, SpatialReferenceSystem) {#constructor_2}

使用默认符号器创建新实例。

```csharp
public VectorMapLayer(FeaturesSequence featuresSequence, VectorSymbolizer symbolizer, 
    Labeling labeling, SpatialReferenceSystem defaultReferenceSystem = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| featuresSequence | FeaturesSequence | 要素序列。 |
| 符号化器 | VectorSymbolizer | 用于渲染图层的符号器。如果 `null`，将使用默认符号器。 |
| labeling | Labeling | 用于标记图层中要素的标签方式。如果 `null`，将使用默认的 [`NullLabeling`](../../../aspose.gis.rendering.labelings/nulllabeling/)。 |
| defaultReferenceSystem | SpatialReferenceSystem | 如果缺少源空间参考（layer\sequence），则指定其值。默认使用 **null**。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |

### 另见

* class [FeaturesSequence](../../../aspose.gis/featuressequence/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [Labeling](../../../aspose.gis.rendering.labelings/labeling/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [VectorMapLayer](../)
* namespace [Aspose.Gis.Rendering](../../vectormaplayer/)
* assembly [Aspose.GIS](../../../)

---

## VectorMapLayer(VectorLayer, bool) {#constructor_6}

使用默认符号器创建新实例。

```csharp
public VectorMapLayer(VectorLayer layer, bool keepOpen = true)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图层 | VectorLayer | 矢量图层。 |
| keepOpen | Boolean | `true` 表示在 [`VectorMapLayer`](../) 对象被释放后保持图层打开；否则为 `false`。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 图层为 `null`。 |

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [VectorMapLayer](../)
* namespace [Aspose.Gis.Rendering](../../vectormaplayer/)
* assembly [Aspose.GIS](../../../)

---

## VectorMapLayer(VectorLayer, VectorSymbolizer, bool) {#constructor_5}

创建新实例。

```csharp
public VectorMapLayer(VectorLayer layer, VectorSymbolizer symbolizer, bool keepOpen = true)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图层 | VectorLayer | 矢量图层。 |
| 符号化器 | VectorSymbolizer | 用于渲染图层的符号器。如果 `null`，将使用默认符号器。 |
| keepOpen | Boolean | `true` 表示在 [`VectorMapLayer`](../) 对象被释放后保持图层打开；否则为 `false`。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 图层为 `null`。 |

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [VectorMapLayer](../)
* namespace [Aspose.Gis.Rendering](../../vectormaplayer/)
* assembly [Aspose.GIS](../../../)

---

## VectorMapLayer(VectorLayer, VectorSymbolizer, Labeling, bool) {#constructor_4}

创建新实例。

```csharp
public VectorMapLayer(VectorLayer layer, VectorSymbolizer symbolizer, Labeling labeling, 
    bool keepOpen = true)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图层 | VectorLayer | 矢量图层。 |
| 符号化器 | VectorSymbolizer | 用于渲染图层的符号器。如果 `null`，将使用默认符号器。 |
| labeling | Labeling | 用于标记图层中要素的标签方式。如果 `null`，将使用默认的 [`NullLabeling`](../../../aspose.gis.rendering.labelings/nulllabeling/)。 |
| keepOpen | Boolean | `true` 表示在 [`VectorMapLayer`](../) 对象被释放后保持图层打开；否则为 `false`。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 图层为 `null`。 |

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [Labeling](../../../aspose.gis.rendering.labelings/labeling/)
* class [VectorMapLayer](../)
* namespace [Aspose.Gis.Rendering](../../vectormaplayer/)
* assembly [Aspose.GIS](../../../)

---

## VectorMapLayer(VectorLayer, VectorSymbolizer, Labeling, SpatialReferenceSystem, bool) {#constructor_3}

创建新实例。

```csharp
public VectorMapLayer(VectorLayer layer, VectorSymbolizer symbolizer, Labeling labeling, 
    SpatialReferenceSystem defaultReferenceSystem, bool keepOpen = true)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图层 | VectorLayer | 矢量图层。 |
| 符号化器 | VectorSymbolizer | 用于渲染图层的符号器。如果 `null`，将使用默认符号器。 |
| labeling | Labeling | 用于标记图层中要素的标签方式。如果 `null`，将使用默认的 [`NullLabeling`](../../../aspose.gis.rendering.labelings/nulllabeling/)。 |
| defaultReferenceSystem | SpatialReferenceSystem | 如果缺少源空间参考（layer\sequence），则指定其值。默认使用 **null**。 |
| keepOpen | Boolean | `true` 表示在 [`VectorMapLayer`](../) 对象被释放后保持图层打开；否则为 `false`。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 图层为 `null`。 |

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [Labeling](../../../aspose.gis.rendering.labelings/labeling/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [VectorMapLayer](../)
* namespace [Aspose.Gis.Rendering](../../vectormaplayer/)
* assembly [Aspose.GIS](../../../)


