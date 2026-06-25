---
demo:
  title: 法務デモ
---

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# 法務デモ

**シナリオ:**

あなたは Contoso の法務アドバイザーとして、同社の新しい AI 履歴書スクリーニング ソフトウェアが EU AI 法に準拠しているかどうかを評価しています。Copilot を使って規制とその採用ツールに関する具体的な義務を調査し、幹部向けの法的リスクと提言のエグゼクティブ サマリーを作成し、その調査結果を次のステップの要望とともに経営幹部にメールで送ります。

## デモ セットアップ

このデモに必要なサンプル ドキュメントはありません。

## デモ

### Copilot Chat

まず、EU AI 法と、Contoso の AI 採用ツールに対するその潜在的な影響を調査します。

1. ブラウザーを開き、[M365copilot.com](https://m365copilot.com/) に移動します。

1. **[Web モード]** が選択されていることを確認します。

    ![[Web モード] タブを示すスクリーンショット。](../Prompts/Media/web-mode.png)

1. プロンプト ウィンドウで、次のように入力します。

    ```text
      Contoso is launching an AI Resume Screening Software to evaluate job applicants. As a legal advisor, I need to assess whether it complies with the EU Artificial Intelligence Act. Summarize key provisions related to AI in hiring, compliance requirements for high-risk systems, and potential legal risks.
    ```

1. Copilot の応答を確認し、関連する法的リスクとコンプライアンス要件をメモします。

1. ここでは、Copilot に一連のフォローアップの質問をして、さらに情報を収集します。

    ```text
    Does the AI Act classify resume screening software as a high-risk AI system?
    ```

    ```text
    What are the key obligations for high-risk AI systems under the AI Act?
    ```

    ```text
    Are there any exemptions in the AI Act that could apply to Contoso's system?
    ```

1. 次に、これまでのすべての情報を要約するように Copilot に依頼します。

    ```text
    Summarize all the information we've discussed into a structured list, ensuring no key details are missed. Then, export the summary to a Word document
    ```

1. 新しい Word 文書のために Copilot が提供するハイパーリンクを選択して、それを開きます。

1. 開いたら、**[編集を可能にする]** を選択してから、[自動保存] をオンにします。 メッセージが表示されたら、自分の OneDrive アカウントを選択します。

1. 次の手順で使用するために、共有 URL をコピーします。 (メッセージが表示されたら、自動保存を有効にして、自分の OneDrive アカウントを選択します。)

    ![リンクを共有します。](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot in Word

次に、Contoso の幹部のために法的リスクと推奨事項を説明したエグゼクティブ サマリーの下書きを作成します。

1. ブラウザーまたはデスクトップ アプリケーションで、Word の新しいインスタンスを開きます。

1. **"Copilot で下書きしたい内容を記述してください"** と表示されたプロンプト ボックスに、次のように入力します。

    ```text
    Reference the following document [Link to exported Copilot Chat summary from the first task] and draft an executive summary outlining key legal risks, compliance requirements, and recommendations for Contoso's AI Resume Screening Software.
    ```

    > **注:** ドキュメントを添付するか、共有リンクをプロンプトに直接貼り付けて、Copilot が関連するコンテンツにアクセスできるようにします。

1. Copilot の出力を確認します。 **[保持]** を選択する前に、Copilot に依頼して応答を改善します。

    ```text
    Add a section on the potential business impact of these compliance requirements.
    ```

1. その他に、次のような改善オプションがあります。

    - より専門的なトーンになるように、セクションの言い換えを Copilot に依頼する。
    - 概要が長すぎる場合は、より短く簡潔なバージョンを要求します。
    - セクションを追加して内容を膨らませる。

1. ドキュメントを確認して最終処理したら、ドキュメントの名前を **Legal Assessment.docx** に変更し、次の手順での使用に備えて共有 URL をコピーします。 (メッセージが表示されたら、自動保存を有効にして、自分の OneDrive アカウントを選択します。)

### Copilot in Outlook

最後に、調査結果と次の手順を要約した Contoso のリーダー陣へのメールの下書きを作成します。

1. (Web ブラウザーまたはデスクトップ アプリケーションの) Outlook を開きます。

1. **[新しいメール]** を選択します。

1. リボンの右側にある **[Copilot]** アイコンを選択します。

1. **[Copilot で編集]** が有効になっていることを確認します。

    ![Outlook の [Copilot で編集] トグル。](../Demos/Media/edit-with-copilot-outlook.png)

1. 次のプロンプトを入力します。

   ```text
    Draft an email to Contoso's executive leadership summarizing our legal assessment of the AI Resume Screening Software under the EU AI Act. Use [Legal Assessment.docx] as a reference.

    Conclude the email with a request for leadership's input on the next steps, including a proposed compliance review meeting.
   ```

    > **注:** **[ソースの追加と管理]** > **[作業コンテンツを追加]** を選択し、**Legal Assessment.docx** を検索します。 ファイルが利用できない場合は **[画像とファイルのアップロード]** を選択して、ファイルを直接アップロードできます。

1. 下書きが生成されたら、トーン、長さ、または丁寧さのレベルを自由に調整できます。

## 重要なポイント

1 つのワークフローで、急速に進行する規制問題を幹部向けの意思決定パケットに変えました。**Copilot Chat** を使って EU AI 法を調査し、Contoso の採用ツールにどの程度適用されるのかを検証しました。**Copilot in Word** を使って、リスクと推奨事項を含む洗練されたエグゼクティブ サマリーを作成し、**Copilot in Outlook** で幹部向けにブリーフィングし、次のステップについての要望を提出しました。 数日間を要する法的調査、下書き、ステークホルダーとのコミュニケーションが、1 つの集中的なセッションに凝縮されます。

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
