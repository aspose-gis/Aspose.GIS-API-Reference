---
title: "AbstractPath.Combine"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة AbstractPath. تجمع هذا الـ AbstractPath مع مكوّنات المسار المحددة"
type: docs
weight: 50
url: /ar/net/aspose.gis/abstractpath/combine/
---
## AbstractPath.Combine method

تجمع هذا [`AbstractPath`](../) مع مكوّنات المسار المحددة.

```csharp
public virtual AbstractPath Combine(string location)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| location | String | مكوّن مسار لإضافته إلى هذا [`AbstractPath`](../). |

### قيمة الإرجاع

جديد [`AbstractPath`](../) يشير إلى [`Location`](../location/) التي هي مزيج من مواقع هذا [`AbstractPath`](../) والوسيط.

## ملاحظات

عادةً لا ينبغي أن يتم تجاوز هذه الطريقة من قبل المُورّث. التنفيذ الافتراضي يدمج هذا [`Location`](../location/) مع الوسيط ويستدعي طريقة [`WithLocation`](../withlocation/) مع السلسلة المدمجة كوسيط. يتم تعريف نتيجة الجمع على النحو التالي: إذا كان الوسيط يبدأ بـ [`Separator`](../separator/)، تكون نتيجة الجمع مساوية للوسيط؛ وإلا إذا كان [`Location`](../location/) ينتهي بـ [`Separator`](../separator/)، تكون نتيجة الجمع مساوية إلى ` + `؛ وإلا تكون النتيجة مساوية إلى ` + + `

### انظر أيضًا

* class [AbstractPath](../)
* namespace [Aspose.Gis](../../abstractpath/)
* assembly [Aspose.GIS](../../../)


