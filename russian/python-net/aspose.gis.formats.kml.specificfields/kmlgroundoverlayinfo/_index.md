---
title: "Класс KmlGroundOverlayInfo"
type: docs
weight: 20
url: /ru/python-net/aspose.gis.formats.kml.specificfields/kmlgroundoverlayinfo/
---

**Summary:** Specifies object from Kml 'GroundOverlay' node

**Module:** [aspose.gis.formats.kml.specificfields](/psd/python-net/aspose.gis.formats.kml.specificfields/)

**Full Name:** aspose.gis.formats.kml.specificfields.KmlGroundOverlayInfo

**Inheritance:** XmlNodeLink

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| children | [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | r | Получает дочерние элементы. |
| draw_order | double | r/w | DrawOrder узла 'GroundOverlay'. |
| icon | [IconInfo](/psd/python-net/aspose.gis.formats.kml.specificfields/iconinfo) | r/w | IconPath узла 'GroundOverlay'. |
| lat_lon_box | [KmlLatLonBox](/psd/python-net/aspose.gis.formats.kml.specificfields/kmllatlonbox) | r/w | Указывает объект из узла Kml 'LatLonAltBox'. |
| имя | string | r/w | Имя наложения Ground Overlay |
| name_without_prefix | string | r | Получает имя без префикса. |
| node_name | string | r/w | Получает или задает имя. |
| node_value | string | r/w | Получает или задает значение. |
| префикс | string | r | Получает префикс. |
| visibility | bool | r/w | Видимость наложения Ground Overlay |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add_child(child)](#add_child_child_1) | Добавляет дочерний элемент. |
| [as_bool()](#as_bool__2) | Возвращает значение, приведённое к типу bool |
| [as_double()](#as_double__3) | Возвращает значение, приведённое к типу double. |
| [as_int()](#as_int__4) | Возвращает значение, приведённое к типу int. |
| [find_nodes_by_name(name)](#find_nodes_by_name_name_5) | Находит XML-узлы по имени |
| [get_node_by_name(name)](#get_node_by_name_name_6) | Получает узел по имени. Обратите внимание, этот метод вернёт первый найденный Node.<br/>            Не имеет значения, на каком уровне он будет найден |
| [get_node_content()](#get_node_content__7) | Получает содержимое узла. |
| [get_nodes_by_name(names)](#get_nodes_by_name_names_8) | Получает все узлы с указанным именем. <br/>            Не имеет значения, на каком уровне они будут найдены |


### Method: add_child(child) {#add_child_child_1}


```
 add_child(child) 
```

Добавляет дочерний элемент.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| child | [NodeLink](/psd/python-net/aspose.gis/nodelink) | Дочерний элемент. |

### Method: as_bool() {#as_bool__2}


```
 as_bool() 
```

Возвращает значение, приведённое к типу bool

**Returns**

| Тип | Описание |
| :- | :- |
| bool | Логическое значение узла |


### Method: as_double() {#as_double__3}


```
 as_double() 
```

Возвращает значение, приведённое к типу double.

**Returns**

| Тип | Описание |
| :- | :- |
| double | Дробное значение узла |


### Method: as_int() {#as_int__4}


```
 as_int() 
```

Возвращает значение, приведённое к типу int.

**Returns**

| Тип | Описание |
| :- | :- |
| int | Целочисленное значение узла |


### Method: find_nodes_by_name(name) {#find_nodes_by_name_name_5}


```
 find_nodes_by_name(name) 
```

Находит XML-узлы по имени

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя узла |

**Returns**

| Тип | Описание |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | Массив XML-узлов по имени |


### Method: get_node_by_name(name) {#get_node_by_name_name_6}


```
 get_node_by_name(name) 
```

Получает узел по имени. Обратите внимание, этот метод вернёт первый найденный Node.<br/>            Не имеет значения, на каком уровне он будет найден

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имя | string | Имя узла, который вы хотите найти. |

**Returns**

| Тип | Описание |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | Найденный узел с помощью NodeLink API |


### Method: get_node_content() {#get_node_content__7}


```
 get_node_content() 
```

Получает содержимое узла.

**Returns**

| Тип | Описание |
| :- | :- |
| string | Содержимое узла |


### Method: get_nodes_by_name(names) {#get_nodes_by_name_names_8}


```
 get_nodes_by_name(names) 
```

Получает все узлы с указанным именем. <br/>            Не имеет значения, на каком уровне они будут найдены

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| имена | string | Имена. |

**Returns**

| Тип | Описание |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | Массив найденных узлов. |


