---
title: "Clase AbstractPath"
type: docs
weight: 10
url: /es/python-net/aspose.gis/abstractpath/
---

**Summary:** An <c>AbstractPath</c> is a base class for classes that specify a unique location in an environment similar to a filesystem,<br/>            like a local filesystem, a remote file storage or a ZIP archive, among others.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.AbstractPath

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| ubicación | string | r | Obtiene una representación en cadena de la ubicación de este <c>AbstractPath</c>. |
| separator | char | r | Obtiene un carácter separador usado para separar los niveles de directorio de la cadena [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [combine(location)](#combine_location_1) | Combina este [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) con los componentes de ruta especificados. |
| delete() | Elimina un archivo señalado por esta ruta. |
| [from_local_path(path)](#from_local_path_path_2) | Crea un [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) que representa una ubicación en el sistema de archivos local. |
| [from_stream(stream)](#from_stream_stream_3) | Crea un [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) a partir de un flujo. |
| [get_extension()](#get_extension__4) | Devuelve la extensión de este [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |
| [get_file_name()](#get_file_name__5) | Devuelve el nombre del archivo y la extensión de este [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |
| [get_file_name_without_extension()](#get_file_name_without_extension__6) | Devuelve el nombre del archivo de este [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) sin la extensión. |
| [is_file()](#is_file__7) | Obtiene un valor que indica si esta ruta apunta a un archivo existente que puede abrirse para lectura. |
| [list_directory()](#list_directory__8) | Devuelve rutas ubicadas dentro de este <c>AbstractPath</c>, si es un directorio. |
| [open(access)](#open_access_9) | Abre este <c>AbstractPath</c> como un archivo. |
| [with_extension(new_extension)](#with_extension_new_extension_10) | Devuelve un nuevo [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) con la extensión del archivo cambiada al valor especificado. |


### Method: combine(location) {#combine_location_1}


```
 combine(location) 
```

Combina este [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) con los componentes de ruta especificados.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| location | string | Un componente de ruta para añadir a este [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Un nuevo [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) que apunta a un [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) que es una combinación de las ubicaciones de este [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) y<br/>            el argumento. |


### Method: from_local_path(path)  [static] {#from_local_path_path_2}


```
 from_local_path(path) 
```

Crea un [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) que representa una ubicación en el sistema de archivos local.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string | Una ruta en el sistema de archivos local, como <c>"C:\\file.shp"</c> o <c>"D:\\directory\\"</c>. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Un [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) que representa la ubicación definida por el <paramref name="path" />. |


### Method: from_stream(stream)  [static] {#from_stream_stream_3}


```
 from_stream(stream) 
```

Crea un [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) a partir de un flujo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| stream | _io.BufferedRandom | Un flujo para crear un [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). <c>Aspose.GIS</c> no elimina el flujo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Una instancia de [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) con el flujo especificado como su contenido. |


### Method: get_extension() {#get_extension__4}


```
 get_extension() 
```

Devuelve la extensión de este [AbstractPath](/psd/python-net/aspose.gis/abstractpath/).

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | La extensión de este [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) (incluyendo el punto ".") o<br/>            una cadena vacía si el [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) no tiene extensión. |


### Method: get_file_name() {#get_file_name__5}


```
 get_file_name() 
```

Devuelve el nombre del archivo y la extensión de este [AbstractPath](/psd/python-net/aspose.gis/abstractpath/).

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | Los caracteres después del último carácter [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) en el [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/). Si el<br/>            último carácter es el carácter [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/), se devuelve una cadena vacía. Si no hay<br/>            caracteres [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) en el [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/), se devuelve el propio [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/). |


### Method: get_file_name_without_extension() {#get_file_name_without_extension__6}


```
 get_file_name_without_extension() 
```

Devuelve el nombre del archivo de este [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) sin la extensión.

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | La cadena devuelta por [AbstractPath.get_file_name()](/psd/python-net/aspose.gis/abstractpath/) menos el último punto y todos los caracteres que le siguen. |


### Method: is_file() {#is_file__7}


```
 is_file() 
```

Obtiene un valor que indica si esta ruta apunta a un archivo existente que puede abrirse para lectura.

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <see langword="true" /> si la ubicación apunta a un archivo; <see langword="false" /> de lo contrario. |


### Method: list_directory() {#list_directory__8}


```
 list_directory() 
```

Devuelve rutas ubicadas dentro de este <c>AbstractPath</c>, si es un directorio.

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPath> | Rutas ubicadas dentro de este <c>AbstractPath</c>. |


### Method: open(access) {#open_access_9}


```
 open(access) 
```

Abre este <c>AbstractPath</c> como un archivo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| acceso | System.IO.FileAccess | Especifica un subconjunto de operaciones que pueden realizarse sobre un flujo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| _io.BufferedRandom | Un flujo abierto con el FileAccess especificado. |


### Method: with_extension(new_extension) {#with_extension_new_extension_10}


```
 with_extension(new_extension) 
```

Devuelve un nuevo [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) con la extensión del archivo cambiada al valor especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_extension | string | Una nueva extensión. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Un nuevo [AbstractPath](/psd/python-net/aspose.gis/abstractpath/), que apunta a un archivo en el mismo directorio, pero con una nueva extensión. |


