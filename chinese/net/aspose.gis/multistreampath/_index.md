---
title: "类 MultiStreamPath"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.MultiStreamPath 类。此类用于处理包含多个文件的格式。"
type: docs
weight: 3430
url: /zh/net/aspose.gis/multistreampath/
---
## MultiStreamPath class

此类用于处理包含多个文件的格式。

```csharp
public class MultiStreamPath : AbstractPath, IDisposable
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [MultiStreamPath](multistreampath/)(string, Dictionary&lt;string, Stream&gt;) | 创建 `MultiStreamPath` 的实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| override [Location](../../aspose.gis/multistreampath/location/) { get; } | 获取此 `AbstractPath` 位置的字符串表示。 |
| override [Separator](../../aspose.gis/multistreampath/separator/) { get; } | 获取用于分隔 [`Location`](./location/) 字符串目录层级的分隔符字符。 |
| [StreamSet](../../aspose.gis/multistreampath/streamset/) { get; } | 一组映射到文件名的实际流。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| virtual [Combine](../../aspose.gis/abstractpath/combine/)(string) | 将此 [`AbstractPath`](../abstractpath/) 与指定的路径组件组合。 |
| override [Delete](../../aspose.gis/multistreampath/delete/)() | 删除此路径指向的文件。 |
| [Dispose](../../aspose.gis/multistreampath/dispose/)() | 销毁对象及其内容。 |
| [GetExtension](../../aspose.gis/abstractpath/getextension/)() | 返回此 [`AbstractPath`](../abstractpath/) 的扩展名。 |
| [GetFileName](../../aspose.gis/abstractpath/getfilename/)() | 返回此 [`AbstractPath`](../abstractpath/) 的文件名和扩展名。 |
| [GetFileNameWithoutExtension](../../aspose.gis/abstractpath/getfilenamewithoutextension/)() | 返回此 [`AbstractPath`](../abstractpath/) 的文件名（不含扩展名）。 |
| override [IsFile](../../aspose.gis/multistreampath/isfile/)() | 获取一个值，指示此路径是否指向可供读取的现有文件。 |
| override [ListDirectory](../../aspose.gis/multistreampath/listdirectory/)() | 如果这是目录，则返回位于此 `AbstractPath` 内的路径。 |
| override [Open](../../aspose.gis/multistreampath/open/)(FileAccess) | 抽象出一组用于访问数据的打开流式多文件格式的路径。 |
| virtual [WithExtension](../../aspose.gis/abstractpath/withextension/)(string) | 返回一个新的 [`AbstractPath`](../abstractpath/)，其文件扩展名已更改为指定值。 |

### 另见

* class [AbstractPath](../abstractpath/)
* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


