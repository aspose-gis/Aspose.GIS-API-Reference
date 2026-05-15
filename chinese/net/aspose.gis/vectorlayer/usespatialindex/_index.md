---
title: "VectorLayer.UseSpatialIndex"
second_title: "Aspose.GIS for .NET API 参考"
description: "VectorLayer 方法。加载空间索引以加快在诸如 WhereIntersects 和 NearestTo 等过滤方法中按属性值进行过滤的速度。如果索引不存在，则先创建它。使用 forceRebuild 强制重新创建索引。"
type: docs
weight: 210
url: /zh/net/aspose.gis/vectorlayer/usespatialindex/
---
## UseSpatialIndex(string, bool) {#usespatialindex_1}

加载空间索引以加快在过滤方法（如 [`WhereIntersects`](../../featuressequence/whereintersects/) 和 [`NearestTo`](../nearestto/)）中按属性值进行过滤的速度。如果索引不存在，则先创建它。使用 *forceRebuild* 强制重新创建索引。

```csharp
public void UseSpatialIndex(string indexPath, bool forceRebuild = false)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| indexPath | String | 索引文件的路径。 |
| forceRebuild | Boolean | 即使索引已存在，是否重新创建索引。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 路径为 `null`。 |
| IOException | 发生 I/O 错误。 |
| InvalidOperationException | 此图层的空间索引已加载。 |
| [GisException](../../gisexception/) | 文件已存在，但它不是由 Aspose.GIS 创建的空间索引文件。 |

### 另见

* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## UseSpatialIndex(AbstractPath, bool) {#usespatialindex}

加载空间索引以加快在过滤方法（如 [`WhereIntersects`](../../featuressequence/whereintersects/) 和 [`NearestTo`](../nearestto/)）中按属性值进行过滤的速度。如果索引不存在，则先创建它。使用 *forceRebuild* 强制重新创建索引。

```csharp
public virtual void UseSpatialIndex(AbstractPath indexPath, bool forceRebuild = false)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| indexPath | AbstractPath | 索引文件的路径。 |
| forceRebuild | Boolean | 即使索引已存在，是否重新创建索引。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 路径为 `null`。 |
| IOException | 发生 I/O 错误。 |
| InvalidOperationException | 此图层的空间索引已加载。 |
| [GisException](../../gisexception/) | 文件已存在，但它不是由 Aspose.GIS 创建的空间索引文件。 |

### 另见

* class [AbstractPath](../../abstractpath/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)


