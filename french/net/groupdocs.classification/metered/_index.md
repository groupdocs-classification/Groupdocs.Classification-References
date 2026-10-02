---
title: "Mesuré"
second_title: "Référence API GroupDocs.Classification pour .NET"
description: "Fournit des méthodes pour définir la clé mesurée."
type: docs
weight: 750
url: /fr/net/groupdocs.classification/metered/
---
## Metered class

Fournit des méthodes pour définir la clé mesurée.

```csharp
public class Metered
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [Metered](metered)() | Initialise une nouvelle instance de cette classe. |

## Méthodes

| Nom | Description |
| --- | --- |
| [SetMeteredKey](../../groupdocs.classification/metered/setmeteredkey)(string, string) | Définit la clé publique et privée mesurée |
| static [GetConsumptionCredit](../../groupdocs.classification/metered/getconsumptioncredit)() | Obtient le crédit de consommation |
| static [GetConsumptionQuantity](../../groupdocs.classification/metered/getconsumptionquantity)() | Obtient la taille du fichier de consommation |

### Exemples

Dans cet exemple, une tentative sera faite pour définir la clé publique et privée mesurée

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Voir aussi

* namespace [GroupDocs.Classification](../../groupdocs.classification)
* assembly [GroupDocs.Classification](../../)

<!-- NE PAS MODIFIER : généré par xmldocmd pour GroupDocs.Classification.dll -->
