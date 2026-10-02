---
title: "Измеряемый"
second_title: "GroupDocs.Classification для .NET справочник API"
description: "Предоставляет методы для установки измеряемого ключа."
type: docs
weight: 750
url: /ru/net/groupdocs.classification/metered/
---
## Metered class

Предоставляет методы для установки измеряемого ключа.

```csharp
public class Metered
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Metered](metered)() | Инициализирует новый экземпляр этого класса. |

## Методы

| Имя | Описание |
| --- | --- |
| [SetMeteredKey](../../groupdocs.classification/metered/setmeteredkey)(string, string) | Устанавливает измеряемый публичный и приватный ключ |
| static [GetConsumptionCredit](../../groupdocs.classification/metered/getconsumptioncredit)() | Получает кредит потребления |
| static [GetConsumptionQuantity](../../groupdocs.classification/metered/getconsumptionquantity)() | Получает размер файла потребления |

### Примеры

В этом примере будет предпринята попытка установить измеряемый публичный и приватный ключ

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### См. также

* namespace [GroupDocs.Classification](../../groupdocs.classification)
* assembly [GroupDocs.Classification](../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Classification.dll -->
