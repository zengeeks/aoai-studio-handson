# Azure OpenAI Studio: On Your Data 体験ハンズオン with Postman

## 💫 概要

Azure OpenAI Studio には、独自のデータをアップロードし、そのデータをもとに回答を生成するチャットを作成する機能である "On Your Data" があります。

- [独自のデータに基づく Azure OpenAI | Microsoft Learn](https://learn.microsoft.com/ja-jp/azure/ai-services/openai/concepts/use-your-data)

このハンズオンでは、この "On Your Data" を体験するハンズオンとなります。

このハンズオンを通して以下の内容を学ぶことができます。

- Azure OpenAI Studio の基本的な使い方
- On Your Data の構成方法
- **Postman** を使った REST API のアクセス方法の基礎と Tips

### ※ Postman について

Postman は、API を構築および使用するための API プラットフォームです。Postman は API ライフサイクルの各ステップを簡素化し、コラボレーションを合理化することで、より優れた API をより迅速に作成できるようにします。今回はこの Postman を使って API をコールする方法を実践します。

<br>

## 🚧 Azure のリソース作成時の注意

**※ 今回のハンズオンでは、Auzre のリソースを作成することで料金が発生するリソースもあります。ご自身の状況に応じて、今回のハンズオンの最後にリソースグループごとすべて消すなどの対応は、自己責任で行なってください。**

<br>

## 🔖 ハンズオンの構成

ハンズオン構成は以下です。

タイトル | 概要
--- | ---
🧪 0. Azure OpenAI Service のセットアップ | Azure OpenAI のリソースをセットアップします。
🧪 1. Cognitive Search のセットアップ | Azure Cognitive Search のリソースをセットアップします。
🧪 2. Storage account のセットアップ | Azure Storage Account のリソースをセットアップします。
🧪 3. On Your Data で独自のデータを活用して回答を生成 | Azure OpenAI Studio から On Your Data をセットアップし、正しく回答が得ることができるかを実践します。
🧪 4. Postman を利用した API のコール | Postman を使って Azur OpenAI の API をコールする方法を実践します。
(Option)<br>🧪 5. On Your Data のデプロイ | On Your Data で作成したチャットをデプロイしてチャットの利用を実践します。
リソースの削除 | リソースグループからリソースの削除をする方法を紹介します。

<br>

## 🛠️ 事前準備

### Azure のサブスクリプション

このハンズオンでは、Azure で以下のリソースを作成します。そのためハンズオンを開始する前に Azure サブスクリプションの準備と以下のリソースが作成できることをご確認ください。

- Azure OpenAI Service
- Cognitive Search
- Storage Account

### Postman

Postman をダウンロードしてインストールします。無料で利用が可能ですが、はじめての場合は Sign up が必要になります。  

- [Postman | The Collaboration Platform for API Development](https://www.postman.com/)

※ 諸事情でインストールが許容できない場合、Postman のハンズオンをスキップして進めることも可能です。

<br>

## 🧑‍💻 Let's Get Started

以下のリンクからハンズオンの旅に出発しょう🚀

- [🧪 0. Azure OpenAI Service のセットアップ](./setup-azure-openai.md)
