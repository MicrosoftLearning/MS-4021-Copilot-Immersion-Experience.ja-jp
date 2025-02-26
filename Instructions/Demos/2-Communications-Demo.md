---
demo:
  title: コミュニケーションのデモ
---

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# コミュニケーションのデモ

**シナリオ:**  
あなたは、有名な報道機関の記者とのインタビューの準備をしています。 目標は、記者に関する分析情報を収集し、記者の視聴者に合わせてメッセージングを調整し、インタビューで聞かれる可能性のある質問に対して、よく練られた回答を作成することです。 このプロセス全体を通して、Copilot がお手伝いします。

## デモ セットアップ

このデモに必要なサンプル ドキュメントはありません。

## デモ

### Copilot Chat

1. ブラウザーを開き、[M365copilot.com](https://m365copilot.com/) に移動します。

1. Web モードが選択されていることを確認します。

    ![[Web モード] タブを示すスクリーンショット。](../Prompts/Media/web-mode.png)

1. プロンプト ウィンドウで、次のように入力します。

    ```text
    I am going to be interviewed by {Reporter Name} from {News Outlet Name} about {Specific Topic, e.g., 'sustainability in tech'}. What are some key things I should know about their previous work and approach to this topic?
    ```

1. 報道機関の視聴者を把握して、アプローチを調整します。 Copilot を使用して、視聴者の人口統計情報と関心を分析します。

    次のプロンプトを入力します。

    ```text
    Tell me about {News Outlet Name}'s demographic and their audience's interests and knowledge level on {Specific Topic}.
    ```

1. Copilot にプロンプトを入力して、インタビューで聞かれる可能性のある質問を予想します。

    次のプロンプトを入力します。

    ```text
    Generate the top 10 questions that {Reporter Name} might ask in my interview. They should be informed by the research conducted above and crafted to be conversational yet concise.
    ```

1. 予想される質問に対する回答の下書きを作成し、それを表形式で整理します。 この表を Word 文書に保存して、後で使用できるようにします。

    次のプロンプトを入力します。

    ```text
    Draft answers to the questions in a table format. Save the table with questions and answers into a Word document.
    ```

    > **注:** この Word 文書は、次のデモで参照されます。

### Word の Copilot

Copilot Chat で生成された分析情報と下書きが、改善されて Word の FAQ に構造化されます。

1. 手順 5 で作成した Q&A 表を保存した Word 文書を開きます。

1. ドキュメントの本文の任意の場所を選択し、Copilot アイコンを選択します。 次のプロンプトに以下のように入力します。

    ```text
    Create an FAQ for a technical audience who are new to {Specific Topic}. Include the top 15 questions for publishing on a blog. Leverage the questions and answers from this document.
    ```

1. FAQ をレビューし改善します。 次のことを確認します。
    - 正確で関連性の高い簡潔な回答が含まれている。
    - 論理的に構造化されていて明瞭で読みやすくなっている。

1. FAQ を反映している。 情報にギャップはありますか? 必要に応じて質問を追加して、対象視聴者に包括的な価値を提供できるようにします。

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
