---
title: "VectorLayer.Convert"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "VectorLayer 方法。将图层转换为不同的格式。"
type: docs
weight: 220
url: /zh/net/aspose.gis/vectorlayer/convert/
---
## Convert(string, FileDriver, string, FileDriver) {#convert_2}

将图层转换为不同的格式。

```csharp
public static void Convert(string sourcePath, FileDriver sourceDriver, string destinationPath, 
    FileDriver destinationDriver)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | 字符串 | 要转换的图层的路径。 |
| sourceDriver | FileDriver | 源图层的格式驱动程序。 |
| destinationPath | 字符串 | 转换后创建的图层的路径。 |
| destinationDriver | FileDriver | 目标图层的格式驱动程序。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 任一路径为 `null`。 |

### 另见

* class [FileDriver](../../filedriver/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Convert(AbstractPath, FileDriver, AbstractPath, FileDriver) {#convert}

将图层转换为不同的格式。

```csharp
public static void Convert(AbstractPath sourcePath, FileDriver sourceDriver, 
    AbstractPath destinationPath, FileDriver destinationDriver)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | AbstractPath | 要转换的图层的路径。 |
| sourceDriver | FileDriver | 源图层的格式驱动程序。 |
| destinationPath | AbstractPath | 转换后创建的图层的路径。 |
| destinationDriver | FileDriver | 目标图层的格式驱动程序。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 任一路径为 `null`。 |

### 另见

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Convert(string, FileDriver, string, FileDriver, ConversionOptions) {#convert_3}

将图层转换为不同的格式。

```csharp
public static void Convert(string sourcePath, FileDriver sourceDriver, string destinationPath, 
    FileDriver destinationDriver, ConversionOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | 字符串 | 要转换的图层的路径。 |
| sourceDriver | FileDriver | 源图层的格式驱动程序。 |
| destinationPath | 字符串 | 转换后创建的图层的路径。 |
| destinationDriver | FileDriver | 目标图层的格式驱动程序。 |
| options | ConversionOptions | 转换过程的选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 任一路径为 `null`。 |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| [GisException](../../gisexception/) | 读取或写入要素到/从文件时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 在 *options* 中指定的空间参考系统不受 *destinationDriver* 支持。 |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception/) | 从源空间参考系统到目标空间参考系统的要素几何转换失败。 |

### 另见

* class [FileDriver](../../filedriver/)
* class [ConversionOptions](../../conversionoptions/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Convert(AbstractPath, FileDriver, AbstractPath, FileDriver, ConversionOptions) {#convert_1}

将图层转换为不同的格式。

```csharp
public static void Convert(AbstractPath sourcePath, FileDriver sourceDriver, 
    AbstractPath destinationPath, FileDriver destinationDriver, ConversionOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourcePath | AbstractPath | 要转换的图层的路径。 |
| sourceDriver | FileDriver | 源图层的格式驱动程序。 |
| destinationPath | AbstractPath | 转换后创建的图层的路径。 |
| destinationDriver | FileDriver | 目标图层的格式驱动程序。 |
| options | ConversionOptions | 转换过程的选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 任一路径为 `null`。 |
| ArgumentException | Options 对象的类型对该驱动程序不正确。 |
| [GisException](../../gisexception/) | 读取或写入要素到/从文件时出错。 |
| IOException | 发生了 I/O 错误。 |
| NotSupportedException | 在 *options* 中指定的空间参考系统不受 *destinationDriver* 支持。 |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception/) | 从源空间参考系统到目标空间参考系统的要素几何转换失败。 |

### 另见

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [ConversionOptions](../../conversionoptions/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)


