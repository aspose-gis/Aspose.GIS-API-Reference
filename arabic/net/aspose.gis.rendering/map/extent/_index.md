---
title: Extent
second_title: Aspose.GIS لمرجع .NET API
description: يحدد حدود الخريطة للعرض . إذا تم التعيين علىnull  يتم حساب المدى أثناء العرض ليشمل كل الأشكال الهندسية في كل الطبقات.
type: docs
weight: 40
url: /ar/net/aspose.gis.rendering/map/extent/
---
## Map.Extent property

يحدد حدود الخريطة للعرض . إذا تم التعيين على`null` ، يتم حساب المدى أثناء العرض ليشمل كل الأشكال الهندسية في كل الطبقات.

```csharp
public Extent Extent { get; set; }
```

### استثناءات

| استثناء | حالة |
| --- | --- |
| ArgumentException | [`IsValid`](../../../aspose.gis/extent/isvalid) هو`false`.[`Width`](../../../aspose.gis/extent/width) أصغر أو يساوي الصفر.[`Height`](../../../aspose.gis/extent/height) أصغر أو يساوي الصفر.[`SpatialReferenceSystem`](../../../aspose.gis/extent/spatialreferencesystem) هو`null`. |

### ملاحظات

إذا كان نظام الإسناد المكاني للمدى لا يساوي نظام الإسناد المكاني للخريطة ، فسيتم تحويل المدى إلى نظام الإسناد المكاني المستهدف أثناء العرض.

### أنظر أيضا

* class [Extent](../../../aspose.gis/extent)
* class [Map](../../map)
* مساحة الاسم [Aspose.Gis.Rendering](../../map)
* المجسم [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->