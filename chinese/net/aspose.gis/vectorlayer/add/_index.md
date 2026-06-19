---
title: "VectorLayer.Add"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "VectorLayer 方法。若 VectorLayers Driver 支持，则向图层添加新要素。"
type: docs
weight: 80
url: /zh/net/aspose.gis/vectorlayer/add/
---
## Add(Feature) {#add}

如果 [`VectorLayer`](../) 的 [`Driver`](../driver/) 支持，则向图层添加新要素。

```csharp
public virtual void Add(Feature feature)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 要素 | Feature | 要添加的要素。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 当图层为只读时抛出。 |

### 另见

* class [Feature](../../feature/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Add(Feature, IFeatureStyle) {#add_1}

如果 [`VectorLayer`](../) 的 [`Driver`](../driver/) 支持，则向图层添加带有指定样式的新要素。

```csharp
public virtual void Add(Feature feature, IFeatureStyle style)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 要素 | Feature | 要添加的要素。 |
| 样式 | IFeatureStyle | 要素样式。使用 `null` 表示缺失的样式。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 当图层不支持样式或为只读时抛出。 |
| InvalidOperationException | 当可编辑图层不支持样式时抛出。 |
| ArgumentException | 当样式与驱动类型不匹配时抛出。 |

### 另见

* class [Feature](../../feature/)
* interface [IFeatureStyle](../../ifeaturestyle/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)


