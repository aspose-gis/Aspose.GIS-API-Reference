---
title: "License.License"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "License 构造函数。初始化此类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.gis/license/license/
---
## License constructor

初始化此类的新实例。

```csharp
public License()
```

## 示例

在此示例中，将尝试在包含组件的文件夹、包含调用程序集的文件夹、入口程序集的文件夹以及调用程序集的嵌入资源中查找名为 MyLicense.lic 的许可证文件。

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

组件 jar 文件：

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### 另见

* class [License](../)
* namespace [Aspose.Gis](../../license/)
* assembly [Aspose.GIS](../../../)


