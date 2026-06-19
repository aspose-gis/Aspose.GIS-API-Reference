---
title: "الفئة GeographicDatum"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.SpatialReferencing.GeographicDatum. المرجع الجغرافي يربط خط الطول وخط العرض بمكان معين على الأرض."
type: docs
weight: 4570
url: /ar/net/aspose.gis.spatialreferencing/geographicdatum/
---
## GeographicDatum class

المرجع الجغرافي يربط خط الطول وخط العرض بمكان معين على الأرض.

```csharp
public class GeographicDatum : IdentifiableObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [GeographicDatum](geographicdatum/)(string, Ellipsoid, BursaWolfParameters, Identifier) | ينشئ نسخة جديدة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Etrs89](../../aspose.gis.spatialreferencing/geographicdatum/etrs89/) { get; } | المرجع ETRS 89. |
| static [Nad83](../../aspose.gis.spatialreferencing/geographicdatum/nad83/) { get; } | المرجع NAD 83. |
| static [Osgb36](../../aspose.gis.spatialreferencing/geographicdatum/osgb36/) { get; } | المرجع OSGB 1936. |
| static [Wgs72](../../aspose.gis.spatialreferencing/geographicdatum/wgs72/) { get; } | المرجع WGS 72. |
| static [Wgs84](../../aspose.gis.spatialreferencing/geographicdatum/wgs84/) { get; } | المرجع WGS 84. |
| [Ellipsoid](../../aspose.gis.spatialreferencing/geographicdatum/ellipsoid/) { get; } | الشكل البيضاوي، المستخدم في هذا المرجع لتقريب شكل الأرض. |
| [EpsgCode](../../aspose.gis.spatialreferencing/identifiableobject/epsgcode/) { get; } | إذا كان معرف هذا الكائن هو معرف EPSG - أعد رمزه. وإلا - أعد -1. |
| [Identifier](../../aspose.gis.spatialreferencing/identifiableobject/identifier/) { get; } | معرف هذا الكائن القابل للتعريف. |
| [Name](../../aspose.gis.spatialreferencing/identifiableobject/name/) { get; } | اسم هذا الكائن. |
| [ToWgs84Parameters](../../aspose.gis.spatialreferencing/geographicdatum/towgs84parameters/) { get; } | معلمات BursaWolfParamters التي يمكن استخدامها لتحويل الإحداثيات في هذا المرجع إلى إحداثيات في مرجع WGS84. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [IsEquivalent](../../aspose.gis.spatialreferencing/geographicdatum/isequivalent/)(GeographicDatum) | يحدد ما إذا كان المرجعان متكافئين. نفس الإحداثيات للمرجعين المتكافئين تشير إلى نفس المكان على الأرض. بعض معلمات المرجع المتكافئ يمكن أن تكون مختلفة، على سبيل المثال [`Name`](../identifiableobject/name/). |
| override [ToString](../../aspose.gis.spatialreferencing/identifiableobject/tostring/)() | يرجع سلسلة تمثل الكائن الحالي. |
| static [IsEquivalent](../../aspose.gis.spatialreferencing/geographicdatum/isequivalent/)(GeographicDatum, GeographicDatum) | يحدد ما إذا كان المرجعان متكافئين. نفس الإحداثيات للمرجعين المتكافئين تشير إلى نفس المكان على الأرض. بعض معلمات المرجع المتكافئ يمكن أن تكون مختلفة، على سبيل المثال [`Name`](../identifiableobject/name/). |

### انظر أيضًا

* class [IdentifiableObject](../identifiableobject/)
* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


