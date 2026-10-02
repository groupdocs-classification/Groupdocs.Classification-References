---
title: "계량된"
second_title: "GroupDocs.Classification .NET용 API 레퍼런스"
description: "계량 키를 설정하기 위한 메서드를 제공합니다."
type: docs
weight: 750
url: /ko/net/groupdocs.classification/metered/
---
## Metered class

계량 키를 설정하기 위한 메서드를 제공합니다.

```csharp
public class Metered
```

## 생성자

| 이름 | 설명 |
| --- | --- |
| [Metered](metered)() | 이 클래스의 새 인스턴스를 초기화합니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| [SetMeteredKey](../../groupdocs.classification/metered/setmeteredkey)(string, string) | 계량된 공개 키와 개인 키를 설정합니다 |
| static [GetConsumptionCredit](../../groupdocs.classification/metered/getconsumptioncredit)() | 소비 크레딧을 가져옵니다 |
| static [GetConsumptionQuantity](../../groupdocs.classification/metered/getconsumptionquantity)() | 소비 파일 크기를 가져옵니다 |

### 예제

이 예제에서는 계량된 공개 키와 개인 키를 설정하려고 시도합니다

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### 또 보기

* namespace [GroupDocs.Classification](../../groupdocs.classification)
* assembly [GroupDocs.Classification](../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Classification.dll용 생성됨 -->
