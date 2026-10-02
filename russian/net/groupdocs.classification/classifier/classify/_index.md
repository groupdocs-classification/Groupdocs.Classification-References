---
title: "Классифицировать"
second_title: "GroupDocs.Classification для .NET справочник API"
description: "Классифицирует текст."
type: docs
weight: 20
url: /ru/net/groupdocs.classification/classifier/classify/
---
## Classify(string, int, Taxonomy, PrecisionRecallBalance) {#classify_1}

Классифицирует текст.

```csharp
public ClassificationResponse Classify(string text, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default)
```

| Parameter | Type | Описание |
| --- | --- | --- |
| текст | String | Исходный текст для классификации. |
| bestClassesCount | Int32 | Количество лучших классов для возврата. |
| taxonomy | Таксономия | Таксономия, используемая для классификации. |
| precisionRecallBalance | PrecisionRecallBalance | Баланс между точностью и полнотой: precision, recall или по умолчанию. |

### Возвращаемое значение

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Исключения

| исключение | условие |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Произошло исключение API. |

### См. также

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

---

## Classify(string, string, int, Taxonomy, PrecisionRecallBalance, string) {#classify_2}

Классифицирует документ по имени файла и имени каталога.

```csharp
public ClassificationResponse Classify(string filename, string directory, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default, 
    string password = null)
```

| Parameter | Type | Описание |
| --- | --- | --- |
| filename | String | Имя документа. |
| directory | String | Каталог документа. |
| bestClassesCount | Int32 | Количество лучших классов для возврата. |
| taxonomy | Таксономия | Таксономия, используемая для классификации. |
| precisionRecallBalance | PrecisionRecallBalance | Баланс между точностью и полнотой: precision, recall или по умолчанию. |
| password | String | Пароль документа. |

### Возвращаемое значение

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Исключения

| исключение | условие |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Произошло исключение API. |

### См. также

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

---

## Classify(Stream, string, int, Taxonomy, PrecisionRecallBalance, string) {#classify}

Классифицирует документ из потока.

```csharp
public ClassificationResponse Classify(Stream stream, string filename = null, 
    int bestClassesCount = 1, Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default, 
    string password = null)
```

| Parameter | Type | Описание |
| --- | --- | --- |
| stream | Stream | Поток файла. |
| filename | String | Имя файла (для необязательной идентификации типа файла). |
| bestClassesCount | Int32 | Количество лучших классов для возврата. |
| taxonomy | Таксономия | Таксономия, используемая для классификации. |
| precisionRecallBalance | PrecisionRecallBalance | Баланс между точностью и полнотой: precision, recall или по умолчанию. |
| password | String | Пароль документа. |

### Возвращаемое значение

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Исключения

| исключение | условие |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Произошло исключение API. |

### См. также

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

<!-- НЕ РЕДАКТИРОВАТЬ: сгенерировано xmldocmd для GroupDocs.Classification.dll -->
