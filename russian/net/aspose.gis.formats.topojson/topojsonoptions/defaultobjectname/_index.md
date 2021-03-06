---
title: DefaultObjectName
second_title: Справочник по Aspose.GIS for .NET API
description: Имя объекта в который по умолчанию помещаются признаки.
type: docs
weight: 20
url: /ru/net/aspose.gis.formats.topojson/topojsonoptions/defaultobjectname/
---
## TopoJsonOptions.DefaultObjectName property

Имя объекта, в который по умолчанию помещаются признаки.

```csharp
public string DefaultObjectName { get; set; }
```

### Примечания

Это опция записи - не влияет на чтение. TopoJSON может содержать любое количество именованных объектов. Каждый такой объект может содержать несколько функций. Чтобы указать, в какой объект поместить вашу функцию, используйте свойство [`ObjectNameAttribute`](../objectnameattribute). Если атрибут с именем[`ObjectNameAttribute`](../objectnameattribute)равен`null`или не установлен для некоторая функция, эта функция добавляется к объекту с именем`DefaultObjectName`. Если атрибут с именем[`ObjectNameAttribute`](../objectnameattribute)отсутствует в[`Attributes`](../../../aspose.gis/vectorlayer/attributes) коллекция, все функции помещены в объект с именем[`ObjectNameAttribute`](../objectnameattribute). Значение по умолчанию "безымянный".

### Смотрите также

* class [TopoJsonOptions](../../topojsonoptions)
* пространство имен [Aspose.Gis.Formats.TopoJson](../../topojsonoptions)
* сборка [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
