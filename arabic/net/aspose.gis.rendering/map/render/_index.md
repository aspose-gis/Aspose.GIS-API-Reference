---
title: "Map.Render"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Map. تُصوّر الخريطة إلى ملف."
type: docs
weight: 140
url: /ar/net/aspose.gis.rendering/map/render/
---
## Render(string, Renderer) {#render_1}

يصير الخريطة إلى ملف.

```csharp
public void Render(string outputPath, Renderer renderer)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| outputPath | String | مسار ملف الإخراج. |
| renderer | Renderer | المُعالج المستخدم. |

### انظر أيضًا

* class [Renderer](../../renderer/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)

---

## Render(AbstractPath, Renderer) {#render}

يصير الخريطة إلى ملف.

```csharp
public void Render(AbstractPath outputPath, Renderer renderer)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| outputPath | AbstractPath | مسار ملف الإخراج. |
| renderer | Renderer | المُعالج المستخدم. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | أي وسيط `null`. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| [GisException](../../../aspose.gis/gisexception/) | خطأ أثناء معالجة أو قراءة بيانات نظام المعلومات الجغرافية (GIS). |

### انظر أيضًا

* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [Renderer](../../renderer/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)


