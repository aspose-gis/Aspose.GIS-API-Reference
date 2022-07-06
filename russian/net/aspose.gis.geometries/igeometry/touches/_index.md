---
title: Touches
second_title: Справочник по Aspose.GIS for .NET API
description: Определяет соприкасаются ли эта геометрия и указанная геометрия.
type: docs
weight: 360
url: /ru/net/aspose.gis.geometries/igeometry/touches/
---
## IGeometry.Touches method

Определяет, соприкасаются ли эта геометрия и указанная геометрия.

```csharp
public bool Touches(IGeometry other)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | IGeometry | Геометрия. |

### Возвращаемое значение

`true`если эта геометрия "пространственно касается" другой геометрии.`false`иначе.

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentNullException | Аргумент:`null`. |
| ArgumentException | Одна из геометрий недействительна, поэтому операция не может быть завершена. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem)геометрий не эквивалентны. Вы можете использовать[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation)для преобразования геометрии в одну и ту же пространственную систему отсчета. |

### Примечания

Этот метод проверяет, касаются ли геометрии друг друга с точки зрения матрицы пересечения DE-9IM. Две геометрии касаются друг друга, если они имеют хотя бы одну общую граничную точку, но не имеют внутренних точек. То есть:два[`LineString`](../../linestring)соприкасаются друг с другом, если они имеют общую конечную точку, но не имеют общего сегмента, два многоугольника касаются друг друга, если они имеют общую часть внешнего или внутреннего кольца, но их внутренние части не перекрываются.&lt;cr /&gt; Этот метод эквивалентен: См. Спецификацию простых функций OpenGIS для получения более подробной информации о DE-9IM и отношении «пространственного касания».

```csharp
this.Relate(other, "FT*******") || this.Relate(other, "F**T*****") || this.Relate(other, "F***T****");
```

### Смотрите также

* interface [IGeometry](../../igeometry)
* пространство имен [Aspose.Gis.Geometries](../../igeometry)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->