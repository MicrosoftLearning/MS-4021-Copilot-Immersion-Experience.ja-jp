---
demo:
  title: ビジネス マネージャーのデモ
---

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# ビジネス マネージャーのデモ

**シナリオ:**

あなたは EV 充電器製品ラインのビジネス マネージャーです。四半期ごとの業績数値と、新しい一連の顧客レビューが届いたばかりです。 Copilot を使用して、販売実績を分析し、顧客が実際にどのような不満を抱いているかを明らかにしたあと、その根本的な問題を調査し、戦略的な質問を作り上げ、最後に、すぐに議論できる議題を準備した上で、製品リーダーとの作業セッションをスケジュールします。

## デモ セットアップ

サンプル ドキュメントは、[こちら](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)の MS-4021 GitHub リポジトリにあります。

このデモに必要な具体的なファイルは次のとおりです。

- [EV_Charger_Sales_Analysis_v1.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/EV_Charger_Sales_Analysis_v1.xlsx)

> **注:** これらのファイルがダウンロード後に OneDrive に同期されるまでに最大 10 分かかることがあります。 デモ中の遅延を避けるために、事前にこれらのファイルをダウンロードし OneDrive で使用できるようにしておいてください。 ファイルが使用できない場合は、ドキュメントを開き、デモで使用する共有ファイルリンクをコピーします。

## デモ

### Copilot in Excel

1. (ブラウザーまたはデスクトップ アプリケーションで) Excel を起動し、**EV_Charger_Sales_Analysis_v1.xlsx** ファイルを開きます。

1. Excel ファイルの **[製品別売上]** タブに移動します。

1. ドキュメントの右下隅にある **[Copilot] アイコン**を選択します。

    ![Excel の [Copilot] アイコン。](../Demos/Media/Open-Copilot-in-Excel.png)

1. **[編集を許可する]** がオンになっていることを確認します。

    ![オンになっている [編集を許可する]。](../Demos/Media/allow-editing.png)

1. Copilot を使用して毎月の収益を計算します。

   まず、ビジネスのどのカテゴリが最も収益を上げているかを見てみましょう。 このシートには 3 年間の売上データが含まれており、数千行に月別の製品別の売上が表示されます。 これはルーチン タスクですが、この量のデータは扱いにくい場合があります。 Copilot に、製品別の月次収益をすばやく計算するように依頼できます。

   次のプロンプトを使用します。

   ```text
   Calculate monthly revenue by product and add a column with total revenue - refer to the Prices worksheet.
   ```

    - Copilot は、それを行う方法とタブ間で参照するデータを認識しています。
    - Copilot は、これらの数値をどのように実行するかの計画を作成し、その計画を実行して進捗状況を表示し、到達したソリューションに関してあなたに質問または反復を求めます。
    - **[+ 列の挿入]** をクリックしてから、**[製品別売上]** タブに戻ります。

1. Copilot ペインで次のプロンプトを入力して、Copilot を使用して収益を分析します。

    ```text
    What is the total revenue for each category so far in 2024?
    ```

    - Copilot は数値を実行し、あなたがブックに追加できる横棒グラフを作成します。
    - **[+ 新しいシートに追加]** をクリックしてから、**[製品別売上]** タブに戻ります。

1. 次に、Copilot を使用して、このプロンプトを入力して、売上が低い製品を強調表示します。

    ```text
    Highlight rows where the value in column H is less than $100K.
    ```

    - Copilot は条件付き書式を適用し、あなたが望む水準に達していない製品を特定するのを手助けします。

1. **[レビュー]** タブに移動して、顧客からのフィードバックを分析します。

1. 次のプロンプトを入力して、Copilot に上位の懸念事項を要約してもらいます。

    ```text
    Summarize the top 3 customer concerns we should focus on.
    ```

    - Copilot はフィードバックを分析し、顧客の懸念事項の上位 3 つを表示します。 充電速度が新たな問題となっているようです。

1. 次に、このプロンプトを入力して、充電速度に関するレビューを強調表示します。

    ```text
    Highlight reviews that mention issues related to charging speeds.
    ```

    - Copilot は、データセット内のすべての関連レビューを強調表示します。

### Copilot Chat

重要な問題として充電速度の遅さが特定されたので、**Copilot Chat** を使用して、その問題をさらに調査し、考えられる解決策を特定します。

1. ブラウザーを開き、[M365copilot.com](https://m365copilot.com/) に移動します。

1. **[Web モード]** が選択されていることを確認します。

    ![[Web モード] タブを示すスクリーンショット。](../Prompts/Media/web-mode.png)

1. この問題に調査するために、次のプロンプトを入力します:

    ```text
    Research common issues with EV charger speeds and identify potential causes or solutions. Summarize findings in a format suitable for a business presentation. Highlight any relevant industry benchmarks or competitor data.
    ```

   - Copilot による概要を確認し、必要に応じて、追加のコンテキストや最近の傾向を要求します。

1. 必要に応じて、出力を改善します:
   - EV 充電器の効率に対処する最近の傾向や技術について Copilot に尋ねます:

    ```text
    What are the latest innovations or technologies addressing slow EV charger speeds in 2024?
    ```

   - 競合他社に関するインサイトを要求します:

    ```text
    Assuming competitors in the EV charging market are improving speed by 20% annually, suggest how we could position our CC-2001 and CC-2000 models to stay competitive.
    ```

1. EV 充電器のプロジェクト リーダーに尋ねる戦略的な質問を 5 つ考案するように Copilot に依頼します。

    ```text
    Based on this information, suggest 5 strategic questions to ask the product team during our meeting tomorrow. Focus on identifying root causes, assessing risks, and brainstorming potential improvements.
    ```

### Copilot in Outlook

このデモでは、考えられる解決策について話し合うために、Copilot in Outlook を使用して、EV 充電器の製品ラインを担当するプロジェクト リーダーとの会議を設定します。

1. ブラウザーを開いて、[outlook.office.com](https://outlook.office.com/) に移動します。

1. リボンの右側にある **[Copilot]** アイコンを選択します。

1. プロンプト ウィンドウで、次のように入力します。

    ```text
    I need to schedule a meeting with [/Pick a colleague] tomorrow afternoon to discuss the EV charger issue reports. Can you suggest a time that works? If they are unavailable, please suggest an alternative time.
    ```

1. Copilot は、会議の日時を提案する必要があります。 プロンプトには、送信または編集できる予定表アイテムが表示されます。 **編集**を選択します。

1. **スケジュール アシスタント**に切り替えて、Copilot によって提案された時間がプロジェクト マネージャーにとって都合が良いかどうかを確認します。 両者とも空いている必要があります。

1. イベント タブに戻ってから、イベント本文で **[Draft with Copilot]** を選択します。

1. プロンプト ウィンドウで、次のように入力します。

    ```text
    Create an agenda for a meeting to discuss slow charging speeds with our CC-2001 and CC-2000 models. Include time for an introduction to the issue, a review of any available data or customer feedback, and a brainstorming session for potential solutions.
    ```

1. 必要に応じて、**[保持する]** を選択する前に、**[長くする]**、**[短くする]**、または **[トーンを変更する]** ように Copilot に依頼します。

## 重要なポイント

1 つのワークフローで、未加工の数字から、作業セッションの計画まで進めることができました。まず、**[Copilot in Excel で編集]** を使用して、収益を計算し、不採算製品にフラグを設定し、数千件のレビューに隠されている顧客の最大の懸念事項を明らかにしました。次に、**Copilot Chat** を使用して、根本原因を調査し、競合企業の動向を探求し、鋭い戦略的な質問を作り上げました。さらに、**Copilot in Outlook** を使用して、製品担当リーダーとの会議を設定し、すぐに送信できる議題も準備しました。 以前は数日を要していた調査が、意思決定にすぐに使用できる、焦点を絞った状況説明になりました。

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
