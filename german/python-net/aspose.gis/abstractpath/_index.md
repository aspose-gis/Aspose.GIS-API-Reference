---
title: "AbstractPath Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.gis/abstractpath/
---

**Summary:** An <c>AbstractPath</c> is a base class for classes that specify a unique location in an environment similar to a filesystem,<br/>            like a local filesystem, a remote file storage or a ZIP archive, among others.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.AbstractPath

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| Ort | string | r | Gibt eine Zeichenkettenrepräsentation des Ortes dieses <c>AbstractPath</c> zurück. |
| separator | char | r | Liefert ein Trennzeichen, das verwendet wird, um Verzeichnisebenen des [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) Strings zu trennen. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [combine(location)](#combine_location_1) | Kombiniert diesen [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) mit angegebenen Pfadkomponenten. |
| delete() | Löscht eine Datei, auf die dieser Pfad zeigt. |
| [from_local_path(path)](#from_local_path_path_2) | Erstellt einen [AbstractPath](/psd/python-net/aspose.gis/abstractpath/), der einen Ort im lokalen Dateisystem darstellt. |
| [from_stream(stream)](#from_stream_stream_3) | Erstellt einen [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) aus einem Stream. |
| [get_extension()](#get_extension__4) | Gibt die Erweiterung dieses [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) zurück. |
| [get_file_name()](#get_file_name__5) | Gibt den Dateinamen und die Erweiterung dieses [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) zurück. |
| [get_file_name_without_extension()](#get_file_name_without_extension__6) | Gibt den Dateinamen dieses [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) ohne die Erweiterung zurück. |
| [is_file()](#is_file__7) | Gibt einen Wert zurück, der angibt, ob dieser Pfad auf eine vorhandene Datei zeigt, die zum Lesen geöffnet werden kann. |
| [list_directory()](#list_directory__8) | Gibt Pfade zurück, die sich innerhalb dieses <c>AbstractPath</c> befinden, falls es ein Verzeichnis ist. |
| [open(access)](#open_access_9) | Öffnet dieses <c>AbstractPath</c> als Datei. |
| [with_extension(new_extension)](#with_extension_new_extension_10) | Gibt einen neuen [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) zurück, bei dem die Dateierweiterung auf den angegebenen Wert geändert wurde. |


### Method: combine(location) {#combine_location_1}


```
 combine(location) 
```

Kombiniert diesen [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) mit angegebenen Pfadkomponenten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| location | string | Eine Pfadkomponente, die an dieses [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) angehängt wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ein neuer [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) der auf einen [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) zeigt, der eine Kombination der Orte dieses [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) und<br/>            des Arguments ist. |


### Method: from_local_path(path)  [static] {#from_local_path_path_2}


```
 from_local_path(path) 
```

Erstellt einen [AbstractPath](/psd/python-net/aspose.gis/abstractpath/), der einen Ort im lokalen Dateisystem darstellt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Ein Pfad im lokalen Dateisystem, z. b. <c>\"C:\\\\file.shp\"</c> oder <c>\"D:\\\\directory\\\"</c>. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ein [AbstractPath](/psd/python-net/aspose.gis/abstractpath/), der den durch das <paramref name=\"path\" /> definierte Ort repräsentiert. |


### Method: from_stream(stream)  [static] {#from_stream_stream_3}


```
 from_stream(stream) 
```

Erstellt einen [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) aus einem Stream.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| stream | _io.BufferedRandom | Ein Stream, aus dem ein [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) erstellt wird. <c>Aspose.GIS</c> gibt den Stream nicht frei. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Eine Instanz von [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) mit dem angegebenen Stream als Inhalt. |


### Method: get_extension() {#get_extension__4}


```
 get_extension() 
```

Gibt die Erweiterung dieses [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) zurück.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Die Erweiterung dieses [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) (einschließlich des Punktes \".\") oder<br/>            eine leere Zeichenkette, wenn das [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) keine Erweiterung hat. |


### Method: get_file_name() {#get_file_name__5}


```
 get_file_name() 
```

Gibt den Dateinamen und die Erweiterung dieses [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) zurück.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Die Zeichen nach dem letzten [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) Zeichen in der [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/). Wenn das<br/>            letzte Zeichen das [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) Zeichen ist, wird eine leere Zeichenkette zurückgegeben. Wenn es kein<br/>            [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) Zeichen in der [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) gibt, wird die [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) selbst<br/>            zurückgegeben. |


### Method: get_file_name_without_extension() {#get_file_name_without_extension__6}


```
 get_file_name_without_extension() 
```

Gibt den Dateinamen dieses [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) ohne die Erweiterung zurück.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | Die von [AbstractPath.get_file_name()](/psd/python-net/aspose.gis/abstractpath/) zurückgegebene Zeichenkette ohne den letzten Punkt und alle darauf folgenden Zeichen. |


### Method: is_file() {#is_file__7}


```
 is_file() 
```

Gibt einen Wert zurück, der angibt, ob dieser Pfad auf eine vorhandene Datei zeigt, die zum Lesen geöffnet werden kann.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool | <see langword="true" /> wenn der Ort auf eine Datei zeigt; <see langword="false" /> andernfalls. |


### Method: list_directory() {#list_directory__8}


```
 list_directory() 
```

Gibt Pfade zurück, die sich innerhalb dieses <c>AbstractPath</c> befinden, falls es ein Verzeichnis ist.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPath> | Pfade, die sich innerhalb dieses <c>AbstractPath</c> befinden. |


### Method: open(access) {#open_access_9}


```
 open(access) 
```

Öffnet dieses <c>AbstractPath</c> als Datei.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Zugriff | System.IO.FileAccess | Gibt eine Teilmenge von Operationen an, die an einem Stream ausgeführt werden können. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| _io.BufferedRandom | Ein Stream, der mit dem angegebenen FileAccess geöffnet wurde. |


### Method: with_extension(new_extension) {#with_extension_new_extension_10}


```
 with_extension(new_extension) 
```

Gibt einen neuen [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) zurück, bei dem die Dateierweiterung auf den angegebenen Wert geändert wurde.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_extension | string | Eine neue Erweiterung. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Ein neuer [AbstractPath](/psd/python-net/aspose.gis/abstractpath/), der auf eine Datei im selben Verzeichnis zeigt, jedoch mit einer neuen Erweiterung. |


