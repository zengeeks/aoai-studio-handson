# Azure OpenAI Studio: On Your Data / Assistants 体験ハンズオン

## 💫 概要

このリポジトリでは、Azure OpenAI Studio の機能を使った2種類のハンズオンがあります。興味のある方を選んでトライしましょう。

1. **On Your Data ハンズオン**
2. **Assistants ハンズオン**

<br>

> [!CAUTION]
> 今回のハンズオンでは、Azure のリソースを作成することで料金が発生するリソースがあります。今回のハンズオンの最後にリソースグループごとすべて消すなどの対応は、自己責任で行なってください。  
> リソースの削除方法は、それぞれのハンズオンコンテンツの最後に記載があります。

<br>

## 1. On Your Data ハンズオン

### On Your Data ハンズオンの概要

Azure OpenAI Studio には、独自のデータをアップロードし、そのデータをもとに回答を生成するチャットを作成する機能である "On Your Data" の機能を実践します。

- [独自のデータに基づく Azure OpenAI | Microsoft Learn](https://learn.microsoft.com/ja-jp/azure/ai-services/openai/concepts/use-your-data)

On Your Data のハンズオンを通して以下の内容を学ぶことができます。

- Azure OpenAI Studio の基本的な使い方
- On Your Data の構成方法

### On Your Data ハンズオンの構成

On Your Data のハンズオン構成は以下です。

タイトル | 概要
--- | ---
[🧪 0. Azure OpenAI Service のセットアップ](./docs/on-your-data/setup-azure-openai.md) | Azure OpenAI のリソースをセットアップします。
[🧪 1. Azure AI Search のセットアップ](./docs/on-your-data/setup-ai-search.md) | Azure AI Search のリソースをセットアップします。
[🧪 2. Storage account のセットアップ](./docs/on-your-data/setup-storage-account.md) | Azure Storage Account のリソースをセットアップします。
[🧪 3. On Your Data で独自のデータを活用して回答を生成](./docs/on-your-data/setup-on-your-data.md) | Azure OpenAI Studio から On Your Data をセットアップし、自身でアップロードしたデータをもとに回答を得ることができるかを実践します。
す。
(Option)<br>[🧪 On Your Data のデプロイ](./docs/on-your-data/deploy-webapp.md) | On Your Data で作成したチャットをデプロイしてチャットの利用を実践します。
[リソースの削除](./docs/on-your-data/remove-azure-resources.md) | リソースグループからリソースの削除をする方法を紹介します。

<br>

## 2. Assistants ハンズオン

### Assistants ハンズオンの概要

Azure OpenAI Service の機能のひとつである "Assistants" を使って、データ分析の AI アシスタントを作成します。
分析対象のデータとして、Kaggle で公開されている Video Game Sales のデータセットを使用します。

Assistants のハンズオンを通して以下の内容を学ぶことができます。

- Assistants の概要
- Azure OpenAI Studio での Assistants の使い方

### Assistants ハンズオンの構成

タイトル | 概要
--- | ---
[🧪 0. Azure OpenAI Service のセットアップ](./docs/assistants/setup-azure-openai.md) | Azure OpenAI のリソースをセットアップします。
[🧪 1. データ分析のアシスタントを作る](./docs/assistants/try-assistants.md) | Assistants の機能を使ってデータ分析の AI アシスタントを作り上げます。

## 🛠️ ハンズオンの事前準備

### Azure のサブスクリプション

このハンズオンでは、Azure で以下のリソースを作成します。そのためハンズオンを開始する前に Azure サブスクリプションの準備と以下のリソースが作成できることをご確認ください。

- Azure OpenAI Service
- AI Search (On Your Data ハンズオン)
- Storage Account (On Your Data ハンズオン)

<br>

## 🧑‍💻 Let's Get Started

以下のリンクからハンズオンの旅に出発しょう🚀

- [On Your Data ハンズオンを開始する🏃‍♀️](./docs/on-your-data/setup-azure-openai.md)
- [Assistants ハンズオンを開始する🏃](./docs/assistants/setup-azure-openai.md)


