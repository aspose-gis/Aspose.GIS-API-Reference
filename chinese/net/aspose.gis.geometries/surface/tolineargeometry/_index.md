---
title: "Surface.ToLinearGeometry"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Surface 方法。使用默认容差获取此几何体的近似或等效的非曲线版本"
type: docs
weight: 40
url: /zh/net/aspose.gis.geometries/surface/tolineargeometry/
---
## ToLinearGeometry() {#tolineargeometry_2}

使用默认的 `tolerance` 获取此几何对象的近似或等效的非曲线版本。

```csharp
public IPolygon ToLinearGeometry()
```

### 返回值

一个 [`IPolygon`](../../ipolygon/) 是一个近似或等价于此 `ISurface` 的多边形。这相当于使用默认 `tolerance` 的 [`ToLinearGeometry`](../../isurface/tolineargeometry/)。默认 `tolerance` 的值取决于此几何体的 [`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)：对于投影坐标系，容差为 0.001 米（在 SRS 单位中）；对于地理坐标系，容差为 `1e-5` 度（在 SRS 单位中）；对于未知坐标系，容差为 `1e-5`。有关应用的转换的更多细节，请参阅 [`ToLinearGeometry`](../../isurface/tolineargeometry/) 规范。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 此几何体以一种方式无效，导致操作无法完成。 |

### 另见

* interface [IPolygon](../../ipolygon/)
* class [Surface](../)
* namespace [Aspose.Gis.Geometries](../../surface/)
* assembly [Aspose.GIS](../../../)

---

## ToLinearGeometry(double) {#tolineargeometry_3}

使用指定的 `tolerance` 获取此几何对象的近似或等效的非曲线版本。

```csharp
public IPolygon ToLinearGeometry(double tolerance)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 容差 | Double | 要使用的 `tolerance`。保证结果与曲线几何的距离小于 `tolerance`，除非线性化几何所需的点数超过每象限的最大值，当前为 10000 点。 |

### 返回值

一个近似或等价于此 `ISurface` 的 [`IPolygon`](../../ipolygon/)：如果此对象本身就是 [`IPolygon`](../../ipolygon/)，结果等同于此对象；如果此对象不是 [`IPolygon`](../../ipolygon/)，则会被线性化并创建 [`IPolygon`](../../ipolygon/)。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | `tolerance` 小于或等于 `0`。 |
| InvalidOperationException | 此几何体以一种方式无效，导致操作无法完成。 |

### 另见

* interface [IPolygon](../../ipolygon/)
* class [Surface](../)
* namespace [Aspose.Gis.Geometries](../../surface/)
* assembly [Aspose.GIS](../../../)


