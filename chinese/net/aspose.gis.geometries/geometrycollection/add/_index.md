---
title: "GeometryCollection.Add"
second_title: "Aspose.GIS for .NET API 参考"
description: "GeometryCollection 方法。将指定的几何体添加到集合中"
type: docs
weight: 110
url: /zh/net/aspose.gis.geometries/geometrycollection/add/
---
## GeometryCollection.Add method

将指定几何体添加到集合中。

```csharp
public void Add(IGeometry geometry)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 几何体 | IGeometry | 要添加的几何体。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 该集合不接受此类型的几何体。 |
| ArgumentException | 此几何体的 [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) 与参数的 [`SpatialReferenceSystem`](../spatialreferencesystem/) 均不为 `null` 且彼此不相等。 |

### 另见

* interface [IGeometry](../../igeometry/)
* class [GeometryCollection](../)
* namespace [Aspose.Gis.Geometries](../../geometrycollection/)
* assembly [Aspose.GIS](../../../)


