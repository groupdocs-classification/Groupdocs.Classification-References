---
title: "분류"
second_title: "GroupDocs.Classification .NET용 API 레퍼런스"
description: "텍스트를 분류합니다."
type: docs
weight: 20
url: /ko/net/groupdocs.classification/classifier/classify/
---
## Classify(string, int, Taxonomy, PrecisionRecallBalance) {#classify_1}

텍스트를 분류합니다.

```csharp
public ClassificationResponse Classify(string text, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| 텍스트 | String | 분류할 원시 텍스트. |
| bestClassesCount | Int32 | 반환할 최상의 클래스 수. |
| taxonomy | 분류 체계 | 분류에 사용할 분류 체계. |
| precisionRecallBalance | PrecisionRecallBalance | 정밀도와 재현율 사이의 균형: precision, recall 또는 기본값. |

### 반환 값

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### 예외

| 예외 | 조건 |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | API 예외가 발생했습니다. |

### 또 보기

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

---

## Classify(string, string, int, Taxonomy, PrecisionRecallBalance, string) {#classify_2}

파일 이름과 디렉터리 이름으로 문서를 분류합니다.

```csharp
public ClassificationResponse Classify(string filename, string directory, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default, 
    string password = null)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| filename | String | 문서 이름. |
| directory | String | 문서 디렉터리. |
| bestClassesCount | Int32 | 반환할 최상의 클래스 수. |
| taxonomy | 분류 체계 | 분류에 사용할 분류 체계. |
| precisionRecallBalance | PrecisionRecallBalance | 정밀도와 재현율 사이의 균형: precision, recall 또는 기본값. |
| password | String | 문서 비밀번호. |

### 반환 값

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### 예외

| 예외 | 조건 |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | API 예외가 발생했습니다. |

### 또 보기

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

---

## Classify(Stream, string, int, Taxonomy, PrecisionRecallBalance, string) {#classify}

스트림에서 문서를 분류합니다.

```csharp
public ClassificationResponse Classify(Stream stream, string filename = null, 
    int bestClassesCount = 1, Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default, 
    string password = null)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| stream | Stream | 파일 스트림. |
| filename | String | 파일 이름(선택적 파일 유형 식별용). |
| bestClassesCount | Int32 | 반환할 최상의 클래스 수. |
| taxonomy | 분류 체계 | 분류에 사용할 분류 체계. |
| precisionRecallBalance | PrecisionRecallBalance | 정밀도와 재현율 사이의 균형: precision, recall 또는 기본값. |
| password | String | 문서 비밀번호. |

### 반환 값

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### 예외

| 예외 | 조건 |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | API 예외가 발생했습니다. |

### 또 보기

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Classification.dll용 생성됨 -->
