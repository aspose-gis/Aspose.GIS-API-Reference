---
title: "MultiCurve.ToLinearGeometry"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "MultiCurve 方法。使用指定的容差获取此几何体的近似或等效的非曲线版本"
type: docs
weight: 70
url: /zh/net/aspose.gis.geometries/multicurve/tolineargeometry/
---
## ToLinearGeometry(double) {#tolineargeometry_5}

使用指定的 `tolerance` 获取此几何对象的近似或等效的非曲线版本。

```csharp
public IMultiLineString ToLinearGeometry(double tolerance)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 容差 | Double | 要使用的 `tolerance`。保证结果与曲线几何的距离小于 `tolerance`，除非线性化几何所需的点数超过每象限的最大值，当前为 10000 点。 |

### 返回值

一个 [`IMultiLineString`](../../imultilinestring/) ，其近似或等价于此 [`IMultiCurve`](../../imulticurve/)：如果此对象本身是 [`IMultiLineString`](../../imultilinestring/)，结果等价于此对象；如果此对象不是 [`IMultiLineString`](../../imultilinestring/)，则所有曲线被线性化并创建新的 `IMultiLineString`

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | `tolerance` 小于或等于 `0`。 |
| InvalidOperationException | 此几何体以一种方式无效，导致操作无法完成。 |

### 另见

* interface [IMultiLineString](../../imultilinestring/)
* class [MultiCurve](../)
* namespace [Aspose.Gis.Geometries](../../multicurve/)
* assembly [Aspose.GIS](../../../)

---

## ToLinearGeometry() {#tolineargeometry_4}

使用默认的 `tolerance` 获取此几何对象的近似或等效的非曲线版本。

```csharp
public IMultiLineString ToLinearGeometry()
```

### 返回值

一个 [`IMultiLineString`](../../imultilinestring/) ，其近似或等价于此 [`IMultiCurve`](../../imulticurve/)。这相当于使用默认 `tolerance` 的 [`ToLinearGeometry`](../../imulticurve/tolineargeometry/)。默认 `tolerance` 的值取决于此几何体的 [`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)：对于投影坐标系，容差为 0.001 米（以 SRS 单位计）；对于地理坐标系，容差为 `1e-5` 度（以 SRS 单位计）；对于未知坐标系，容差为 `1e-5`。有关应用的转换的更多细节，请参阅 [`ToLinearGeometry`](../../imulticurve/tolineargeometry/) 规范。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 此几何体以一种方式无效，导致操作无法完成。 |

### 另见

* interface [IMultiLineString](../../imultilinestring/)
* class [MultiCurve](../)
* namespace [Aspose.Gis.Geometries](../../multicurve/)
* assembly [Aspose.GIS](../../../)


