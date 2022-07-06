---
title: NumericFormat
second_title: Справочник по Aspose.GIS for .NET API
description: NumericFormat./numericformatиспользуются для форматирования общих числовых типов в тексте.
type: docs
weight: 1180
url: /ru/net/aspose.gis/numericformat/
---
## NumericFormat class

[`NumericFormat`](../numericformat)используются для форматирования общих числовых типов в тексте.

```csharp
public abstract class NumericFormat
```

## Характеристики

| Имя | Описание |
| --- | --- |
| static [RoundTrip](../../aspose.gis/numericformat/roundtrip) { get; } | Преобразует и пытается гарантировать, что числовое значение, преобразованное в строку , анализируется обратно в то же самое числовое значение. |

## Методы

| Имя | Описание |
| --- | --- |
| static [Flat](../../aspose.gis/numericformat/flat)(int) | Преобразует число в текст с фиксированной точкой без научного представления. |
| static [General](../../aspose.gis/numericformat/general)(int) | Преобразует число в более компактную запись с фиксированной точкой или экспоненциальную запись, в зависимости от типа числа и наличия спецификатора точности настоящее. Рекомендуется использовать. |

### Примечания

Существует три типа[`NumericFormat`](../numericformat): &lt;ul&gt;&lt;li&gt;Общие - фиксированная точка или научная запись. Некоторое количество цифр является значимым. &lt;/li&gt;&lt;li&gt;Обход туда и обратно — запись с фиксированной точкой или экспоненциальная запись. Максимальное число цифр является значимым. &lt;/li&gt;&lt;li&gt;Плоская — запись с фиксированной точкой. Некоторое количество цифр является значимым. &lt;/li&gt;&lt;/ul&gt; A[`NumericFormat`](../numericformat)можно установить в[`IGeometry`](../../aspose.gis.geometries/igeometry)via[`AsText`](../../aspose.gis.geometries/igeometry/astext) для указания числового формата при преобразовании геометрии в ее представление в виде общеизвестного текста (WKT).

### Смотрите также

* пространство имен [Aspose.Gis](../../aspose.gis)
* сборка [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->