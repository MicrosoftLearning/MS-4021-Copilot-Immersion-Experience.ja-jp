---
demo:
  title: リサーチ ツールとアナリストのデモ
---

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# リサーチ ツールとアナリストのデモ

このデモでは特に、Copilot アプリに組み込まれている 2 つのエキスパート エージェントである**リサーチ ツール**と**アナリスト**の使い方を見ていきます。  

- **リサーチ ツール**は、Web データと会社のファイルや知識を組み合わせて、複数ステップの研究タスクに取り組むのに役立ちます。  
- **アナリスト**は熟練したデータ サイエンティストのように思考し、ユーザーがコーディング方法を知らない場合でも、高度なデータ分析と Python の実行を行えます。  

## デモ セットアップ

これらのデモを最後まで行うには、必要なすべてのファイルとリソースを含む [Researcher and Analyst Demo - Content Pack](https://microsoft.sharepoint.com/:u:/r/teams/MTTCentral/Immersion%20Experience%20Source%20Control/MS-4021%20Copilot%20Immersion%20Experience/Demos/Agent%20Demo%20Sample%20Docs/Researcher%20and%20Analyst%20Demo%20-%20Content%20Pack.zip?csf=1&web=1&e=384sFW) をダウンロードする必要があります。  

> **ヒント:** デモを行う前に、デモ環境に SharePoint サイトを作成してすべてのファイルを格納すると、簡単にアクセスできます。 または、ファイルをローカル環境に保存し、**/** を使ってプロンプトで直接参照することもできます。  

これらのエージェントにアクセスするには:  

- [m365.cloud.microsoft](https://m365.cloud.microsoft) から **Copilot アプリ**を開きます。  
- ナビゲーション ウィンドウで **[リサーチ ツール]** または **[アナリスト]** を選びます。  

> **注:**  典拠とする分析情報を得るには、リサーチ ツールとアナリストで内部ファイル (SharePoint/OneDrive) を参照する必要があります。

---

## 話題

- **リサーチ ツール**は高給のコンサルタントのように機能し、内部ファイル、競合他社のインテリジェンス、Web ソースを組み合わせて、構造化されて適切に引用された成果物を構築できます。  
- **アナリスト**はデータ サイエンティストが身近にいるようなもので、モデルの構築、Python コードの実行、傾向の視覚化などを即座に行います。  
- どちらのエージェントも推論を隠さず説明するので、ユーザーは結果を検証できます。  
- また、それらを使うとマーケティング計画、顧客のセグメント化、財務予測などの戦略的な作業に要する時間が短縮されるため、自信を持ってより速く先に進むことができます。  

---

## デモの手順

### リサーチ ツール: マーケティング計画を作成する

> **重要:** リサーチ ツールが十分に時間をかけて最初のプロンプトを作成できるよう、ステップ 1 から 4 は (スライド 5 で示されているように) トレーニングの開始時に済ませておく必要があります。

1. ナビゲーション ウィンドウから **[リサーチ ツール]** を開きます。  

    ![M365 Copilot メニューで選ばれた [リサーチ ツール] を示すスクリーンショット。](../Prompts/Media/researcher.png)  

1. 次のプロンプトを入力します。

    ```text
    Create a marketing plan for our newest SprintCycle EV charger launch. 
    Emphasize its AI-powered adaptive charging, modular design, and biometric access control. 
    Make sure to include recommendations on the right digital channels and content strategy. 
    Include insights from competitors and our past GTM campaigns.
    ```

1. `/` (SharePoint/OneDrive を指します) を使って参照ファイルを添付します。  

   - **/SprintCycle Charger Product Launch.docx**  
   - *(省略可能)* **/Contoso - PedalPerks GTM Plan.docx**  

1. **送信**を選択します。  

リサーチ ツールは次のことを行います。  

- 内部ファイルと Web の両方からのインサイトを結合します。  
- チャネルとコンテンツ戦略に関する推奨事項を含むマーケティング計画を構成します。  
- ソースを引用して、ユーザーがその作業を検証できるようにします。  

> **注:**  リサーチ ツールはその推論の過程 ("思考の連鎖") を示し、必要に応じて他のエージェントを呼び出すことができます。  

### アナリスト: 顧客のセグメント化と財務モデリング

**注:**  このデモは Executive バージョンのコンテンツでは実行されません。代わりに、**Copilot Studio** のデモに進んでください。

1. ナビゲーション ウィンドウから **[アナリスト]** を選びます。

    ![M365 Copilot メニューで選ばれた [アナリスト] を示すスクリーンショット。](../Prompts/Media/analyst.png)  

1. 次のプロンプトを入力します。

    ```text
    Find the right customer segment and demographic to sell our new EV charger, 
    include a graph to show how this will maximize our market opportunity.
    ```

1. **+** を使ってファイルを添付します。  

   - **BoulderEV ebike Internal Market Forecast.xlsx**  

    ![アナリストでの添付ファイルを示すスクリーンショット。](../Prompts/Media/Analyst-Attach-Files.png)  

1. **[送信]** をクリックします。  

アナリストは次のことを行います。  

- データセットを分析します。  
- 価値の高い顧客セグメントを特定します。  
- 推奨事項の裏付けとなる視覚化を提供します。  

### アナリストのその他のシナリオ

さらに次のようなさまざまなプロンプトを実行できます。 いずれも同じパターンに従います。**プロンプト → ファイルの添付 → 送信 → 結果の確認。**

- **財務予測**  

    ```text
    Build a 5-year financial projection from this data along with a graph to view revenue growth over time.
    ```  

    ファイル:**BoulderEV ebike Internal Market Forecast.xlsx**  

- **販売実績**  

    ```text
    Analyze sales volume across locations to identify our highest and lowest performing stores, 
    along with a visualization of the best-selling products.
    ```  

    ファイル:**BoulderEV ebike Internal Market Forecast.xlsx**  

- **キャンペーンのパフォーマンス**  

    ```text
    Analyze and visualize how the marketing campaign performed across each target segment 
    and help me decide where to re-target our next campaign.
    ```  

    ファイル:**BoulderEV ebike Internal Market Forecast.xlsx**  

## 重要なポイント

- **リサーチ ツール**: 高品質の研究によって戦略と計画をより速く行います。  
- **アナリスト**: 高度な分析と視覚化により、データ主導のインサイトを提供します。  

リサーチ ツールとアナリストを併用すると、**質問からインサイト**までの過程が短縮され、数週間かかっていた作業が数分で済むようになります。  

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
