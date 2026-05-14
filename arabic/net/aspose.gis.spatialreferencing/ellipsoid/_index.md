---
title: "الفئة Ellipsoid"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.SpatialReferencing.Ellipsoid. الـ Ellipsoid يمثل شكلًا بيضاويًا يقترب من شكل الأرض"
type: docs
weight: 4520
url: /ar/net/aspose.gis.spatialreferencing/ellipsoid/
---
## Ellipsoid class

الإهليلج يمثل إهليلجًا يقترب من شكل الأرض.

```csharp
public class Ellipsoid : IdentifiableObject
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Ellipsoid](ellipsoid/)(string, double, double, Identifier) | ينشئ Ellipsoid جديد. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Airy](../../aspose.gis.spatialreferencing/ellipsoid/airy/) { get; } | Ellipsoid Airy. |
| static [Grs80](../../aspose.gis.spatialreferencing/ellipsoid/grs80/) { get; } | Ellipsoid GRS 1980. |
| static [Wgs72](../../aspose.gis.spatialreferencing/ellipsoid/wgs72/) { get; } | Ellipsoid WGS 72. |
| static [Wgs84](../../aspose.gis.spatialreferencing/ellipsoid/wgs84/) { get; } | Ellipsoid WGS 84. |
| [EpsgCode](../../aspose.gis.spatialreferencing/identifiableobject/epsgcode/) { get; } | إذا كان معرف هذا الكائن هو معرف EPSG - أعد رمزه. وإلا - أعد -1. |
| [Identifier](../../aspose.gis.spatialreferencing/identifiableobject/identifier/) { get; } | معرف هذا الكائن القابل للتعريف. |
| [InverseFlattening](../../aspose.gis.spatialreferencing/ellipsoid/inverseflattening/) { get; } | القيمة العكسية للتسطح للـ ellipsoid. 0 إذا كان هذا كرة. |
| [IsSphere](../../aspose.gis.spatialreferencing/ellipsoid/issphere/) { get; } | يكشف ما إذا كان هذا ellipsoid كرة. |
| [IsValid](../../aspose.gis.spatialreferencing/ellipsoid/isvalid/) { get; } | يكشف ما إذا كان الشكل البيضاوي صالحًا: نصف المحور الرئيسي له أكبر من 0 وتسطح العكسي إيجابي أو يساوي 0. |
| [Name](../../aspose.gis.spatialreferencing/identifiableobject/name/) { get; } | اسم هذا الكائن. |
| [SemiMajorAxis](../../aspose.gis.spatialreferencing/ellipsoid/semimajoraxis/) { get; } | نصف المحور الرئيسي للشكل البيضاوي. |
| [SemiMinorAxis](../../aspose.gis.spatialreferencing/ellipsoid/semiminoraxis/) { get; } | نصف المحور الصغير للشكل البيضاوي. يساوي نصف المحور الرئيسي إذا كان هذا كرة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [IsEquivalent](../../aspose.gis.spatialreferencing/ellipsoid/isequivalent/)(Ellipsoid) | يحدد ما إذا كان الشكلان البيضاويان متكافئين. إذا كان الشكل البيضاوي A متكافئًا مع الشكل البيضاوي B، فإنهما يمتلكان نفس نصف المحور الرئيسي وتسطح العكسي. |
| override [ToString](../../aspose.gis.spatialreferencing/identifiableobject/tostring/)() | يعيد سلسلة تمثل الكائن الحالي. |
| static [IsEquivalent](../../aspose.gis.spatialreferencing/ellipsoid/isequivalent/)(Ellipsoid, Ellipsoid) | يحدد ما إذا كان الشكلان البيضاويان متكافئين. إذا كان الشكل البيضاوي A متكافئًا مع الشكل البيضاوي B، فإنهما يمتلكان نفس نصف المحور الرئيسي وتسطح العكسي. |

### انظر أيضًا

* class [IdentifiableObject](../identifiableobject/)
* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


