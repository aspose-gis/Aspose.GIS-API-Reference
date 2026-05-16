---
title: "DatabaseExternalSrsSettingsBuilder क्लास"
type: docs
weight: 30
url: /hi/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/
---

**Summary:** Provides the possibility of configuring a database query to retrieve a list of used spatial reference systems.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseExternalSrsSettingsBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [end_external_srs()](#end_external_srs__1) | बाहरी srs की कॉन्फ़िगरेशन पूर्ण करें और पैरेंट कॉन्टेक्स्ट लौटाएँ। |
| [external_srs_fields(auth_srid_field, sr_text_field)](#external_srs_fields_auth_srid_field_sr_text_field_2) | अतिरिक्त अनुरोधित स्पैशियल रेफ़रेंस सिस्टम्स के बारे में जानकारी पढ़ने के लिए विशेष फ़ील्ड नाम निर्दिष्ट करता है। |


### Method: end_external_srs() {#end_external_srs__1}


```
 end_external_srs() 
```

बाहरी srs की कॉन्फ़िगरेशन पूर्ण करें और पैरेंट कॉन्टेक्स्ट लौटाएँ।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: external_srs_fields(auth_srid_field, sr_text_field) {#external_srs_fields_auth_srid_field_sr_text_field_2}


```
 external_srs_fields(auth_srid_field, sr_text_field) 
```

अतिरिक्त अनुरोधित स्पैशियल रेफ़रेंस सिस्टम्स के बारे में जानकारी पढ़ने के लिए विशेष फ़ील्ड नाम निर्दिष्ट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| auth_srid_field | string | स्पैशियल रेफ़रेंस आईडी पढ़ने के लिए फ़ील्ड, डिफ़ॉल्ट: auth_srid। |
| sr_text_field | string | WKT द्वारा दर्शाए गए स्पैशियल कोऑर्डिनेट सिस्टम को पढ़ने के लिए फ़ील्ड, डिफ़ॉल्ट: srtext। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


