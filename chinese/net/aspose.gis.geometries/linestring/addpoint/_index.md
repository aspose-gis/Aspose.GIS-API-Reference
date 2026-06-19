---
title: "LineString.AddPoint"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "LineString 方法。向线的末尾添加一个点"
type: docs
weight: 110
url: /zh/net/aspose.gis.geometries/linestring/addpoint/
---
## AddPoint(IPoint) {#addpoint}

在直线的末端添加一个点。

```csharp
public void AddPoint(IPoint point)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 点 | IPoint | 要添加的点。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | 参数为空（其[`IsEmpty`](../../igeometry/isempty/) 为 `true`）。 |
| ArgumentException | 此几何体的[`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/)和参数的[`SpatialReferenceSystem`](../spatialreferencesystem/)均不为 `null`，且彼此不相等。 |

### 另见

* interface [IPoint](../../ipoint/)
* class [LineString](../)
* namespace [Aspose.Gis.Geometries](../../linestring/)
* assembly [Aspose.GIS](../../../)

---

## AddPoint(double, double) {#addpoint_1}

在直线的末端添加一个点。

```csharp
public void AddPoint(double x, double y)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | Double | X 坐标的值。 |
| y | Double | Y 坐标的值。 |

### 另见

* class [LineString](../)
* namespace [Aspose.Gis.Geometries](../../linestring/)
* assembly [Aspose.GIS](../../../)

---

## AddPoint(double, double, double) {#addpoint_2}

在直线的末端添加一个点。

```csharp
public void AddPoint(double x, double y, double z)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | Double | X 坐标的值。 |
| y | Double | Y 坐标的值。 |
| z | Double | Z 坐标的值。 |

### 另见

* class [LineString](../)
* namespace [Aspose.Gis.Geometries](../../linestring/)
* assembly [Aspose.GIS](../../../)

---

## AddPoint(double, double, double, double) {#addpoint_3}

在直线的末端添加一个点。

```csharp
public void AddPoint(double x, double y, double z, double m)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| x | Double | X 坐标的值。 |
| y | Double | Y 坐标的值。 |
| z | Double | Z 坐标的值。 |
| m | Double | M 坐标的值。 |

### 另见

* class [LineString](../)
* namespace [Aspose.Gis.Geometries](../../linestring/)
* assembly [Aspose.GIS](../../../)


