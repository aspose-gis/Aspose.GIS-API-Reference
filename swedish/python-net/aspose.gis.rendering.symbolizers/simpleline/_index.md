---
title: "SimpleLine-klass"
type: docs
weight: 120
url: /sv/python-net/aspose.gis.rendering.symbolizers/simpleline/
---

**Summary:** Simple line symbolizer.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.SimpleLine

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [SimpleLine()](#SimpleLine__1) | Skapar ny instans. |
| [SimpleLine(other)](#SimpleLine_other_2) | Initierar en ny instans av klassen [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline/). |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| cap_style | [CapStyle](/psd/python-net/aspose.gis.rendering/capstyle) | r/w | Anger hur linjer renderas i sina ändar. |
| färg | System.Drawing.Color | läs/skriv | Anger färg och transparens för linjen. |
| dash_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Anger avståndet från början av en linje till starten av ett streckmönster. |
| dash_pattern | System.Collections.Generic.IEnumerable<Measurement> | läs/skriv | Anger en matris av avstånd som specificerar längderna på alternerande streck och mellanslag<br/>            i streckade linjer. |
| line_join | [LineJoin](/psd/python-net/aspose.gis.rendering/linejoin) | r/w | Bestämmer hur linjer renderas vid skärningspunkten av linjesegment. |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | Den [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) ritar ingenting och hoppar effektivt över rendering av en geometri som den tillämpas på. |
| offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Anger förskjutning från den ursprungliga linjen.<br/>            För ett positivt avstånd kommer förskjutningen att vara på vänster sida av indatalinjen (relativt linjeriktningen).<br/>            För ett negativt avstånd kommer den att vara på höger sida. |
| style | [StrokeStyle](/psd/python-net/aspose.gis.rendering/strokestyle) | r/w | Anger hur symbolens linjer ska ritas. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Anger linjens bredd. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [clone()](#clone__1) | Klonar detta objekt. |


### Constructor: SimpleLine() {#SimpleLine__1}


```
 SimpleLine() 
```

Skapar ny instans.

### Constructor: SimpleLine(other) {#SimpleLine_other_2}


```
 SimpleLine(other) 
```

Initierar en ny instans av klassen [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| other | [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline) | Den andra [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline/) att kopiera data från. |

### Method: clone() {#clone__1}


```
 clone() 
```

Klonar detta objekt.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline) | En klon av denna instans. |


