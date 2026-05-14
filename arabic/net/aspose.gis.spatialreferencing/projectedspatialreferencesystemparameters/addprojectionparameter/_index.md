---
title: "ProjectedSpatialReferenceSystemParameters.AddProjectionParameter"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة ProjectedSpatialReferenceSystemParameters. تُضيف معلمة إسقاط إلى هذا النظام. إذا كانت معلمة بنفس الاسم مضافة مسبقًا، يتم تحديثها."
type: docs
weight: 100
url: /ar/net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/addprojectionparameter/
---
## ProjectedSpatialReferenceSystemParameters.AddProjectionParameter method

يضيف معامل الإسقاط إلى نظام الإسناد المكاني هذا. إذا كان معامل بنفس الاسم مضافًا بالفعل - يتم تحديثه.

```csharp
public void AddProjectionParameter(string parameterName, double value)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| parameterName | String | اسم معلمة الإسقاط. |
| value | Double | قيمة المعلمة. يجب أن تكون وحدة القيمة في [`LinearUnit`](../linearunit/) أو [`AngularUnit`](../../geographicspatialreferencesystem/angularunit/) الخاصة بـ [`Base`](../base/). |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *parameterName* فارغ. |

### انظر أيضًا

* class [ProjectedSpatialReferenceSystemParameters](../)
* namespace [Aspose.Gis.SpatialReferencing](../../projectedspatialreferencesystemparameters/)
* assembly [Aspose.GIS](../../../)


