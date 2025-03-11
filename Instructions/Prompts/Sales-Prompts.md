---
task:
  title: 没入体験 - 営業
---

## 没入体験 - 営業

顧客との最近のやり取りからインサイトを収集し、重要な実施項目に合わせて調整し、今後の顧客との会合の準備をします。

次の 3 つのタスクを実行します。

- **Microsoft 365 Copilot Chat** を使用してインサイトを収集する
- **Copilot in Outlook** を使用して実施項目に合わせる
- **Copilot in Word** を使用して顧客との会合を準備する

> **注:** 作業を開始するのに役立つサンプル プロンプトが用意されています。 これらを自分のニーズに合わせて自由にカスタマイズします - 創造的な姿勢で取り組み、応用方法を探ってください。 求める結果が Copilot で得られない場合は、プロンプトを改善して、もう一度やり直してください。 このプロセスと実験を楽しんでください。

### タスク 1: インサイトを収集する

**Microsoft 365 Copilot Chat** (in Teams) を使用して、プロジェクトの実装に関する顧客との最近のやり取りからインサイトを収集して確認します。 これらのインサイトは、顧客の懸念、進行状況、および今後の関わり合い中に対処するべき新しい商機を理解するのに役立ちます。

**手順**:

- **Microsoft Teams**で、**[チャット]** ペインの上部にある **[Copilot]** を選択します。  これで **Copilot** ウィンドウが開きます。

    ![Teams 内の Copilot Chat を示すスクリーンショット。](../Prompts/Media/Copilot-chat-in-teams.png)

- Copilot Chat で "作業モード" のタブが選択されていることを確認します。

    ![作業モード タブを示すスクリーンショット。](../Prompts/Media/work-mode.png)

**サンプル プロンプト**:

```text
Summarize my recent interactions with [/Name of Person] regarding [specific customer / topic / project]. Organize the summary by key points or actions discussed, and include any follow-up items or outstanding questions that may require attention.
```

> **注:** [人名] を重点を置いている人に置き換え、[特定の顧客/トピック/プロジェクト] を関連するトピックに置き換えます。 **/** 文字 (スラッシュ) を使用すると、社内の連絡先を参照して最近のやり取りにすばやくアクセスできます。

### タスク 2: 実施項目に合わせる

**Copilot in Outlook** を使用して、Copilot Chat から収集されたインサイトに基づいてフォローアップ メールの下書きを作成します。 オープンな実施項目を含め、責任を明確にし、同僚またはチームに更新を提供して、調整とアカウンタビリティを確保します。

**手順**:

- **Outlook** で **[新しいメール]** を選択し、リボンから **[Copilot]**、**[Copilot で下書き]** の順に選択します。

    ![Copilot in Outlook を示すスクリーンショット。](../Prompts/Media/copilot-outlook-desktop.png)

**サンプル プロンプト**:

```text
Using the insights below, draft a follow-up email to [Name of Person] highlighting the key actions and next steps. Also, ask for a follow-up meeting to discuss further.

[Paste insights from Copilot Chat here]
```

### タスク 3: 顧客との会合を準備する

**Copilot in Word** を使用して、今後の顧客との近況報告会合用の話題の下書きを作成します。 その話題が重要な成果物に焦点を当てていて、顧客の優先事項に対処しており、次の手順を明確にしているようにします

**手順**:

- ブラウザーの [word.new](https://word.new) から Microsoft Word を起動するか、デスクトップ アプリケーションを使用します。
- "**書きたい内容を記述してください**" と表示された場所にプロンプトを入力します。

    ![Copilot in Word を示すスクリーンショット。](../Prompts/Media/draft-with-copilot.png)

**サンプル プロンプト**:

```text
Using the insights below, draft talking points for an upcoming status update meeting with [Customer Name]. Focus on any challenges and next steps.

[Paste insights from Copilot Chat here, or add your own insights]
```
