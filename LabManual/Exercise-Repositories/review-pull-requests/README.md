# 演習06　プルリクエストをレビューする

ゲームの変更を題材に、担当者の設定、レビュー、修正提案、マージを練習します。ブランチとコミットの基本を使います。教材の目安は30分未満です。

## 始め方

1. 講師から案内された日本語版テンプレートの GitHub ページを開きます。**Use this template** → **Create a new repository** を選び、**Owner** と公開範囲を確認して **Create repository** を選びます。
2. 20秒ほど待って再読み込みします。自分のコピーの **Issues** または **README** に出る案内に合わせて、この資料の同じ番号を開きます。
3. ファイル名、ブランチ名、コード、指定コメントは掲載どおりに入力します。操作後は GitHub 上で次の案内を確認します。

[GitHub Skills の原文 README](https://github.com/skills/review-pull-requests) · [教材のライセンス](LICENSE)

## Step 1　プルリクエストを作る

**Conversation** は会話、**Commits** はコミット、**Checks** は自動チェック、**Files changed** は変更の差分を確認する画面です。

1. **Pull requests** → **New pull request** を選びます。
2. **base** を `main`、**compare** を `update-game` に設定し、**Create pull request** を選びます。
3. タイトルと説明には、下の入力例を順に使います。**Create pull request** で確定します。

### 原文のコマンド・入力例

```md
Update game over message
```

```md
Update the game over message so people know how to play again!
```

[このステップの原文](https://github.com/skills/review-pull-requests/blob/main/.github/steps/1-step.md)

## Step 2　自分を担当者にする

作成した PR を開き、右側の **Assignees** にある **assign yourself** を選びます。担当者は作業を引き受ける人です。

[このステップの原文](https://github.com/skills/review-pull-requests/blob/main/.github/steps/2-step.md)

## Step 3　レビューを送る

変更の目的がタイトルと説明から分かるか、差分が目的に沿っているかを確認します。必要に応じて実際の動作やリポジトリの貢献ガイドも確認します。

1. PR の **Files changed** で変更を読みます。
2. 比較画面の上にある **Submit review** を開きます。
3. 下のコメントを入力し、**Submit review** で送信します。自分で作成した PR では、教材の指示どおりコメントとして提出します。

### 原文のコマンド・入力例

```md
Looks good to me. I think this is more intuitive. Nice work!
```

[このステップの原文](https://github.com/skills/review-pull-requests/blob/main/.github/steps/3-step.md)

## Step 4　修正案を投稿して適用する

1. **Files changed** で `index.html` の変更行を見つけ、行番号の横に表示される `+` を選びます。
2. **Add a suggestion** で修正提案の枠を作り、下の例に合わせて **Comment** を選びます。
3. **Conversation** に戻り、**Commit suggestion** を選びます。指定のコミットメッセージを入力して **Commit changes** を選びます。

### 原文のコマンド・入力例

````md
```suggestion
<h2 hidden>Game over! Want to play again?! Just click refresh. 🧑‍🚀!</h2>
```
Let's make it a bit more friendly. 🤓
````

```markdown
Make the end game experience more friendly
```

[このステップの原文](https://github.com/skills/review-pull-requests/blob/main/.github/steps/4-step.md)

## Step 5　プルリクエストをマージする

**Conversation** の **Merge pull request** で変更を取り込みます。必要に応じて `update-game` を削除し、完了案内を確認します。

[このステップの原文](https://github.com/skills/review-pull-requests/blob/main/.github/steps/5-step.md)

## 振り返り

担当者を設定し、全体へのレビューと行単位の修正提案を投稿しました。修正をコミットしてマージするところまでを体験しました。

[このステップの原文](https://github.com/skills/review-pull-requests/blob/main/.github/steps/x-review.md)
