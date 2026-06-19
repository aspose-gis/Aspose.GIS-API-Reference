---
title: "Map.Add"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Map 方法。创建一个具有默认符号器的 VectorMapLayer 并将其添加到地图。图层按照添加顺序渲染。"
type: docs
weight: 110
url: /zh/net/aspose.gis.rendering/map/add/
---
## Add(VectorLayer, bool) {#add_8}

创建一个具有默认符号器的 [`VectorMapLayer`](../../vectormaplayer/) 并将其添加到地图。图层按照添加顺序渲染。

```csharp
public void Add(VectorLayer layer, bool keepOpen = false)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| layer | VectorLayer | 用于由 [`VectorMapLayer`](../../vectormaplayer/) 表示的矢量图层。 |
| keepOpen | Boolean | `true` 表示在 [`Map`](../) 对象释放后保持矢量图层打开；`false` 表示释放该图层。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 图层为 `null`。 |

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)

---

## Add(VectorLayer, VectorSymbolizer, bool) {#add_7}

创建并将一个 [`VectorMapLayer`](../../vectormaplayer/) 添加到地图。图层按照添加顺序渲染。

```csharp
public void Add(VectorLayer layer, VectorSymbolizer symbolizer, bool keepOpen = false)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| layer | VectorLayer | 用于由 [`VectorMapLayer`](../../vectormaplayer/) 表示的矢量图层。 |
| 符号化器 | VectorSymbolizer | 用于渲染的符号化器。如果为 `null`，则使用默认符号化器。 |
| keepOpen | Boolean | `true` 表示在 [`Map`](../) 对象释放后保持矢量图层打开；`false` 表示释放该图层。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 图层为 `null`。 |

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)

---

## Add(VectorLayer, VectorSymbolizer, Labeling, bool) {#add_6}

创建并将一个 [`VectorMapLayer`](../../vectormaplayer/) 添加到地图。图层按照添加顺序渲染。

```csharp
public void Add(VectorLayer layer, VectorSymbolizer symbolizer, Labeling labeling, 
    bool keepOpen = false)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| layer | VectorLayer | 用于由 [`VectorMapLayer`](../../vectormaplayer/) 表示的矢量图层。 |
| 符号化器 | VectorSymbolizer | 用于渲染的符号化器。如果为 `null`，则使用默认符号化器。 |
| labeling | Labeling | 用于标记图层中要素的标签方式。如果 `null`，将使用默认的 [`NullLabeling`](../../../aspose.gis.rendering.labelings/nulllabeling/)。 |
| keepOpen | Boolean | `true` 表示在 [`Map`](../) 对象释放后保持图层打开；否则为 `false`。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 图层为 `null`。 |

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [Labeling](../../../aspose.gis.rendering.labelings/labeling/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)

---

## Add(VectorLayer, VectorSymbolizer, Labeling, SpatialReferenceSystem, bool) {#add_5}

创建并将一个 [`VectorMapLayer`](../../vectormaplayer/) 添加到地图。图层按照添加顺序渲染。

```csharp
public void Add(VectorLayer layer, VectorSymbolizer symbolizer, Labeling labeling, 
    SpatialReferenceSystem defaultReferenceSystem, bool keepOpen = false)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| layer | VectorLayer | 用于由 [`VectorMapLayer`](../../vectormaplayer/) 表示的矢量图层。 |
| 符号化器 | VectorSymbolizer | 用于渲染的符号化器。如果为 `null`，则使用默认符号化器。 |
| labeling | Labeling | 用于标记图层中要素的标签方式。如果 `null`，将使用默认的 [`NullLabeling`](../../../aspose.gis.rendering.labelings/nulllabeling/)。 |
| defaultReferenceSystem | SpatialReferenceSystem | 如果缺少源空间参考（layer\sequence），则指定其值。默认使用 **null**。 |
| keepOpen | Boolean | `true` 表示在 [`Map`](../) 对象释放后保持图层打开；否则为 `false`。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 图层为 `null`。 |

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [Labeling](../../../aspose.gis.rendering.labelings/labeling/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)

---

## Add(FeaturesSequence) {#add}

创建并将一个 [`VectorMapLayer`](../../vectormaplayer/) 添加到地图。图层按照添加顺序渲染。

```csharp
public void Add(FeaturesSequence featuresSequence)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| featuresSequence | FeaturesSequence | 用于由 [`VectorMapLayer`](../../vectormaplayer/) 表示的要素序列。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 要素序列为 `null`。 |

### 另见

* class [FeaturesSequence](../../../aspose.gis/featuressequence/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)

---

## Add(FeaturesSequence, VectorSymbolizer) {#add_1}

创建并将一个 [`VectorMapLayer`](../../vectormaplayer/) 添加到地图。图层按照添加顺序渲染。

```csharp
public void Add(FeaturesSequence featuresSequence, VectorSymbolizer symbolizer)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| featuresSequence | FeaturesSequence | 用于由 [`VectorMapLayer`](../../vectormaplayer/) 表示的要素序列。 |
| 符号化器 | VectorSymbolizer | 用于渲染的符号化器。如果为 `null`，则使用默认符号化器。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 要素序列为 `null`。 |

### 另见

* class [FeaturesSequence](../../../aspose.gis/featuressequence/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)

---

## Add(FeaturesSequence, VectorSymbolizer, Labeling) {#add_2}

创建并将一个 [`VectorMapLayer`](../../vectormaplayer/) 添加到地图。图层按照添加顺序渲染。

```csharp
public void Add(FeaturesSequence featuresSequence, VectorSymbolizer symbolizer, Labeling labeling)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| featuresSequence | FeaturesSequence | 用于由 [`VectorMapLayer`](../../vectormaplayer/) 表示的要素序列。 |
| 符号化器 | VectorSymbolizer | 用于渲染的符号器。 |
| labeling | Labeling | 用于标记图层中要素的标签方式。如果 `null`，将使用 [`NullLabeling`](../../../aspose.gis.rendering.labelings/nulllabeling/)。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 要素序列为 `null`。 |

### 另见

* class [FeaturesSequence](../../../aspose.gis/featuressequence/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [Labeling](../../../aspose.gis.rendering.labelings/labeling/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)

---

## Add(MapLayer) {#add_4}

向地图添加图层。图层按添加顺序渲染。

```csharp
public void Add(MapLayer mapLayer)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mapLayer | MapLayer | 要添加的图层。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |

### 另见

* class [MapLayer](../../maplayer/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)

---

## Add(RasterLayer, RasterColorizer, bool) {#add_3}

创建一个具有默认着色器的 [`RasterMapLayer`](../../rastermaplayer/) 并将其添加到地图。

```csharp
public void Add(RasterLayer layer, RasterColorizer colorizer = null, bool keepOpen = false)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| layer | RasterLayer | 用于由 [`RasterLayer`](../../../aspose.gis.raster/rasterlayer/) 表示的矢量图层。 |
| colorizer | RasterColorizer | 用于渲染的着色器。如果 `null`，将使用默认着色器。 |
| keepOpen | Boolean | `true` 表示在 [`Map`](../) 对象释放后保持栅格图层打开；`false` 表示释放该图层。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 图层为 `null`。 |

### 另见

* class [RasterLayer](../../../aspose.gis.raster/rasterlayer/)
* class [RasterColorizer](../../../aspose.gis.rendering.colorizers/rastercolorizer/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)


