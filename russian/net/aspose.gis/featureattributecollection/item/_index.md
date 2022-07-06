---
title: Item
second_title: Справочник по Aspose.GIS for .NET API
description: Получает или задаетFeatureAttributeaspose.gis/featureattributeпо указанному индексу.
type: docs
weight: 30
url: /ru/net/aspose.gis/featureattributecollection/item/
---
## FeatureAttributeCollection indexer (1 of 2)

Получает или задает[`FeatureAttribute`](../../featureattribute)по указанному индексу.

```csharp
public FeatureAttribute this[int index] { get; set; }
```

| Параметр | Описание |
| --- | --- |
| index | Отсчитываемый от нуля индекс атрибута, который необходимо получить или установить. |

### Возвращаемое значение

Атрибут по указанному индексу.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Индекс вне допустимого диапазона. |
| InvalidOperationException | Попытка изменить заблокированную коллекцию. |

### Смотрите также

* class [FeatureAttribute](../../featureattribute)
* class [FeatureAttributeCollection](../../featureattributecollection)
* пространство имен [Aspose.Gis](../../featureattributecollection)
* сборка [Aspose.GIS](../../../)

---

## FeatureAttributeCollection indexer (2 of 2)

Получает или задает[`FeatureAttribute`](../../featureattribute)с указанным именем.

```csharp
public FeatureAttribute this[string name] { get; }
```

| Параметр | Описание |
| --- | --- |
| name | Имя атрибута. |

### Возвращаемое значение

Атрибут с указанным именем или`null`если не найден.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Имя атрибута:`null`. |

### Смотрите также

* class [FeatureAttribute](../../featureattribute)
* class [FeatureAttributeCollection](../../featureattributecollection)
* пространство имен [Aspose.Gis](../../featureattributecollection)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->