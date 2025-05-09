# GitHub-manual-beginners
GitHub Beginner's Manual

# GitHub使用マニュアル（未経験者向け）  ※サンプル
コード編集・Push・Pull Requestを用いないWeb操作ベースの入門ガイド

---

## 1. GitHubとは？

GitHubとは、**ファイルの保管・共同作業・プロジェクト管理**をWeb上で行えるプラットフォームである。特に「誰が」「いつ」「どのような変更」を加えたかを記録する**バージョン管理機能**があるため、研究・課題・開発など幅広い用途に対応している。

---

## 2. アカウントの作成

1. [https://github.com](https://github.com) にアクセスする。
2. 「Sign up」より新規アカウントを作成する。
3. メールアドレス、パスワード、ユーザー名を登録する。
4. 届いた確認メールのリンクをクリックし、登録を完了する。

---

## 3. リポジトリの作成方法

### 3.1 リポジトリとは？

リポジトリとは、**1つのプロジェクトや課題に対応するファイル集**である。フォルダのような役割を果たす。

### 3.2 作成手順

1. GitHubログイン後、右上の「＋」マーク →「New repository」をクリックする。
2. 次の項目を入力する：
   - **Repository name（必須）**：例 `urban-planning-project`
   - **Description（任意）**：例 `都市計画に関する研究資料`
   - **Public / Private**：外部公開するか非公開にするか選択する。
   - **Initialize this repository with:**
     - ✅ Add a README file（必ずチェックする）  
       ※ 初心者はこれにチェックすることで、Web上で編集可能な初期ファイルが作成される。
3. 「Create repository」をクリックして完了。

---

## 4. ファイル管理の方法（Web操作）

### 4.1 ファイルのアップロード

1. リポジトリページに移動する。
2. 「Add file」→「Upload files」を選択。
3. ファイルをドラッグ＆ドロップでアップロード。
4. 下部にある「Commit changes」で保存する。

### 4.2 ファイルの編集

1. アップロード済みのファイルをクリック。
2. 右上の「✏️」ボタン（Edit this file）をクリック。
3. 編集後、「Commit changes」で保存する。

---

## 5. Issueを使ったタスク管理

### 5.1 Issueとは？

Issueとは、**やるべきこと（ToDo）、バグ、メモ、質問などを記録する掲示板的機能**である。共同作業でも個人プロジェクトでも役立つ。

### 5.2 Issueの作成方法

1. リポジトリ画面上部の「Issues」タブをクリック。
2. 「New issue」をクリック。
3. 次の情報を入力する：
   - **Title**：簡潔なタイトル（例：地図データの収集）
   - **Description**：詳細な内容（例：国土地理院のDEMを取得し整理する）
4. 必要に応じて「Labels（分類タグ）」や「Assignees（担当者）」を設定。
5. 「Submit new issue」で登録完了。

---

## 6. Projectsを使った進行管理（かんばんボード）

### 6.1 Projectsとは？

Projectsは、**複数のIssueをボード形式（Kanban）で整理できる**機能である。「To do」「Doing」「Done」といった列に分けて視覚的に進捗を把握できる。

### 6.2 Projectの作成手順（旧UI）

1. リポジトリ内で「Projects」タブをクリック。
2. 「New project」→「Classic project」を選ぶ。
3. ボード名やテンプレート（例：Basic Kanban）を選択し、「Create project」をクリック。
4. 自動で「To do」「In progress」「Done」の3列が作成される。

### 6.3 Issueの追加方法

- 作成済みのIssueをドラッグすることでボード上に追加可能。
- または、ボード上の「＋」から新規Issueを作成して追加することもできる。

---

## 7. 通知設定と他者との共有

- **通知設定**：右上のプロフィールアイコン → Settings → Notifications からメール通知をON/OFFにできる。
- **共有**：リポジトリのURLを送るだけでOK（Public設定の場合）。
- **共同編集**：Privateの場合は「Settings」→「Collaborators」で他者を招待する。

---

## 8. 活用例

| 活用内容           | 説明                                       |
|--------------------|--------------------------------------------|
| レポート・研究の共有 | 章ごとにMarkdownで整理し、進捗をIssueで管理 |
| チーム作業の記録     | 作業分担をIssueとProjectで可視化           |
| 講義ノートの保管     | テキストと画像ファイルを一元管理           |

---

## 9. よくある質問（FAQ）

| 質問                                     | 回答                                                      |
|------------------------------------------|-----------------------------------------------------------|
| ファイルはどこまで公開される？           | Public設定の場合、誰でも閲覧可能。Privateなら本人のみ。 |
| 他人と共有するには？                     | リポジトリのURLを送信すればよい（閲覧権限は要確認）。    |
| IssueやProjectの使い分けは？             | Issue＝タスク、Project＝全体の進捗管理と考えるとよい。    |

---

## 10. 補足

- **Markdown**を使うことで、GitHub上の説明文（READMEやIssue）が整った書式で表示される。
- Markdownの基本記法も別途まとめると便利である（必要なら用意可能）。

---
