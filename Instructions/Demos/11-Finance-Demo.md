---
demo:
  title: 財務のデモ
---

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# 財務のデモ

**シナリオ:**  

あなたは Contoso の財務アナリストで、EV 充電業界での販売実績と市場での位置付けを評価する業務を担当しています。 あなたの目標は、売上データを分析し、分析情報を生成し、チーム向けのサマリーを準備することです。

## デモ セットアップ

サンプル ドキュメントは、[こちら](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)の MS-4021 GitHub リポジトリにあります。

このデモに必要な具体的なファイルは次のとおりです。

- [EV_Charger_Sales_Analysis_v1.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/EV_Charger_Sales_Analysis_v1.xlsx)

### Copilot in Excel  

Copilot in Excel を使用して、売上データの分析、主要な傾向の特定、財務メトリックの計算を行います。

1. Excel を起動してファイルを開く  

1. (ブラウザーまたはデスクトップ アプリケーションの) Excel で **EV_Charger_Sales_Analysis_v1.xlsx** を開きます。  

1. **[製品別売上]** タブに移動します。  

1. Copilot を使用して、次のプロンプトを入力してテーブルを並べ替えます。  

    ```text
    Sort the table by date in descending order, from the most recent to the oldest entry.
    ```  

    - Copilot がテーブルを並べ替え、データセットを更新します。  
    - 並べ替えの後で **[適用]** を選択します。  

1. "売上合計" 列を挿入する  

    [Copilot] ペインで、次のプロンプトを入力します。  

    ```text
    Add a new column named 'Total Revenue'. Populate it by multiplying 'Units Sold' by 'Product Price' for each row.
    ```  

    - Copilot が新しい列を作成し、数式を適用します。  
    - **[列の挿入]** を選択します。  

1. 2024 年の売上概要テーブルを生成する  

    [Copilot] ペインで、次のプロンプトを入力します。  

    ```text
    Create a summary table for total sales in 2024. The table should include Product ID, total units sold, and total revenue.
    ```  

    - Copilot が概要テーブルを生成します。  
    - **[新しいデータシートに追加]** を選択して、テーブルを別個に格納します。  
    - テーブルに **2024 年のデータのみ**が含まれていることを確認します。  
    - **[製品別売上]** タブに戻るか、Copilot の最後の応答の下にある **[データに戻る]** を選択します。  

1. 最も売れている製品を特定する  

    [Copilot] ペインで、次のプロンプトを入力します。  

    ```text
    Identify the product ID with the highest total revenue in 2024. Provide both total revenue and total units sold for better comparison.
    ```  

    - Copilot がデータセットを分析し、最も売れている製品を表示します。
    - **[製品別売上]** タブに戻るか、Copilot の最後の応答の下にある **[データに戻る]** を選択します。  

1. 売上で顧客を並べ替える

    - Excel で "**顧客**" シートに移動します。

    [Copilot] ペインで、次のプロンプトを入力します。  

    ```text
    Sort the 'Customers' tab by annual revenue in descending order.
    ```  

    - Copilot が**売上高**で顧客を並べ替えます。  
    - 並べ替えの後で **[適用]** を選択します。  

1. 顧客ごとの平均売上を計算する

    次のプロンプトを入力します。  

    ```text
    Calculate the average revenue per customer.
    ```  

    - Copilot が平均を計算し、結果を追加します。  
    - **[行を挿入]** を選択して、平均売上値を格納します。  

1. 最も多くの電力を使用している業界を見つける  

    [Copilot] ペインで、次のプロンプトを入力します。  

    ```text
    Analyze the data to determine which industry has the highest total power consumption. Provide the industry name and total power usage.
    ```  

    - Copilot がデータを処理し、消費電力が最大の業界を返します。

1. ドキュメントを保存します。 ドキュメントから共有 URL をコピーします (自動保存を有効にし、メッセージが表示されたら OneDrive アカウントを選択します)。

    ![リンクを共有します。](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot Chat

Copilot Chat を使用して、財務実績を業界ベンチマークや競合他社と比較します。

1. ブラウザーを開き、[M365copilot.com](https://m365copilot.com/) に移動します。

1. [Web モード] が選択されていることを確認します。

    ![[Web モード] タブを示すスクリーンショット。](../Prompts/Media/web-mode.png)

1. プロンプト ウィンドウで、次のように入力します。

    ```text
    Our total revenue for [EV chargers] exceeded $50,000,000 for firth half of 2024. Compare this to the industry average and provide insights on whether we are above or below industry standards. If possible, include market share estimates and trends
    ```

1. 次に、これを競合他社と比較するように Copilot Chat に依頼します。

    ```text
    Summarize the key financial statements of two major competitors in the [EV charging] industry. Include revenue, net profit, and any other relevant financial insights. If available, provide comparisons to our financial performance.
    ```

1. 最後に、今までのチャット履歴を Word 文書にエクスポートするように Copilot に依頼します。

    ```text
    Export this conversation, including financial insights, to a Word document for further review.
    ```

1. ダウンロードするリンクされたファイルを選択して、ドキュメントを開きます。

1. **編集を有効にする**を選択します。

1. ファイルのタイトルは "**Charging_industry_Financial_Summary.docx**" のようになります。 ドキュメントから共有 URL をコピーします (自動保存を有効にし、メッセージが表示されたら OneDrive アカウントを選択します)。

    ![リンクを共有します。](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot in Word

Copilot in Word を使用して、財務分析情報をチーム向けのメールにまとめます。

1. (Web ブラウザーまたはデスクトップ アプリケーションで) 新しい Word 文書を開きます。

1. "**書きたい内容を記述してください**" と表示されたプロンプト ボックスに、次のように入力します。

    ```text
    Draft an email to my team summarizing the key insights from [Charging_industry_Financial_Summary.docx].
    ```

    > **注:** 前のタスクで作成したCharging_industry_Financial_Summary.docx ファイルを添付するか、共有リンクをプロンプトに直接貼り付けて、関連するコンテンツに Copilot がアクセスできるようにします。

1. Copilot の出力を確認します。 **[保持]** を選択する前に、Copilot に依頼して応答を改善します。

    ```text
    Shorten this email draft
    ```

1. その他に、次のような改善オプションがあります。

    - より専門的なトーンになるように、セクションの言い換えを Copilot に依頼する。
    - セクションを追加して内容を膨らませる。
    - より砕けた表現にする

1. 完了したら、**[保持]** を選択できます。

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
