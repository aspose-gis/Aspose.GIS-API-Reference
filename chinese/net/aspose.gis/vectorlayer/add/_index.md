---
title: VectorLayer.Add
second_title: Aspose.GIS for .NET API 参考
description: VectorLayer 方法. 向图层添加新功能如果支持VectorLayer秒Driver.
type: docs
weight: 80
url: /zh/net/aspose.gis/vectorlayer/add/
---
## Add(Feature) {#add}

向图层添加新功能（如果支持）[`VectorLayer`](../)秒[`Driver`](../driver/).

```csharp
public void Add(Feature feature)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| feature | Feature | 要添加的功能。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| InvalidOperationException | 如果层是只读的，则抛出。 |

### 也可以看看

* class [Feature](../../feature/)
* class [VectorLayer](../)
* 命名空间 [Aspose.Gis](../../vectorlayer/)
* 部件 [Aspose.GIS](../../../)

---

## Add(Feature, IFeatureStyle) {#add_1}

向图层添加具有指定样式的新功能（如果支持）[`VectorLayer`](../)秒[`Driver`](../driver/).

```csharp
public virtual void Add(Feature feature, IFeatureStyle style)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| feature | Feature | 要添加的功能。 |
| style | IFeatureStyle | 特征样式。使用`null`表示缺少样式。 |

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| InvalidOperationException | 如果图层不支持样式或图层是只读的，则抛出。 |
| InvalidOperationException | 如果可编辑图层不支持样式则抛出。 |
| ArgumentException | 如果样式与驱动程序类型不匹配则抛出。 |

### 也可以看看

* class [Feature](../../feature/)
* interface [IFeatureStyle](../../ifeaturestyle/)
* class [VectorLayer](../)
* 命名空间 [Aspose.Gis](../../vectorlayer/)
* 部件 [Aspose.GIS](../../../)


