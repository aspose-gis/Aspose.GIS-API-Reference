---
title: "TopoJsonOptions.DefaultObjectName"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "خاصية TopoJsonOptions. اسم الكائن الذي تُوضع فيه الميزات بشكل افتراضي."
type: docs
weight: 20
url: /ar/net/aspose.gis.formats.topojson/topojsonoptions/defaultobjectname/
---
## TopoJsonOptions.DefaultObjectName property

اسم الكائن حيث تُوضع الميزات افتراضيًا.

```csharp
public string DefaultObjectName { get; set; }
```

## ملاحظات

هذا خيار كتابة - لا يؤثر على القراءة. يمكن أن يحتوي TopoJSON على أي عدد من الكائنات المسماة. كل كائن من هذا النوع يمكنه احتواء عدة ميزات. لتحديد الكائن الذي تُوضع فيه ميزتك، استخدم خاصية [`ObjectNameAttribute`](../objectnameattribute/). إذا كانت السمة ذات الاسم [`ObjectNameAttribute`](../objectnameattribute/) `null` أو غير محددة لبعض الميزة، تُضاف هذه الميزة إلى الكائن الذي اسمه `DefaultObjectName`. إذا لم تكن السمة ذات الاسم [`ObjectNameAttribute`](../objectnameattribute/) موجودة في مجموعة [`Attributes`](../../../aspose.gis/vectorlayer/attributes/)، تُوضع جميع الميزات في كائن يحمل الاسم [`ObjectNameAttribute`](../objectnameattribute/). القيمة الافتراضية هي "unnamed".

### انظر أيضًا

* class [TopoJsonOptions](../)
* namespace [Aspose.Gis.Formats.TopoJson](../../topojsonoptions/)
* assembly [Aspose.GIS](../../../)


