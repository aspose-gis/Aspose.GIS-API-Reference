---
title: "License.License"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "منشئ License. يهيئ مثيلًا جديدًا من هذه الفئة"
type: docs
weight: 10
url: /ar/net/aspose.gis/license/license/
---
## License constructor

يُهيئ نسخة جديدة من هذه الفئة.

```csharp
public License()
```

## أمثلة

في هذا المثال، سيتم محاولة العثور على ملف ترخيص يُدعى MyLicense.lic في المجلد الذي يحتوي على المكوّن، وفي المجلد الذي يحتوي على التجميع المستدعي، وفي مجلد التجميع الرئيسي، ثم في الموارد المضمنة للتجميع المستدعي.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

ملف jar المكوّن:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### انظر أيضًا

* class [License](../)
* namespace [Aspose.Gis](../../license/)
* assembly [Aspose.GIS](../../../)


