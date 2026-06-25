---
demo:
  title: 役員秘書のデモ
---

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# 役員秘書のデモ

**シナリオ:**

あなたはエグゼクティブ アシスタントであり、経営幹部から、次の幹部会議の前に、最新の決算説明会に関する簡単な概要の作成を依頼されました。あなたは、Copilot を使用して重要なポイントと詳細な分析を完全なトランスクリプトから抜き出し、その資料を話し合いのポイントを含む簡潔なエグゼクティブ サマリーにまとめ、議題の下書きを準備した状態でフォローアップ会議をスケジュールします。

## デモ セットアップ

サンプル ドキュメントは、[こちら](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)の MS-4021 GitHub リポジトリにあります。

このデモに必要な具体的なファイルは次のとおりです。

- [Microsoft_FY24_Second_Quarter_Earnings_Conference_Call_Transcript.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Microsoft_FY24_Second_Quarter_Earnings_Conference_Call_Transcript.docx)

> **注:** これらのファイルがダウンロード後に OneDrive に同期されるまでに最大 10 分かかることがあります。 デモ中の遅延を避けるために、事前にこれらのファイルをダウンロードし OneDrive で使用できるようにしておいてください。 ファイルが使用できない場合は、ドキュメントを開き、デモで使用する共有ファイルリンクをコピーします。

## デモ

### Copilot in Word

まず、最新の収益に関する決算説明会のトランスクリプトを確認し、担当する役員にとって重要なポイントを抜き出します。

1. (ブラウザーまたはデスクトップ アプリケーションの) Word で **Microsoft_FY24_Second_Quarter_Earnings_Conference_Call_Transcript.docx** ファイルを開きます。

    > **注:** 素早くスクロールして、ドキュメントの大きさや手作業で要約する場合はどのくらい時間がかかるのかを確認してみてください。

1. ドキュメントの右下隅にある **[Copilot] アイコン**を選択します。

    ![Word の Copilot アイコン。](../Demos/Media/Open-Copilot-in-Word.png)

1. [Copilot] ペインで **[チャット]** モードに切り替えます。 チャット (編集ではなく) を使うので、チャット ペインに出典付きの返答が表示され、基になるトランスクリプトには手を加えずにすみます。

1. 次のプロンプトを入力します。

    ```text
    Summarize the key points from the Microsoft FY24 Second Quarter Earnings Conference Call.
    ```

1. あなたの上司が、Satya Nadella が話した内容を具体的に知りたがっているとします。 次のプロンプトを入力します。

    ```text
    Provide a brief summary of Satya Nadella's remarks during the earnings call.
    ```

    - 各箇条書きには参照が含まれています。 1 つを選択すると、トランスクリプトの正確なセクションにジャンプします。

1. 詳細なレポートを作成するには、以下のプロンプトを入力します。

    ```text
    Analyze the Microsoft FY24 Second Quarter Earnings Conference Call document to provide a comprehensive report that includes:
    - A summary of the key points from each speaker
    - Identification of the top three growth areas and their contributing factors.
    - A detailed breakdown of the financial performance, including revenue, operating income, and earnings per share.
    - Trends in AI adoption and its influence on Microsoft's business strategy.
    - A comparison of this quarter's performance with the same quarter last year, highlighting significant changes.
    - Key strategic initiatives and future outlook as discussed in the call.
    ```

    > **ヒント:** これは複雑なプロンプトであり、Copilot が応答を生成するのに少し時間がかかる場合があります。

1. Copilot が分析を完了したら、**Copy** アイコンを選択して、結果を次の手順のために保存します。

    ![結果をコピーします。](../Demos/Media/Copilot-in-word-copy-results.png)

### Copilot Chat

Word から提供されるレポートは出発点として最適ですが、ここでは Copilot Chat を使用して、エグゼクティブ サマリーの作成に役立てたいと思います。

1. ブラウザーを開き、[M365copilot.com](https://m365copilot.com/) に移動します。

1. **[Web モード]** が選択されていることを確認します。

    ![[Web モード] タブを示すスクリーンショット。](../Prompts/Media/web-mode.png)

1. Copilot in Word からの応答を、次のプロンプトで Copilot チャットに貼り付けます。

    ```text
    Based on the following information, provide an executive summary on the following information:

    [paste the Word output here]
    ```

    > **注:** コピーしたコンテンツから無関係なテキストをクリーンアップして、わかりやすくします。

1. サマリーを改善して簡潔な形式にします。

    ```text
    Summarize this executive summary into a more concise format by focusing on the most critical insights and metrics for each speaker. Use a structured format with headings and bullet points to improve readability.
    ```

1. 要約に問題がなければ、応答を直接 Word にエクスポートします。 Copilot の応答の一番下で **[その他のオプション (...)]** メニューを選択し、**[Word にエクスポート]** を選択します。

    ![Copilot Chat の応答メニューの [Word にエクスポート] のオプション。](../Demos/Media/export-to-word.png)

    > **注:** Copilot は応答を Word 文書として OneDrive に保存します。 **[Word を開く]** を選択して、新しいブラウザー タブで Word 文書を開きます。

1. エグゼクティブ サマリーが完成したら、Copilot に次のように依頼します。

    ```text
    Based on the summarized executive summary, generate 5-7 concise and impactful talking points my manager can use in their next leadership call. Focus on key achievements, growth areas, and strategic priorities.
    ```

### Copilot in Outlook

このデモでは、Copilot in Outlook を使用して、第 2 四半期の収益に関する電話会議で持ち上がったすべての問題に迅速に対処する態勢を整えるために、役員との会議を設定します。

1. ブラウザーを開いて、[outlook.office.com](https://outlook.office.com/) に移動します。

1. リボンの右側にある **[Copilot]** アイコンを選択します。

1. 次のプロンプトを使用して、同期をスケジュールします。

    ```text
    I need to schedule a 30-minute meeting with [/Pick a colleague] tomorrow afternoon to discuss the Second Quarter Earnings Conference Call. Can you suggest a time that works? If they are unavailable, provide an alternative.
    ```

1. Copilot により、会議の日時が提案されます。 プロンプトには、送信または編集できる予定表アイテムが表示されます。 **[編集して送信]** を選択します。

1. **スケジュール アシスタント**に切り替えて、Copilot によって提案された時間が上司とあなたに都合が良いことを確認します。

1. イベント タブに戻ってから、イベント本文で **[Draft with Copilot]** を選択します。

1. プロンプト ウィンドウで、次のように入力します。

    ```text
    I'm meeting with my boss to discuss key updates and strategic initiatives they missed from the Second Quarter Earnings Conference Call. Create an agenda to discuss financial performance, AI and technology integration, strategic acquisitions, productivity updates, and future outlook.
    ```

1. 必要に応じて、**[保持する]** を選択する前に、**[長くする]**、**[短くする]**、または **[トーンを変更する]** ように Copilot に依頼します。

## 重要なポイント

1 つのデモを通じて、情報量の多い決算説明会を経営者層向けのブリーフィング資料にまとめました。**Copilot in Word** を使用して、重要なポイントと詳細分析をトランスクリプトから直接抽出し、**Copilot Chat** を使用して、話し合いのポイントを含む簡潔なエグゼクティブ サマリーに形成しました。また、**Copilot in Outlook** を使って、すぐに送信できる予定一覧でフォローアップ会議をスケジュールしました。 通常は、午前中いっぱいかかる準備作業が、要点を押さえたエンドツーエンドのワークフローに凝縮されます。

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
