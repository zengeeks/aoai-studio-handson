# 🧪 1. Azure AI Search のセットアップ

Azure の AI Search は、フルテキスト検索やベクター検索などの検索機能を提供するフルマネージドの PaaS です。ここでは、On your Data で利用する AI Search のリソースを作成します。

## 1-1. AI Search のリソース作成

Azure portal (`portal.azure.com`) を開き、上部の検索で「ai search」と入力して表示される "AI Search" をクリックします。

![](./images/1-1-1.png)

<br>

AI Search の一覧が表示されますので、"作成" をクリックします。

![](./images/1-1-2.png)

<br>

以下を参考に入力し、"確認および作成" をクリックします。

 No. | 項目 | 入力内容
---: | --- | ---
1 | サブスクリプション | 任意のサブスクリプションを選択します。
2 | リソースグループ | Azure OpenAI Service を作成したときに作ったリソースグループを選択します。
3 | サービス名 | 任意の名称を入力します。これはグローバルで一意の名称になる必要があります。例:「srch-xxxx-202403」( "xxx" は自分のハンドルネームや任意のプロジェクト名など、その後ろに yyyymm をつけるなどをしてグローバルで一意にします) 。
4 | 場所 | Azure OpenAI Service を作成したときに作ったリソースグループを選択します。
5 | 価格レベル | "基本" (Basic) を選択します。

![](./images/1-1-3-basic.png)

> [!NOTE]
> AI Search における Vector Search 機能は Free プランで利用できるようになりましたが、On Your Data の UI の validation では 2023年10月時点では未対応のため "基本" (Basic) を選択します。

<br>

検証が完了したら、"作成" をクリックします。もしエラーが起きた場合は、エラーの内容を確認して修正してください。

![](./images/1-1-4.png)

<br>

作成は30秒程度でできます。完了したら、"リソースに移動" をクリックします。

![](./images/1-1-5.png)

<br>

## ✨ Congratulations ✨

おめでとうございます🎉。これで AI Search のセットアップは完了です。  
後ほどこの画面から操作をするので、ブラウザのタブは閉じないようにしてください。

次は Storage account のセットアップを行います。

---

[⏮️ 前へ](./setup-azure-openai.md) | [📋 目次](../../README.md) | [⏭️ 次へ](./setup-storage-account.md)
