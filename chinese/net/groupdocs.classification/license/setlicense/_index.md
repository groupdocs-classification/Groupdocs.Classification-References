---
title: "SetLicense"
second_title: "GroupDocs.Classification 适用于 .NET API 参考"
description: "为组件授权。"
type: docs
weight: 20
url: /zh/net/groupdocs.classification/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

为组件授权。

```csharp
public void SetLicense(string licenseName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| licenseName | String | 可以是完整或简短的文件名，或嵌入资源的名称。使用空字符串切换到评估模式。 |

### 备注

尝试在以下位置查找许可证：

1. 明确路径。

2. 包含 Aspose 组件程序集的文件夹。

3. 包含客户端调用程序集的文件夹。

4. 包含入口（启动）程序集的文件夹。

5. 客户端调用程序集中的嵌入资源。

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. 明确路径。

2. 客户端调用程序集中的嵌入资源。

### 另见

* class [License](../../license)
* namespace [GroupDocs.Classification](../../license)
* assembly [GroupDocs.Classification](../../../)

---

## SetLicense(Stream) {#setlicense}

为组件授权。

```csharp
public void SetLicense(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 一个包含许可证的流。 |

### 备注

使用此方法从流中加载许可证。

### 另见

* class [License](../../license)
* namespace [GroupDocs.Classification](../../license)
* assembly [GroupDocs.Classification](../../../)

<!-- 请勿编辑：由 xmldocmd 为 GroupDocs.Classification.dll 生成 -->
