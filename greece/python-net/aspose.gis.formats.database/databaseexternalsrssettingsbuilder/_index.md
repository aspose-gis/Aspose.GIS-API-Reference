---
title: "DatabaseExternalSrsSettingsBuilder Κλάση"
type: docs
weight: 30
url: /el/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/
---

**Summary:** Provides the possibility of configuring a database query to retrieve a list of used spatial reference systems.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseExternalSrsSettingsBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [end_external_srs()](#end_external_srs__1) | Ολοκληρώστε τη διαμόρφωση του εξωτερικού srs και επιστρέψτε το γονικό πλαίσιο. |
| [external_srs_fields(auth_srid_field, sr_text_field)](#external_srs_fields_auth_srid_field_sr_text_field_2) | Καθορίζει ειδικά ονόματα πεδίων από τα οποία διαβάζονται πληροφορίες σχετικά με επιπλέον αιτούμενα συστήματα αναφοράς χώρου. |


### Method: end_external_srs() {#end_external_srs__1}


```
 end_external_srs() 
```

Ολοκληρώστε τη διαμόρφωση του εξωτερικού srs και επιστρέψτε το γονικό πλαίσιο.

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: external_srs_fields(auth_srid_field, sr_text_field) {#external_srs_fields_auth_srid_field_sr_text_field_2}


```
 external_srs_fields(auth_srid_field, sr_text_field) 
```

Καθορίζει ειδικά ονόματα πεδίων από τα οποία διαβάζονται πληροφορίες σχετικά με επιπλέον αιτούμενα συστήματα αναφοράς χώρου.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| auth_srid_field | string | Πεδίο για ανάγνωση του αναγνωριστικού αναφοράς χώρου, προεπιλογή: auth_srid. |
| sr_text_field | string | Πεδίο για ανάγνωση του συστήματος συντεταγμένων χώρου που αναπαρίσταται από WKT, προεπιλογή: srtext. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


