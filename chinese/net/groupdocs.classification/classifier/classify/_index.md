---
title: "Classify"
second_title: "GroupDocs.Classification 适用于 .NET API 参考"
description: "对文本进行分类。"
type: docs
weight: 20
url: /zh/net/groupdocs.classification/classifier/classify/
---
## Classify(string, int, Taxonomy, PrecisionRecallBalance) {#classify_1}

对文本进行分类。

```csharp
public ClassificationResponse Classify(string text, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | String | 待分类的原始文本。 |
| bestClassesCount | Int32 | 要返回的最佳类别数量。 |
| 分类法 | 分类法 | 用于分类的分类法。 |
| precisionRecallBalance | PrecisionRecallBalance | 精确率与召回率之间的平衡：precision、recall 或默认值。 |

### 返回值

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Exceptions

| exception | condition |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | 发生了 API 异常。 |

### 另见

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

---

## Classify(string, string, int, Taxonomy, PrecisionRecallBalance, string) {#classify_2}

按文件名和目录名对文档进行分类。

```csharp
public ClassificationResponse Classify(string filename, string directory, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default, 
    string password = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| filename | String | 文档名称。 |
| directory | String | 文档目录。 |
| bestClassesCount | Int32 | 要返回的最佳类别数量。 |
| 分类法 | 分类法 | 用于分类的分类法。 |
| precisionRecallBalance | PrecisionRecallBalance | 精确率与召回率之间的平衡：precision、recall 或默认值。 |
| password | String | 文档密码。 |

### 返回值

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Exceptions

| exception | condition |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | 发生了 API 异常。 |

### 另见

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

---

## Classify(Stream, string, int, Taxonomy, PrecisionRecallBalance, string) {#classify}

从流中对文档进行分类。

```csharp
public ClassificationResponse Classify(Stream stream, string filename = null, 
    int bestClassesCount = 1, Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default, 
    string password = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 文件流。 |
| filename | String | 文件名（用于可选的文件类型识别）。 |
| bestClassesCount | Int32 | 要返回的最佳类别数量。 |
| 分类法 | 分类法 | 用于分类的分类法。 |
| precisionRecallBalance | PrecisionRecallBalance | 精确率与召回率之间的平衡：precision、recall 或默认值。 |
| password | String | 文档密码。 |

### 返回值

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Exceptions

| exception | condition |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | 发生了 API 异常。 |

### 另见

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.Classification.dll 生成 -->
