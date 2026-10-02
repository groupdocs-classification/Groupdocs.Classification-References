---
title: "Medido"
second_title: "Referencia de API de GroupDocs.Classification para .NET"
description: "Proporciona métodos para establecer la clave medida."
type: docs
weight: 750
url: /es/net/groupdocs.classification/metered/
---
## Metered class

Proporciona métodos para establecer la clave medida.

```csharp
public class Metered
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Metered](metered)() | Inicializa una nueva instancia de esta clase. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [SetMeteredKey](../../groupdocs.classification/metered/setmeteredkey)(string, string) | Establece la clave pública y privada medida |
| static [GetConsumptionCredit](../../groupdocs.classification/metered/getconsumptioncredit)() | Obtiene el crédito de consumo |
| static [GetConsumptionQuantity](../../groupdocs.classification/metered/getconsumptionquantity)() | Obtiene el tamaño del archivo de consumo |

### Ejemplos

En este ejemplo, se intentará establecer la clave pública y privada medida

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Ver también

* namespace [GroupDocs.Classification](../../groupdocs.classification)
* assembly [GroupDocs.Classification](../../)

<!-- NO EDITAR: generado por xmldocmd para GroupDocs.Classification.dll -->
