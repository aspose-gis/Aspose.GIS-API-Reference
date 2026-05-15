---
title: "Classe AbstractPath"
type: docs
weight: 10
url: /fr/python-net/aspose.gis/abstractpath/
---

**Summary:** An <c>AbstractPath</c> is a base class for classes that specify a unique location in an environment similar to a filesystem,<br/>            like a local filesystem, a remote file storage or a ZIP archive, among others.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.AbstractPath

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| emplacement | string | r | Obtient une représentation sous forme de chaîne de l'emplacement de ce <c>AbstractPath</c>. |
| separator | char | r | Obtient un caractère séparateur utilisé pour séparer les niveaux de répertoire de la chaîne [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [combine(location)](#combine_location_1) | Combine ce [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) avec les composants de chemin spécifiés. |
| delete() | Supprime un fichier pointé par ce chemin. |
| [from_local_path(path)](#from_local_path_path_2) | Crée un [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) qui représente un emplacement sur le système de fichiers local. |
| [from_stream(stream)](#from_stream_stream_3) | Crée un [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) à partir d'un flux. |
| [get_extension()](#get_extension__4) | Renvoie l'extension de ce [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |
| [get_file_name()](#get_file_name__5) | Renvoie le nom de fichier et l'extension de ce [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |
| [get_file_name_without_extension()](#get_file_name_without_extension__6) | Renvoie le nom de fichier de ce [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) sans l'extension. |
| [is_file()](#is_file__7) | Obtient une valeur indiquant si ce chemin pointe vers un fichier existant qui peut être ouvert en lecture. |
| [list_directory()](#list_directory__8) | Renvoie les chemins situés à l'intérieur de ce <c>AbstractPath</c>, s'il s'agit d'un répertoire. |
| [open(access)](#open_access_9) | Ouvre ce <c>AbstractPath</c> en tant que fichier. |
| [with_extension(new_extension)](#with_extension_new_extension_10) | Renvoie un nouveau [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) avec l'extension de fichier modifiée à la valeur spécifiée. |


### Method: combine(location) {#combine_location_1}


```
 combine(location) 
```

Combine ce [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) avec les composants de chemin spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| location | string | Un composant de chemin à ajouter à cet [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |

**Returns**

| Type | Description |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Un nouveau [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) pointant vers un [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) qui est une combinaison des emplacements de cet [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) et<br/>            l'argument. |


### Method: from_local_path(path)  [static] {#from_local_path_path_2}


```
 from_local_path(path) 
```

Crée un [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) qui représente un emplacement sur le système de fichiers local.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Un chemin sur le système de fichiers local, comme <c>\"C:\\file.shp\"</c> ou <c>\"D:\\directory\\\"</c>. |

**Returns**

| Type | Description |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Un [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) qui représente l'emplacement défini par le <paramref name=\"path\" />. |


### Method: from_stream(stream)  [static] {#from_stream_stream_3}


```
 from_stream(stream) 
```

Crée un [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) à partir d'un flux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | Un flux pour créer un [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) à partir de celui-ci. <c>Aspose.GIS</c> ne libère pas le flux. |

**Returns**

| Type | Description |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Une instance de [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) avec le flux spécifié comme son contenu. |


### Method: get_extension() {#get_extension__4}


```
 get_extension() 
```

Renvoie l'extension de ce [AbstractPath](/psd/python-net/aspose.gis/abstractpath/).

**Returns**

| Type | Description |
| :- | :- |
| string | L'extension de cet [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) (incluant le point \".\") ou<br/>            une chaîne vide si le [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) n'a pas d'extension. |


### Method: get_file_name() {#get_file_name__5}


```
 get_file_name() 
```

Renvoie le nom de fichier et l'extension de ce [AbstractPath](/psd/python-net/aspose.gis/abstractpath/).

**Returns**

| Type | Description |
| :- | :- |
| string | Les caractères après le dernier caractère [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) dans le [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/). Si le<br/>            dernier caractère est le caractère [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/), une chaîne vide est renvoyée. S'il n'y a pas de<br/>            caractères [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) dans le [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/), le [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) lui‑même<br/>            est renvoyé. |


### Method: get_file_name_without_extension() {#get_file_name_without_extension__6}


```
 get_file_name_without_extension() 
```

Renvoie le nom de fichier de ce [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) sans l'extension.

**Returns**

| Type | Description |
| :- | :- |
| string | La chaîne renvoyée par [AbstractPath.get_file_name()](/psd/python-net/aspose.gis/abstractpath/) moins le dernier point et tous les caractères qui le suivent. |


### Method: is_file() {#is_file__7}


```
 is_file() 
```

Obtient une valeur indiquant si ce chemin pointe vers un fichier existant qui peut être ouvert en lecture.

**Returns**

| Type | Description |
| :- | :- |
| bool | <see langword=\"true\" /> si l'emplacement pointe vers un fichier; <see langword=\"false\" /> sinon. |


### Method: list_directory() {#list_directory__8}


```
 list_directory() 
```

Renvoie les chemins situés à l'intérieur de ce <c>AbstractPath</c>, s'il s'agit d'un répertoire.

**Returns**

| Type | Description |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPath> | Chemins situés à l'intérieur de cet <c>AbstractPath</c>. |


### Method: open(access) {#open_access_9}


```
 open(access) 
```

Ouvre ce <c>AbstractPath</c> en tant que fichier.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| accès | System.IO.FileAccess | Spécifie un sous‑ensemble d'opérations pouvant être effectuées sur un flux. |

**Returns**

| Type | Description |
| :- | :- |
| _io.BufferedRandom | Un flux ouvert avec le FileAccess spécifié. |


### Method: with_extension(new_extension) {#with_extension_new_extension_10}


```
 with_extension(new_extension) 
```

Renvoie un nouveau [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) avec l'extension de fichier modifiée à la valeur spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_extension | string | Une nouvelle extension. |

**Returns**

| Type | Description |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Un nouveau [AbstractPath](/psd/python-net/aspose.gis/abstractpath/), qui pointe vers un fichier dans le même répertoire, mais avec une nouvelle extension. |


