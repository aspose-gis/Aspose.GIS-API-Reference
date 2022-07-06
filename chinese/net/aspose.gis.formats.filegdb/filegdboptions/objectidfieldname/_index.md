---
title: ObjectIdFieldName
second_title: Aspose.GIS for .NET API 参考
description: 对象 ID 字段的名称
type: docs
weight: 60
url: /zh/net/aspose.gis.formats.filegdb/filegdboptions/objectidfieldname/
---
## FileGdbOptions.ObjectIdFieldName property

对象 ID 字段的名称。

```csharp
public string ObjectIdFieldName { get; set; }
```

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| ArgumentException | 值不是有效的字段名称。有效的字段名称必须: &lt;ul&gt;&lt;li&gt;不能为`null`且不能为空&lt;/li&gt;&lt;li&gt;以拉丁字母或下划线开头&lt;/li&gt; &lt;li&gt;仅包含拉丁字母、数字或下划线&lt;/li&gt;&lt;/ul&gt; |

### 评论

这是一个创建选项，不影响读取。 定义对象 ID 字段（列）的名称。 默认为“OBJECTID”。 如果[`Attributes`](../../../aspose.gis/vectorlayer/attributes)中的任何属性的名称等于该属性的值，则 该属性被重命名.

### 也可以看看

* class [FileGdbOptions](../../filegdboptions)
* 命名空间 [Aspose.Gis.Formats.FileGdb](../../filegdboptions)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->