---
demo:
  title: IT デモ
---

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# IT デモ

**シナリオ:**

あなたは Contoso の IT インフラストラクチャ マネージャーで、新しいネットワーク セキュリティ製品 Contoso CipherGuard を企業ネットワーク全体に展開するよう依頼されました。 あなたは、Copilot を使用して再利用可能なプロジェクト実装計画テンプレートを作成し、製品仕様書に基づいた CipherGuard 固有の計画を下書きし、完成した計画をエグゼクティブ向けプレゼンテーションに変換します。

## デモ セットアップ

サンプル ドキュメントは、[こちら](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)の MS-4021 GitHub リポジトリにあります。

このデモに必要な具体的なファイルは次のとおりです。

- [Contoso_CipherGuard_Product_Specification.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_CipherGuard_Product_Specification.docx)

> **注:** これらのファイルがダウンロード後に OneDrive に同期されるまでに最大 10 分かかることがあります。 デモ中の遅延を避けるために、事前にこれらのファイルをダウンロードし OneDrive で使用できるようにしておいてください。 ファイルが使用できない場合は、ドキュメントを開き、デモで使用する共有ファイルリンクをコピーします。

## デモ

### Copilot Chat

まずは Copilot に、ネットワーク セキュリティ製品から始めて、あらゆるロールアウトに適用でき、再利用可能なプロジェクト実装計画テンプレートを作成するように依頼しましょう。

1. ブラウザーを開き、[M365copilot.com](https://m365copilot.com/) に移動します。

1. **[Web モード]** が選択されていることを確認します。

    ![[Web モード] タブを示すスクリーンショット。](../Prompts/Media/web-mode.png)

1. プロンプト ウィンドウで、次のように入力します。

    ```text
    You are an IT infrastructure manager at Contoso. Your task is to create a detailed project implementation plan for installing a new network security product in your corporate network. Your plan should include key milestones, resource allocation, potential risks, and a timeline to ensure successful deployment and minimal disruption to operations.
    ```

    > **注:** ロールベースのプロンプトは、Copilot がユーザーの責任とコンテキストを理解し、出力の関連性と特定性を向上させるのに役立ちます。

1. 次に、プロジェクト計画に新しいセクションを追加するように Copilot に依頼して、プロジェクト計画を改善します。

    次のプロンプトを入力します。

    ```text
    Please add the following sections to the existing plan: testing and QA, training, communication, documentation and reporting, stakeholder analysis, project timeline, and risk assessment and mitigation. Ensure these sections provide detailed action steps and align with the existing content. Avoid duplicating any items already included in the original plan.
    ```

1. 下書きが問題なければ、応答を直接 Word にエクスポートします。 Copilot の応答の一番下で **[その他のオプション (...)]** メニューを選択し、**[Word にエクスポート]** を選択します。

    ![Copilot Chat の応答メニューの [Word にエクスポート] のオプション。](../Demos/Media/export-to-word.png)

    > **注:** Copilot は応答を Word 文書として OneDrive に保存します。 **[Word を開く]** を選択して、新しいブラウザー タブで Word 文書を開きます。

1. 新しい Word 文書タブで、ファイル名を **Project Implementation Plan.docx** に変更します。 その後、文書から共有 URL をコピーします (自動保存を有効にし、メッセージが表示されたら OneDrive アカウントを選択します)。

    ![リンクを共有します。](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot in Word

今回は、そのテンプレートと CipherGuard 製品仕様書を組み合わせて、このロールアウトに合わせた展開計画を下書きします。

> **ヒント — Word エージェントを使用したオプションの代替手段:** Word を開くために Copilot Chat を離れる代わりに、Chat に留まって **Word** エージェントを `@` でメンションして、新しい文書を作成してもらうこともできます。 次のようなプロンプトを使用します。
>
> ```text
> @Word Using the [Contoso_CipherGuard_Product_Specification.docx] for product details and the project plan we just created as a structural template, draft a comprehensive project implementation plan for deploying Contoso CipherGuard. Ensure the plan aligns with the product specifications and follows the structure outlined in the template. Save it as Contoso_Project_Plan.docx.
> ```
>
> 作業が終わったら、作成された **Contoso_Project_Plan.docx** を OneDrive から開き、PowerPoint セクションにスキップします。 **注意点:** Word エージェントの完了までに数分かかることがあるため、ライブ デモ中は通常、以下のアプリ内フローを選択する方がより安全です。

1. (Web ブラウザーまたはデスクトップ アプリケーションで) 新しい Word 文書を開きます。

1. **"Copilot で下書きしたい内容を記述してください"** と表示されたプロンプト ボックスに、次のように入力します。

    ```text
    Using the [Contoso_CipherGuard_Product_Specification.docx] for product details and the [Project Implementation Plan.docx] as a structural template, draft a comprehensive project implementation plan for deploying Contoso CipherGuard. Ensure the plan aligns with the product specifications and follows the structure outlined in the template.
    ```

    > **注:** 角かっこは、ドキュメントが参照されていることを示します。 ファイルを直接添付したり、OneDrive の共有リンクを貼り付けたり、`/` を使用して名前で参照したりできます。 このデモでは、以下を使用します。
    >
    > - **Contoso_CipherGuard_Product_Specification.docx** — デモのセットアップでダウンロードしたファイルです。
    > - **Project Implementation Plan.docx** — 前のセクションの最後にコピーした共有リンクを使用します。

1. 出力に問題がなければ、**[保持する]** を選択します。

1. 完了したら、ドキュメントを **Contoso_Project_Plan.docx** として保存し、共有 URL をコピーします (自動保存を有効にして、メッセージが表示されたら自分の OneDrive アカウントを選択します)。

    ![リンクを共有します。](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot in PowerPoint

最後に、Copilot を使用して CipherGuard の実装計画に基づく PowerPoint プレゼンテーションを生成します。

1. ブラウザーの [PowerPoint.new](https://PowerPoint.new) から Microsoft PowerPoint を起動するか、デスクトップ アプリケーションを使用します。

1. 新しい空白のプレゼンテーションを開きます。

1. プレゼンテーションの右下にある **Copilot アイコン**を選択します。

    ![PowerPoint の Copilot アイコン。](../Demos/Media/Open-Copilot-in-PowerPoint.png)

1. [Copilot] ペインで、次のプロンプトを入力します。

    ```text
    Create a presentation from [Link to Contoso_Project_Plan.docx].
    ```

    > **注:** **Contoso_Project_Plan.docx** 文書の共有リンクを貼り付けるか、**[作業内容を追加]**、**[画像とファイルのアップロード]** の順に選択してアップロードしてください。

1. Copilot は、プロジェクト計画に基づいてスライドの生成を開始し、発表者のメモ、画像、スライド レイアウト、一般的な秘密度ラベルなどの機能と共にアウトラインを提供します。

    > **注:** ドキュメントの複雑さとスライド数によっては、スライドの生成に最大 2 分かかることがあります。

## 重要なポイント

1 回のデモで、汎用的な展開依頼を CipherGuard 対応のロールアウト パッケージに変換しました。**[Copilot Chat]** を使用して再利用可能なプロジェクト実装計画テンプレートを作成し、**[Copilot in Word]** で CipherGuard 仕様に基づいた製品固有の計画を下書きし、**[Copilot in PowerPoint]** でエグゼクティブ向けプレゼンテーションを生成しました。 通常はテンプレートの作成ややり取りに数週間が必要なプロジェクト作業が、集中したエンドツーエンドのワークフローに集約されます。

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
