---
demo:
  title: コミュニケーションのデモ
---

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# コミュニケーションのデモ

**シナリオ:**

あなたは内部コミュニケーション マネージャーです。 あなたの組織は新しい内部 AI アシスタント ツールを導入しており、ニュースが伝達されるように、コミュニケーション コミュニティに啓発の投稿を公開する必要があります。 Copilot を使用してリリース場所を調査し、投稿を下書きし、これまでのトーンに合わせて書き直し、楽しいイントロとアウトロを加えて仕上げ、最後にニュースレター形式のメールで送信します。

## デモ セットアップ

サンプル ドキュメントは、[こちら](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)の MS-4021 GitHub リポジトリにあります。

このデモに必要な具体的なファイルは次のとおりです。

- [Contoso_Companion_One_Pager.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Companion_One_Pager.docx)

> **注:** これらのファイルがダウンロード後に OneDrive に同期されるまでに最大 10 分かかることがあります。 デモ中の遅延を避けるために、事前にファイルをダウンロードして OneDrive で使用できるようにしておいてください。 ファイルが使用できない場合は、ドキュメントを開き、デモで使用する共有ファイル リンクをコピーしてください。

## デモ

### Copilot Chat

最初に Copilot Chat (Web モード) でリリース場所の調査を行い、啓発の初稿を下書きします。内部データは不要です。

1. ブラウザーを開き、[M365copilot.com](https://m365copilot.com/) に移動します。

1. **[Web モード]** が選択されていることを確認します。

    ![[Web モード] タブを示すスクリーンショット。](../Prompts/Media/web-mode.png)

1. まずは、新しい投稿が適切なトーンで伝わるように、他の組織がどのように新しい社内 AI ツールを通知しているかを調査しましょう。 次のプロンプトを入力します。

    ```text
    Research how leading organizations announce new internal AI assistant tools to employees. Summarize the tone and sentiment patterns that resonate (e.g., reassuring, empowering, playful), and list 5 themes that consistently appear in successful launch communications.
    ```

1. 次に、1 ページャーを基にした啓発の投稿の最初のバージョンを下書きします。 次のプロンプトを入力し、**Contoso_Companion_One_Pager.docx** ファイルを添付 (または `/` で参照) します。

    ```text
    Using the attached Contoso Companion one-pager as the source of truth, draft an internal awareness post announcing the launch. The audience is the global Contoso Communications Community (the first-wave audience called out in the one-pager). Include: what Companion is, the top 3 things it helps with, how to get access, and a clear next step. Follow the voice and brand notes from the one-pager. Aim for ~400 words and a confident, optimistic tone.

    [Contoso_Companion_One_Pager.docx]
    ```

    > **注:** 角かっこは、ドキュメントが参照されていることを示します。 ファイルを添付したり、その OneDrive の共有リンクを貼り付けたり、`/` を使用して名前で参照したりできます。

1. 下書きが問題なければ、応答を直接 Word にエクスポートします。 Copilot の応答の一番下で **[その他のオプション (...)]** メニューを選択し、**[Word にエクスポート]** を選択します。

    ![Copilot Chat の応答メニューの [Word にエクスポート] のオプション。](../Demos/Media/export-to-word.png)

    > **注:** Copilot は応答を Word 文書として OneDrive に保存します。 新しいブラウザー タブで Word 文書を開くには **[Word を開く]** を選択します。

### Copilot in Word

今回は、下書きを Word に移し、**[Copilot で編集]** でこれまでのトーンで書き直し、楽しいイントロとアウトロを加えます。

1. 前のステップで Copilot Chat からエクスポートした Word 文書が既に開いているはずです。 **Contoso_Companion_Awareness_Post.docx** に名前を変更します。 その後、自動適用された秘密度ラベルを必要に応じて削除します。

1. 文書の右下に表示される **Copilot アイコン**を選択します。

    ![Word の Copilot アイコン。](../Demos/Media/Open-Copilot-in-Word.png)

1. **[編集を許可する]** が選択されていることを確認します。

    ![[編集を許可する] が選択されています。](../Demos/Media/allow-editing.png)

1. 次のプロンプトを入力します。

    ```text
    Rewrite this awareness post in my established voice: warm and conversational, second-person, short paragraphs, a playful opener, a "What's in it for you" bulleted section, and a clear call-to-action at the end. Keep the core facts and tighten anything that feels corporate or jargon-heavy.
    ```

1. 書き直したものをレビューし、問題がなければ **[完了]** を選択します。

1. 次に、以下のプロンプトを入力します。

    ```text
    Based on the awareness post below, draft a fun and engaging 2–3 sentence intro and a short outro that will get the communications community excited about Contoso Companion. The intro should hook the reader; the outro should reinforce the call-to-action.
    ```

1. 新しいイントロとアウトロをレビューし、問題がなければ **[完了]** を選択します。

### Copilot in Outlook

最後に、仕上がった投稿をニュースレター形式のメールでコミュニケーション コミュニティに送信します。

1. (Web ブラウザーまたはデスクトップ アプリケーションの) Outlook を開きます。

1. **[新しいメール]** を選択します。

1. リボンの右上にある **[Copilot]** アイコンを選択します。

1. **[Copilot で編集]** が有効になっていることを確認します。

    ![Outlook の [Copilot で編集] トグル。](../Demos/Media/edit-with-copilot-outlook.png)

1. 次のプロンプトを入力します。

    ```text
    Draft a newsletter-style email to the communications community announcing Contoso Companion. Use the awareness post I just finalized as the source material. Lead with the playful intro, include the "What's in it for you" bullets, and end with the call-to-action and a link placeholder for the access form. Keep it warm and skimmable — under 250 words.
    ```

    > **注:** 開いている **[Contoso_Companion_Awareness_Post.docx]** タブから直接リンクをコピーするか、**[作業内容を追加]** を選択してドキュメントを検索できます。

1. オプションとして、Copilot に**より短く**、**よりフォーマルに**、または**件名を追加する**ように依頼します。

## 重要なポイント

1 回のデモで、空白のページが洗練され、ブランドに合った啓発の投稿とお知らせメールに変わりました。**[Copilot Chat]** で調査と下書きを行い、**[Copilot in Word で編集]** でトーンを合わせ、**[Copilot in Outlook]** でリリースしました。 実際のテナント データは不要で、どんなデモ環境でも Microsoft 365 Copilot のエンドツーエンドの価値を示すのに最適です。

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
