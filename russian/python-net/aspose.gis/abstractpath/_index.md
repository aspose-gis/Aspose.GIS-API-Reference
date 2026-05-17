---
title: "Класс AbstractPath"
type: docs
weight: 10
url: /ru/python-net/aspose.gis/abstractpath/
---

**Summary:** An <c>AbstractPath</c> is a base class for classes that specify a unique location in an environment similar to a filesystem,<br/>            like a local filesystem, a remote file storage or a ZIP archive, among others.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.AbstractPath

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| location | string | r | Получает строковое представление местоположения этого <c>AbstractPath</c>. |
| separator | char | r | Получает символ-разделитель, используемый для разделения уровней каталогов в строке [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/). |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [combine(location)](#combine_location_1) | Объединяет этот [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) с указанными компонентами пути. |
| delete() | Удаляет файл, на который указывает этот путь. |
| [from_local_path(path)](#from_local_path_path_2) | Создаёт [AbstractPath](/psd/python-net/aspose.gis/abstractpath/), представляющий расположение в локальной файловой системе. |
| [from_stream(stream)](#from_stream_stream_3) | Создаёт [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) из потока. |
| [get_extension()](#get_extension__4) | Возвращает расширение этого [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |
| [get_file_name()](#get_file_name__5) | Возвращает имя файла и его расширение этого [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |
| [get_file_name_without_extension()](#get_file_name_without_extension__6) | Возвращает имя файла этого [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) без расширения. |
| [is_file()](#is_file__7) | Получает значение, указывающее, указывает ли этот путь на существующий файл, который можно открыть для чтения. |
| [list_directory()](#list_directory__8) | Возвращает пути, расположенные внутри этого <c>AbstractPath</c>, если это каталог. |
| [open(access)](#open_access_9) | Открывает этот <c>AbstractPath</c> как файл. |
| [with_extension(new_extension)](#with_extension_new_extension_10) | Возвращает новый [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) с изменённым расширением файла на указанное значение. |


### Method: combine(location) {#combine_location_1}


```
 combine(location) 
```

Объединяет этот [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) с указанными компонентами пути.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| location | string | Компонент пути для добавления к этому [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |

**Returns**

| Тип | Описание |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Новый [AbstractPath](/psd/python-net/aspose.gis/abstractpath/), указывающий на [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/), который является комбинацией местоположений этого [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) и<br/>            аргумента. |


### Method: from_local_path(path)  [static] {#from_local_path_path_2}


```
 from_local_path(path) 
```

Создаёт [AbstractPath](/psd/python-net/aspose.gis/abstractpath/), представляющий расположение в локальной файловой системе.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string | Путь в локальной файловой системе, например <c>"C:\\file.shp"</c> или <c>"D:\\directory\\"</c>. |

**Returns**

| Тип | Описание |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Объект [AbstractPath](/psd/python-net/aspose.gis/abstractpath/), представляющий местоположение, определённое параметром <paramref name="path" />. |


### Method: from_stream(stream)  [static] {#from_stream_stream_3}


```
 from_stream(stream) 
```

Создаёт [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) из потока.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | _io.BufferedRandom | Поток для создания [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) из него. <c>Aspose.GIS</c> не освобождает поток. |

**Returns**

| Тип | Описание |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Экземпляр [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) с указанным потоком в качестве его содержимого. |


### Method: get_extension() {#get_extension__4}


```
 get_extension() 
```

Возвращает расширение этого [AbstractPath](/psd/python-net/aspose.gis/abstractpath/).

**Returns**

| Тип | Описание |
| :- | :- |
| string | Расширение этого [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) (включая точку ".") или<br/>            пустая строка, если у [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) нет расширения. |


### Method: get_file_name() {#get_file_name__5}


```
 get_file_name() 
```

Возвращает имя файла и его расширение этого [AbstractPath](/psd/python-net/aspose.gis/abstractpath/).

**Returns**

| Тип | Описание |
| :- | :- |
| string | Символы после последнего символа [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) в [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/). Если<br/>            последний символ является символом [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/), возвращается пустая строка. Если в [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) нет<br/>            символов [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/), возвращается само [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/). |


### Method: get_file_name_without_extension() {#get_file_name_without_extension__6}


```
 get_file_name_without_extension() 
```

Возвращает имя файла этого [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) без расширения.

**Returns**

| Тип | Описание |
| :- | :- |
| string | Строка, возвращаемая [AbstractPath.get_file_name()](/psd/python-net/aspose.gis/abstractpath/), без последней точки и всех символов, следующих за ней. |


### Method: is_file() {#is_file__7}


```
 is_file() 
```

Получает значение, указывающее, указывает ли этот путь на существующий файл, который можно открыть для чтения.

**Returns**

| Тип | Описание |
| :- | :- |
| bool | <see langword="true" /> если местоположение указывает на файл; <see langword="false" /> иначе. |


### Method: list_directory() {#list_directory__8}


```
 list_directory() 
```

Возвращает пути, расположенные внутри этого <c>AbstractPath</c>, если это каталог.

**Returns**

| Тип | Описание |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPath> | Пути, расположенные внутри этого <c>AbstractPath</c>. |


### Method: open(access) {#open_access_9}


```
 open(access) 
```

Открывает этот <c>AbstractPath</c> как файл.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| доступ | System.IO.FileAccess | Указывает подмножество операций, которые могут быть выполнены над потоком. |

**Returns**

| Тип | Описание |
| :- | :- |
| _io.BufferedRandom | Поток, открытый с указанным FileAccess. |


### Method: with_extension(new_extension) {#with_extension_new_extension_10}


```
 with_extension(new_extension) 
```

Возвращает новый [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) с изменённым расширением файла на указанное значение.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_extension | string | Новое расширение. |

**Returns**

| Тип | Описание |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Новый [AbstractPath](/psd/python-net/aspose.gis/abstractpath/), который указывает на файл в том же каталоге, но с новым расширением. |


