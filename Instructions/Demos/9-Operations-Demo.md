---
demo:
  title: 運用のデモ
---

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# 運用のデモ

**シナリオ:**

あなたは Contoso の運用マネージャーで、ベンダー調達とプロジェクトの実行を担当しています。 Copilot を使用して、実際に重要な条件に対して完成した RFP をマイニングし、Contoso テンプレートを使用して新しいプロジェクト ガイドラインから新しい RFP を下書きし、それを 1 つにまとめて候補となるサプライヤーに送信します。

## デモ セットアップ

サンプル ドキュメントは、[こちら](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)の MS-4021 GitHub リポジトリにあります。

このデモに必要な具体的なファイルは次のとおりです。

- [Contoso_Completed_RFP.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Completed_RFP.docx)

- [Project_Guidelines_Contoso.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Project_Guidelines_Contoso.docx)

- [Contoso_RFP_Template.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_RFP_Template.docx)

> **注:** これらのファイルがダウンロード後に OneDrive に同期されるまでに最大 10 分かかることがあります。 デモ中の遅延を避けるために、事前にこれらのファイルをダウンロードし OneDrive で使用できるようにしておいてください。 ファイルが使用できない場合は、ドキュメントを開き、デモで使用する共有ファイルリンクをコピーします。

## デモ

### Copilot in Word

まず、Copilot in Word に提案依頼書 (RFP) に関していくつか質問します。

1. (Web ブラウザーまたはデスクトップ アプリケーションの) Word を開きます。

1. ドキュメント [Contoso_Completed_RFP.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Completed_RFP.docx) を開きます。

1. 文書の右下に表示される **[Copilot] アイコン**を選択します。

    ![Word の Copilot アイコン。](../Demos/Media/Open-Copilot-in-Word.png)

1. [Copilot] ペインで **[編集]** モードから **[チャット]** モードに切り替えます。

1. [チャット] ペインで、プロンプトを選択または入力します。

   ```text
   Summarize this document
   ```

1. 次に、以下のプロンプトを入力します。

   ```text
   Analyze this document and generate a categorized list of required items needed to create an RFP.
   ```

1. **編集モード**に切り替えます

    ![[編集を許可する] が選択されています。](../Demos/Media/allow-editing.png)

1. 次に、次のように入力して RFP テンプレートを作成するように Copilot に依頼します。

   ```text
   Analyze this document and create an RFP template based on the content.
   ```

    > **注:** これは Copilot が完成した RFP を基に、ゼロからテンプレートを作成できることを示しています。 次のセクションでは、時間を節約するために、この出力をコピーせずに、洗練された事前構築済みの Contoso テンプレートに切り替えます。

### Copilot Chat

これで RFP ドキュメントを要約し、Copilot でテンプレートが作成されるしくみを確認したので、Copilot Chat を使用して、新しい RFP のプロジェクト要件を要約しましょう。

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

    > **注:** 角かっこは、ドキュメントが参照されていることを示します。 こちらのリンクを使用します。[Contoso_RFP_Template.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_RFP_Template.docx)

1. **生成された RFP** をクリップボードにコピーして、次のデモで使用できるようにします。

1. 必要に応じて、応答を直接 Word にエクスポートします。 Copilot の応答の一番下で **[その他のオプション (...)]** メニューを選択し、**[Word にエクスポート]** を選択します。

    ![Copilot Chat の応答メニューの [Word にエクスポート] のオプション。](../Demos/Media/export-to-word.png)

### Copilot in Outlook

最後に、Copilot in Outlook を使用して、RFP ドキュメントを要約した、候補となるサプライヤーへのメールを下書きします。

1. (Web ブラウザーまたはデスクトップ アプリケーションの) Outlook を開きます。

1. **[新しいメール]** を選択します。

1. リボンの右側にある **[Copilot]** アイコンを選択します。

1. **[Copilot で編集]** が有効になっていることを確認します。

    ![Outlook の [Copilot で編集] トグル。](../Demos/Media/edit-with-copilot-outlook.png)

1. 次のプロンプトを入力します。

   ```text
   Draft an email to potential suppliers summarizing the RFP below:

   [paste the RFP contents, or type / to reference the Word document you exported in the previous step]
   ```

1. 下書きが生成されたら、トーン、長さ、または丁寧さのレベルを自由に調整できます。

## 重要なポイント

1 つのワークフローで、完全な RFP ループを最初から最後まで実行しました。**Copilot in Word** を使用して完全な RFP から要件と選択条件を抽出し、**Copilot Chat** を使用して新しいプロジェクト ガイドラインを Contoso テンプレートを基に洗練された新しい RFP に変換し、**Copilot in Outlook** を使用して適切なトーンでサプライヤーに送信しました。 通常は数日間にわたるレビュー、下書き作成、メールのやり取りが 1 つの一元的なセッションに凝縮されます。

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
