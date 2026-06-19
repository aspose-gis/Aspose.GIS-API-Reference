---
title: "SpatialReferenceSystem.IsCompound"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "خاصية SpatialReferenceSystem. تُعيد ما إذا كان هذا الـ SRS مركبًا وهو اتحاد لاثنين من الـ SRS. تُعتبر التركيبات التالية من الـ SRS في نظام إسناد مكاني مركب صالحة: نظام إسناد جغرافي + نظام إسناد عمودي؛ في هذه الحالة سيكون نوع نظام الإسناد المركب جغرافي. نظام إسناد إسقاطي + نظام إسناد عمودي؛ في هذه الحالة سيكون نوع نظام الإسناد المركب إسقاطي. إذا اختلفت تركيبة الـ SRS فإن نوع نظام الإسناد المركب سيكون غير معروف."
type: docs
weight: 130
url: /ar/net/aspose.gis.spatialreferencing/spatialreferencesystem/iscompound/
---
## SpatialReferenceSystem.IsCompound property

يعيد ما إذا كان هذا SRS مركبًا (اتحاد بين SRSين). تُعتبر التركيبات التالية من SRS في SRS المركب صالحة: Geographic SRS + Vertical SRS، في هذه الحالة سيكون نوع SRS المركب جغرافيًا. Projected SRS + Vertical SRS، في هذه الحالة سيكون نوع SRS المركب إسقاطيًا. إذا اختلفت تركيبة الـ SRSs، سيكون نوع SRS المركب غير معروف.

```csharp
public virtual bool IsCompound { get; }
```

## ملاحظات

في WKT هذا هو COMPD_CS.

### انظر أيضًا

* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


