---
title: "FileDriver.EditLayer"
second_title: "Aspose.GIS for .NET API 参考"
description: "FileDriver 方法。打开图层进行编辑"
type: docs
weight: 70
url: /zh/net/aspose.gis/filedriver/editlayer/
---
## EditLayer(string, DriverOptions) {#editlayer_1}

打开图层进行编辑。

```csharp
public VectorLayer EditLayer(string path, DriverOptions options = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 文件的路径。 |
| options | DriverOptions | 驱动程序特定的选项。 |

### 返回值

一个 [`VectorLayer`](../../vectorlayer/) 实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 读取文件中的要素时出错。 |
| IOException | 发生 I/O 错误。 |

### 另见

* class [VectorLayer](../../vectorlayer/)
* class [DriverOptions](../../driveroptions/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## EditLayer(AbstractPath, DriverOptions) {#editlayer}

打开图层进行编辑。

```csharp
public virtual VectorLayer EditLayer(AbstractPath path, DriverOptions options = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 文件的路径。 |
| options | DriverOptions | 驱动程序特定的选项。 |

### 返回值

一个 [`VectorLayer`](../../vectorlayer/) 实例。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| ArgumentNullException | 路径为 `null`。 |
| [GisException](../../gisexception/) | 读取文件中的要素时出错。 |
| NotSupportedException | 驱动程序无法编辑图层。 |
| IOException | 发生 I/O 错误。 |

## 备注

驱动程序会创建一个包含所有要素的内部图层。但我们可以选择使用磁盘空间而不是 RAM。存在用于更优化资源使用的驱动程序（参见特定驱动程序文档）。此外，如果驱动程序能够创建和打开图层，它也可以编辑图层。

### 另见

* class [VectorLayer](../../vectorlayer/)
* class [AbstractPath](../../abstractpath/)
* class [DriverOptions](../../driveroptions/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)


