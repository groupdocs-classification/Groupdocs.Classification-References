---
title: "분류"
second_title: "GroupDocs.Classification .NET용 API 레퍼런스"
description: "텍스트에 대한 감성 분류."
type: docs
weight: 20
url: /ko/net/groupdocs.classification/sentimentclassifier/classify/
---
## SentimentClassifier.Classify method

텍스트에 대한 감성 분류.

```csharp
public ClassificationResponse Classify(string text, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Sentiment)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 텍스트 | String | 분류할 원시 텍스트. |
| bestClassesCount | Int32 | 반환할 최상의 클래스 수. |
| taxonomy | 분류 체계 | 감정 분류 체계 (Sentiment 또는 Sentiment3). |

### 반환 값

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### 예외

| 예외 | 조건 |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | API 예외가 발생했습니다. |

### 또 보기

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* class [SentimentClassifier](../../sentimentclassifier)
* namespace [GroupDocs.Classification](../../sentimentclassifier)
* assembly [GroupDocs.Classification](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Classification.dll용 생성됨 -->
