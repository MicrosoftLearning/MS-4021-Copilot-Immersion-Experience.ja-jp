---
task:
  title: イマージョン エクスペリエンス - 運用
---

## イマージョン エクスペリエンス - 運用

可能性のあるベンダーを評価し移行プロセスの概要を示して、サプライヤー移行計画の下書きを作成します。

次の 3 つのタスクを実行します。  

- **Microsoft 365 Copilot Chat** を使用してサプライヤーの選択肢を調査する。  
- **Copilot in Word** を使用してサプライヤー移行計画を立てる。  
- **Copilot in Outlook** を使用して、サプライヤーの変更を伝える。  

> **注:** 作業を開始するのに役立つサンプル プロンプトが用意されています。 これらを自分のニーズに合わせて自由にカスタマイズします - 創造的な姿勢で取り組み、応用方法を探ってください。 求める結果が Copilot で得られない場合は、プロンプトを改善して、もう一度やり直してください。 このプロセスと実験を楽しんでください。  

### タスク 1: サプライヤーの選択肢を調査する  

**Microsoft 365 Copilot Chat** を使用して、特定の製品やサービスを提供できる可能性のあるサプライヤーを調査および比較します。 コスト、信頼性、サービス レベル アグリーメント (SLA)、スケーラビリティなどの主要な決定要因を特定します。  

**手順**:

- 新しいブラウザー タブを開き、[M365copilot.com](https://m365copilot.com/) に移動します。
- Copilot Chat で [Web モード] タブが選択されていることを確認します。

    ![[Web モード] タブを示すスクリーンショット。](../Prompts/Media/web-mode.png)

**サンプル プロンプト**:

```text
Compare three leading suppliers for [product/service] in [select your industry]. Provide a summary of pricing, contract flexibility, service reliability, and customer support quality.
```

> **注:** [product/service] を、サプライヤー移行のために評価する品目またはサービスに置き換えます。 [select your industry] を、医療、製造、小売などの関連業界に置き換えます。  

> **ヒント**  
>
> - 応答を Word 文書にエクスポートして次のタスクのために保存するように Copilot に依頼します。 ドキュメントを OneDrive に保存し、共有 URL をコピーします。
> - リンクをコピーするには、保存した Word 文書を開き、次に示すように **[共有]**、**[リンクのコピー]** の順に選択します。  
> ![リンクの共有。](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### タスク 2: サプライヤー移行計画を立てる  

**Copilot in Word** を使用して、サプライヤー移行プロセス、期待される利益、主要なリスクの概要を説明する構造化された計画の下書きを作成します。 計画には、切り替えの正当な理由、移行のタイムライン、関係者に関する考慮事項が必ず含まれるようにします。  

- ブラウザーから Microsoft Word を起動 (アドレス バーに「[word.new](https://word.new)」と入力) するか、デスクトップ アプリケーションを使用します。
- "**書きたい内容を記述してください**" と表示された場所にプロンプトを入力します。

    ![Copilot in Word を示すスクリーンショット。](../Prompts/Media/draft-with-copilot.png)

**サンプル プロンプト**:

```text
Based on the supplier research from [Paste in shared Word document link from Task 1], draft a Supplier Transition Plan outlining why [Company] is switching to [Supplier X]. Include key benefits, a transition timeline, and potential risks.
```

> **注:** [Company] を所属組織に置き換え、[Supplier X] を選択したサプライヤーに置き換えます。 ビジネス ニーズに合わせて詳細を調整します。

> **ヒント** 移行計画をメール更新で使用できるように 3 から 4 個の重要なポイントにまとめるように Copilot in Word に依頼します。

### タスク 3: サプライヤーの変更を伝える  

**Copilot in Word** を使用して、サプライヤー移行の提案をチームに公表するメールを下書きします。 移行の理由、期待される利益、スムーズな移行に必要なアクション ステップを明確に説明します。  

**手順**:

- **Outlook** で **[新しいメール]** を選択し、リボンから **[Copilot]**、**[Copilot で下書き]** の順に選択します。

    ![Copilot in Outlook を示すスクリーンショット。](../Prompts/Media/copilot-outlook-desktop.png)

**サンプル プロンプト**:

```text
Write an internal email to my team announcing a potential supplier transition to [Supplier X] using the key points below:

[Summarized key points from the Supplier Transition Plan]
```

> **注:** [Supplier X] を選定したサプライヤーに置き換え、社内の対象者に合わせてメッセージを調整します。
