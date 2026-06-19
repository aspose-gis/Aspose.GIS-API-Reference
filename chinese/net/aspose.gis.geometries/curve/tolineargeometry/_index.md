---
title: "Curve.ToLinearGeometry"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Curve 方法。获取此几何体的近似或等效的非曲线版本，使用默认容差"
type: docs
weight: 70
url: /zh/net/aspose.gis.geometries/curve/tolineargeometry/
---
## ToLinearGeometry() {#tolineargeometry_2}

使用默认的 `tolerance` 获取此几何对象的近似或等效的非曲线版本。

```csharp
public ILineString ToLinearGeometry()
```

### 返回值

一个 [`ILineString`](../../ilinestring/) ，其近似或等价于此曲线。它相当于使用默认 `tolerance` 的 [`ToLinearGeometry`](../../icurve/tolineargeometry/)。默认 `tolerance` 的值取决于此几何体的 [`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)：  对于投影坐标系，容差为 0.001 米（以 SRS 单位计）  对于地理坐标系，容差为 `1e-5` 度（以 SRS 单位计）  对于未知坐标系，容差为 `1e-5`  更多关于所应用的转换细节，请参阅 [`ToLinearGeometry`](../../icurve/tolineargeometry/) 规范。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 此几何体以一种方式无效，导致操作无法完成。 |

### 另见

* interface [ILineString](../../ilinestring/)
* class [Curve](../)
* namespace [Aspose.Gis.Geometries](../../curve/)
* assembly [Aspose.GIS](../../../)

---

## ToLinearGeometry(double) {#tolineargeometry_3}

使用指定的 `tolerance` 获取此几何对象的近似或等效的非曲线版本。

```csharp
public ILineString ToLinearGeometry(double tolerance)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 容差 | Double | 要使用的 `tolerance`。保证结果与曲线几何的距离小于 `tolerance`，除非线性化几何所需的点数超过每象限的最大值，当前为 10000 点。 |

### 返回值

一个 [`ILineString`](../../ilinestring/) ，其近似或等价于此曲线：  如果此对象本身是 [`ILineString`](../../ilinestring/)，结果等价于该对象；如果此对象是 [`ICircularString`](../../icircularstring/)，则结果为使用指定 *tolerance* 线性化后的圆弧字符串；如果此对象是 [`ICompoundCurve`](../../icompoundcurve/)，则所有曲线都会被线性化后合并为 [`ILineString`](../../ilinestring/)。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | `tolerance` 小于或等于 `0`。 |
| InvalidOperationException | 此几何体以一种方式无效，导致操作无法完成。 |

### 另见

* interface [ILineString](../../ilinestring/)
* class [Curve](../)
* namespace [Aspose.Gis.Geometries](../../curve/)
* assembly [Aspose.GIS](../../../)


