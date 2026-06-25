---
demo:
  title: マーケティングのデモ
---

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# マーケティングのデモ

**シナリオ:**

あなたはラテン アメリカでのミスティック スパイス プレミアム チャイ ティーの発売を準備している、ある飲料ブランドのマーケティング チームに所属しています。 Copilot を使って、商品、トレンド、プロモーションのドキュメントを 1 つの市場分析にまとめ、ラテン アメリカの対象ユーザーに最適なソーシャル キャンペーンの妥当性をテストしてスローガンを作成し、最後に Excel でソーシャルマーケティングデータを詳細に分析し、機会の規模を見積もります。

## デモ セットアップ

サンプル ドキュメントは、[こちら](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)の MS-4021 GitHub リポジトリにあります。

このデモに必要な具体的なファイルは次のとおりです。

- [Promotion_Plan_for_Chai_Tea_in_Latin_America.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Promotion_Plan_for_Chai_Tea_in_Latin_America.docx)

- [Mystic_Spice_Premium_Chai_Tea_product_description.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Mystic_Spice_Premium_Chai_Tea_product_description.docx)

- [Contoso_Chai_Tea_market_trends.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Chai_Tea_market_trends.docx)

- [Contoso_Chai_Tea_social_marketing_trends.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Chai_Tea_social_marketing_trends.xlsx)

> **注:** これらのファイルがダウンロード後に OneDrive に同期されるまでに最大 10 分かかることがあります。 デモ中の遅延を避けるために、事前にこれらのファイルをダウンロードし OneDrive で使用できるようにしておいてください。 ファイルが使用できない場合は、ドキュメントを開き、デモで使用する共有ファイルリンクをコピーします。

## デモ

### Copilot in Word

Copilot in Word を使用して、詳細な市場分析レポートの下書きを作成し、ラテン アメリカ市場に合わせたクリエイティブ マーケティング キャンペーンのアイデアをブレーンストーミングします。

1. (Web ブラウザーまたはデスクトップ アプリケーションの) Word を開きます。

1. **"Copilot で下書きしたい内容を記述してください"** と表示されたプロンプト ボックスに、次のように入力します。

    ```text
    Create a Market Analysis report for Mystic Spice Premium Chai Tea using the attached files. Include the product description, market trend analysis, and a promotion plan for Latin America.

    [Promotion_Plan_for_Chai_Tea_in_Latin_America.docx], [Mystic_Spice_Premium_Chai_Tea_product_description.docx], [Contoso_Chai_Tea_market_trends.docx]
    ```

    > **注:** 角かっこは、ドキュメントが参照されていることを示します。 ドキュメントを参照する場合は、共有リンクを直接貼り付けるか、OneDrive で使用できる場合はファイル名を参照できます。

1. 次に、文書の右下に表示される **[Copilot] アイコン**を選択します。

    ![Word の Copilot アイコン。](../Demos/Media/Open-Copilot-in-Word.png)

1. **[編集を許可する]** が選択されていることを確認します。

    ![[編集を許可する] が選択されています。](../Demos/Media/allow-editing.png)

1. ソーシャル メディア キャンペーンのアイデアを追加する新しいセクションを Copilot に作成させます。

    次のプロンプトを入力します。

    ```text
    Draft a new section for social media campaigns to promote Mystic Spice Premium Chai Tea. Include a brief description of 2-3 campaign ideas, each with a unique focus. For each campaign, provide a tagline that reflects its theme and resonates with our target audience of young professionals and tea enthusiasts.
    ```

1. コンテンツに問題がなければ **[完了]** を選択します。 その後、デモの次の部分で使用するために **LATAM_Market_Analysis.docx** として保存します。

### Copilot Chat

Copilot Chat を使用して、提案されたソーシャル メディア キャンペーンの有効性を評価し、LATAM 市場における文化的関連性に合わせて戦略を調整します。

1. ブラウザーを開き、[M365copilot.com](https://m365copilot.com/) に移動します。

1. **[Web モード]** が選択されていることを確認します。

    ![[Web モード] タブを示すスクリーンショット。](../Prompts/Media/web-mode.png)

1. プロンプト ウィンドウで、次のように入力します。

    ```text
    Review the social media campaigns outlined in the LATAM_Market_Analysis.docx file. Evaluate which campaign might resonate best with the LATAM market based on cultural relevance, target audience preferences, and alignment with regional trends. Provide reasons for your choice and suggest any adjustments to improve its impact.
    ```

    > **注:** プロンプトはまだ送信しないでください。 次の手順に進み、ファイルをアップロードします。

1. **[ソースの追加と管理]** > **[作業コンテンツを追加]** を選択して **LATAM_Market_Analysis.docx** を検索し、プロンプトを送信します。

    ![Copilot Chatの [コンテンツの追加]。](../Demos/Media/add-work-content.png)

    > **注:** ファイルが利用できない場合は **[画像とファイルのアップロード]** を選択して、ファイルを直接アップロードできます。

1. 重点を置くべきキャンペーンの 1 つを Copilot が推奨し、改善の提案をします。 次のプロンプトでは、この新しいアイデアに合うマーケティング キャンペーン スローガンを Copilot に提案してもらいます。

    ```text
    Generate a catchy marketing slogan for the [Campaign name - e.g., 'Morning Motivation'] campaign that highlights its unique value proposition and resonates with the LATAM market. Ensure the slogan reflects a vibrant and culturally relevant tone that appeals to young professionals.
    ```

1. 必要に応じて、最後のプロンプトで、キャンペーンの新しいビデオを生成するように Copilot に依頼できます。

    Copilot でアプリ セレクターを選択し、次に **[エージェントの作成]** を選択します。 **[何を作成しますか?]** の下で、**[動画の作成]** を選択します。 次に、次のプロンプトを入力します。

    ```text
    Create a captivating social media video for Mystic Spice Chai Tea that highlights its unique flavor and vibrant appeal. The video should feature eye-catching visuals, with colors, and themes that resonate with young professionals and tea enthusiasts.
    ```

### Copilot in Excel

次に話題を変えて、Copilot in Excel を使ってソーシャル マーケティングの機会を評価します。基礎となるシートは変更せずに。キャンペーン データに対する質問をします。

1. [Contoso_Chai_Tea_social_marketing_trends.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Chai_Tea_social_marketing_trends.xlsx) をダウンロードしてあることを確認し、ドキュメントを (Web またはデスクトップ アプリケーションの) Excel で開きます。

1. ドキュメントの右下隅にある **[Copilot] アイコン**を選択します。

    ![Excel の [Copilot] アイコン。](../Demos/Media/Open-Copilot-in-Excel.png)

1. [Copilot] ペインで **[編集]** モードから **[チャット]** モードに切り替えます。

1. 次のプロンプトを Excel に入力します。

    ```text
    On average, how many sales do we get per social media campaign view?
    ```

1. 次に、売上とソーシャル メディア エンゲージメントを比較するように Copilot に依頼します。

    ```text
    Can you show a correlation between social media engagement and sales?
    ```

1. 次に、以下のプロンプトを入力します。

    ```text
    How many social media campaign views did we have from September to December?
    ```

## 重要なポイント

一度にキャンペーンを白紙からデータに基づくプランへと移行させました。**Copilot in Word** を使って、商品、トレンド、プロモーションのドキュメントを、新しいソーシャル キャンペーンのアイデアとともに 1 つの市場分析にまとめました。**Copilot Chat** を使って、ラテン アメリカの対象ユーザーに最適なキャンペーンを評価し、文化的に響くスローガンを展開しました。また **Copilot in Excel** で、ソーシャル マーケティング データを精査し、機会を定量化しました。 以前は数日間にわたった調査、下書き作成、分析が、一元的なエンドツーエンドのワークフローに収束されます。

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
