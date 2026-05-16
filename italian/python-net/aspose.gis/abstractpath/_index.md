---
title: "Classe AbstractPath"
type: docs
weight: 10
url: /it/python-net/aspose.gis/abstractpath/
---

**Summary:** An <c>AbstractPath</c> is a base class for classes that specify a unique location in an environment similar to a filesystem,<br/>            like a local filesystem, a remote file storage or a ZIP archive, among others.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.AbstractPath

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| posizione | string | r | Restituisce una rappresentazione stringa della posizione di questo <c>AbstractPath</c>. |
| separator | char | r | Ottiene un carattere separatore usato per separare i livelli di directory della stringa [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/). |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [combine(location)](#combine_location_1) | Combina questo [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) con i componenti di percorso specificati. |
| delete() | Elimina un file a cui punta questo percorso. |
| [from_local_path(path)](#from_local_path_path_2) | Crea un [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) che rappresenta una posizione sul filesystem locale. |
| [from_stream(stream)](#from_stream_stream_3) | Crea un [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) da uno stream. |
| [get_extension()](#get_extension__4) | Restituisce l'estensione di questo [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |
| [get_file_name()](#get_file_name__5) | Restituisce il nome file e l'estensione di questo [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |
| [get_file_name_without_extension()](#get_file_name_without_extension__6) | Restituisce il nome file di questo [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) senza l'estensione. |
| [is_file()](#is_file__7) | Restituisce un valore che indica se questo percorso punta a un file esistente che può essere aperto in lettura. |
| [list_directory()](#list_directory__8) | Restituisce i percorsi situati all'interno di questo <c>AbstractPath</c>, se è una directory. |
| [open(access)](#open_access_9) | Apre questo <c>AbstractPath</c> come file. |
| [with_extension(new_extension)](#with_extension_new_extension_10) | Restituisce un nuovo [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) con l'estensione del file modificata al valore specificato. |


### Method: combine(location) {#combine_location_1}


```
 combine(location) 
```

Combina questo [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) con i componenti di percorso specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| location | string | Una componente di percorso da aggiungere a questo [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Un nuovo [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) che punta a un [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) che è una combinazione delle posizioni di questo [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) e<br/>            l'argomento. |


### Method: from_local_path(path)  [static] {#from_local_path_path_2}


```
 from_local_path(path) 
```

Crea un [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) che rappresenta una posizione sul filesystem locale.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Un percorso sul filesystem locale, ad esempio <c>"C:\\file.shp"</c> o <c>"D:\\directory\\"</c>. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Un [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) che rappresenta la posizione definita dal <paramref name="path" />. |


### Method: from_stream(stream)  [static] {#from_stream_stream_3}


```
 from_stream(stream) 
```

Crea un [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) da uno stream.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Uno stream da cui creare un [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). <c>Aspose.GIS</c> non elimina lo stream. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Un'istanza di [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) con lo stream specificato come contenuto. |


### Method: get_extension() {#get_extension__4}


```
 get_extension() 
```

Restituisce l'estensione di questo [AbstractPath](/psd/python-net/aspose.gis/abstractpath/).

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | L'estensione di questo [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) (incluso il punto ".") o<br/>            una stringa vuota se il [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) non ha estensione. |


### Method: get_file_name() {#get_file_name__5}


```
 get_file_name() 
```

Restituisce il nome file e l'estensione di questo [AbstractPath](/psd/python-net/aspose.gis/abstractpath/).

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | I caratteri dopo l'ultimo carattere [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) nella [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/). Se il<br/>            ultimo carattere è il carattere [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/), viene restituita una stringa vuota. Se non ci sono<br/>            caratteri [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) nella [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/), viene restituita la stessa [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/). |


### Method: get_file_name_without_extension() {#get_file_name_without_extension__6}


```
 get_file_name_without_extension() 
```

Restituisce il nome file di questo [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) senza l'estensione.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | La stringa restituita da [AbstractPath.get_file_name()](/psd/python-net/aspose.gis/abstractpath/) meno l'ultimo punto e tutti i caratteri successivi. |


### Method: is_file() {#is_file__7}


```
 is_file() 
```

Restituisce un valore che indica se questo percorso punta a un file esistente che può essere aperto in lettura.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <see langword="true" /> se la posizione punta a un file; <see langword="false" /> altrimenti. |


### Method: list_directory() {#list_directory__8}


```
 list_directory() 
```

Restituisce i percorsi situati all'interno di questo <c>AbstractPath</c>, se è una directory.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPath> | Percorsi situati all'interno di questo <c>AbstractPath</c>. |


### Method: open(access) {#open_access_9}


```
 open(access) 
```

Apre questo <c>AbstractPath</c> come file.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| accesso | System.IO.FileAccess | Specifica un sottoinsieme di operazioni che possono essere eseguite su uno stream. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| _io.BufferedRandom | Un flusso aperto con il FileAccess specificato. |


### Method: with_extension(new_extension) {#with_extension_new_extension_10}


```
 with_extension(new_extension) 
```

Restituisce un nuovo [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) con l'estensione del file modificata al valore specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_extension | string | Una nuova estensione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Un nuovo [AbstractPath](/psd/python-net/aspose.gis/abstractpath/), che punta a un file nella stessa directory, ma con una nuova estensione. |


