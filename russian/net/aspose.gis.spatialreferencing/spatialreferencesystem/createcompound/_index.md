---
title: CreateCompound
second_title: Справочник по Aspose.GIS for .NET API
description: Создать составной SRS.
type: docs
weight: 340
url: /ru/net/aspose.gis.spatialreferencing/spatialreferencesystem/createcompound/
---
## SpatialReferenceSystem.CreateCompound method

Создать составной SRS.

```csharp
public static CompoundSpatialReferenceSystem CreateCompound(string name, 
    SpatialReferenceSystem head, SpatialReferenceSystem tail, Identifier identifier = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| name | String | Имя нового SRS. |
| head | SpatialReferenceSystem | Головка SRS новой SRS. |
| tail | SpatialReferenceSystem | Хвост SRS нового SRS. |
| identifier | Identifier | Идентификатор, который будет прикреплен к SRS. Присоединение идентификатора не изменит другие параметры SRS. Вы должны обеспечить согласованность идентификатора и параметров SRS. |

### Возвращаемое значение

Новая составная SRS.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Любой аргумент, кроме*identifier*is`null`. |
| InvalidOperationException | *head*или*tail*сами являются составными SRS. |

### Смотрите также

* class [CompoundSpatialReferenceSystem](../../compoundspatialreferencesystem)
* class [Identifier](../../identifier)
* class [SpatialReferenceSystem](../../spatialreferencesystem)
* пространство имен [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
