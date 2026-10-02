---
title: "计量"
second_title: "GroupDocs.Classification 适用于 .NET API 参考"
description: "提供用于设置计量密钥的方法。"
type: docs
weight: 750
url: /zh/net/groupdocs.classification/metered/
---
## Metered class

提供用于设置计量密钥的方法。

```csharp
public class Metered
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Metered](metered)() | 初始化此类的新实例。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [SetMeteredKey](../../groupdocs.classification/metered/setmeteredkey)(string, string) | 设置计量的公钥和私钥 |
| static [GetConsumptionCredit](../../groupdocs.classification/metered/getconsumptioncredit)() | 获取消费积分 |
| static [GetConsumptionQuantity](../../groupdocs.classification/metered/getconsumptionquantity)() | 获取消费文件大小 |

### 示例

在此示例中，将尝试设置计量的公钥和私钥

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### 另见

* namespace [GroupDocs.Classification](../../groupdocs.classification)
* assembly [GroupDocs.Classification](../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.Classification.dll 生成 -->
