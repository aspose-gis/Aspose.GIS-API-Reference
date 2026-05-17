---
title: "AbstractPath-klass"
type: docs
weight: 10
url: /sv/python-net/aspose.gis/abstractpath/
---

**Summary:** An <c>AbstractPath</c> is a base class for classes that specify a unique location in an environment similar to a filesystem,<br/>            like a local filesystem, a remote file storage or a ZIP archive, among others.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.AbstractPath

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| plats | string | r | Hämtar en strängrepresentation av platsen för detta <c>AbstractPath</c>. |
| separator | char | r | Hämtar ett separator‑tecken som används för att separera katalognivåer i [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/)-strängen. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [combine(location)](#combine_location_1) | Kombinerar detta [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) med angivna sökvägskomponenter. |
| delete() | Raderar en fil som pekas ut av denna sökväg. |
| [from_local_path(path)](#from_local_path_path_2) | Skapar ett [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) som representerar en plats på det lokala filsystemet. |
| [from_stream(stream)](#from_stream_stream_3) | Skapar ett [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) från en ström. |
| [get_extension()](#get_extension__4) | Returnerar filändelsen för detta [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |
| [get_file_name()](#get_file_name__5) | Returnerar filnamnet och filändelsen för detta [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |
| [get_file_name_without_extension()](#get_file_name_without_extension__6) | Returnerar filnamnet för detta [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) utan filändelsen. |
| [is_file()](#is_file__7) | Hämtar ett värde som indikerar om denna sökväg pekar på en befintlig fil som kan öppnas för läsning. |
| [list_directory()](#list_directory__8) | Returnerar sökvägar som finns inuti detta <c>AbstractPath</c>, om det är en katalog. |
| [open(access)](#open_access_9) | Öppnar detta <c>AbstractPath</c> som en fil. |
| [with_extension(new_extension)](#with_extension_new_extension_10) | Returnerar ett nytt [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) med filändelsen ändrad till det angivna värdet. |


### Method: combine(location) {#combine_location_1}


```
 combine(location) 
```

Kombinerar detta [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) med angivna sökvägskomponenter.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| location | string | En sökvägskomponent att lägga till denna [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | En ny [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) som pekar på en [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) som är en kombination av platserna för denna [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) och<br/>            argumentet. |


### Method: from_local_path(path)  [static] {#from_local_path_path_2}


```
 from_local_path(path) 
```

Skapar ett [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) som representerar en plats på det lokala filsystemet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | En sökväg på det lokala filsystemet, till exempel <c>"C:\\file.shp"</c> eller <c>"D:\\directory\\"</c>. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | En [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) som representerar platsen som definieras av <paramref name="path" />. |


### Method: from_stream(stream)  [static] {#from_stream_stream_3}


```
 from_stream(stream) 
```

Skapar ett [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) från en ström.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| stream | _io.BufferedRandom | En ström för att skapa en [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) från. <c>Aspose.GIS</c> disponerar inte strömmen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | En instans av [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) med den angivna strömmen som innehåll. |


### Method: get_extension() {#get_extension__4}


```
 get_extension() 
```

Returnerar filändelsen för detta [AbstractPath](/psd/python-net/aspose.gis/abstractpath/).

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Filändelsen för denna [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) (inklusive punkten ".") eller<br/>            en tom sträng om [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) saknar filändelse. |


### Method: get_file_name() {#get_file_name__5}


```
 get_file_name() 
```

Returnerar filnamnet och filändelsen för detta [AbstractPath](/psd/python-net/aspose.gis/abstractpath/).

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Tecknen efter det sista [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) tecknet i [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/). Om det<br/>            sista tecknet är [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) tecknet, returneras en tom sträng. Om det inte finns några<br/>            [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) tecken i [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/), returneras själva [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/). |


### Method: get_file_name_without_extension() {#get_file_name_without_extension__6}


```
 get_file_name_without_extension() 
```

Returnerar filnamnet för detta [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) utan filändelsen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Strängen som returneras av [AbstractPath.get_file_name()](/psd/python-net/aspose.gis/abstractpath/) utan den sista punkten och alla efterföljande tecken. |


### Method: is_file() {#is_file__7}


```
 is_file() 
```

Hämtar ett värde som indikerar om denna sökväg pekar på en befintlig fil som kan öppnas för läsning.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <see langword="true" /> om platsen pekar på en fil; <see langword="false" /> annars. |


### Method: list_directory() {#list_directory__8}


```
 list_directory() 
```

Returnerar sökvägar som finns inuti detta <c>AbstractPath</c>, om det är en katalog.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPath> | Sökvägar som finns inuti detta <c>AbstractPath</c>. |


### Method: open(access) {#open_access_9}


```
 open(access) 
```

Öppnar detta <c>AbstractPath</c> som en fil.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| åtkomst | System.IO.FileAccess | Anger en delmängd av operationer som kan utföras på en ström. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| _io.BufferedRandom | En ström öppnad med den angivna FileAccess. |


### Method: with_extension(new_extension) {#with_extension_new_extension_10}


```
 with_extension(new_extension) 
```

Returnerar ett nytt [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) med filändelsen ändrad till det angivna värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_extension | string | En ny filändelse. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | En ny [AbstractPath](/psd/python-net/aspose.gis/abstractpath/), som pekar på en fil i samma katalog, men med en ny filändelse. |


