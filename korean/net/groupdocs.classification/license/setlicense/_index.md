---
title: "SetLicense"
second_title: "GroupDocs.Classification .NET용 API 레퍼런스"
description: "구성 요소에 라이선스를 적용합니다."
type: docs
weight: 20
url: /ko/net/groupdocs.classification/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

구성 요소에 라이선스를 적용합니다.

```csharp
public void SetLicense(string licenseName)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| licenseName | String | 전체 또는 짧은 파일 이름이나 포함된 리소스 이름일 수 있습니다. 빈 문자열을 사용하면 평가 모드로 전환됩니다. |

### 비고

다음 위치에서 라이선스를 찾으려고 시도합니다:

1. 명시적 경로.

2. Aspose 구성 요소 어셈블리를 포함하는 폴더.

3. 클라이언트의 호출 어셈블리를 포함하는 폴더.

4. 엔트리(시작) 어셈블리를 포함하는 폴더.

5. 클라이언트의 호출 어셈블리 내에 포함된 리소스.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. 명시적 경로.

2. 클라이언트의 호출 어셈블리 내에 포함된 리소스.

### 또 보기

* class [License](../../license)
* namespace [GroupDocs.Classification](../../license)
* assembly [GroupDocs.Classification](../../../)

---

## SetLicense(Stream) {#setlicense}

구성 요소에 라이선스를 적용합니다.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Type | 설명 |
| --- | --- | --- |
| stream | Stream | 라이선스를 포함하는 스트림. |

### 비고

스트림에서 라이선스를 로드하려면 이 메서드를 사용하십시오.

### 또 보기

* class [License](../../license)
* namespace [GroupDocs.Classification](../../license)
* assembly [GroupDocs.Classification](../../../)

<!-- 수정 금지: xmldocmd에 의해 GroupDocs.Classification.dll용 생성됨 -->
