---
title: "XyzTiles.GetTiles"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة XyzTiles. يحمل البلاط وفقًا لمربع الحد المكاني ومستوى التكبير"
type: docs
weight: 40
url: /ar/net/aspose.gis.formats.xyztile/xyztiles/gettiles/
---
## XyzTiles.GetTiles method

يحمّل البلاط وفقًا لمربع الحد المكاني ومستوى التكبير.

```csharp
public IEnumerable<WebTile> GetTiles(int zoom, Extent extent)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| تكبير | Int32 | مستوى التكبير لتحميل البلاط. أعلى مستوى تكبير هو 0. معظم مزودي البلاط لديهم حوالي 22 مستوى تكبير كحد أقصى. |
| مدى | مدى | مربع الحد لتحميل البلاط. سيتم استخدام مرجع الفضاء Wgs84 إذا تم فقدانه. |

### قيمة الإرجاع

بلاط الويب.

### انظر أيضًا

* class [WebTile](../../../aspose.gis.raster.web/webtile/)
* class [Extent](../../../aspose.gis/extent/)
* class [XyzTiles](../)
* namespace [Aspose.Gis.Formats.XyzTile](../../xyztiles/)
* assembly [Aspose.GIS](../../../)


