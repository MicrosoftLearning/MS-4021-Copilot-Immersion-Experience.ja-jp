---
demo:
  title: HR デモ
---

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# HR デモ

**シナリオ:**  

カスタマイズされた職務明細を作成し、履歴書に基づいて候補者を選別し、チームを調整するための採用戦略の下書きを作成することで、UX デザイナーのチームの採用プロセスを効率化します

## デモ セットアップ

サンプル ドキュメントは、[こちら](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles)の MS-4021 GitHub リポジトリにあります。

このデモに必要な具体的なファイルは次のとおりです。

- [Design_Team_Responsibilities.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Graphic_Design_Institute_Design_Team_Responsibilities.docx)

- [Resume_Patti_Fernandez.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Patti_Fernandez.docx)

- [Resume_Nestor_Wilke.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Nestor_Wilke.docx)

- [Resume_Holly_Dickson.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Holly_Dickson.docx)

- [Resume_Alex_Wilber.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Resume_Alex_Wilber.docx)

> **注:** これらのファイルがダウンロード後に OneDrive に同期されるまでに最大 10 分かかることがあります。 デモ中の遅延を避けるために、事前にこれらのファイルをダウンロードし OneDrive で使用できるようにしておいてください。 ファイルが使用できない場合は、ドキュメントを開き、デモで使用する共有ファイルリンクをコピーします。

## デモ

### Word の Copilot

まず、Copilot in Word に職務明細を生成するように依頼します。

1. (Web ブラウザーまたはデスクトップ アプリケーションの) Word を開きます。

1. "**書きたい内容を記述してください**" と表示されたプロンプト ボックスに、次のように入力します。

    ```text
    I'm the HR Manager at the Graphic Design Institute. We've currently started the hiring process for a new Senior Animation Designer. Please review the attached document outlining the job responsibilities for this role and generate a detailed job description based on this information.

    [copy link or reference file to Design_Team_Responsibilities.docx]
    ```

    > **注:** Design_Team_Responsibilities.docx ファイルを添付するか、共有リンクをプロンプトに直接貼り付けて、Copilot が関連するコンテンツにアクセスできるようにします。

1. 職務明細を確認して終了したら、ドキュメントを **GDI_Job_Description.docx** として保存し、次の手順で使用するために、共有 URL をコピーします。 (メッセージが表示されたら、自動保存を有効にして、自分の OneDrive アカウントを選択します。)

    ![リンクを共有します。](../Demos/Media/share-menu-with-copy-link-9fd1c60a.png)

### Copilot Chat

次に、Copilot Chat を使用して、受け取った履歴書と職務明細を比較し、最適な候補者を特定します。

1. ブラウザーを開き、[M365copilot.com](https://m365copilot.com/) に移動します。

1. 作業モードが選択されていることを確認します。

    ![[Web モード] タブを示すスクリーンショット。](../Prompts/Media/work-mode.png)

1. プロンプト ウィンドウで、次のように入力します。

    ```text
    We are hiring for the position of Senior Animation Designer. Please analyze the attached resumes and compare them to the requirements outlined in the job description provided here: [paste link to GDI_Job_Description.docx]. Rank the candidates from most qualified to least qualified, based on their alignment with the role.

    [Resume - Patti Fernandez
    Resume - Nestor Wilke
    Resume - Holly Dickson
    Resume - Alex Wilber]
    ```

    > **注:** 履歴書を添付するか、プロンプト ウィンドウにアップロードします。 または、自分の OneDrive の共有リンクまたはファイル名を使用して各ファイルを参照します。

1. 必要に応じて、応答を Word 文書にエクスポートしてこの機能を強調表示するように Copilot Chat に依頼することができます。

### Outlook の Copilot

最後に、Copilot in Outlook を使用して、上位の候補者に関する採用チームへのメールの下書きを作成します。

1. (Web ブラウザーまたはデスクトップ アプリケーションの) Outlook を開きます。

1. **[新しいメール]** を選択します。

1. リボンの **[Copilot]** を選択します。 ドロップダウン メニューから **[Copilot で下書き]** を選択します。

1. "**メールに書きたい内容**" プロンプト ウィンドウで、次のように入力します:

    ```text
    Please draft an email to the hiring team to share that Nester Wilke and Patti Fernandez align best with the Senior Animation Designer role based on their qualifications. Include a recommendation to schedule interviews for these candidates and request feedback on next steps.
    ```

[インデックスに戻る](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
