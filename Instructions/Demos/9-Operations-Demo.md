---
demo:
  title: 運用のデモ
---

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# 運用のデモ

## シナリオ

あなたは Contoso の 運用マネージャーで、ベンダー調達とプロジェクト実行を担当しています。 あなたの目標は、過去の RFP を確認し、主要な選択基準を抽出し、今度のイニシアチブの新しい RFP の下書きを作成することです。

## デモ セットアップ

サンプル ドキュメントは、[こちら](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)の MS-4021 GitHub リポジトリにあります。

このデモに必要な具体的なファイルは次のとおりです。

- [Contoso_Completed_RFP.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Completed_RFP.docx)

- [Project_Guidelines_Contoso.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Project_Guidelines_Contoso.docx)

- [Contoso_RFP_Template.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_RFP_Template.docx)

> **注:** これらのファイルがダウンロード後に OneDrive に同期されるまでに最大 10 分かかることがあります。 デモ中の遅延を避けるために、事前にこれらのファイルをダウンロードし OneDrive で使用できるようにしておいてください。 ファイルが使用できない場合は、ドキュメントを開き、デモで使用する共有ファイルリンクをコピーします。

## デモ

### Word の Copilot

まず、Copilot in Word に提案依頼書 (RFP) に関する質問をいくつかします。

1. (Web ブラウザーまたはデスクトップ アプリケーションの) Word を開きます。
1
1. ドキュメント [Contoso_Completed_RFP.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Completed_RFP.docx) を開きます。

1. Word リボンで Copilot アイコンを選択して、[チャット] ペインを開きます。

    ![作業モード タブを示すスクリーンショット。](../Demos/Media/copilot-ribbon-word.png)

1. [チャット] ペインで、プロンプトを選択または入力します。

   ```text
   Summarize this document
   ```

1. 次に、以下のプロンプトを入力します。

   ```text
   Analyze this document and generate a categorized list of required items needed to create an RFP.
   ```

1. 次に、次のように入力して RFP テンプレートを作成するように Copilot に依頼します。

   ```text
   Analyze this document and create an RFP template based on the content.
   ```

    > **注:** 次のデモでは事前に作成されたテンプレート ドキュメントを使用するので、生成されたコンテンツをコピーする必要はありません。 ただし、対象者に関係がある場合は、Copilot の応答をコピーしたりドキュメントに挿入したりする方法を紹介できます。

### Copilot Chat

これで RFP ドキュメントを要約し、RFP テンプレートを作成したので、Copilot Chat を使用して、新しい RFP のプロジェクト要件を要約しましょう。

1. ブラウザーを開き、[M365copilot.com](https://m365copilot.com/) に移動します。  

1. **[Web モード]** が選択されていることを確認します。

    ![[Web モード] タブを示すスクリーンショット。](../Prompts/Media/web-mode.png)

1. 次のプロンプトを入力します。

   ```text
   Summarize [Project_Guidelines_Contoso.docx] highlighting the key objectives, scope, implementation timeline, budget, compliance needs, and vendor selection criteria in a bulleted list.
   ```

    > **注:** 角かっこは、ドキュメントが参照されていることを示します。 リンク [Project_Guidelines_Contoso.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Project_Guidelines_Contoso.docx) を使用します

1. 次に、ベンダーの選定基準を抽出するように Copilot に依頼します。

   ```text
   Extract and summarize the key vendor selection criteria from this document, including weight percentages and evaluation factors.
   ```

1. 次に、プロジェクトのガイドラインに基づいて RFP を作成するように Copilot に依頼します。

   ```text
   Using the project requirements outlined above, draft an RFP using the following template: [Contoso_RFP_Template.docx].
   ```

    > **注:** 角かっこは、ドキュメントが参照されていることを示します。

1. **生成された RFP** をクリップボードにコピーして、次のデモで使用できるようにします。

1. 必要に応じて、生成された RFP を Word 文書にエクスポートするように Copilot に依頼します。

### Copilot in Outlook

最後に、Copilot in Outlook を使用して、RFP ドキュメントを要約した、候補となるサプライヤーへのメールを下書きします。

1. (Web ブラウザーまたはデスクトップ アプリケーションの) Outlook を開きます。

1. **[新しいメール]** を選択します。

1. リボンの **[Copilot]** を選択します。 ドロップダウン メニューから **[Copilot で下書き]** を選択します。

1. "**メールに書きたい内容**" プロンプト ウィンドウで、次のように入力します。

   ```text
   Draft an email to potential suppliers summarizing the RFP below:

   [paste contents of RFP]
   ```

    > **注:** 前のデモからコピーした RFP コンテンツを貼り付けます。

1. 下書きが生成されたら、**調節**機能を使用して、トーン、長さ、または形式レベルを変更できます。

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
