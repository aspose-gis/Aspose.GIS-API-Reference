---
title: "ShapefileDriver.EditLayer"
second_title: "Aspose.GIS for .NET API 参考"
description: "ShapefileDriver 方法。打开图层进行编辑"
type: docs
weight: 50
url: /zh/net/aspose.gis.formats.shapefile/shapefiledriver/editlayer/
---
## EditLayer(AbstractPath, DriverOptions) {#editlayer}

打开图层进行编辑。

```csharp
public override VectorLayer EditLayer(AbstractPath path, DriverOptions options = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 文件的路径。 |
| options | DriverOptions | 驱动程序特定的选项。 |

### 返回值

[`VectorLayer`](../../../aspose.gis/vectorlayer/) 的实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../../aspose.gis/gisexception/) | 读取文件中的要素时出错。 |
| IOException | 发生 I/O 错误。 |

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [DriverOptions](../../../aspose.gis/driveroptions/)
* class [ShapefileDriver](../)
* namespace [Aspose.Gis.Formats.Shapefile](../../shapefiledriver/)
* assembly [Aspose.GIS](../../../)

---

## EditLayer(string, ShapefileOptions) {#editlayer_3}

打开图层进行编辑。

```csharp
public VectorLayer EditLayer(string path, ShapefileOptions options = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 文件的路径。 |
| options | ShapefileOptions | 驱动程序特定的选项。 |

### 返回值

[`VectorLayer`](../../../aspose.gis/vectorlayer/) 的实例。

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [ShapefileOptions](../../shapefileoptions/)
* class [ShapefileDriver](../)
* namespace [Aspose.Gis.Formats.Shapefile](../../shapefiledriver/)
* assembly [Aspose.GIS](../../../)

---

## EditLayer(AbstractPath, ShapefileOptions) {#editlayer_1}

打开图层进行编辑。

```csharp
public VectorLayer EditLayer(AbstractPath path, ShapefileOptions options = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 文件的路径。 |
| options | ShapefileOptions | 驱动程序特定的选项。 |

### 返回值

[`VectorLayer`](../../../aspose.gis/vectorlayer/) 的实例。

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [ShapefileOptions](../../shapefileoptions/)
* class [ShapefileDriver](../)
* namespace [Aspose.Gis.Formats.Shapefile](../../shapefiledriver/)
* assembly [Aspose.GIS](../../../)


