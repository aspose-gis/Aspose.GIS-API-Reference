---
title: ToLinearGeometry
second_title: Справочник по Aspose.GIS for .NET API
description: Получает приблизительную или эквивалентную некривую версию этой геометрии используя допуск по умолчанию .
type: docs
weight: 220
url: /ru/net/aspose.gis.geometries/geometrycollection/tolineargeometry/
---
## ToLinearGeometry() {#tolineargeometry_2}

Получает приблизительную или эквивалентную некривую версию этой геометрии, используя допуск по умолчанию .

```csharp
public IGeometryCollection ToLinearGeometry()
```

### Возвращаемое значение

Геометрия, не имеющая кривых геометрий. Это эквивалент[`ToLinearGeometry`](../../igeometrycollection/tolineargeometry)с по умолчанию` допуска` . Значение по умолчанию` допуска` s зависит от[`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem) этой геометрии: &lt;ul&gt;&lt;li&gt; Для проектируемого SRS Допуск составляет 0,001 метра (в единицах SRS) &lt;/li&gt;&lt;li&gt; Для географического SRS Допуск составляет` 1e-5` градусов (в единицах SRS) &lt;/li&gt;&lt;li&gt; Для неизвестного SRS Допуск составляет` 1e-5` &lt;/li&gt;&lt;/ ul&gt; Подробнее о применяемых преобразованиях см. в спецификации[`ToLinearGeometry`](../../igeometrycollection/tolineargeometry).

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | Эта геометрия недействительна таким образом, что операция не может быть завершенный. |

### Смотрите также

* interface [IGeometryCollection](../../igeometrycollection)
* class [GeometryCollection](../../geometrycollection)
* пространство имен [Aspose.Gis.Geometries](../../geometrycollection)
* сборка [Aspose.GIS](../../../)

---

## ToLinearGeometry(double) {#tolineargeometry_3}

Получает приблизительную или эквивалентную некривую версию этой геометрии с использованием указанного допуска .

```csharp
public IGeometryCollection ToLinearGeometry(double tolerance)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| допуск | Double | Допуск использовать. Результат гарантированно будет меньше` допуска` вдали от криволинейной геометрии. |

### Возвращаемое значение

Геометрия, не имеющая кривых геометрий. Применяются следующие преобразования: &lt;ul&gt;&lt;li&gt;CircularStringлинеаризуются (преобразуются вLineStrings с указанным*tolerance*) &lt;/li&gt;&lt;li&gt;CompoundCurves объединяются в` LineString` s &lt;/li&gt;&lt;li&gt;CurvePolygons преобразуются вPolygons &lt;/li&gt;&lt;li&gt;MultiCurves преобразуются вMultiCurves &lt;/li&gt;&lt;li&gt;MultiSurfaces преобразуются вMultiPolygons &lt;/li&gt;&lt;/ul&gt; В результате[`HasCurveGeometry`](../../igeometry/hascurvegeometry)выходной геометрии:`false`.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | ` допуск` меньше или равно` 0` . |
| InvalidOperationException | Эта геометрия недействительна таким образом, что операция не может быть завершенный. |

### Смотрите также

* interface [IGeometryCollection](../../igeometrycollection)
* class [GeometryCollection](../../geometrycollection)
* пространство имен [Aspose.Gis.Geometries](../../geometrycollection)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
