---
title: "AbstractPath.GetFileName"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة AbstractPath. تُرجع اسم الملف وامتداده لهذا AbstractPath"
type: docs
weight: 80
url: /ar/net/aspose.gis/abstractpath/getfilename/
---
## AbstractPath.GetFileName method

تُرجع اسم الملف وامتداده لهذا [`AbstractPath`](../).

```csharp
public string GetFileName()
```

### قيمة الإرجاع

الأحرف التي تلي آخر حرف [`Separator`](../separator/) في الـ[`Location`](../location/). إذا كان الحرف الأخير هو حرف [`Separator`](../separator/)، يتم إرجاع سلسلة فارغة. إذا لم يكن هناك أحرف [`Separator`](../separator/) في الـ[`Location`](../location/)، يتم إرجاع الـ[`Location`](../location/) نفسه.

## أمثلة

بالنسبة إلى `AbstractPath` مع [`Location`](../location/) يساوي `"/directory/file.txt"` و[`Separator`](../separator/) يساوي `'/'`، تُرجع هذه الطريقة `"file.txt"`.

### انظر أيضًا

* class [AbstractPath](../)
* namespace [Aspose.Gis](../../abstractpath/)
* assembly [Aspose.GIS](../../../)


