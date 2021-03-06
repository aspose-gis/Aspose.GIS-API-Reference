---
title: ToLinearGeometry
second_title: Справочник по Aspose.GIS for .NET API
description: Получает приблизительную или эквивалентную некривую версию этой геометрии используя допуск по умолчанию .
type: docs
weight: 60
url: /ru/net/aspose.gis.geometries/multisurface/tolineargeometry/
---
## ToLinearGeometry() {#tolineargeometry_4}

Получает приблизительную или эквивалентную некривую версию этой геометрии, используя допуск по умолчанию .

```csharp
public IMultiPolygon ToLinearGeometry()
```

### Возвращаемое значение

A[`IMultiPolygon`](../../imultipolygon)что приблизительно или эквивалент этому[`IMultiSurface`](../../imultisurface). Это эквивалент[`ToLinearGeometry`](../../imultisurface/tolineargeometry)с по умолчанию` допуск` . Значение по умолчанию` допуска` s зависит от[`SpatialReferenceSystem`](../../../aspose.gis.spatialreferencing/spatialreferencesystem) этой геометрии: &lt;ul&gt;&lt;li&gt; Для проектируемого SRS Допуск составляет 0,001 метра (в единицах SRS) &lt;/li&gt;&lt;li&gt; Для географического SRS Допуск составляет` 1e-5` градусов (в единицах SRS) &lt;/li&gt;&lt;li&gt; Для неизвестного SRS Допуск составляет` 1e-5` &lt;/li&gt;&lt;/ ul&gt; Подробнее о применяемых преобразованиях см. в спецификации[`ToLinearGeometry`](../../imultisurface/tolineargeometry).

### Исключения

| исключение | условие |
| --- | --- |
| InvalidOperationException | Эта геометрия недействительна таким образом, что операция не может быть завершенный. |

### Смотрите также

* interface [IMultiPolygon](../../imultipolygon)
* class [MultiSurface](../../multisurface)
* пространство имен [Aspose.Gis.Geometries](../../multisurface)
* сборка [Aspose.GIS](../../../)

---

## ToLinearGeometry(double) {#tolineargeometry_5}

Получает приблизительную или эквивалентную некривую версию этой геометрии с использованием указанного допуска .

```csharp
public IMultiPolygon ToLinearGeometry(double tolerance)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| допуск | Double | Допуск использовать. Результат гарантированно будет меньше` допуска` вдали от криволинейной геометрии, если только количество точек, необходимых для линеаризации геометрии, не превышает максимум на квадрант, в настоящее время равно 10000 точек. |

### Возвращаемое значение

A[`IMultiPolygon`](../../imultipolygon)что приблизительно или эквивалент этому[`IMultiSurface`](../../imultisurface): &lt;ul&gt; Если этот объект[`IMultiPolygon`](../../imultipolygon)сам результат эквивалентен этому объекту Если этот объект не[`IMultiPolygon`](../../imultipolygon)- все поверхности линеаризуются и создаются новые` IMultiPolygon` &lt;/ul&gt;

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | ` допуск` меньше или равно` 0` . |
| InvalidOperationException | Эта геометрия недействительна таким образом, что операция не может быть завершенный. |

### Смотрите также

* interface [IMultiPolygon](../../imultipolygon)
* class [MultiSurface](../../multisurface)
* пространство имен [Aspose.Gis.Geometries](../../multisurface)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
