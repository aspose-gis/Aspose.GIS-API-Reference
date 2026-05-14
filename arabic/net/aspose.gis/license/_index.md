---
title: "فئة الترخيص"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "فئة Aspose.Gis.License. توفر طرقًا لترخيص المكوّن."
type: docs
weight: 3410
url: /ar/net/aspose.gis/license/
---
## License class

يوفر طرقًا لتفعيل الترخيص للمكوّن.

```csharp
public class License
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [License](license/)() | يُهيئ نسخة جديدة من هذه الفئة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SetLicense](../../aspose.gis/license/setlicense/#setlicense)(Stream) | يرخص المكوّن. |
| [SetLicense](../../aspose.gis/license/setlicense/#setlicense_1)(string) | يرخص المكوّن. |

## أمثلة

في هذا المثال، سيُحاول العثور على ملف ترخيص باسم MyLicense.lic في المجلد الذي يحتوي على المكوّن، وفي المجلد الذي يحتوي على التجميع المستدعي، وفي مجلد التجميع الرئيسي، ثم في الموارد المدمجة للتجميع المستدعي.

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

* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


