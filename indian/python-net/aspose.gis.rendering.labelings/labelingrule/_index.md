---
title: "LabelingRule क्लास"
type: docs
weight: 30
url: /hi/python-net/aspose.gis.rendering.labelings/labelingrule/
---

**Summary:** A user-defined rule for [RuleBasedLabeling](/psd/python-net/aspose.gis.rendering.labelings/rulebasedlabeling/).

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LabelingRule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि यह नियम "else-rule" है या नहीं। |
| is_filter_rule | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि यह नियम "filter-rule" है या नहीं। |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | r | फ़ीचर पर लागू करने के लिए लेबलिंग। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [create_else_rule(labeling)](#create_else_rule_labeling_1) | एक नया नियम बनाता है जो फ़ीचर पर लेबलिंग लागू करता है जब भी यह किसी भी फ़िल्टर नियम से मेल नहीं खाता। |


### Method: create_else_rule(labeling)  [static] {#create_else_rule_labeling_1}


```
 create_else_rule(labeling) 
```

एक नया नियम बनाता है जो फ़ीचर पर लेबलिंग लागू करता है जब भी यह किसी भी फ़िल्टर नियम से मेल नहीं खाता।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling) | लागू करने के लिए लेबलिंग। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [LabelingRule](/psd/python-net/aspose.gis.rendering.labelings/labelingrule) | नया LabelingRule ऑब्जेक्ट। |


