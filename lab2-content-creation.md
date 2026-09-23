# Lab 2: PowerPoint と Word でコンテンツ作成 (M03・M04)

- 対応する公式手順 (英語):
  - [Lab 2: Build a presentation from start to finish with Copilot in PowerPoint](https://microsoftlearning.github.io/MS-4018-Draft-analyze-present-Microsoft-365-Copilot/Instructions/Labs/Lab_02_Build_Presentation_PowerPoint.html)
  - [Lab 3: Draft, improve, and share your document with Copilot in Word](https://microsoftlearning.github.io/MS-4018-Draft-analyze-present-Microsoft-365-Copilot/Instructions/Labs/Lab_03_Write_Document_Word.html)
- 必須パートの目安: 30 分 (PowerPoint 約 18 分 + Word 約 12 分)
- サンプルファイル: 次の 2 ファイルを OneDrive へ配置します
  ([README の共通の事前準備](README.md#共通の事前準備)を参照)
  - `Promotion Plan for Chai Tea in Latin America.docx`
  - `Market Analysis Report for Mystic Spice Premium Chai Tea.docx`

## シナリオ

架空の会社 Contoso のマーケティング担当として、中南米向けの Chai Tea 新製品戦略を
幹部へ報告します。サンプルの事業計画書と市場分析レポートを材料に、PowerPoint で
プレゼン資料を作り、Word でプロジェクト レポートを作ります。

## 環境別の進め方

- **環境 A (Microsoft 365 Copilot ライセンスあり)**: 手順どおりに実施します。
- **環境 B (Copilot Chat など一部の機能)**: PowerPoint・Word 内の Copilot が表示されない
  場合、アプリ内での生成は行えません。各手順の「環境 B の場合」の案内に従い、Copilot Chat で
  アウトラインや文章の素案を作る代替手順を行ってください。
- **環境 C (観察版)**: 講師の画面共有を見ながら、操作と確認観点を把握してください。

## 必須パート (授業内・30 分)

### Part A: PowerPoint でプレゼン資料を作る

#### A-1. Idea Coach で構成を考える

「Idea Coach」(要確認: 日本語表示名と利用条件) は、資料の構成案を対話しながら練るための
エージェントです。資料そのものは生成しません。

1. [https://m365.cloud.microsoft](https://m365.cloud.microsoft) を開き、職場または学校
   アカウントでサインインします。
2. 左側の一覧から「Idea Coach」を選びます。表示されない場合は「その他のエージェント」
   (More agents) (要確認) で検索して追加します。
3. 次のプロンプトを入力します。

   ```text
   中南米向けの Chai Tea 製品戦略について、地域担当副社長と CFO へ報告します。
   CFO は投資対効果と市場機会を重視します。
   8 枚構成の幹部向けプレゼンに向けて、主要なメッセージを 3〜4 点と、
   スライドの流れを提案してください。
   ```

4. 返ってきた構成案を開いたままにします。次の手順でプロンプトへ反映します。

   > **環境 B の場合**: Idea Coach が使えなくても、通常の Copilot Chat に同じプロンプトを
   > 入力すれば構成案は得られます。

#### A-2. 2 つの資料を参照してプレゼンを生成する

1. ブラウザーで [https://powerpoint.cloud.microsoft/new](https://powerpoint.cloud.microsoft/new)
   を開き、空のプレゼンテーションを作成します。
2. キャンバス右下の「Copilot」アイコンを選びます (要確認: アイコンの位置)。
3. 次のプロンプトを入力します。

   ```text
   Contoso の中南米向け Chai Tea 戦略について、8 枚構成の幹部向けプレゼンを作成してください。
   事業戦略と推奨アクションは Promotion Plan の文書から、市場機会のデータと地域の傾向は
   Market Analysis Report の文書から使ってください。
   文体は簡潔でデータ重視の幹部向けにしてください。
   聴衆は地域担当副社長と、投資対効果を重視する CFO です。
   ```

4. 参照の追加方法: 入力欄で `/` を入力するか、「+」→「仕事のコンテンツを追加」
   (Add work content) (要確認: 表示名) から、次の 2 ファイルを選択します。
   - `Promotion Plan for Chai Tea in Latin America.docx`
   - `Market Analysis Report for Mystic Spice Premium Chai Tea.docx`
5. Copilot から確認の質問が出た場合は、A-1 の構成案の内容で回答します。
6. 生成されたスライドを確認します。アウトラインや枚数、各スライドの主旨が依頼と
   合っているかを見ます。

   > **環境 B の場合**: PowerPoint 内に Copilot がなければ、Copilot Chat で
   > 「上記の構成案に沿って、各スライドのタイトルと箇条書きの本文案を書いてください」と
   > 依頼し、テキスト案の生成までを体験してください。スライドへの流し込みは手動です。

**【Part A はここで停止】** スピーカー ノート以降は発展パートです。続けて Part B へ
進んでください。

### Part B: Word でプロジェクト レポートを作る

#### B-1. 参照付きで下書きを生成する

1. ブラウザーで [https://word.cloud.microsoft/new](https://word.cloud.microsoft/new) を
   開き、空の文書を作成します。
2. 文書上部の「Copilot で下書きする内容を入力」欄 (Describe what you'd like to draft
   with Copilot) (要確認: 日本語表示名) に、次のプロンプトを入力します。

   ```text
   エグゼクティブ サマリー、はじめに、製品の説明、プロジェクトの目的、考察を含む
   プロジェクト レポートを作成してください。
   リンクする文書を内容の参照先として使ってください。
   ```

3. `/` に続けてファイル名 `Market Analysis Report for Mystic Spice Premium Chai Tea.docx`
   を入力し、候補から選択します (または「ファイル」(Files) から参照します)。
4. 「生成」(Generate) ボタンを押して下書きを作成し、内容を確認してから「完了」
   (Done) で文書へ挿入します。

   > **環境 B の場合**: Word 内に Copilot がなければ、Copilot Chat で文書を参照するか、
   > 参照なしの文章生成を試してください。Copilot Chat でのファイル参照の可否は
   > ライセンスによって異なります (要確認)。

#### B-2. 1 か所を書き換える

1. 生成された文書の「製品の説明」に相当する段落を範囲選択します。
2. 表示されるツールバーから「Copilot で編集」(Edit with Copilot) (要確認: 表示名) を
   選びます。
3. 次のプロンプトを入力します。

   ```text
   選択した部分を、上級ビジネス層の読者向けに詳細で読みやすい内容へ書き換えてください。
   文体はフォーマルなままにしてください。
   ```

4. 書き換え結果を確認し、「完了」(Done) で差し替えます。

**【ここで停止】必須パートはここまでです。** 以降は発展パートです。

## 発展パート (講義後)

### PowerPoint の続き

1. **スピーカー ノートの生成**: Copilot ペインで「このプレゼンの全スライドに、簡潔で
   フォーマルなスピーカー ノートを作成してください」と入力します。市場機会や投資対効果を
   扱うスライドで「CFO の厳しい質問を想定し、自信のあるデータ重視の説明へ書き換えて
   ください」と追加入力します。ノートの表示は、画面下のステータス バーの「ノート」
   (Notes) またはリボンの「表示」(View) →「ノート」から行います。
2. **グラフの説明**: グラフを含むスライドを開き、「このグラフの内容を、リーダーへ説明
   できるように分かりやすく解釈してください」と入力します。
3. **最終チェック**: 「このプレゼン全体と各スライドへの改善案を出してください。ストーリー
   の一貫性、幹部向けメッセージの明確さ、データの裏付けが弱いスライドを見てください」と
   入力し、指摘へ対応します。

### Word の続き

1. **表への変換**: 「プロジェクトの目的」の部分について、「目的、根拠、成功指標、対象
   チャネル、優先度の列を持つ表へ変換してください」と Copilot ペインへ入力します。
2. **Writing Coach でレビュー**: [https://m365.cloud.microsoft](https://m365.cloud.microsoft)
   の「エージェント」(Agents) から「Writing Coach」(要確認: 表示名と利用条件) を開き、
   Word 文書の 1 節 (例: エグゼクティブ サマリー) の文章を貼り付けて「明確さと文体を
   レビューし、具体的な改善案を出してください」と依頼します。Writing Coach は 1 回に
   1 つの質問へ答える形なので、質問を絞って入力してください。

## うまくいかないとき

- **参照ファイルが候補に出ない**: OneDrive で対象ファイルを一度開き、数分待ってから
  `/` の候補を再表示してください。ローカルに保存したままのファイルは参照できません。
- **PowerPoint・Word の画面に Copilot が見えない**: 環境 B 相当です。各手順の
  「環境 B の場合」の案内へ切り替えてください。
- **Idea Coach・Writing Coach が一覧にない**: エージェントの提供はライセンスと組織の
  ポリシーに依存します (要確認)。通常の Copilot Chat で同じ依頼を行ってください。
- **生成されたスライドや文書の内容がサンプルと食い違う**: 参照ファイルが正しく
  アタッチされているか確認し、「どの文書のどの部分を使ったか」を Copilot へ質問して
  ください。
- **生成に失敗する・応答が止まる**: 新しい文書・プレゼンでやり直すか、プロンプトを
  短く分割して再試行してください。
