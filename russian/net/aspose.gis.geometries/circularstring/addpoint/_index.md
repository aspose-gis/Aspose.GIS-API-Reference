---
title: AddPoint
second_title: Справочник по Aspose.GIS for .NET API
description: Добавляет точку в конец циклической строки.
type: docs
weight: 120
url: /ru/net/aspose.gis.geometries/circularstring/addpoint/
---
## AddPoint(IPoint) {#addpoint}

Добавляет точку в конец циклической строки.

```csharp
public void AddPoint(IPoint point)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| point | IPoint | Добавляемая точка. |

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Аргумент:`null`. |
| ArgumentException | Аргумент пуст (его[`IsEmpty`](../../igeometry/isempty)is`true`). |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem)этого геометрия и[`SpatialReferenceSystem`](../spatialreferencesystem)аргумента не являются`null` и не равны друг другу . |

### Смотрите также

* interface [IPoint](../../ipoint)
* class [CircularString](../../circularstring)
* пространство имен [Aspose.Gis.Geometries](../../circularstring)
* сборка [Aspose.GIS](../../../)

---

## AddPoint(double, double) {#addpoint_1}

Добавляет точку в конец циклической строки.

```csharp
public void AddPoint(double x, double y)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Double | Значение координаты X. |
| y | Double | Значение координаты Y. |

### Смотрите также

* class [CircularString](../../circularstring)
* пространство имен [Aspose.Gis.Geometries](../../circularstring)
* сборка [Aspose.GIS](../../../)

---

## AddPoint(double, double, double) {#addpoint_2}

Добавляет точку в конец циклической строки.

```csharp
public void AddPoint(double x, double y, double z)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Double | Значение координаты X. |
| y | Double | Значение координаты Y. |
| z | Double | Значение координаты Z. |

### Смотрите также

* class [CircularString](../../circularstring)
* пространство имен [Aspose.Gis.Geometries](../../circularstring)
* сборка [Aspose.GIS](../../../)

---

## AddPoint(double, double, double, double) {#addpoint_3}

Добавляет точку в конец циклической строки.

```csharp
public void AddPoint(double x, double y, double z, double m)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | Double | Значение координаты X. |
| y | Double | Значение координаты Y. |
| z | Double | Значение координаты Z. |
| m | Double | Значение координаты M. |

### Смотрите также

* class [CircularString](../../circularstring)
* пространство имен [Aspose.Gis.Geometries](../../circularstring)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
