---
title: "MarkerCluster.FeaturesBasedConfiguration"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "خاصية MarkerCluster. رد نداء يُستخدم لتكوين هذا الرموز قبل عرض مركز التجمع"
type: docs
weight: 20
url: /ar/net/aspose.gis.rendering.symbolizers/markercluster/featuresbasedconfiguration/
---
## MarkerCluster.FeaturesBasedConfiguration property

استدعاء رد نداء يُستخدم لتكوين هذا المُرمّز قبل رسم مركز المجموعة.

```csharp
public Action<IEnumerable<Feature>, MarkerCluster> FeaturesBasedConfiguration { get; set; }
```

## ملاحظات

يتم استدعاء رد النداء هذا قبل عرض كل مركز تجميع. وهو يقبل ميزات على وشك العرض ونسخة مستنسخة من هذا symbolizer. من خلال تغيير خصائص النسخة المستنسخة، يمكن تحديث سلوك symbolizer بناءً على سمات الميزات.

### انظر أيضًا

* class [Feature](../../../aspose.gis/feature/)
* class [MarkerCluster](../)
* namespace [Aspose.Gis.Rendering.Symbolizers](../../markercluster/)
* assembly [Aspose.GIS](../../../)


