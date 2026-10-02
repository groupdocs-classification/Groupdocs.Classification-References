---
title: "Classify"
second_title: "GroupDocs.Classification 适用于 .NET API 参考"
description: "文本的情感分类。"
type: docs
weight: 20
url: /zh/net/groupdocs.classification/sentimentclassifier/classify/
---
## SentimentClassifier.Classify method

文本的情感分类。

```csharp
public ClassificationResponse Classify(string text, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Sentiment)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | String | 待分类的原始文本。 |
| bestClassesCount | Int32 | 要返回的最佳类别数量。 |
| 分类法 | 分类法 | 情感分类法（Sentiment 或 Sentiment3）。 |

### 返回值

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Exceptions

| exception | condition |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | 发生了 API 异常。 |

### 另见

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* class [SentimentClassifier](../../sentimentclassifier)
* namespace [GroupDocs.Classification](../../sentimentclassifier)
* assembly [GroupDocs.Classification](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.Classification.dll 生成 -->
