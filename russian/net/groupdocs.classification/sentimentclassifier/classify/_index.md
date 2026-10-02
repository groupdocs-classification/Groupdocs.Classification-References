---
title: "Классифицировать"
second_title: "GroupDocs.Classification для .NET справочник API"
description: "Классификация настроения для текста."
type: docs
weight: 20
url: /ru/net/groupdocs.classification/sentimentclassifier/classify/
---
## SentimentClassifier.Classify method

Классификация настроения для текста.

```csharp
public ClassificationResponse Classify(string text, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Sentiment)
```

| Parameter | Type | Описание |
| --- | --- | --- |
| текст | String | Исходный текст для классификации. |
| bestClassesCount | Int32 | Количество лучших классов для возврата. |
| taxonomy | Таксономия | Таксономия настроений (Sentiment или Sentiment3). |

### Возвращаемое значение

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Исключения

| исключение | условие |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Произошло исключение API. |

### См. также

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* class [SentimentClassifier](../../sentimentclassifier)
* namespace [GroupDocs.Classification](../../sentimentclassifier)
* assembly [GroupDocs.Classification](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Classification.dll -->
