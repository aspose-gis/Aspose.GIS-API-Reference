---
title: "IGeometry.ToLinearGeometry"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "IGeometry 方法。使用默认容差获取此几何的近似或等效的非曲线版本"
type: docs
weight: 350
url: /zh/net/aspose.gis.geometries/igeometry/tolineargeometry/
---
## ToLinearGeometry() {#tolineargeometry}

使用默认的 `tolerance` 获取此几何对象的近似或等效的非曲线版本。

```csharp
public IGeometry ToLinearGeometry()
```

### 返回值

一种没有曲线几何的几何体。这相当于使用默认 `tolerance` 的 `ToLinearGeometry`。默认的 `tolerance` 由此几何体的 [`SpatialReferenceSystem`](../spatialreferencesystem/) 定义： 对于投影 SRS，容差为 0.001 米（以 SRS 单位计） 对于地理 SRS，容差为 `1e-5` 度（以 SRS 单位计） 对于未知 SRS，容差为 `1e-5` 如需了解所应用的转换的更多细节，请参阅 `ToLinearGeometry` 规范。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 此几何体以一种方式无效，导致操作无法完成。 |

### 另见

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)

---

## ToLinearGeometry(double) {#tolineargeometry_1}

使用指定的 `tolerance` 获取此几何对象的近似或等效的非曲线版本。

```csharp
public IGeometry ToLinearGeometry(double tolerance)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 容差 | Double | 要使用的 `tolerance`。结果保证与曲线几何体的距离小于 `tolerance`，除非线性化几何体所需的点数超过当前每象限最大值 10000 点。 |

### 返回值

一种没有曲线几何的几何体。应用以下转换：CircularStrings 被线性化（使用指定的 *tolerance* 转换为 LineStrings）CompoundCurves 被合并为 `LineString`s，CurvePolygons 被转换为 Polygons，MultiCurves 被转换为 MultiLineStrings，MultiSurfaces 被转换为 MultiPolygons。结果，输出几何体的 [`HasCurveGeometry`](../hascurvegeometry/) 为 `false`。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | `tolerance` 小于或等于 `0`。 |
| InvalidOperationException | 此几何体以一种方式无效，导致操作无法完成。 |

### 另见

* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


