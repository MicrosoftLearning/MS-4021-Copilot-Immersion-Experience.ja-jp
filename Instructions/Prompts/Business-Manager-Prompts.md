---
task:
  title: イマージョン エクスペリエンス - ビジネス マネージャー
---

## イマージョン エクスペリエンス - ビジネス マネージャー  

コミュニケーションを確認し、メールを送信し、今度の会議に向けて準備することで、日々のタスクを最適化します。  

次の 3 つのタスクを実行します。  

- **Microsoft 365 Copilot Chat** を使用してコミュニケーションの内容を確認する。  
- **Copilot in Pages** を使用して会議の話題を準備する。
- **Copilot in Outlook** を使用してフォローアップ メールの下書きを作成する。  

> **注:** 作業を開始するのに役立つサンプル プロンプトが用意されています。 これらを自分のニーズに合わせて自由にカスタマイズします - 創造的な姿勢で取り組み、応用方法を探ってください。 求める結果が Copilot で得られない場合は、プロンプトを改善して、もう一度やり直してください。 このプロセスと実験を楽しんでください。  

### タスク 1: コミュニケーションの内容を確認する  

**Microsoft 365 Copilot Chat** を使用して、特定のトピックまたはプロジェクトに関する特定の個人との最近のやり取りから分析情報を収集します。 重要なポイント、実施項目、未解決の質問の特定に重点を置きます。 これにより、チーム プロジェクトを常に最新の状態に保ち、その進行状況、課題、結果を関係者に常に知らせることができます。  

**手順**:

- 新しいブラウザー タブを開き、[M365copilot.com](https://m365copilot.com/) に移動します。
- Copilot Chat で "作業モード" のタブが選択されていることを確認します。

    ![作業モード タブを示すスクリーンショット。](../Prompts/Media/work-mode.png)

**サンプル プロンプト**:

```text
Summarize my recent interactions with [/Name of Person] regarding [specific topic or project]. Organize the summary by key points or actions discussed, and include any follow-up items or outstanding questions that may require attention.
```

> **注:** [Name of Person] を対象とする個人に置き換え、[specific topic or project] を関連するトピックに置き換えます。 **/** 文字 (スラッシュ) を使用すると、社内の連絡先を参照して最近のやり取りにすばやくアクセスできます。

### タスク 2: 会議の準備をする  

**Copilot in Pages** を使用して、Microsoft 365 Copilot Chat で収集された分析情報に基づいて、今度の関係者会議の話題を作成します。 進行状況の更新、重要な日付、課題またはリスク、アクション可能な次のステップに重点を置いて、実りある話し合いにします。

**手順**:

1. 前のタスクの **[Copilot Chat の応答]** で、**[Pages で編集]** を選択します。  
   ![Copilot in Pages を示すスクリーンショット。](../Prompts/Media/edit_in_pages.png)

2. 開いた新しい Pages 画面で、**[すべてのページを表示]** を選択します。  
   ![Copilot in Pages を示すスクリーンショット。](../Prompts/Media/view-all-pages.png)

3. 新しい Pages ウィンドウで、ドキュメントの右側にある **Copilot アイコン**を選択して Copilot と対話します。

**サンプル プロンプト**:

```text
Using these insights, draft talking points for an upcoming stakeholder meeting. Focus on progress updates, key dates, challenges and next steps. 
```

> **ヒント:**  
> - Pages は、同僚とリアルタイムで共同作業するためのコラボレーション スペースとして使用できます。 "@" 記号の後に同僚の名前を入力して、ページを共有します。
> - 同僚を追加したら、その同僚の名前をクリックしてアクセス権を付与します。 同僚は、ページで共同作業するためのリンクが記載されたメール通知を受け取ります。  

### タスク 3: フォローアップ メールを送信する  

**Copilot in Outlook** を使用して、Microsoft 365 Copilot Chat で収集された分析情報に基づいて、フォローアップ メールを下書きします。 進行状況の更新、保留中のアクション、次の手順、さらに話し合いを続けるフォローアップ会議の要求などの詳細を含めます。

**手順**:

- **Outlook** で **[新しいメール]** を選択し、リボンから **[Copilot]**、**[Copilot で下書き]** の順に選択します。

    ![Copilot in Outlook を示すスクリーンショット。](../Prompts/Media/copilot-outlook-desktop.png)

**サンプル プロンプト**:

```text
Using the insights below, draft a follow-up email to [Name of Person] requesting an update on progress and next steps. Also, ask for a follow-up meeting to discuss further on the project deadline. 

[Paste insights from Copilot Chat here, or add your own insights]
```
