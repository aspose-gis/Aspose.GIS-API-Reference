---
title: "GeographicDatum.GeographicDatum"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "منشئ GeographicDatum. ينشئ نسخة جديدة"
type: docs
weight: 10
url: /ar/net/aspose.gis.spatialreferencing/geographicdatum/geographicdatum/
---
## GeographicDatum constructor

ينشئ نسخة جديدة.

```csharp
public GeographicDatum(string name, Ellipsoid ellipsoid, 
    BursaWolfParameters toWgs84Parameters = null, Identifier identifier = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | String | اسم هذه النقطة المرجعية. |
| البيضاوي | Ellipsoid | البيضاوي لهذه النقطة المرجعية. لا يمكن أن يكون فارغًا. |
| toWgs84Parameters | BursaWolfParameters | معلمات يمكن إعطاؤها لصيغة bursa wolf لتحويل الإحداثيات في هذه النقطة المرجعية إلى إحداثيات في نقطة مرجعية WGS84. إذا كانت هذه النقطة المرجعية قريبة من WGS84 ولا يلزم تحويل، مرّر معلمات bursa wolf مع ضبط جميع القيم إلى 0. إذا كانت فارغة، سيتم ضبط ToWgs84 إلى معلمات [`IsNull`](../../bursawolfparameters/isnull/). |
| معرّف | معرّف | معرف هذه النقطة المرجعية. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | البيضاوي فارغ. |

### انظر أيضًا

* class [Ellipsoid](../../ellipsoid/)
* class [BursaWolfParameters](../../bursawolfparameters/)
* class [Identifier](../../identifier/)
* class [GeographicDatum](../)
* namespace [Aspose.Gis.SpatialReferencing](../../geographicdatum/)
* assembly [Aspose.GIS](../../../)


