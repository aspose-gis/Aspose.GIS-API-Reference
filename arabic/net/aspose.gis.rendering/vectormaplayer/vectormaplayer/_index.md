---
title: "VectorMapLayer.VectorMapLayer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "منشئ VectorMapLayer. ينشئ مثيلاً جديداً باستخدام المُرمّز الافتراضي"
type: docs
weight: 10
url: /ar/net/aspose.gis.rendering/vectormaplayer/vectormaplayer/
---
## VectorMapLayer(FeaturesSequence) {#constructor}

ينشئ نسخة جديدة مع المُرمّز الافتراضي.

```csharp
public VectorMapLayer(FeaturesSequence featuresSequence)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| featuresSequence | FeaturesSequence | تسلسل الميزات. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |

### انظر أيضًا

* class [FeaturesSequence](../../../aspose.gis/featuressequence/)
* class [VectorMapLayer](../)
* namespace [Aspose.Gis.Rendering](../../vectormaplayer/)
* assembly [Aspose.GIS](../../../)

---

## VectorMapLayer(FeaturesSequence, VectorSymbolizer) {#constructor_1}

ينشئ نسخة جديدة مع المُرمّز الافتراضي.

```csharp
public VectorMapLayer(FeaturesSequence featuresSequence, VectorSymbolizer symbolizer)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| featuresSequence | FeaturesSequence | تسلسل الميزات. |
| symbolizer | VectorSymbolizer | المُرمّز المستخدم لعرض الطبقة. إذا كان `null`، سيُستخدم المُرمّز الافتراضي. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |

### انظر أيضًا

* class [FeaturesSequence](../../../aspose.gis/featuressequence/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [VectorMapLayer](../)
* namespace [Aspose.Gis.Rendering](../../vectormaplayer/)
* assembly [Aspose.GIS](../../../)

---

## VectorMapLayer(FeaturesSequence, VectorSymbolizer, Labeling, SpatialReferenceSystem) {#constructor_2}

ينشئ نسخة جديدة مع المُرمّز الافتراضي.

```csharp
public VectorMapLayer(FeaturesSequence featuresSequence, VectorSymbolizer symbolizer, 
    Labeling labeling, SpatialReferenceSystem defaultReferenceSystem = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| featuresSequence | FeaturesSequence | تسلسل الميزات. |
| symbolizer | VectorSymbolizer | المُرمّز المستخدم لعرض الطبقة. إذا كان `null`، سيُستخدم المُرمّز الافتراضي. |
| labeling | Labeling | التصنيف المستخدم لتسمية المميزات في الطبقة. إذا كان `null`، سيتم استخدام [`NullLabeling`](../../../aspose.gis.rendering.labelings/nulllabeling/) الافتراضي. |
| defaultReferenceSystem | SpatialReferenceSystem | يحدد قيمة لمرجع فضائي مصدر (layer\sequence) إذا كان مفقودًا. سيتم استخدام **null** الافتراضي. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |

### انظر أيضًا

* class [FeaturesSequence](../../../aspose.gis/featuressequence/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [Labeling](../../../aspose.gis.rendering.labelings/labeling/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [VectorMapLayer](../)
* namespace [Aspose.Gis.Rendering](../../vectormaplayer/)
* assembly [Aspose.GIS](../../../)

---

## VectorMapLayer(VectorLayer, bool) {#constructor_6}

ينشئ نسخة جديدة مع المُرمّز الافتراضي.

```csharp
public VectorMapLayer(VectorLayer layer, bool keepOpen = true)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الطبقة | VectorLayer | طبقة متجهية. |
| keepOpen | Boolean | `true` لترك الطبقة مفتوحة بعد التخلص من كائن [`VectorMapLayer`](../)؛ وإلا، `false`. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الطبقة هي `null`. |

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [VectorMapLayer](../)
* namespace [Aspose.Gis.Rendering](../../vectormaplayer/)
* assembly [Aspose.GIS](../../../)

---

## VectorMapLayer(VectorLayer, VectorSymbolizer, bool) {#constructor_5}

ينشئ نسخة جديدة.

```csharp
public VectorMapLayer(VectorLayer layer, VectorSymbolizer symbolizer, bool keepOpen = true)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الطبقة | VectorLayer | طبقة متجهية. |
| symbolizer | VectorSymbolizer | المُرمّز المستخدم لعرض الطبقة. إذا كان `null`، سيُستخدم المُرمّز الافتراضي. |
| keepOpen | Boolean | `true` لترك الطبقة مفتوحة بعد التخلص من كائن [`VectorMapLayer`](../)؛ وإلا، `false`. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الطبقة هي `null`. |

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [VectorMapLayer](../)
* namespace [Aspose.Gis.Rendering](../../vectormaplayer/)
* assembly [Aspose.GIS](../../../)

---

## VectorMapLayer(VectorLayer, VectorSymbolizer, Labeling, bool) {#constructor_4}

ينشئ نسخة جديدة.

```csharp
public VectorMapLayer(VectorLayer layer, VectorSymbolizer symbolizer, Labeling labeling, 
    bool keepOpen = true)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الطبقة | VectorLayer | طبقة متجهية. |
| symbolizer | VectorSymbolizer | المُرمّز المستخدم لعرض الطبقة. إذا كان `null`، سيُستخدم المُرمّز الافتراضي. |
| labeling | Labeling | التصنيف المستخدم لتسمية المميزات في الطبقة. إذا كان `null`، سيتم استخدام [`NullLabeling`](../../../aspose.gis.rendering.labelings/nulllabeling/) الافتراضي. |
| keepOpen | Boolean | `true` لترك الطبقة مفتوحة بعد التخلص من كائن [`VectorMapLayer`](../)؛ وإلا، `false`. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الطبقة هي `null`. |

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [Labeling](../../../aspose.gis.rendering.labelings/labeling/)
* class [VectorMapLayer](../)
* namespace [Aspose.Gis.Rendering](../../vectormaplayer/)
* assembly [Aspose.GIS](../../../)

---

## VectorMapLayer(VectorLayer, VectorSymbolizer, Labeling, SpatialReferenceSystem, bool) {#constructor_3}

ينشئ نسخة جديدة.

```csharp
public VectorMapLayer(VectorLayer layer, VectorSymbolizer symbolizer, Labeling labeling, 
    SpatialReferenceSystem defaultReferenceSystem, bool keepOpen = true)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الطبقة | VectorLayer | طبقة متجهية. |
| symbolizer | VectorSymbolizer | المُرمّز المستخدم لعرض الطبقة. إذا كان `null`، سيُستخدم المُرمّز الافتراضي. |
| labeling | Labeling | التصنيف المستخدم لتسمية المميزات في الطبقة. إذا كان `null`، سيتم استخدام [`NullLabeling`](../../../aspose.gis.rendering.labelings/nulllabeling/) الافتراضي. |
| defaultReferenceSystem | SpatialReferenceSystem | يحدد قيمة لمرجع فضائي مصدر (layer\sequence) إذا كان مفقودًا. سيتم استخدام **null** الافتراضي. |
| keepOpen | Boolean | `true` لترك الطبقة مفتوحة بعد التخلص من كائن [`VectorMapLayer`](../)؛ وإلا، `false`. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الطبقة هي `null`. |

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [Labeling](../../../aspose.gis.rendering.labelings/labeling/)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [VectorMapLayer](../)
* namespace [Aspose.Gis.Rendering](../../vectormaplayer/)
* assembly [Aspose.GIS](../../../)


