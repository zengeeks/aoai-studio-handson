# Azure OpenAI Studio: On Your Data / Assisntans 体験ハンズオン

## 💫 概要

このリポジトリでは、Azure OpenAI Studio の機能を使った2種類のハンズオンがあります。興味のある方を選んでトライしましょう。

1. On Your Data ハンズオン
2. Assistants ハンズオン

## 🚧 ハンズオンでの注意事項

> [!CAUTION]
> **今回のハンズオンでは、Auzre のリソースを作成することで料金が発生するリソースがあります。今回のハンズオンの最後にリソースグループごとすべて消すなどの対応は、自己責任で行なってください。**

<br>


## 1. On Your Data ハンズオン

### On Your Data ハンズオンの概要

Azure OpenAI Studio には、独自のデータをアップロードし、そのデータをもとに回答を生成するチャットを作成する機能である "On Your Data" があります。この機能を実践します。

- [独自のデータに基づく Azure OpenAI | Microsoft Learn](https://learn.microsoft.com/ja-jp/azure/ai-services/openai/concepts/use-your-data)

On Your Data のハンズオンを通して以下の内容を学ぶことができます。

- Azure OpenAI Studio の基本的な使い方
- On Your Data の構成方法

### On Your Data ハンズオンの構成

On Your Data のハンズオン構成は以下です。

タイトル | 概要
--- | ---
[🧪 0. Azure OpenAI Service のセットアップ](./docs/setup-azure-openai.md) | Azure OpenAI のリソースをセットアップします。
[🧪 1. Azure AI Search のセットアップ](./docs/setup-ai-search.md) | Azure AI Search のリソースをセットアップします。
[🧪 2. Storage account のセットアップ](./docs/setup-storage-account.md) | Azure Storage Account のリソースをセットアップします。
[🧪 3. On Your Data で独自のデータを活用して回答を生成](./docs/setup-on-your-data.md) | Azure OpenAI Studio から On Your Data をセットアップし、自身でアップロードしたデータをもとに回答を得ることができるかを実践します。
す。
(Option)<br>[🧪 OPTION: On Your Data のデプロイ](./docs/deploy-webapp.md) | On Your Data で作成したチャットをデプロイしてチャットの利用を実践します。
[リソースの削除](./docs/remove-azure-resources.md) | リソースグループからリソースの削除をする方法を紹介します。

<br>


## 2. Assistants ハンズオン

### Assistants ハンズオンの概要

TODO !!!!!

### Assistants ハンズオンの構成

TODO !!!!!



## 🛠️ ハンズオンの事前準備

### Azure のサブスクリプション

このハンズオンでは、Azure で以下のリソースを作成します。そのためハンズオンを開始する前に Azure サブスクリプションの準備と以下のリソースが作成できることをご確認ください。

- Azure OpenAI Service
- AI Search (On Your Data ハンズオン)
- Storage Account (On Your Data ハンズオン)

<br>

## 🧑‍💻 Let's Get Started

以下のリンクからハンズオンの旅に出発しょう🚀

On Your Data ハンズオン:

- [🧪 0. Azure OpenAI Service のセットアップ](./docs/on-your-data/setup-azure-openai.md)

<br>

Assisntans ハンズオン:

- [🧪 0. Azure OpenAI Service のセットアップ](./docs/assistants/setup-azure-openai.md)
