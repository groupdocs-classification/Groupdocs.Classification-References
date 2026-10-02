---
title: "Gemeten"
second_title: "GroupDocs.Classification voor .NET API-referentie"
description: "Biedt methoden om de metered-sleutel in te stellen."
type: docs
weight: 750
url: /nl/net/groupdocs.classification/metered/
---
## Metered class

Biedt methoden om de metered-sleutel in te stellen.

```csharp
public class Metered
```

## Constructors

| Naam | Beschrijving |
| --- | --- |
| [Metered](metered)() | Initialiseert een nieuw exemplaar van deze klasse. |

## Methoden

| Naam | Beschrijving |
| --- | --- |
| [SetMeteredKey](../../groupdocs.classification/metered/setmeteredkey)(string, string) | Stelt de gemeten openbare en privésleutel in |
| static [GetConsumptionCredit](../../groupdocs.classification/metered/getconsumptioncredit)() | Haalt verbruikskrediet op |
| static [GetConsumptionQuantity](../../groupdocs.classification/metered/getconsumptionquantity)() | Haalt verbruik bestandsgrootte op |

### Voorbeelden

In dit voorbeeld wordt geprobeerd de gemeten openbare en privésleutel in te stellen

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Zie ook

* namespace [GroupDocs.Classification](../../groupdocs.classification)
* assembly [GroupDocs.Classification](../../)

<!-- NIET BEWERKEN: gegenereerd door xmldocmd voor GroupDocs.Classification.dll -->
