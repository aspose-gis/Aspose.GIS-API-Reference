---
title: "الفئة Projection"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.SpatialReferencing.Projection. تمثل طريقة إسقاط مع معلمات تحول خط الطول والعرض إلى x y"
type: docs
weight: 4690
url: /ar/net/aspose.gis.spatialreferencing/projection/
---
## Projection class

يمثل طريقة إسقاط مع معلمات، تحول (خط الطول، خط العرض) إلى (س، ص).

```csharp
public class Projection : IdentifiableObject
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AngularParametersUnit](../../aspose.gis.spatialreferencing/projection/angularparametersunit/) { get; } | الوحدة المستخدمة للمعلمات الزاوية. |
| [EpsgCode](../../aspose.gis.spatialreferencing/identifiableobject/epsgcode/) { get; } | إذا كان معرف هذا الكائن هو معرف EPSG - أعد رمزه. وإلا - أعد -1. |
| [Identifier](../../aspose.gis.spatialreferencing/identifiableobject/identifier/) { get; } | معرف هذا الكائن القابل للتعريف. |
| [LinearParametersUnit](../../aspose.gis.spatialreferencing/projection/linearparametersunit/) { get; } | الوحدة المستخدمة للمعلمات الخطية. |
| [Name](../../aspose.gis.spatialreferencing/identifiableobject/name/) { get; } | اسم هذا الكائن. |
| [ParametersNames](../../aspose.gis.spatialreferencing/projection/parametersnames/) { get; } | يحصل على مجموعة قابلة للتعداد من أسماء المعلمات المخصصة لهذا الإسقاط |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [GetParameterValue](../../aspose.gis.spatialreferencing/projection/getparametervalue/)(string, ParameterType) | يحصل على المعلمة ذات الاسم المحدد لهذا الإسقاط. |
| [IsEquivalent](../../aspose.gis.spatialreferencing/projection/isequivalent/)(Projection) | يحدد ما إذا كان الإسقاطان متكافئين. الإسقاطات المتكافئة تحول (خط الطول، خط العرض) إلى (x, y) بنفس الطريقة. |
| override [ToString](../../aspose.gis.spatialreferencing/identifiableobject/tostring/)() | يعيد سلسلة تمثل الكائن الحالي. |
| [TryGetParameterValue](../../aspose.gis.spatialreferencing/projection/trygetparametervalue/)(string, ParameterType) | يحصل على المعلمة ذات الاسم المحدد لهذا الإسقاط. إذا لم توجد مثل هذه المعلمة - يعيد `null`. |

### انظر أيضًا

* class [IdentifiableObject](../identifiableobject/)
* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


