---
title: FeatureAttributeCollection.Item
second_title: Справочник по Aspose.GIS for .NET API
description: FeatureAttributeCollection свойство. Получает или задаетFeatureAttribute по указанному индексу.
type: docs
weight: 30
url: /ru/net/aspose.gis/featureattributecollection/item/
---
## FeatureAttributeCollection indexer (1 of 2)

Получает или задает[`FeatureAttribute`](../../featureattribute/) по указанному индексу.

```csharp
public FeatureAttribute this[int index] { get; set; }
```

| Параметр | Описание |
| --- | --- |
| index | Отсчитываемый от нуля индекс атрибута, который нужно получить или установить. |

### Возвращаемое значение

Атрибут по указанному индексу.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | Индекс вне допустимого диапазона. |
| InvalidOperationException | Попытка изменить заблокированную коллекцию. |

### Смотрите также

* class [FeatureAttribute](../../featureattribute/)
* class [FeatureAttributeCollection](../)
* пространство имен [Aspose.Gis](../../featureattributecollection/)
* сборка [Aspose.GIS](../../../)

---

## FeatureAttributeCollection indexer (2 of 2)

Получает или задает[`FeatureAttribute`](../../featureattribute/) с указанным именем.

```csharp
public FeatureAttribute this[string name] { get; }
```

| Параметр | Описание |
| --- | --- |
| name | Имя атрибутов. |

### Возвращаемое значение

Атрибут с указанным именем или`null` если он не найден.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Имя атрибута`null`. |

### Смотрите также

* class [FeatureAttribute](../../featureattribute/)
* class [FeatureAttributeCollection](../)
* пространство имен [Aspose.Gis](../../featureattributecollection/)
* сборка [Aspose.GIS](../../../)


