---
title: "Projection.TryGetParameterValue"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Projection. تحصل على المعامل بالاسم المحدد لهذا الإسقاط. إذا لم يكن هناك مثل هذا المعامل تُعيد null"
type: docs
weight: 60
url: /ar/net/aspose.gis.spatialreferencing/projection/trygetparametervalue/
---
## Projection.TryGetParameterValue method

يحصل على المعلمة بالاسم المحدد لهذا الإسقاط. إذا لم توجد مثل هذه المعلمة - يرجع `null`.

```csharp
public double? TryGetParameterValue(string name, ParameterType type = ParameterType.Other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | String | اسم المعلمة. |
| type | ParameterType | نوع المعامل. يحدد عامل الوحدة الذي سيُطبق: إذا كان النوع Linear فإن [`LinearParametersUnit`](../linearparametersunit/) سيُطبق وستكون النتيجة بالمتر. إذا كان النوع Angular فإن [`AngularParametersUnit`](../angularparametersunit/) سيُطبق وستكون النتيجة بالراديان. إذا كان النوع Other فستُعاد قيمة المعامل كما هي. |

### قيمة الإرجاع

معامل بالاسم المحدد أو `null` إذا لم يكن موجودًا.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المعطى فارغ. |

### انظر أيضًا

* enum [ParameterType](../../parametertype/)
* class [Projection](../)
* namespace [Aspose.Gis.SpatialReferencing](../../projection/)
* assembly [Aspose.GIS](../../../)


