---
title: "FeaturesSequence.WhereIntersects"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "FeaturesSequence 方法。根据其他要素序列中所有几何的联合来过滤要素"
type: docs
weight: 100
url: /zh/net/aspose.gis/featuressequence/whereintersects/
---
## WhereIntersects(FeaturesSequence) {#whereintersects_1}

根据其他要素序列中所有几何的并集过滤要素。

```csharp
public FeaturesSequence WhereIntersects(FeaturesSequence sequence)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 序列 | FeaturesSequence | 其他要素序列。 |

### 返回值

与其他要素序列中所有几何的联合相交的要素。

### 另见

* class [FeaturesSequence](../)
* namespace [Aspose.Gis](../../featuressequence/)
* assembly [Aspose.GIS](../../../)

---

## WhereIntersects(IGeometry) {#whereintersects_2}

根据提供的几何过滤要素。

```csharp
public virtual FeaturesSequence WhereIntersects(IGeometry geometry)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 几何体 | IGeometry | 过滤几何。 |

### 返回值

与提供的几何相交的要素。

### 另见

* interface [IGeometry](../../../aspose.gis.geometries/igeometry/)
* class [FeaturesSequence](../)
* namespace [Aspose.Gis](../../featuressequence/)
* assembly [Aspose.GIS](../../../)

---

## WhereIntersects(Extent) {#whereintersects}

根据范围过滤要素。

```csharp
public virtual FeaturesSequence WhereIntersects(Extent extent)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 范围 | 范围 | 过滤范围。 |

### 返回值

与提供的几何相交的要素。

### 另见

* class [Extent](../../extent/)
* class [FeaturesSequence](../)
* namespace [Aspose.Gis](../../featuressequence/)
* assembly [Aspose.GIS](../../../)


