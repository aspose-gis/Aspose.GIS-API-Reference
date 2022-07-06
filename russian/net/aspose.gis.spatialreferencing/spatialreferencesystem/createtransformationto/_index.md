---
title: CreateTransformationTo
second_title: Справочник по Aspose.GIS for .NET API
description: Создает преобразование из этой SpatialReferenceSystem в другую SpatialReferenceSystem .
type: docs
weight: 180
url: /ru/net/aspose.gis.spatialreferencing/spatialreferencesystem/createtransformationto/
---
## SpatialReferenceSystem.CreateTransformationTo method

Создает преобразование из этой` SpatialReferenceSystem` в другую` SpatialReferenceSystem` .

```csharp
public SpatialReferenceSystemTransformation CreateTransformationTo(SpatialReferenceSystem targetSrs)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| targetSrs | SpatialReferenceSystem | Другое` SpatialReferenceSystem` . |

### Возвращаемое значение

Преобразование из этой` SpatialReferenceSystem` в другую` SpatialReferenceSystem` .

### Исключения

| исключение | условие |
| --- | --- |
| NotSupportedException | Преобразование между этим` SpatialReferenceSystem` и аргумент не поддерживается. Это может произойти, потому что одна из проекций не поддерживается, или одна из систем[`VerticalSpatialReferenceSystem`](../../verticalspatialreferencesystem)или [`LocalSpatialReferenceSystem`](../../localspatialreferencesystem). |
| [TransformationException](../../transformationexception) | Не удалось создать преобразование из-за неверных параметров внутри` SpatialReferenceSystem` . |

### Смотрите также

* method [TryCreateTransformationTo](../trycreatetransformationto)
* class [SpatialReferenceSystemTransformation](../../spatialreferencesystemtransformation)
* class [SpatialReferenceSystem](../../spatialreferencesystem)
* пространство имен [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->