---
title: "AbstractPath.Open"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة AbstractPath. تفتح هذا AbstractPath كملف"
type: docs
weight: 120
url: /ar/net/aspose.gis/abstractpath/open/
---
## AbstractPath.Open method

يفتح هذا `AbstractPath` كملف.

```csharp
public abstract Stream Open(FileAccess access)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الوصول | FileAccess | يحدد مجموعة فرعية من العمليات التي يمكن إجراؤها على الـ Stream. |

### قيمة الإرجاع

دفق تم فتحه باستخدام FileAccess المحدد.

## ملاحظات

إذا كان *access* يحتوي على علامة Write مُفعَّلة، ولم يكن الملف موجودًا، يجب على المُورِّث إنشاءه. يمكن فتح `AbstractPath` عدة مرات بواسطة `Aspose.GIS`. هذا مطلوب لقراءة ملف بشكل مستقل باستخدام تدفقات متعددة. لا ينبغي عليك تخزين النتيجة مؤقتًا بل يجب إرجاع تدفق جديد في كل مرة يتم فيها استدعاء هذه الطريقة.

### انظر أيضًا

* class [AbstractPath](../)
* namespace [Aspose.Gis](../../abstractpath/)
* assembly [Aspose.GIS](../../../)


