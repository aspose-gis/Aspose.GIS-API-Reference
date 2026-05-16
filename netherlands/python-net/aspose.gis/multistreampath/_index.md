---
title: "MultiStreamPath Klasse"
type: docs
weight: 2760
url: /nl/python-net/aspose.gis/multistreampath/
---

**Summary:** This class works with formats which contains several files.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.MultiStreamPath

**Inheritance:** AbstractPath

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [MultiStreamPath(entry_file_name, file_names, streams)](#MultiStreamPath_entry_file_name_file_names_streams_1) | Initialiseert een nieuw exemplaar van de [MultiStreamPath](/psd/python-net/aspose.gis/multistreampath/) klasse. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| locatie | string | r | Haalt een tekenreeksrepresentatie op van de locatie van dit <c>AbstractPath</c>. |
| separator | char | r | Haalt een scheidingsteken op dat wordt gebruikt om directory-niveaus te scheiden in de [MultiStreamPath.location](/psd/python-net/aspose.gis/multistreampath/) tekenreeks. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [combine(location)](#combine_location_1) | Combineert dit [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) met opgegeven padcomponenten. |
| delete() | Verwijdert een bestand waar dit pad naar verwijst. |
| [from_local_path(path)](#from_local_path_path_2) | Maakt een [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) aan die een locatie op het lokale bestandssysteem vertegenwoordigt. |
| [from_stream(stream)](#from_stream_stream_3) | Maakt een [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) aan vanuit een stream. |
| [get_extension()](#get_extension__4) | Retourneert de extensie van dit [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |
| [get_file_name()](#get_file_name__5) | Retourneert de bestandsnaam en extensie van dit [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |
| [get_file_name_without_extension()](#get_file_name_without_extension__6) | Retourneert de bestandsnaam van dit [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) zonder de extensie. |
| [is_file()](#is_file__7) | Haalt een waarde op die aangeeft of dit pad naar een bestaand bestand wijst dat geopend kan worden voor lezen. |
| [list_directory()](#list_directory__8) | Retourneert paden die zich binnen dit <c>AbstractPath</c> bevinden, als het een map is. |
| [open(access)](#open_access_9) | Abstracteert een reeks open streaming multi‑bestandformaten als een pad voor het benaderen van gegevens. |
| [with_extension(new_extension)](#with_extension_new_extension_10) | Retourneert een nieuw [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) met de bestandsextensie gewijzigd naar de opgegeven waarde. |


### Constructor: MultiStreamPath(entry_file_name, file_names, streams) {#MultiStreamPath_entry_file_name_file_names_streams_1}


```
 MultiStreamPath(entry_file_name, file_names, streams) 
```

Initialiseert een nieuw exemplaar van de [MultiStreamPath](/psd/python-net/aspose.gis/multistreampath/) klasse.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| entry_file_name | string | Naam van het invoerbestand. |
| file_names | string | De bestandsnamen. |
| streams | _io.BufferedRandom[] | De streams. |

### Method: combine(location) {#combine_location_1}


```
 combine(location) 
```

Combineert dit [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) met opgegeven padcomponenten.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| location | string | Een padcomponent om aan deze [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) toe te voegen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Een nieuw [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) dat wijst naar een [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) die een combinatie is van de locaties van deze [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) en<br/>            het argument. |


### Method: from_local_path(path)  [static] {#from_local_path_path_2}


```
 from_local_path(path) 
```

Maakt een [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) aan die een locatie op het lokale bestandssysteem vertegenwoordigt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Een pad op het lokale bestandssysteem, bijvoorbeeld <c>"C:\\file.shp"</c> of <c>"D:\\directory\\"</c>. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Een [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) die de locatie vertegenwoordigt die gedefinieerd is door de <paramref name="path" />. |


### Method: from_stream(stream)  [static] {#from_stream_stream_3}


```
 from_stream(stream) 
```

Maakt een [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) aan vanuit een stream.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stream | _io.BufferedRandom | Een stream om een [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) van te maken. <c>Aspose.GIS</c> verwijdert de stream niet. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Een instantie van [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) met de opgegeven stream als inhoud. |


### Method: get_extension() {#get_extension__4}


```
 get_extension() 
```

Retourneert de extensie van dit [AbstractPath](/psd/python-net/aspose.gis/abstractpath/).

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | De extensie van deze [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) (inclusief de punt ".") of<br/>            een lege string als de [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) geen extensie heeft. |


### Method: get_file_name() {#get_file_name__5}


```
 get_file_name() 
```

Retourneert de bestandsnaam en extensie van dit [AbstractPath](/psd/python-net/aspose.gis/abstractpath/).

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | De tekens na het laatste [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) teken in de [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/). Als het<br/>            laatste teken het [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) teken is, wordt een lege string geretourneerd. Als er geen<br/>            [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) tekens in de [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) zijn, wordt de [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) zelf<br/>            geretourneerd. |


### Method: get_file_name_without_extension() {#get_file_name_without_extension__6}


```
 get_file_name_without_extension() 
```

Retourneert de bestandsnaam van dit [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) zonder de extensie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | De string die wordt geretourneerd door [AbstractPath.get_file_name()](/psd/python-net/aspose.gis/abstractpath/) minus de laatste punt en alle daaropvolgende tekens. |


### Method: is_file() {#is_file__7}


```
 is_file() 
```

Haalt een waarde op die aangeeft of dit pad naar een bestaand bestand wijst dat geopend kan worden voor lezen.

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | <see langword="true" /> als locatie naar een bestand wijst; <see langword="false" /> anders. |


### Method: list_directory() {#list_directory__8}


```
 list_directory() 
```

Retourneert paden die zich binnen dit <c>AbstractPath</c> bevinden, als het een map is.

**Returns**

| Type | Beschrijving |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPath> | Paden die zich binnen deze <c>AbstractPath</c> bevinden. |


### Method: open(access) {#open_access_9}


```
 open(access) 
```

Abstracteert een reeks open streaming multi‑bestandformaten als een pad voor het benaderen van gegevens.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| toegang | System.IO.FileAccess | Specificeert een subset van bewerkingen die op een stream kunnen worden uitgevoerd. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| _io.BufferedRandom | Dit kan ofwel een   zijn of de stream die oorspronkelijk door de client is doorgegeven. |


### Method: with_extension(new_extension) {#with_extension_new_extension_10}


```
 with_extension(new_extension) 
```

Retourneert een nieuw [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) met de bestandsextensie gewijzigd naar de opgegeven waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_extension | string | Een nieuwe extensie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Een nieuw [AbstractPath](/psd/python-net/aspose.gis/abstractpath/), dat naar een bestand in dezelfde map wijst, maar met een nieuwe extensie. |


