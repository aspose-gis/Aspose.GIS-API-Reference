---
title: "DriverOptions.LinearizationTolerance"
second_title: "Aspose.GIS for .NET API 参考"
description: "DriverOptions 属性。用于线性化曲线几何的容差"
type: docs
weight: 50
url: /zh/net/aspose.gis/driveroptions/linearizationtolerance/
---
## DriverOptions.LinearizationTolerance property

用于线性化曲线几何体的容差。

```csharp
public double LinearizationTolerance { get; set; }
```

### Property Value

在添加几何之前传递给 [`ToLinearGeometry`](../../../aspose.gis.geometries/geometry/tolineargeometry/) 的容差。

## 备注

这是一个创建选项 - 它不影响打开。如果驱动不支持非线性几何，它们会自动线性化。此属性指定传递给用于线性化的 [`ToLinearGeometry`](../../../aspose.gis.geometries/geometry/tolineargeometry/) 方法的参数。

### 另见

* class [DriverOptions](../)
* namespace [Aspose.Gis](../../driveroptions/)
* assembly [Aspose.GIS](../../../)


