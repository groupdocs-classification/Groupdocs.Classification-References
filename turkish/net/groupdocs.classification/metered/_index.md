---
title: "Ölçümlü"
second_title: "GroupDocs.Classification .NET için API Referansı"
description: "Ölçülen anahtarı ayarlamak için yöntemler sağlar."
type: docs
weight: 750
url: /tr/net/groupdocs.classification/metered/
---
## Metered class

Ölçülen anahtarı ayarlamak için yöntemler sağlar.

```csharp
public class Metered
```

## Yapıcılar

| Ad | Açıklama |
| --- | --- |
| [Metered](metered)() | Bu sınıfın yeni bir örneğini başlatır. |

## Yöntemler

| Ad | Açıklama |
| --- | --- |
| [SetMeteredKey](../../groupdocs.classification/metered/setmeteredkey)(string, string) | Ölçümlü genel ve özel anahtarı ayarlar |
| static [GetConsumptionCredit](../../groupdocs.classification/metered/getconsumptioncredit)() | Tüketim kredisini alır |
| static [GetConsumptionQuantity](../../groupdocs.classification/metered/getconsumptionquantity)() | Tüketim dosya boyutunu alır |

### Örnekler

Bu örnekte, ölçümlü genel ve özel anahtarı ayarlamaya çalışılacak

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Ayrıca Bakınız

* namespace [GroupDocs.Classification](../../groupdocs.classification)
* assembly [GroupDocs.Classification](../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Classification.dll için oluşturuldu -->
