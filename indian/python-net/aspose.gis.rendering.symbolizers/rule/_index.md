---
title: "Rule क्लास"
type: docs
weight: 90
url: /hi/python-net/aspose.gis.rendering.symbolizers/rule/
---

**Summary:** A user-defined rule for [RuleBasedSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/).

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.Rule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि यह नियम "else-rule" है या नहीं। |
| is_filter_rule | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि यह नियम "filter-rule" है या नहीं। |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | r | फ़ीचर पर लागू करने के लिए सिम्बोलाइज़र। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [create_else_rule(symbolizer)](#create_else_rule_symbolizer_1) | एक नया नियम बनाता है जो फ़ीचर पर सिम्बोलाइज़र लागू करता है जब भी वह किसी फ़िल्टर नियम से मेल नहीं खाता। |


### Method: create_else_rule(symbolizer)  [static] {#create_else_rule_symbolizer_1}


```
 create_else_rule(symbolizer) 
```

एक नया नियम बनाता है जो फ़ीचर पर सिम्बोलाइज़र लागू करता है जब भी वह किसी फ़िल्टर नियम से मेल नहीं खाता।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | लागू करने के लिए सिम्बोलाइज़र। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | नया Rule ऑब्जेक्ट। |


