---
title: "Geometry.AsImage"
second_title: "Aspose.GIS for .NET API 参考"
description: "Geometry 方法。将此几何体导出为图像表示"
type: docs
weight: 120
url: /zh/net/aspose.gis.geometries/geometry/asimage/
---
## AsImage(AbstractPath, Measurement, Measurement, Renderer, VectorSymbolizer) {#asimage_1}

将此几何体导出为图像表示。

```csharp
public void AsImage(AbstractPath outputPath, Measurement width, Measurement height, 
    Renderer renderer, VectorSymbolizer symbolizer = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputPath | AbstractPath | 输出图像的路径。 |
| 宽度 | 测量 | 地图的宽度。 |
| 高度 | 测量 | 地图的高度。 |
| 渲染器 | 渲染器 | 要使用的渲染器。 |
| 符号化器 | VectorSymbolizer | 用于渲染的符号化器。如果 `null`，则使用默认符号化器。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 任何参数 `null`。 |
| IOException | 发生 I/O 错误。 |
| [GisException](../../../aspose.gis/gisexception/) | 处理或读取 GIS 数据时出错。 |
| ArgumentException | 宽度或高度的单位是 !:Unit.MapUnits。 |
| ArgumentOutOfRangeException | 宽度或高度为负数或零。 |

### 另见

* class [AbstractPath](../../../aspose.gis/abstractpath/)
* struct [Measurement](../../../aspose.gis.rendering/measurement/)
* class [Renderer](../../../aspose.gis.rendering/renderer/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)

---

## AsImage(string, Measurement, Measurement, Renderer, VectorSymbolizer) {#asimage_2}

将此几何体导出为图像表示。

```csharp
public void AsImage(string outputPath, Measurement width, Measurement height, Renderer renderer, 
    VectorSymbolizer symbolizer = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputPath | String | 输出图像的路径。 |
| 宽度 | 测量 | 地图的宽度。 |
| 高度 | 测量 | 地图的高度。 |
| 渲染器 | 渲染器 | 要使用的渲染器。 |
| 符号化器 | VectorSymbolizer | 用于渲染的符号化器。如果 `null`，则使用默认符号化器。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 任何参数 `null`。 |
| IOException | 发生 I/O 错误。 |
| [GisException](../../../aspose.gis/gisexception/) | 处理或读取 GIS 数据时出错。 |
| ArgumentException | 宽度或高度的单位是 !:Unit.MapUnits。 |
| ArgumentOutOfRangeException | 宽度或高度为负数或零。 |

### 另见

* struct [Measurement](../../../aspose.gis.rendering/measurement/)
* class [Renderer](../../../aspose.gis.rendering/renderer/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)

---

## AsImage(Measurement, Measurement, Renderer, VectorSymbolizer) {#asimage}

将此几何体导出为图像表示。

```csharp
public Stream AsImage(Measurement width, Measurement height, Renderer renderer, 
    VectorSymbolizer symbolizer = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 宽度 | 测量 | 地图的宽度。 |
| 高度 | 测量 | 地图的高度。 |
| 渲染器 | 渲染器 | 要使用的渲染器。 |
| 符号化器 | VectorSymbolizer | 用于渲染的符号化器。如果 `null`，则使用默认符号化器。 |

### 返回值

图像作为流

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 任何参数 `null`。 |
| IOException | 发生 I/O 错误。 |
| [GisException](../../../aspose.gis/gisexception/) | 处理或读取 GIS 数据时出错。 |
| ArgumentException | 宽度或高度的单位是 !:Unit.MapUnits。 |
| ArgumentOutOfRangeException | 宽度或高度为负数或零。 |

### 另见

* struct [Measurement](../../../aspose.gis.rendering/measurement/)
* class [Renderer](../../../aspose.gis.rendering/renderer/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


