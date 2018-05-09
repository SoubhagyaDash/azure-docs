---
title: Microsoft Translator Text API overview - Azure Cognitive Services  | Microsoft Docs
description: Integrate the Microsoft Translator Text API into your applications, websites, tools, and other solutions to provide multi-language user experiences.
services: cognitive-services
author: noellelacharite
manager: nolachar
ms.service: cognitive-services
ms.component: translator-text
ms.topic: overview
ms.date: 05/03/2018
ms.author: nolachar
---

# What is Microsoft Translator?

The Microsoft Translator Text API can be seamlessly integrated into your applications, websites, tools, or other solutions to provide multi-language user experiences in more than 60 languages. It can be used on any hardware platform and with any operating system to perform text to text language translation.

Microsoft Translator Text API is part of the Microsoft [Cognitive Services API](https://docs.microsoft.com/azure/#pivot=products&panel=ai) collection of machine learning and AI algorithms in the cloud, readily consumable in your development projects.

## About Microsoft Translator

Microsoft Translator is a cloud-based machine translation service. At the core of this service are the Translator Text API and [Translator Speech API](https://www.microsoft.com/en-us/translator/speech.aspx) which power various Microsoft products and services and are used by thousands of businesses worldwide in their applications and workflows, allowing their content to reach a worldwide audience.

Learn more about the [Microsoft Translator service](https://www.microsoft.com/en-us/translator/home.aspx)

## Language customization

An extension of the core Microsoft Translator service, the Microsoft Translator Hub, can be used in conjunction with the Translator Text API to help you customize the translation system and improve the translation for your specific terminology and style.

With the Microsoft Translator Hub, you can build translation systems that handle the terminology used in your own business or industry. Your customized translation system will then easily integrate into your existing applications, workflows, and websites, across multiple types of devices, through the regular Microsoft Translator Text API, by using the category parameter. The Hub customizes the statistical translation systems.

Learn more about [language customization](customization.md)

## Microsoft Translator Neural Machine Translation (NMT)

Microsoft Translator has used statistical machine translation (SMT) technology to provide translations. The technology has reached a plateau in terms of performance improvement. Translation quality is no longer improving in any significant way for generic systems with SMT. A new AI-based translation technology is gaining momentum based on Neural Networks (NN).

NMT provides better translations not only from a raw translation quality scoring standpoint but also because they will sound more fluent, more human, than SMT ones. The key reason for this fluidity is that NMT uses the full context of a sentence to translate words. SMT only takes the immediate context of a few words before and after each word.

NMT models are at the core of the API and are not visible to end users.
The only noticeable differences are

- The improved translation quality, especially for languages such as Chinese, Japanese, and Arabic. View supported languages on [Microsoft.com](https://www.microsoft.com/en-us/translator/languages.aspx).
- The incompatibility with the existing Hub customization features

Learn more about [how NMT works](https://www.microsoft.com/en-us/translator/mt.aspx#nnt)

## Next steps

- Read about [pricing details](https://azure.microsoft.com/pricing/details/cognitive-services/translator-text-api/).

- [Sign up](translator-text-how-to-signup.md) for an access key.

- [Quickstart](quickstarts/csharp.md) is a walkthrough of the REST API calls written in C#. Learn how to translate text from one language to another with minimal code.

- [API reference documentation](https://aka.ms/translator-text-api) provides the technical documentation for the APIs.

## See also

- [Cognitive Services Documentation page](https://docs.microsoft.com/azure/#pivot=products&panel=ai)
- [Cognitive Services Product page](https://azure.microsoft.com/services/cognitive-services/)
- [Solution and pricing information](https://www.microsoft.com/en-us/translator/default.aspx)
