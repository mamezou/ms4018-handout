---
lab:
  title: 'ラボのセットアップ: Microsoft Copilot 用のサンプル データを準備する'
  description: Microsoft Copilot - ラボ全体で使用するサンプル ファイルを OneDrive にアップロードします。
  level: Lab 100
  duration: '10'
  islab: true
  status: 'released'
  targetDate: 2026-12-31
  primarytopics:
    - Microsoft 365
    - Microsoft Copilot
---

# Microsoft Copilot でサンプル データを使って進める

これらのラボでは、次のファイルを参照する Microsoft Copilot 用のプロンプトを作成します。

- [Promotion Plan for Chai Tea in Latin America.docx](https://github.com/MicrosoftLearning/MS-4018-Draft-analyze-present-Microsoft-365-Copilot/raw/master/Allfiles/Promotion%20Plan%20for%20Chai%20Tea%20in%20Latin%20America%20(2).docx)
- [Market Analysis Report for Mystic Spice Premium Chai Tea.docx](https://github.com/MicrosoftLearning/MS-4018-Draft-analyze-present-Microsoft-365-Copilot/raw/master/Allfiles/Market%20Analysis%20Report%20for%20Mystic%20Spice%20Premium%20Chai%20Tea.docx)
- [Contoso Chai Tea market trends.xlsx](https://github.com/MicrosoftLearning/MS-4018-Draft-analyze-present-Microsoft-365-Copilot/raw/master/Allfiles/Contoso%20Chai%20Tea%20market%20trends.xlsx)

後の手順で Microsoft Copilot がこれらのファイルを利用できるよう、先に OneDrive へアップロードします。

## OneDrive へのファイルのアップロード

次の手順で、必要なすべてのファイルを **OneDrive** にアップロードします。

1. テナント プロバイダーから提供された仮想マシンにログインします。

1. **Microsoft Edge** ブラウザーを開き、https://onedrive.live.com/login/ にアクセスします。提供された資格情報を入力してログインします。

1. サインイン状態を保持するか確認されたら、**はい** を選びます。

1. **OneDrive の準備ができました** を選び、ウェルカム メッセージをスキップして、**作成またはアップロード** (Create or upload) > **ファイルのアップロード** (Files upload) を選びます。

1. **エクスプローラー** (File Explorer) で、**PC** (This PC) > **ローカル ディスク (C:)** を開き、**Allfiles** (MS-4018 ResourceFiles) フォルダーを開きます。

1. **MS-4018 ResourceFiles** フォルダー内のすべてのファイルを選び、**開く** を選びます。

1. アップロードが完了すると、画面下部の中央に **4 個のアイテムを Documents にアップロードしました** (Uploaded 4 items to Documents) と表示されます。

### ファイルの参照

Copilot からファイルを参照するとき、候補として表示される一覧に目的のファイルが見つからない場合があります。Copilot の一部の機能は「最近使用したファイル」(Most Recently Used、MRU) の一覧にあるファイルのみを参照し、それ以外の機能では OneDrive を参照してファイルを探せることが原因です。対象のファイルを該当する Microsoft 365 アプリで一度開けば、MRU の一覧に追加されます。

> [!IMPORTANT]
> Microsoft Copilot が扱えるのは OneDrive に保存されたファイルのみです。PC のローカルに保存されたファイルを使うには、OneDrive へ移す必要があります。

ラボを進める中で、これらのファイルに対して別のプロンプトを試す機会があります。プロンプトのスキルを高めるために、積極的に試してください。
