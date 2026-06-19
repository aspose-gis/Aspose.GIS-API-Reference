---
title: "RasterLayer.Crop"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "RasterLayer 方法。使用形状和波段掩码裁剪栅格图层。"
type: docs
weight: 110
url: /zh/net/aspose.gis.raster/rasterlayer/crop/
---
## Crop(IGeometry, double[]) {#crop}

使用形状（以及波段掩码）裁剪栅格图层。

```csharp
public RasterLayer Crop(IGeometry geometry, double[] masks = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 几何体 | IGeometry | 几何表示形状。 |
| 掩码 | Double[] | 裁剪图层的掩码 |

### 返回值

裁剪后的栅格图层。如果未找到交集则返回 `null`。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数不能为空。参数名：geometry。 |
| NotSupportedException | 参数必须是多边形或曲面。参数名：geometry。 |
| InvalidOperationException | 原始图层不能是另一个 CropRasterLayer。 |
| [GisException](../../../aspose.gis/gisexception/) | 裁剪图层时出错。 |

### 另见

* interface [IGeometry](../../../aspose.gis.geometries/igeometry/)
* class [RasterLayer](../)
* namespace [Aspose.Gis.Raster](../../rasterlayer/)
* assembly [Aspose.GIS](../../../)

---

## Crop(double[]) {#crop_1}

使用波段掩码裁剪栅格图层)。

```csharp
public RasterLayer Crop(double[] masks)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 掩码 | Double[] | 裁剪图层的掩码 |

### 返回值

裁剪后的栅格图层。如果未找到交集则返回 `null`。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException |  |

### 另见

* class [RasterLayer](../)
* namespace [Aspose.Gis.Raster](../../rasterlayer/)
* assembly [Aspose.GIS](../../../)


