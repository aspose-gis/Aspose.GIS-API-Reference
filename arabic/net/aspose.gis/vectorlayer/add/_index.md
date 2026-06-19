---
title: "VectorLayer.Add"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة VectorLayer. يضيف عنصرًا جديدًا إلى الطبقة إذا كان VectorLayers Driver يدعم ذلك."
type: docs
weight: 80
url: /ar/net/aspose.gis/vectorlayer/add/
---
## Add(Feature) {#add}

يضيف عنصرًا جديدًا إلى الطبقة، إذا كان [`VectorLayer`](../) الخاص بـ[`Driver`](../driver/) يدعم ذلك.

```csharp
public virtual void Add(Feature feature)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| عنصر | Feature | العنصر المراد إضافته. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | يتم إلقاؤه إذا كانت الطبقة للقراءة فقط. |

### انظر أيضًا

* class [Feature](../../feature/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)

---

## Add(Feature, IFeatureStyle) {#add_1}

يضيف عنصرًا جديدًا مع النمط المحدد إلى الطبقة، إذا كان [`VectorLayer`](../) الخاص بـ[`Driver`](../driver/) يدعم ذلك.

```csharp
public virtual void Add(Feature feature, IFeatureStyle style)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| عنصر | Feature | العنصر المراد إضافته. |
| نمط | IFeatureStyle | نمط العنصر. استخدم `null` للإشارة إلى عدم وجود نمط. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | يتم إلقاؤه إذا كانت الطبقة لا تدعم الأنماط أو كانت الطبقة للقراءة فقط. |
| InvalidOperationException | يتم إلقاؤه إذا كانت الطبقات القابلة للتحرير لا تدعم الأنماط. |
| ArgumentException | يتم إلقاؤه إذا كان النمط لا يتطابق مع نوع السائق. |

### انظر أيضًا

* class [Feature](../../feature/)
* interface [IFeatureStyle](../../ifeaturestyle/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)


