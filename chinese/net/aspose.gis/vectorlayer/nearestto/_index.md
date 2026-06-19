---
title: "VectorLayer.NearestTo"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "VectorLayer 方法。获取提供的坐标最近的 Feature"
type: docs
weight: 170
url: /zh/net/aspose.gis/vectorlayer/nearestto/
---
## NearestTo(double, double) {#nearestto_1}

获取最近于提供的坐标的特征。

```csharp
public Feature NearestTo(double x, double y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | Double | 坐标的 X。 |
| y | Double | 坐标的 Y。 |

### 返回值

提供的坐标最近的 Feature。

### 另见

* class [Feature](../../feature/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## NearestTo(IPoint) {#nearestto}

获取最近于提供的点的特征。

```csharp
public Feature NearestTo(IPoint point)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 点 | IPoint | 点。 |

### 返回值

提供的点最近的 Feature。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 点为 `null`。 |
| ArgumentException | 点为空或无效。 |

### 另见

* class [Feature](../../feature/)
* interface [IPoint](../../../aspose.gis.geometries/ipoint/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)


