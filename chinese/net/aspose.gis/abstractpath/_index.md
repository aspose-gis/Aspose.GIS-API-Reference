---
title: "类 AbstractPath"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.AbstractPath 类。AbstractPath 是用于指定类似文件系统环境（如本地文件系统、远程文件存储或 ZIP 存档等）中唯一位置的基类。"
type: docs
weight: 10
url: /zh/net/aspose.gis/abstractpath/
---
## AbstractPath class

`AbstractPath` 是一个基类，用于指定在类似文件系统的环境中唯一位置的类，例如本地文件系统、远程文件存储或 ZIP 存档等。

```csharp
public abstract class AbstractPath
```

## 属性

| 名称 | 描述 |
| --- | --- |
| abstract [Location](../../aspose.gis/abstractpath/location/) { get; } | 获取此 `AbstractPath` 位置的字符串表示。 |
| abstract [Separator](../../aspose.gis/abstractpath/separator/) { get; } | 获取用于分隔 [`Location`](./location/) 字符串目录层级的分隔符字符。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [FromLocalPath](../../aspose.gis/abstractpath/fromlocalpath/)(string) | 创建一个表示本地文件系统上位置的 `AbstractPath`。 |
| static [FromStream](../../aspose.gis/abstractpath/fromstream/)(Stream) | 从流创建 `AbstractPath`。 |
| virtual [Combine](../../aspose.gis/abstractpath/combine/)(string) | 将此 `AbstractPath` 与指定的路径组件组合。 |
| abstract [Delete](../../aspose.gis/abstractpath/delete/)() | 删除此路径指向的文件。 |
| [GetExtension](../../aspose.gis/abstractpath/getextension/)() | 返回此 `AbstractPath` 的扩展名。 |
| [GetFileName](../../aspose.gis/abstractpath/getfilename/)() | 返回此 `AbstractPath` 的文件名和扩展名。 |
| [GetFileNameWithoutExtension](../../aspose.gis/abstractpath/getfilenamewithoutextension/)() | 返回此 `AbstractPath` 的文件名（不含扩展名）。 |
| abstract [IsFile](../../aspose.gis/abstractpath/isfile/)() | 获取一个值，指示此路径是否指向可供读取的现有文件。 |
| abstract [ListDirectory](../../aspose.gis/abstractpath/listdirectory/)() | 如果这是目录，则返回位于此 `AbstractPath` 内的路径。 |
| abstract [Open](../../aspose.gis/abstractpath/open/)(FileAccess) | 将此 `AbstractPath` 作为文件打开。 |
| virtual [WithExtension](../../aspose.gis/abstractpath/withextension/)(string) | 返回一个新的 `AbstractPath`，其文件扩展名已更改为指定的值。 |

## 备注

`AbstractPath` 可以指定本地文件系统上的位置、远程文件系统上的位置或类似 Azure Blob 存储的外部存储，等等。该位置可能指向已存在或不存在的类文件对象、类目录对象，或具有对其所属环境合理的其他含义。例如，表示本地文件系统位置的 `AbstractPath` 子类可以指向已有的文件、目录，或指向尚未创建的文件系统位置。为了使新的类文件系统存储可供 `Aspose.GIS` 使用，应继承此类并实现其抽象方法。

### 另见

* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


