---
title: "FromDefinitionDataSourceBuilder Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/
---

**Summary:** Provides the ability to configure a data source object

**Module:** [aspose.gis.formats.database.fromdefinition](/psd/python-net/aspose.gis.formats.database.fromdefinition/)

**Full Name:** aspose.gis.formats.database.fromdefinition.FromDefinitionDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | Konfiguriert den Namen des Feldes, das Informationen für das Feature‑Attribut enthält. |
| [build()](#build__2) | Die Methode ruft eine Implementierung von [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) ab. |
| [geometry_field(name)](#geometry_field_name_3) | Konfiguriert den Namen des Feldes, aus dem die Geometrie extrahiert wird. |
| [identity_attribute(name, overwrite_same_key)](#identity_attribute_name_overwrite_same_key_4) | Obligatorische Einstellung, die das Verfolgen von Änderungen ermöglicht. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

Konfiguriert den Namen des Feldes, das Informationen für das Feature‑Attribut enthält.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Name des Datenbankfeldes für das Attribut. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Datentyp, in den Daten aus der Datenbank konvertiert werden sollen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: build() {#build__2}


```
 build() 
```

Die Methode ruft eine Implementierung von [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) ab.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource) | Implementierung von [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) |


### Method: geometry_field(name) {#geometry_field_name_3}


```
 geometry_field(name) 
```

Konfiguriert den Namen des Feldes, aus dem die Geometrie extrahiert wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Name des Geometriefelds. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: identity_attribute(name, overwrite_same_key) {#identity_attribute_name_overwrite_same_key_4}


```
 identity_attribute(name, overwrite_same_key) 
```

Obligatorische Einstellung, die das Verfolgen von Änderungen ermöglicht.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Name | string | Ein Attribut eines Features, das als eindeutige Identifizierung des Features behandelt wird. |
| overwrite_same_key | bool | Wenn dieses Flag auf true gesetzt ist, werden neu hinzugefügte Features mit einer eindeutigen Kennung, die bereits in der Ebene vorhanden ist, <br/>            das aktuelle überschrieben, und die Daten werden als aktualisiert gelesen, wenn Unterschiede gefunden werden.<br/>            Andernfalls wird eine Ausnahme ausgelöst. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


