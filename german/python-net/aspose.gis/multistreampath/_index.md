---
title: "MultiStreamPath Klasse"
type: docs
weight: 2760
url: /de/python-net/aspose.gis/multistreampath/
---

**Summary:** This class works with formats which contains several files.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.MultiStreamPath

**Inheritance:** AbstractPath

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [MultiStreamPath(entry_file_name, file_names, streams)](#MultiStreamPath_entry_file_name_file_names_streams_1) | Initialisiert eine neue Instanz der [MultiStreamPath](/psd/python-net/aspose.gis/multistreampath/) Klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| Ort | string | r | Gibt eine Zeichenkettenrepräsentation des Ortes dieses <c>AbstractPath</c> zurück. |
| separator | char | r | Gibt ein Trennzeichen zurück, das verwendet wird, um Verzeichnisebenen der Zeichenkette [MultiStreamPath.location](/psd/python-net/aspose.gis/multistreampath/) zu trennen. |
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
| [open(access)](#open_access_9) | Abstrahiert einen Satz von offenen Streaming‑Multi‑Datei‑Formaten als Pfad zum Zugriff auf Daten. |
| [with_extension(new_extension)](#with_extension_new_extension_10) | Gibt einen neuen [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) zurück, bei dem die Dateierweiterung auf den angegebenen Wert geändert wurde. |


### Constructor: MultiStreamPath(entry_file_name, file_names, streams) {#MultiStreamPath_entry_file_name_file_names_streams_1}


```
 MultiStreamPath(entry_file_name, file_names, streams) 
```

Initialisiert eine neue Instanz der [MultiStreamPath](/psd/python-net/aspose.gis/multistreampath/) Klasse.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| entry_file_name | string | Name der Eintragsdatei. |
| file_names | string | Die Dateinamen. |
| streams | _io.BufferedRandom[] | Die Streams. |

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

Abstrahiert einen Satz von offenen Streaming‑Multi‑Datei‑Formaten als Pfad zum Zugriff auf Daten.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Zugriff | System.IO.FileAccess | Gibt eine Teilmenge von Operationen an, die an einem Stream ausgeführt werden können. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| _io.BufferedRandom | Dies kann entweder ein   oder der vom Client ursprünglich übergebene Stream sein. |


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


