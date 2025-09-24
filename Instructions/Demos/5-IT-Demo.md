---
demo:
  title: IT デモ
---

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# IT デモ

**シナリオ:**  

IT インフラストラクチャ マネージャーとして、あなたは新しいネットワーク セキュリティ製品を企業ネットワークにインストールする予定です。

## デモ セットアップ

サンプル ドキュメントは、[こちら](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)の MS-4021 GitHub リポジトリにあります。

このデモに必要な具体的なファイルは次のとおりです。

- [Contoso_CipherGuard_Product_Specification.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_CipherGuard_Product_Specification.docx)

> **注:** これらのファイルがダウンロード後に OneDrive に同期されるまでに最大 10 分かかることがあります。 デモ中の遅延を避けるために、事前にこれらのファイルをダウンロードし OneDrive で使用できるようにしておいてください。 ファイルが使用できない場合は、ドキュメントを開き、デモで使用する共有ファイルリンクをコピーします。

## デモ

### Copilot Chat

まず、Copilot にプロジェクト実装計画の作成を依頼します。

1. ブラウザーを開き、[M365copilot.com](https://m365copilot.com/) に移動します。

1. [Web モード] が選択されていることを確認します。

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

1. 最後に、Copilot にプロジェクト計画案を Word 文書に出力させます。

    次のプロンプトを入力します。

    ```text
    Please export the project plan to a Word document.
    ```

1. Copilot が表示する新しく作成されたファイルへのリンクを選択して、ダウンロード フォルダーにダウンロードします。 ファイルを OneDrive フォルダーに移動して、開きます。 ドキュメントから共有 URL をコピーします (自動保存を有効にし、メッセージが表示されたら OneDrive アカウントを選択します)。

    ![リンクを共有します。](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot in Word

次に、これらの戦略を拡張し、それらを実装する方法に関する提案の下書きを作成するように Copilot に依頼します。

1. (Web ブラウザーまたはデスクトップ アプリケーションの) Word を開きます。

1. **[Copilot で何についての下書きをしますか?]** プロンプト ボックスに、次のように入力します。

    ```text
    Using the Contoso [/CipherGuard Product Specification.docx] and the 'Project Implementation Plan' template provided in [paste in link to Project_Implementation_Plan.docx], draft a comprehensive project implementation plan for deploying Contoso CipherGuard. Ensure the plan aligns with the product specifications and follows the structure outlined in the template.
    ```

    > **注:** 角かっこは、ドキュメントが参照されていることを示します。
    > 1. CipherGuard Product Specification.docx = [Contoso_CipherGuard_Product_Specification.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_CipherGuard_Product_Specification.docx)
    > 1. Project Implementation Plan.docx = 前のデモでコピーしたリンクを使用します。
    > ドキュメントを参照するときは、リンクを直接貼り付けるか、OneDrive で使用できる場合はファイル名を参照することができます。

1. **[維持する]** を選択するか、時間が許す場合は、Copilot を使用してドキュメントを調整する方法を示します。

1. 完了したら、ドキュメントを **Contoso_Project_Plan.docx** として保存し、共有 URL をコピーします (自動保存を有効にして、メッセージが表示されたら自分の OneDrive アカウントを選択します)。

    ![リンクを共有します。](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot in PowerPoint

ここでは、Copilot を使用して、Contoso CipherGuard 製品を実装する新しい提案に基づいて PowerPoint プレゼンテーションを生成します。

1. ブラウザーの [PowerPoint.new](https://PowerPoint.new) から Microsoft PowerPoint を起動するか、デスクトップ アプリケーションを使用します。

1. 新しい空白のプレゼンテーションを開きます。

1. Copilot ペインで、[ファイルからプレゼンテーションを作成する] プロンプトを選択します。

1. **Contoso_Project_Plan.docx** ドキュメントの共有リンクを貼り付けて、**[送信]** を選択します。

    完全なプロンプトは次のようになります。

    ```text
    Create a presentation from [Link to Contoso_Project_Plan.docx].
    ```

1. Copilot は、プロジェクト計画に基づいてスライドの生成を開始し、発表者のメモ、画像、スライド レイアウト、一般的な秘密度ラベルなどの機能と共にアウトラインを提供します。

    > **注:** ドキュメントの複雑さとスライドの数によっては、スライドの生成に最大 2 分かかることがあります。

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
