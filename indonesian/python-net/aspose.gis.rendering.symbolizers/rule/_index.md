---
title: "Kelas Rule"
type: docs
weight: 90
url: /id/python-net/aspose.gis.rendering.symbolizers/rule/
---

**Summary:** A user-defined rule for [RuleBasedSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/rulebasedsymbolizer/).

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.Rule

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| is_else_rule | bool | r | Mendapatkan nilai yang menunjukkan apakah aturan ini adalah "else-rule". |
| is_filter_rule | bool | r | Mendapatkan nilai yang menunjukkan apakah aturan ini adalah "filter-rule". |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | r | Simbolizer yang diterapkan pada fitur. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [create_else_rule(symbolizer)](#create_else_rule_symbolizer_1) | Membuat aturan baru yang menerapkan simbolizer pada fitur setiap kali tidak cocok dengan aturan filter apa pun. |


### Method: create_else_rule(symbolizer)  [static] {#create_else_rule_symbolizer_1}


```
 create_else_rule(symbolizer) 
```

Membuat aturan baru yang menerapkan simbolizer pada fitur setiap kali tidak cocok dengan aturan filter apa pun.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | Simbolizer yang diterapkan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Rule](/psd/python-net/aspose.gis.rendering.symbolizers/rule) | Objek Rule baru. |


