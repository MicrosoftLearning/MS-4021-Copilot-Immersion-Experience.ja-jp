---
task:
  title: 没入体験 - 法務
---

## 没入体験 - 法務  

インサイトを収集し、法的分析を行い、専門的コミュニケーションの下書きを作成することで、法的意思決定を強化します。  

次の 3 つのタスクを実行します。  

- **Copilot Chat** を使用して法的情報を調査します。  
- **Copilot Chat** を使用して法的分析を行います。  
- **Copilot in Word** を使用して法的コミュニケーションの下書きを作成します。  

> **注:** 作業を開始するのに役立つサンプル プロンプトが用意されています。 これらを自分のニーズに合わせて自由にカスタマイズします - 創造的な姿勢で取り組み、応用方法を探ってください。 求める結果が Copilot で得られない場合は、プロンプトを改善して、もう一度やり直してください。 このプロセスと実験を楽しんでください。  

### タスク 1: 法的情報を調査する  

**Copilot Chat** を使用して、メール、チャット履歴、SharePoint ドキュメントなどの内部ソースを分析することで、関連する法的トピックについてのインサイトを収集します。 その後、業界の記事、法的データベース、外部レポート、または関連する訴訟法を使用して調査を拡大することができます。  

調査するべき内部の法的事項がない場合は、**契約法、データ プライバシー、雇用法、コンプライアンス要件**など、選択した法的トピックに関する一般に利用可能なソースからインサイトを収集することに重点を置きます。  

**手順**:

- 新しいブラウザー タブを開き、[M365copilot.com](https://m365copilot.com/) に移動します。  
- Copilot Chat で [作業モード] タブが選択されていることを確認します。  

    ![[作業モード] タブを示すスクリーンショット。](../Prompts/Media/work-mode.png)  

**サンプル プロンプト**:

```text
Summarize information from emails, chat messages, and SharePoint documentation related to [specific legal topic]. Then, enhance these insights by summarizing information from relevant legal articles, external reports, and other authoritative sources to provide a well-rounded perspective on [specific legal topic].
```

**代替サンプル プロンプト***(内部の法的トピックがない場合)*:

```text
Research key considerations, compliance risks, and recent updates related to [select a legal topic, for example: data privacy laws]. Summarize information from authoritative sources such as government regulations, case law, and industry best practices. Highlight key challenges organizations face when addressing this issue.
```

> **注:** プロンプトを送信する前に、角括弧で囲まれたテキスト ([ ]) を選択した法的トピックに置き換えます。

### タスク 2: 法的分析を実行する  

**Copilot Chat** を使用して、重要な規定、影響、および潜在的なリスクを調査する構造化された法的分析を実行します。 一般的な法的課題を特定し、類似の組織や業界がこれらの問題にどのように取り組むかを比較します。 法的意思決定をサポートするために最も重要なポイントをまとめます。  

**サンプル プロンプト**:

```text
Analyze [specific legal topic] by summarizing its key provisions, potential risks, and business implications. Identify common legal challenges organizations face and compare how similar industries approach compliance and risk mitigation. Highlight key trends and assess potential impacts to provide a well-rounded understanding of its significance.
```

> **注:** プロンプトを送信する前に、角括弧で囲まれたテキスト ([ ]) を選択した法的トピックに置き換えます。

> **ヒント**  
>
> - 応答を Word 文書にエクスポートして今後の使用のために保存するように Copilot に依頼します。 ドキュメントを OneDrive に保存し、共有 URL をコピーします。  
> - リンクをコピーするには、保存した Word 文書を開き、次に示すように **[共有]**、**[リンクのコピー]** の順に選択します。  
> ![リンクの共有。](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)  

### タスク 3: 法的コミュニケーションの下書きを作成する  

**Copilot in Word** を使用して、調査と分析に基づいて法的コミュニケーションの下書きを作成します。 これは、法的メモ、リスク評価、コンプライアンス ガイダンス、クライアント アドバイザリ、FAQ ドキュメントなどです。  

**手順**:

- ブラウザーの [word.new](https://word.new) から Microsoft Word を起動するか、デスクトップ アプリケーションを使用します。  
- "**書きたい内容を記述してください**" と表示された場所にプロンプトを入力します。  

    ![Copilot in Word を示すスクリーンショット。](../Prompts/Media/draft-with-copilot.png)  

**サンプル プロンプト**:

```text
Using the insights below, draft a legal advisory memo for internal stakeholders. Focus on explaining [specific legal topic], outlining potential risks, and providing recommendations for compliance or risk mitigation. [Paste insights from Copilot Chat here, or add your own insights]
```

> **注:** プロンプトを送信する前に、角括弧で囲まれたテキスト ([ ]) を選択した法的トピックに置き換えます。

> **ヒント:** コミュニケーションの下書きを作成するときは、タスク 2 の共有ドキュメント リンクを使用して、重要なインサイトを参照します。 または、Copilot に **「/」** と入力して、OneDrive から関連ファイルをすばやく参照して挿入します。
