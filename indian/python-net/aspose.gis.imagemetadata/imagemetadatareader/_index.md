---
title: "ImageMetadataReader क्लास"
type: docs
weight: 30
url: /hi/python-net/aspose.gis.imagemetadata/imagemetadatareader/
---

**Summary:** Class for editing, adding some EXIF tags

**Module:** [aspose.gis.imagemetadata](/psd/python-net/aspose.gis.imagemetadata/)

**Full Name:** aspose.gis.imagemetadata.ImageMetadataReader

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [get_reader(file_name)](#get_reader_file_name_1) | EXIF टैग्स के लिए एक रीडर इंस्टेंस बनाता है |
| [get_reader(stream)](#get_reader_stream_2) | EXIF टैग्स के लिए एक रीडर इंस्टेंस बनाता है |
| [read_data()](#read_data__3) | सभी समर्थित EXIF टैग्स को निकालता है |
| [save(file_name)](#save_file_name_4) | परिवर्तनों के लिए मूल फ़ाइल लॉक होने के कारण नई फ़ाइल में सहेजें |
| [save(file_name, format)](#save_file_name_format_5) | परिवर्तनों के लिए मूल फ़ाइल लॉक होने के कारण नई फ़ाइल में सहेजें |
| [save(stream)](#save_stream_6) | परिवर्तनों को एक अलग स्ट्रीम में सहेजा जा रहा है |
| [save(stream, format)](#save_stream_format_7) | परिवर्तनों को एक अलग स्ट्रीम में सहेजा जा रहा है |
| [set_artist(artist)](#set_artist_artist_8) | EXIF Artist टैग को सहेजना, डेटा को जोड़ना या अधिलेखित करना। |
| [set_description(description)](#set_description_description_9) | EXIF ImageDescription टैग को सहेजना, डेटा जोड़ना या अधिलेखित करना। |
| [set_geo_location(latitude, longitude)](#set_geo_location_latitude_longitude_10) | EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude और GPSLongitude टैग को सहेजना, डेटा जोड़ना या अधिलेखित करना। |
| [set_image_size(width, height)](#set_image_size_width_height_11) | EXIF ImageWidth और ImageHeight टैग को सहेजना, डेटा जोड़ना या अधिलेखित करना। |
| [set_modify_date(modify_date)](#set_modify_date_modify_date_12) | EXIF ModifyDate (DataTime) टैग को सहेजना, डेटा जोड़ना या अधिलेखित करना। |
| [try_get_artist(artist)](#try_get_artist_artist_13) | यह EXIF टैग Artist को खोजने का प्रयास करता है, यदि टैग नहीं मिलता तो यह null लौटाता है |
| [try_get_description(description)](#try_get_description_description_14) | यह EXIF टैग ImageDescription को खोजने का प्रयास करता है, यदि टैग नहीं मिलता तो यह null लौटाता है |
| [try_get_geo_location(geo_location)](#try_get_geo_location_geo_location_15) | यह EXIF टैग सेट GPSLatitudeRef, GPSLongitudeRef, GPSLatitude, GPSLongitude को खोजने का प्रयास करता है, यदि टैग मौजूद नहीं हैं तो यह null लौटाता है |
| [try_get_image_size(image_size)](#try_get_image_size_image_size_16) | यह EXIF टैग सेट ImageWidth और ImageHeight को खोजने का प्रयास करता है, यदि टैग मौजूद नहीं हैं तो यह null लौटाता है |
| [try_get_modify_date(modify_date)](#try_get_modify_date_modify_date_17) | यह EXIF टैग ModifyDate (DataTime) को खोजने का प्रयास करता है, यदि टैग नहीं मिलता तो यह डिफ़ॉल्ट DataTime मान लौटाता है |


### Method: get_reader(file_name)  [static] {#get_reader_file_name_1}


```
 get_reader(file_name) 
```

EXIF टैग्स के लिए एक रीडर इंस्टेंस बनाता है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_name | string | इमेज फ़ाइल का पूरा नाम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | मेटाडेटा रीडर इंस्टेंस |


### Method: get_reader(stream)  [static] {#get_reader_stream_2}


```
 get_reader(stream) 
```

EXIF टैग्स के लिए एक रीडर इंस्टेंस बनाता है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | इमेज डेटा स्रोत स्ट्रीम |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | मेटाडेटा रीडर इंस्टेंस |


### Method: read_data() {#read_data__3}


```
 read_data() 
```

सभी समर्थित EXIF टैग्स को निकालता है

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ImageData](/psd/python-net/aspose.gis.imagemetadata/imagedata) | ImageData जो समर्थित टैग सेट का प्रतिनिधित्व करता है |


### Method: save(file_name) {#save_file_name_4}


```
 save(file_name) 
```

परिवर्तनों के लिए मूल फ़ाइल लॉक होने के कारण नई फ़ाइल में सहेजें

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_name | string | गंतव्य फ़ाइल का पूरा नाम |

### Method: save(file_name, format) {#save_file_name_format_5}


```
 save(file_name, format) 
```

परिवर्तनों के लिए मूल फ़ाइल लॉक होने के कारण नई फ़ाइल में सहेजें

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| file_name | string | गंतव्य फ़ाइल का पूरा नाम |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | सहेजने के लिए फ़ॉर्मेट निर्दिष्ट करता है |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

परिवर्तनों को एक अलग स्ट्रीम में सहेजा जा रहा है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | गंतव्य स्ट्रीम |

### Method: save(stream, format) {#save_stream_format_7}


```
 save(stream, format) 
```

परिवर्तनों को एक अलग स्ट्रीम में सहेजा जा रहा है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| स्ट्रीम | _io.BufferedRandom | गंतव्य स्ट्रीम |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | सहेजने के लिए फ़ॉर्मेट निर्दिष्ट करता है |

### Method: set_artist(artist) {#set_artist_artist_8}


```
 set_artist(artist) 
```

EXIF Artist टैग को सहेजना, डेटा को जोड़ना या अधिलेखित करना।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| कलाकार | string | कलाकार। |

### Method: set_description(description) {#set_description_description_9}


```
 set_description(description) 
```

EXIF ImageDescription टैग को सहेजना, डेटा जोड़ना या अधिलेखित करना।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| विवरण | string | विवरण। |

### Method: set_geo_location(latitude, longitude) {#set_geo_location_latitude_longitude_10}


```
 set_geo_location(latitude, longitude) 
```

EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude और GPSLongitude टैग को सहेजना, डेटा जोड़ना या अधिलेखित करना।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| अक्षांश | double | अक्षांश। |
| देशांतर | double | देशांतर। |

### Method: set_image_size(width, height) {#set_image_size_width_height_11}


```
 set_image_size(width, height) 
```

EXIF ImageWidth और ImageHeight टैग को सहेजना, डेटा जोड़ना या अधिलेखित करना।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| width | इंट | चौड़ाई। |
| ऊँचाई | इंट | ऊँचाई। |

### Method: set_modify_date(modify_date) {#set_modify_date_modify_date_12}


```
 set_modify_date(modify_date) 
```

EXIF ModifyDate (DataTime) टैग को सहेजना, डेटा जोड़ना या अधिलेखित करना।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| modify_date | datetime | संशोधित तिथि। |

### Method: try_get_artist(artist) {#try_get_artist_artist_13}


```
 try_get_artist(artist) 
```

यह EXIF टैग Artist को खोजने का प्रयास करता है, यदि टैग नहीं मिलता तो यह null लौटाता है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| कलाकार | String | कलाकार। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | सफल होने पर True |


### Method: try_get_description(description) {#try_get_description_description_14}


```
 try_get_description(description) 
```

यह EXIF टैग ImageDescription को खोजने का प्रयास करता है, यदि टैग नहीं मिलता तो यह null लौटाता है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| विवरण | String | विवरण। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | सफल होने पर True |


### Method: try_get_geo_location(geo_location) {#try_get_geo_location_geo_location_15}


```
 try_get_geo_location(geo_location) 
```

यह EXIF टैग सेट GPSLatitudeRef, GPSLongitudeRef, GPSLatitude, GPSLongitude को खोजने का प्रयास करता है, यदि टैग मौजूद नहीं हैं तो यह null लौटाता है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| geo_location | [GeoLocation[]](/psd/python-net/aspose.gis.imagemetadata/geolocation) | भौगोलिक स्थान। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | सफल होने पर True |


### Method: try_get_image_size(image_size) {#try_get_image_size_image_size_16}


```
 try_get_image_size(image_size) 
```

यह EXIF टैग सेट ImageWidth और ImageHeight को खोजने का प्रयास करता है, यदि टैग मौजूद नहीं हैं तो यह null लौटाता है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| image_size | [ImageSize[]](/psd/python-net/aspose.gis.imagemetadata/imagesize) | छवि का आकार। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | सफल होने पर True |


### Method: try_get_modify_date(modify_date) {#try_get_modify_date_modify_date_17}


```
 try_get_modify_date(modify_date) 
```

यह EXIF टैग ModifyDate (DataTime) को खोजने का प्रयास करता है, यदि टैग नहीं मिलता तो यह डिफ़ॉल्ट DataTime मान लौटाता है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| modify_date | datetime[] | संशोधित तिथि। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | सफल होने पर True |


