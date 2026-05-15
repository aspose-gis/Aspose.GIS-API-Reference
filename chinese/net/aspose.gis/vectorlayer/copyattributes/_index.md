---
title: "VectorLayer.CopyAttributes"
second_title: "Aspose.GIS for .NET API 参考"
description: "VectorLayer 方法。将其他 VectorLayer 的属性复制到此对象"
type: docs
weight: 110
url: /zh/net/aspose.gis/vectorlayer/copyattributes/
---
## CopyAttributes(FeaturesSequence) {#copyattributes}

将其他 [`VectorLayer`](../) 的属性复制到此对象。

```csharp
public void CopyAttributes(FeaturesSequence featuresSequence)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| featuresSequence | FeaturesSequence | 用于复制属性的要素序列。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 输入图层为 `null`。 |

### 另见

* class [FeaturesSequence](../../featuressequence/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## CopyAttributes(FeaturesSequence, IAttributesConverter) {#copyattributes_1}

将其他 [`VectorLayer`](../) 的属性复制到此对象。

```csharp
public void CopyAttributes(FeaturesSequence featuresSequence, IAttributesConverter converter)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| featuresSequence | FeaturesSequence | 用于复制属性的要素序列。 |
| converter | IAttributesConverter | 自定义 [`IAttributesConverter`](../../iattributesconverter/) 的实例，将逐个处理属性。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 输入图层为 `null`。 |

### 另见

* class [FeaturesSequence](../../featuressequence/)
* interface [IAttributesConverter](../../iattributesconverter/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)


