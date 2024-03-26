# 🧪 1. Assistants を試す

Azure OpenAI Service で Assisntans の機能を使い、以下の内容を試します。

- Assistants の機能のひとつである Code Interpreter を使ってデータの分析を行います。
- 分析するデータは、kaggle で公開されている [Video Game Sales のデータセット](https://www.kaggle.com/datasets/gregorut/videogamesales) を使います。
  - このデータは、販売本数が 100,000 本を超えるゲームの売上データです。
  - 日本、ヨーロッパ、北米などの地域別、プラットフォーム (プレイステーション2～4や PC、XBOXなど)ごとに売上が記録されています。



Assistants の実行は時間がかかることもあるので、最初にセットアップして質問をしてから、実行中の待ち時間を使って Assisntants の概要を説明します。


TODO:



## 1-1. Assistant のセットアップ

Assistant を、与えた Video Game Sales のデータセットを分析する専門家としてセットアップします。

Azure OpenAI Service で「アシスタント (プレビュー)」をクリック (①) して以下を参考にセットアップします。

- "New" をクリック (②) します。
- "アシスタント名" (③) には「Video Game Sales Analyst」と入力します。
- 手順 (④) には、以下の内容を入力します。

  ```txt
   あなたは、データ分析の専門家です。
   与えられたデータには販売本数が 100,000 本を超えるビデオ ゲームのリストが含まれています。

   フィールドの定義は以下です。

   Rank - Ranking of overall sales
   Name - The games name
   Platform - Platform of the games release (i.e. PC,PS4, etc.)\
   Year - Year of the game's release
   Genre - Genre of the game
   Publisher - Publisher of the game
   NA_Sales - Sales in North America (in millions)
   EU_Sales - Sales in Europe (in millions)
   JP_Sales - Sales in Japan (in millions)
   Other_Sales - Sales in the rest of the world (in millions)
   Global_Sales - Total worldwide sales.  
  ```

- "デプロイ" (④) には、デプロイしたものを選択します。
- "コードインタープリター" のトグル (⑥)をオンにします。
- "ファイルの追加" をクリック (⑦) し、"ローカルファイルをアップロード" をクリックして
