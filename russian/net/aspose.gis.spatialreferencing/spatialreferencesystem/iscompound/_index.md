---
title: IsCompound
second_title: Справочник по Aspose.GIS for .NET API
description: Возвращает является ли эта SRS составной объединение двух SRS. Следующие комбинации СГД в составной ССО считаются допустимыми Географическая ССО  Вертикальная ССО в этом случае тип составной ССО будетGeographic. Проецируемая SRS  Вертикальная SRS в этом случае тип составной SRS будетProjected. Если комбинация SRS различается тип составной SRS будетUnknown.
type: docs
weight: 130
url: /ru/net/aspose.gis.spatialreferencing/spatialreferencesystem/iscompound/
---
## SpatialReferenceSystem.IsCompound property

Возвращает, является ли эта SRS составной (объединение двух SRS). Следующие комбинации СГД в составной ССО считаются допустимыми: Географическая ССО + Вертикальная ССО, в этом случае тип составной ССО будетGeographic. Проецируемая SRS + Вертикальная SRS, в этом случае тип составной SRS будетProjected. Если комбинация SRS различается, тип составной SRS будетUnknown.

```csharp
public virtual bool IsCompound { get; }
```

### Примечания

В WKT это COMPD_CS.

### Смотрите также

* class [SpatialReferenceSystem](../../spatialreferencesystem)
* пространство имен [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
