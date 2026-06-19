---
title: "类 Metered"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.Metered 类。提供设置计量密钥的方法"
type: docs
weight: 3420
url: /zh/net/aspose.gis/metered/
---
## Metered class

提供设置计量密钥的方法。

```csharp
public class Metered
```

## 方法

| 名称 | 描述 |
| --- | --- |
| static [GetConsumptionCredit](../../aspose.gis/metered/getconsumptioncredit/)() | 获取消耗积分 |
| static [GetConsumptionQuantity](../../aspose.gis/metered/getconsumptionquantity/)() | 获取消耗文件大小 |
| static [ResetMeteredKey](../../aspose.gis/metered/resetmeteredkey/)() | 移除先前设置的许可证 |
| static [SetMeteredKey](../../aspose.gis/metered/setmeteredkey/)(string, string) | 设置计量公共密钥和私有密钥 |

## 示例

在此示例中，将尝试设置计量公共密钥和私有密钥

```csharp
[C#]

Metered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Metered.SetMeteredKey("PublicKey", "PrivateKey")
```

组件 jar 文件：

```csharp
Metered.setMeteredKey("PublicKey", "PrivateKey");
```

### 另见

* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


