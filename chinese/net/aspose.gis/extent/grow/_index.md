---
title: "Extent.Grow"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Extent 方法。扩展此范围以包含参数。"
type: docs
weight: 160
url: /zh/net/aspose.gis/extent/grow/
---
## Grow(Extent) {#grow}

扩展此范围，使其包含参数。

```csharp
public void Grow(Extent extent)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 范围 | 范围 | 另一个范围。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 此范围和参数的[`SpatialReferenceSystem`](../spatialreferencesystem/)均不为 `null` 且彼此不相等。 |

## 备注

如果此 SRS 的 [`SpatialReferenceSystem`](../spatialreferencesystem/) 为 `null`，则会使用参数的 SRS 进行更新。

### 另见

* class [Extent](../)
* namespace [Aspose.Gis](../../extent/)
* assembly [Aspose.GIS](../../../)

---

## Grow(double, double) {#grow_1}

扩展此范围，使其包含指定的点。

```csharp
public void Grow(double x, double y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | Double | 要包含的 X 坐标。 |
| y | Double | 要包含的 Y 坐标。 |

### 另见

* class [Extent](../)
* namespace [Aspose.Gis](../../extent/)
* assembly [Aspose.GIS](../../../)


