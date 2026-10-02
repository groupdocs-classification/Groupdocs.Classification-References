---
title: "SetLicense"
second_title: "GroupDocs.Classification .NET için API Referansı"
description: "Bileşeni lisanslar."
type: docs
weight: 20
url: /tr/net/groupdocs.classification/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Bileşeni lisanslar.

```csharp
public void SetLicense(string licenseName)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| licenseName | String | Tam veya kısa bir dosya adı ya da gömülü kaynağın adı olabilir. Değerlendirme moduna geçmek için boş bir dize kullanın. |

### Açıklamalar

Lisansı aşağıdaki konumlarda bulmaya çalışır:

1. Açık yol.

2. Aspose bileşen derlemesini içeren klasör.

3. İstemcinin çağıran derlemesini içeren klasör.

4. Giriş (başlangıç) derlemesini içeren klasör.

5. İstemcinin çağıran derlemesindeki gömülü kaynak.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Açık yol.

2. İstemcinin çağıran derlemesindeki gömülü kaynak.

### Ayrıca Bakınız

* class [License](../../license)
* namespace [GroupDocs.Classification](../../license)
* assembly [GroupDocs.Classification](../../../)

---

## SetLicense(Stream) {#setlicense}

Bileşeni lisanslar.

```csharp
public void SetLicense(Stream stream)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| akış | Akış | Lisansı içeren bir akış. |

### Açıklamalar

Bir akıştan lisans yüklemek için bu yöntemi kullanın.

### Ayrıca Bakınız

* class [License](../../license)
* namespace [GroupDocs.Classification](../../license)
* assembly [GroupDocs.Classification](../../../)

<!-- DÜZENLEMEYİN: xmldocmd tarafından GroupDocs.Classification.dll için oluşturuldu -->
