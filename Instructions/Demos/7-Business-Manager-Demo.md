---
demo:
  title: ビジネス マネージャーのデモ
---

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# ビジネス マネージャーのデモ

**シナリオ:**

販売実績と顧客フィードバックを分析して製品の問題に対処してから、チームと協力して改善の計画を立てます。

## デモのセットアップ

サンプル ドキュメントは、[こちら](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)の MS-4021 GitHub リポジトリにあります。

このデモに必要な具体的なファイルは次のとおりです。

- [EV_Charger_Sales_Analysis_v1.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/EV_Charger_Sales_Analysis_v1.xlsx)

> **注:** これらのファイルがダウンロード後に OneDrive に同期されるまでに最大 10 分かかることがあります。 デモ中の遅延を避けるために、事前にこれらのファイルをダウンロードし OneDrive で使用できるようにしておいてください。 ファイルが使用できない場合は、ドキュメントを開き、デモで使用する共有ファイルリンクをコピーします。

## デモの手順

### Copilot in Excel

1. (ブラウザーまたはデスクトップ アプリケーションで) Excel を起動し、**EV_Charger_Sales_Analysis_v1.xlsx** ファイルを開きます。

1. Excel ファイルの **[製品別売上] タブに移動します。**

1. Excel リボンから **[Copilot]** を選択し、**[アプリ スキル]** を選択して [Copilot] ウィンドウを開きます。

1. Copilot を使用して毎月の収益を計算する:  

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

    - Copilot は条件付き書式を適用し、あなたが望む水準に達していない製品を特定するのを助けます。

1. **[レビュー] タブに移動**して顧客からのフィードバックを分析します。

1. 次のプロンプトを入力して、Copilot に上位の懸念事項を要約してもらいます。

    ```text
    Summarize the top 3 customer concerns we should focus on.
    ```

    - Copilot はフィードバックを分析し、上位 3 つの顧客の懸念事項を示します。 充電速度が新たな問題となっているようです。

1. 次に、このプロンプトを入力して、充電速度に関するレビューを強調表示します。

    ```text
    Highlight reviews that mention issues related to charging speeds.
    ```

    - Copilot は、データセット内のすべての関連レビューを強調表示します。

### Copilot Chat

充電速度の低下を主な問題として特定したので、**Copilot Chat** を使用して問題をさらに調査し、可能な解決策を特定します。

1. ブラウザーを開き、[M365copilot.com](https://m365copilot.com/) に移動します。  

1. **[Web モード]** が選択されていることを確認します。  

    ![[Web モード] タブを示すスクリーンショット。](../Prompts/Media/web-mode.png)

1. この問題に調査するために、次のプロンプトを入力します:
  
    ```text
    Research common issues with EV charger speeds and identify potential causes or solutions. Summarize findings in a format suitable for a business presentation. Highlight any relevant industry benchmarks or competitor data.
    ```

   - Copilot による概要を確認し、必要に応じて、追加のコンテキストまたは最近の傾向を要求します。  

1. 必要に応じて、出力を改善します:
   - EV 充電器の効率に対処する最近の傾向や技術について Copilot に尋ねます:

    ```text
    What are the latest innovations or technologies addressing slow EV charger speeds in 2024?
    ```

   - 競合他社に関するインサイトを要求します:

    ```text
    Assuming competitors in the EV charging market are improving speed by 20% annually, suggest how we could position our CC-2001 and CC-2000 models to stay competitive.
    ```

1. EV 充電器のプロジェクト リーダーに尋ねるために、5 つの戦略的な質問を思い付くように Copilot に依頼します:

    ```text
    Based on this information, suggest 5 strategic questions to ask the product team during our meeting tomorrow. Focus on identifying root causes, assessing risks, and brainstorming potential improvements.
    ```

### Copilot in Outlook

このデモでは、Copilot in Outlook を使用して、EV 充電器の製品ラインを担当するプロジェクト リーダーとの会議を設けて可能な解決策について話し合います。

1. ブラウザーを開いて、[outlook.office.com](https://outlook.office.com.com/) に移動します。

1. Outlook のリボンで [Copilot] アイコンを選択し、[Copilot] ペインを開きます。

1. プロンプト ウィンドウで、次のように入力します。

    ```text
    I need to schedule a meeting with [/Pick a colleague] tomorrow afternoon to discuss the EV charger issue reports. Can you suggest a time that works? If they are unavailable, please suggest an alternative time.
    ```

1. Copilot は、会議の日時を提案する必要があります。 プロンプトに送信または編集できる予定表アイテムが表示されたら、**[編集]** を選択します。

1. スケジュール アシスタントに切り替えて、Copilot によって提案された時間がプロジェクト マネージャーに都合が良いことを示します。 両者とも空いている必要があります。

1. イベント タブに戻ってから、イベント本文で **[Draft with Copilot]** を選択します。

1. プロンプト ウィンドウで、次のように入力します。

    ```text
    Create an agenda for a meeting to discuss slow charging speeds with our CC-2001 and CC-2000 models. Include time for an introduction to the issue, a review of any available data or customer feedback, and a brainstorming session for potential solutions.  
    ```

1. 必要に応じて、**[維持する]** を選択する前に、下書きのアジェンダを長くまたは短くしたり、そのトーンを変更したりするように Copilot に依頼できます。

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
