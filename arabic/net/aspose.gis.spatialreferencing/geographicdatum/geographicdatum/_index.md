---
title: "GeographicDatum.GeographicDatum"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "منشئ GeographicDatum. ينشئ مثالًا جديدًا"
type: docs
weight: 10
url: /ar/net/aspose.gis.spatialreferencing/geographicdatum/geographicdatum/
---
## GeographicDatum constructor

ينشئ مثيلًا جديدًا.

```csharp
public GeographicDatum(string name, Ellipsoid ellipsoid, 
    BursaWolfParameters toWgs84Parameters = null, Identifier identifier = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | String | اسم هذا المرجع. |
| ellipsoid | Ellipsoid | البيضاوي لهذا المرجع. لا يمكن أن يكون فارغًا. |
| toWgs84Parameters | BursaWolfParameters | المعلمات التي يمكن إعطاؤها لصيغة bursa wolf لتحويل الإحداثيات في هذا المرجع إلى إحداثيات في مرجع WGS84. إذا كان هذا المرجع قريبًا من WGS84 ولا يلزم تحويل، مرّر معلمات bursa wolf مع ضبط جميع القيم إلى 0. إذا كان فارغًا، سيتم ضبط ToWgs84 إلى معلمات [`IsNull`](../../bursawolfparameters/isnull/). |
| معرّف | معرّف | معرف هذا المرجع. |

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


