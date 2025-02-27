---
demo:
  title: 法務デモ
---

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# 法務デモ

**シナリオ:**  

あなたは Contoso の法律アドバイザーで、会社の AI 再開スクリーニング ソフトウェアが EU の AI 法に準拠しているかどうかを評価する責任があります。あなたの目標は、法的リスクを調査し、概要の下書きを作成し、会社の経営陣に推奨事項を伝えることです。

## デモ セットアップ

このデモに必要なサンプル ドキュメントはありません。

## デモ

### Copilot Chat

まず、AI 法と、その法の Contoso の AI 採用ツールに対する潜在的な影響を調査してみましょう。

1. ブラウザーを開き、[M365copilot.com](https://m365copilot.com/) に移動します。

1. **[Web モード]** が選択されていることを確認します。

    ![[Web モード] タブを示すスクリーンショット。](../Prompts/Media/web-mode.png)

1. プロンプト ウィンドウで、次のように入力します。

    ```text
      Contoso is launching an AI Resume Screening Software to evaluate job applicants. As a legal advisor, I need to assess whether it complies with the EU Artificial Intelligence Act. Summarize key provisions related to AI in hiring, compliance requirements for high-risk systems, and potential legal risks.
    ```

1. Copilot の応答を確認し、関連する法的リスクとコンプライアンス要件に関するメモを取ります。

1. ここでは、Copilot に一連のフォローアップの質問をして、さらに情報を収集します。

    ```text
    Does the AI Act classify resume screening software as a high-risk AI system?
    ```

    ```text
    What are the key obligations for high-risk AI systems under the AI Act?
    ```

    ```text
    Are there any exemptions in the AI Act that could apply to Contoso’s system?
    ```

1. 次に、これまでのすべての情報を要約するように Copilot に依頼します。

    ```text
    Summarize all the information we've discussed into a structured list, ensuring no key details are missed. Then, export the summary to a Word document
    ```

1. 新しい Word 文書のために Copilot が提供するハイパーリンクを選択して、それを開きます。

1. 開いたら、**[編集を可能にする]** を選択してから、[自動保存] をオンにします。 メッセージが表示されたら、自分の OneDrive アカウントを選択します。

1. 次の手順で使用するために、共有 URL をコピーします。 (メッセージが表示されたら、自動保存を有効にして、自分の OneDrive アカウントを選択します。)

    ![リンクを共有します。](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Word の Copilot

次に、Contoso のリーダー陣のために法的リスクと推奨事項を説明した概要の下書きを作成します。

1. ブラウザーまたはデスクトップ アプリケーションで、Word の新しいインスタンスを開きます。

1. "**書きたい内容を記述してください**" と表示されたプロンプト ボックスに、次のように入力します。

    ```text
    Reference the following document [Link to exported Copilot Chat summary from the first task] and draft an executive summary outlining key legal risks, compliance requirements, and recommendations for Contoso’s AI Resume Screening Software.
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

1. ドキュメントを確認して完成したら、次のデモで使用するために、クリップボードに**生成された概要をコピー**します。

### Outlook の Copilot

最後に、調査結果と次の手順を要約した Contoso のリーダー陣へのメールの下書きを作成します。

1. (Web ブラウザーまたはデスクトップ アプリケーションの) Outlook を開きます。

1. **[新しいメール]** を選択します。

1. リボンの **[Copilot]** を選択します。 ドロップダウン メニューから **[Copilot で下書き]** を選択します。

1. "**メールに書きたい内容**" プロンプト ウィンドウで、次のように入力します。

   ```text
    Draft an email to Contoso’s executive leadership summarizing our legal assessment of the AI Resume Screening Software under the EU AI Act. Use the following executive summary as a reference.

    [paste Executive Summary from the previous task]

    Conclude the email with a request for leadership’s input on the next steps, including a proposed compliance review meeting.
   ```

    > **注:** 前のデモからコピーした概要の内容を貼り付けます。

1. 下書きが生成されたら、**調節**機能を使用して、トーン、長さ、または形式レベルを変更できます。

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
