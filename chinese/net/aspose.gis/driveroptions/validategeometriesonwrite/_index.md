---
title: "DriverOptions.ValidateGeometriesOnWrite"
second_title: "Aspose.GIS for .NET API 参考"
description: "DriverOptions 属性。确定在将几何添加到图层时是否应进行验证。如果设置为 true，则在几何被添加到图层时会调用 IsValid；如果验证失败，IsValid 为 false，则会抛出 GisException。"
type: docs
weight: 90
url: /zh/net/aspose.gis/driveroptions/validategeometriesonwrite/
---
## DriverOptions.ValidateGeometriesOnWrite property

确定在将几何添加到图层时是否应进行验证。如果设置为 `true`，则在几何被添加到图层时会调用 [`IsValid`](../../../aspose.gis.geometries/geometry/isvalid/)。如果验证失败（[`IsValid`](../../../aspose.gis.geometries/geometry/isvalid/) 为 `false`），则会抛出 [`GisException`](../../gisexception/)。

```csharp
public bool ValidateGeometriesOnWrite { get; set; }
```

## 备注

这是一个创建选项——它不影响打开。

### 另见

* class [DriverOptions](../)
* namespace [Aspose.Gis](../../driveroptions/)
* assembly [Aspose.GIS](../../../)


