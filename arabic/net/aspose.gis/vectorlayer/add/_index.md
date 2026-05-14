---
title: "VectorLayer.Add"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة VectorLayer. يضيف ميزة جديدة إلى الطبقة إذا كان مدعومًا من قبل VectorLayers Driver"
type: docs
weight: 80
url: /ar/net/aspose.gis/vectorlayer/add/
---
## Add(Feature) {#add}

يضيف ميزة جديدة إلى الطبقة، إذا كان مدعومًا من قبل [`VectorLayer`](../) الخاص بـ [`Driver`](../driver/).

```csharp
public virtual void Add(Feature feature)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| ميزة | Feature | الميزة التي سيتم إضافتها. |

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

يضيف ميزة جديدة مع النمط المحدد إلى الطبقة، إذا كان مدعومًا من قبل [`VectorLayer`](../) الخاص بـ [`Driver`](../driver/).

```csharp
public virtual void Add(Feature feature, IFeatureStyle style)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| ميزة | Feature | الميزة التي سيتم إضافتها. |
| نمط | IFeatureStyle | نمط الميزة. استخدم `null` للإشارة إلى عدم وجود نمط. |

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


