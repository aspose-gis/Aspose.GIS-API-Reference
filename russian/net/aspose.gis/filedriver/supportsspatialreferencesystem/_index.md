---
title: SupportsSpatialReferenceSystem
second_title: Справочник по Aspose.GIS for .NET API
description: Определяет поддерживается ли драйвером указанная система пространственной привязки.
type: docs
weight: 100
url: /ru/net/aspose.gis/filedriver/supportsspatialreferencesystem/
---
## FileDriver.SupportsSpatialReferenceSystem method

Определяет, поддерживается ли драйвером указанная система пространственной привязки.

```csharp
public abstract bool SupportsSpatialReferenceSystem(SpatialReferenceSystem spatialReferenceSystem)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| spatialReferenceSystem | SpatialReferenceSystem | Пространственная система отсчета. |

### Возвращаемое значение

Логическое значение, указывающее, поддерживается ли драйвером указанная система пространственной привязки. `null`считается поддерживаемым любым драйвером.

### Примечания

Если система пространственной привязки не поддерживается, и вы передаете ее[`CreateLayer`](../createlayer)метод, aNotSupportedExceptionбудет брошен.

### Смотрите также

* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem)
* class [FileDriver](../../filedriver)
* пространство имен [Aspose.Gis](../../filedriver)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
