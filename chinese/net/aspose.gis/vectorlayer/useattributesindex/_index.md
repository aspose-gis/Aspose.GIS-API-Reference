---
title: "VectorLayer.UseAttributesIndex"
second_title: "Aspose.GIS for .NET API 参考"
description: "VectorLayer 方法。加载属性索引以加速在诸如 WhereGreater 等过滤方法中按属性值进行过滤。如果索引不存在，则先创建。使用 forceRebuild 强制重新创建索引"
type: docs
weight: 200
url: /zh/net/aspose.gis/vectorlayer/useattributesindex/
---
## UseAttributesIndex(string, string, bool) {#useattributesindex_1}

加载属性索引以加速在诸如 [`WhereGreater`](../../featuressequence/wheregreater/) 等过滤方法中按属性值进行过滤。如果索引不存在，则先创建。使用 *forceRebuild* 强制重新创建索引。

```csharp
public void UseAttributesIndex(string indexPath, string attributeName, bool forceRebuild = false)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| indexPath | String | 索引文件的路径。 |
| attributeName | String | 用于构建索引的属性名称。 |
| forceRebuild | Boolean | 即使索引已存在，是否重新创建索引。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 图层中不存在具有该名称的属性。 |
| IOException | 发生 I/O 错误。 |
| InvalidOperationException | 指定属性的索引已为此图层加载。 |
| [GisException](../../gisexception/) | 文件已存在，但它不是由 Aspose.GIS 创建的属性索引文件。 |

### 另见

* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## UseAttributesIndex(AbstractPath, string, bool) {#useattributesindex}

加载属性索引以加速在诸如 [`WhereGreater`](../../featuressequence/wheregreater/) 等过滤方法中按属性值进行过滤。如果索引不存在，则先创建。使用 *forceRebuild* 强制重新创建索引。

```csharp
public virtual void UseAttributesIndex(AbstractPath indexPath, string attributeName, 
    bool forceRebuild = false)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| indexPath | AbstractPath | 索引文件的路径。 |
| attributeName | String | 用于构建索引的属性名称。 |
| forceRebuild | Boolean | 即使索引已存在，是否重新创建索引。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 图层中不存在具有该名称的属性。 |
| IOException | 发生 I/O 错误。 |
| InvalidOperationException | 指定属性的索引已为此图层加载。 |
| [GisException](../../gisexception/) | 文件已存在，但它不是由 Aspose.GIS 创建的属性索引文件。 |

### 另见

* class [AbstractPath](../../abstractpath/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)


