---
title: "Clasificar"
second_title: "Referencia de API de GroupDocs.Classification para .NET"
description: "Clasifica texto."
type: docs
weight: 20
url: /es/net/groupdocs.classification/classifier/classify/
---
## Classify(string, int, Taxonomy, PrecisionRecallBalance) {#classify_1}

Clasifica texto.

```csharp
public ClassificationResponse Classify(string text, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| texto | String | Texto sin procesar para clasificar. |
| bestClassesCount | Int32 | Cantidad de las mejores clases a devolver. |
| taxonomía | Taxonomía | Taxonomía a usar para la clasificación. |
| precisionRecallBalance | PrecisionRecallBalance | Equilibrio entre precisión y exhaustividad: precisión, exhaustividad o predeterminado. |

### Valor de retorno

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Excepciones

| excepción | condición |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Se produjo una excepción de API. |

### Ver también

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

---

## Classify(string, string, int, Taxonomy, PrecisionRecallBalance, string) {#classify_2}

Clasifica documento por nombre de archivo y nombre de directorio.

```csharp
public ClassificationResponse Classify(string filename, string directory, int bestClassesCount = 1, 
    Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default, 
    string password = null)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| filename | String | Nombre del documento. |
| directory | String | Directorio del documento. |
| bestClassesCount | Int32 | Cantidad de las mejores clases a devolver. |
| taxonomía | Taxonomía | Taxonomía a usar para la clasificación. |
| precisionRecallBalance | PrecisionRecallBalance | Equilibrio entre precisión y exhaustividad: precisión, exhaustividad o predeterminado. |
| password | String | Contraseña del documento. |

### Valor de retorno

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Excepciones

| excepción | condición |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Se produjo una excepción de API. |

### Ver también

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

---

## Classify(Stream, string, int, Taxonomy, PrecisionRecallBalance, string) {#classify}

Clasifica documento desde flujo.

```csharp
public ClassificationResponse Classify(Stream stream, string filename = null, 
    int bestClassesCount = 1, Taxonomy taxonomy = Taxonomy.Iab2, 
    PrecisionRecallBalance precisionRecallBalance = PrecisionRecallBalance.Default, 
    string password = null)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | Flujo de archivo. |
| filename | String | Nombre de archivo (para identificación opcional del tipo de archivo). |
| bestClassesCount | Int32 | Cantidad de las mejores clases a devolver. |
| taxonomía | Taxonomía | Taxonomía a usar para la clasificación. |
| precisionRecallBalance | PrecisionRecallBalance | Equilibrio entre precisión y exhaustividad: precisión, exhaustividad o predeterminado. |
| password | String | Contraseña del documento. |

### Valor de retorno

[`ClassificationResponse`](../../../groupdocs.classification.dto/classificationresponse) with classification results.

### Excepciones

| excepción | condición |
| --- | --- |
| [ApiException](../../../groupdocs.classification.exceptions/apiexception) | Se produjo una excepción de API. |

### Ver también

* class [ClassificationResponse](../../../groupdocs.classification.dto/classificationresponse)
* enum [Taxonomy](../../taxonomy)
* enum [PrecisionRecallBalance](../../precisionrecallbalance)
* class [Classifier](../../classifier)
* namespace [GroupDocs.Classification](../../classifier)
* assembly [GroupDocs.Classification](../../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Classification.dll -->
