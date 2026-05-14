---
title: "SpatialReferenceSystem.IsCompound"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "خاصية SpatialReferenceSystem. تُعيد ما إذا كان هذا الـ SRS مركبًا وهو اتحاد لاثنين من الـ SRS. تُعتبر التركيبات التالية للـ SRS في الـ SRS المركب صالحة: Geographic SRS + Vertical SRS؛ في هذه الحالة سيكون نوع الـ SRS المركب Geographic. Projected SRS + Vertical SRS؛ في هذه الحالة سيكون نوع الـ SRS المركب Projected. إذا اختلفت تركيبة الـ SRSs فإن نوع الـ SRS المركب سيكون Unknown."
type: docs
weight: 130
url: /ar/net/aspose.gis.spatialreferencing/spatialreferencesystem/iscompound/
---
## SpatialReferenceSystem.IsCompound property

يعيد ما إذا كان هذا نظام الإسناد المكاني مركبًا (اتحاد نظامين إسناد مكاني). تُعتبر التركيبات التالية لنظام الإسناد المكاني في النظام المركب صالحة: نظام إسناد مكاني جغرافي + نظام إسناد مكاني عمودي، في هذه الحالة سيكون نوع النظام المركب جغرافيًا. نظام إسناد مكاني إسقاطي + نظام إسناد مكاني عمودي، في هذه الحالة سيكون نوع النظام المركب إسقاطيًا. إذا اختلفت تركيبة الأنظمة، سيكون نوع النظام المركب غير معروف.

```csharp
public virtual bool IsCompound { get; }
```

## ملاحظات

في WKT هذا هو COMPD_CS.

### انظر أيضًا

* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


