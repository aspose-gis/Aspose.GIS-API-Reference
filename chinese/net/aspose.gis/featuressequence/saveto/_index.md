---
title: "FeaturesSequence.SaveTo"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "FeaturesSequence 方法。将要素序列保存到图层"
type: docs
weight: 50
url: /zh/net/aspose.gis/featuressequence/saveto/
---
## SaveTo(string, FileDriver) {#saveto_2}

将特征序列保存到图层。

```csharp
public void SaveTo(string destinationPath, FileDriver destinationDriver)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destinationPath | 字符串 | 输出图层的路径。 |
| destinationDriver | FileDriver | 输出图层的格式驱动程序。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 任意参数为 `null`。 |
| [GisException](../../gisexception/) | 读取或写入要素到/从文件时出错。 |
| IOException | 发生了 I/O 错误。 |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception/) | 从源空间参考系统到目标空间参考系统的要素几何转换失败。 |

### 另见

* class [FileDriver](../../filedriver/)
* class [FeaturesSequence](../)
* namespace [Aspose.Gis](../../featuressequence/)
* assembly [Aspose.GIS](../../../)

---

## SaveTo(AbstractPath, FileDriver) {#saveto}

将特征序列保存到图层。

```csharp
public void SaveTo(AbstractPath destinationPath, FileDriver destinationDriver)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destinationPath | AbstractPath | 输出图层的路径。 |
| destinationDriver | FileDriver | 输出图层的格式驱动程序。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [GisException](../../gisexception/) | 读取或写入要素到/从文件时出错。 |
| IOException | 发生了 I/O 错误。 |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception/) | 从源空间参考系统到目标空间参考系统的要素几何转换失败。 |

### 另见

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [FeaturesSequence](../)
* namespace [Aspose.Gis](../../featuressequence/)
* assembly [Aspose.GIS](../../../)

---

## SaveTo(string, FileDriver, SavingOptions) {#saveto_3}

将特征序列保存到图层。

```csharp
public void SaveTo(string destinationPath, FileDriver destinationDriver, SavingOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destinationPath | 字符串 | 输出图层的路径。 |
| destinationDriver | FileDriver | 输出图层的格式驱动程序。 |
| options | SavingOptions | 保存过程的选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [GisException](../../gisexception/) | 读取或写入要素到/从文件时出错。 |
| IOException | 发生了 I/O 错误。 |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception/) | 从源空间参考系统到目标空间参考系统的要素几何转换失败。 |
| NotSupportedException | 在 *options* 中指定的空间参考系统不受 *destinationDriver* 支持。 |

### 另见

* class [FileDriver](../../filedriver/)
* class [SavingOptions](../../savingoptions/)
* class [FeaturesSequence](../)
* namespace [Aspose.Gis](../../featuressequence/)
* assembly [Aspose.GIS](../../../)

---

## SaveTo(AbstractPath, FileDriver, SavingOptions) {#saveto_1}

将特征序列保存到图层。

```csharp
public void SaveTo(AbstractPath destinationPath, FileDriver destinationDriver, 
    SavingOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| destinationPath | AbstractPath | 输出图层的路径。 |
| destinationDriver | FileDriver | 输出图层的格式驱动程序。 |
| options | SavingOptions | 保存过程的选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| [GisException](../../gisexception/) | 读取或写入要素到/从文件时出错。 |
| IOException | 发生了 I/O 错误。 |
| [TransformationException](../../../aspose.gis.spatialreferencing/transformationexception/) | 从源空间参考系统到目标空间参考系统的要素几何转换失败。 |
| NotSupportedException | 在 *options* 中指定的空间参考系统不受 *destinationDriver* 支持。 |

### 另见

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [SavingOptions](../../savingoptions/)
* class [FeaturesSequence](../)
* namespace [Aspose.Gis](../../featuressequence/)
* assembly [Aspose.GIS](../../../)


