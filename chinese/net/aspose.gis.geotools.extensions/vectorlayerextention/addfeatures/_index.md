---
title: "VectorLayerExtention.AddFeatures"
second_title: "Aspose.GIS for .NET API 参考"
description: "VectorLayerExtention 方法。使用通用列表添加要素"
type: docs
weight: 10
url: /zh/net/aspose.gis.geotools.extensions/vectorlayerextention/addfeatures/
---
## AddFeatures&lt;T&gt;(this VectorLayer, List&lt;T&gt;) {#addfeatures_1}

使用通用列表添加要素。

```csharp
public static void AddFeatures<T>(this VectorLayer layer, List<T> featuresData)
    where T : new()
```

| 参数 | 描述 |
| --- | --- |
| T | 通用类型。 |
| 图层 | 要添加的图层。 |
| featuresData | 输入数据。 |

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [VectorLayerExtention](../)
* namespace [Aspose.Gis.GeoTools.Extensions](../../vectorlayerextention/)
* assembly [Aspose.GIS](../../../)

---

## AddFeatures(this VectorLayer, IEnumerable&lt;IGeometry&gt;) {#addfeatures}

使用通用列表添加要素。

```csharp
public static void AddFeatures(this VectorLayer layer, IEnumerable<IGeometry> geometries)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图层 | VectorLayer | 要添加的图层。 |
| geometries | IEnumerable`1 | 输入几何体。 |

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* interface [IGeometry](../../../aspose.gis.geometries/igeometry/)
* class [VectorLayerExtention](../)
* namespace [Aspose.Gis.GeoTools.Extensions](../../vectorlayerextention/)
* assembly [Aspose.GIS](../../../)


