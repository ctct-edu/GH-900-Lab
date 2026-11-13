# 演習02　GitHub の基本操作

初めての方向けに、ブランチ、コミット、プルリクエスト、マージを体験します。プロフィールに使える Markdown ファイルを作ります。目安は1時間未満です。

## 始め方

1. 講師から案内された日本語版テンプレートの GitHub ページを開きます。**Use this template** → **Create a new repository** を選び、**Owner** と公開範囲を確認して **Create repository** を選びます。
2. 20秒ほど待って再読み込みします。自分のコピーの **Issues** または **README** に出る案内に合わせて、この資料の同じ番号を開きます。
3. ファイル名、ブランチ名、コード、指定コメントは掲載どおりに入力します。操作後は GitHub 上で次の案内を確認します。

[GitHub Skills の原文 README](https://github.com/skills/introduction-to-github) · [教材のライセンス](LICENSE)

## Step 1　ブランチを作る

ブランチは元の内容を残しながら別の作業を進める場所です。案内を表示するタブと操作するタブを分けると進めやすくなります。

1. 自分のリポジトリの **Code** を開きます。
2. `main` のブランチ一覧を開き、**Find or create a branch...** に `my-first-branch` と入力します。
3. **Create branch: my-first-branch from main** を選びます。Issue のコメントに次の案内が届くまで待ちます。

[このステップの原文](https://github.com/skills/introduction-to-github/blob/main/.github/steps/1-create-a-branch.md)

## Step 2　ファイルをコミットする

コミットは、変更内容とその説明を履歴に記録する操作です。

1. **Code** で `my-first-branch` を選んでいることを確認します。
2. **Add file** → **Create new file** を選び、ファイル名を `PROFILE.md` にします。本文は下の入力例を使います。
3. **Commit changes...** を選び、メッセージ欄に `Add PROFILE.md` を入力します。
4. **Commit changes** で確定し、次の案内を待ちます。

### 原文のコマンド・入力例

```
Welcome to my GitHub profile!
```

[このステップの原文](https://github.com/skills/introduction-to-github/blob/main/.github/steps/2-commit-a-file.md)

## Step 3　プルリクエストを作る

プルリクエストでは変更を共有し、取り込む前に意見をもらえます。

1. **Pull requests** → **New pull request** を選び、取り込み先 **base** を `main`、変更元 **compare** を `my-first-branch` にします。
2. **Create pull request** を選び、タイトルに `Add my first file`、説明に作業の概要を入力します。
3. **Create pull request** で作成し、次の案内を待ちます。

[このステップの原文](https://github.com/skills/introduction-to-github/blob/main/.github/steps/3-open-a-pull-request.md)

## Step 4　プルリクエストをマージする

1. **Merge pull request** → **Confirm merge** で変更を取り込みます。
2. **Delete branch** で取り込み済みの作業ブランチを削除します。
3. 演習の完了コメントを確認します。

[このステップの原文](https://github.com/skills/introduction-to-github/blob/main/.github/steps/4-merge-your-pull-request.md)

## 振り返り

ブランチの作成から、ファイルのコミット、プルリクエスト、マージまでを体験しました。プロフィールをカスタマイズする場合は、自分のユーザー名と同じ名前の公開リポジトリを作り、ルートの `README.md` を編集します。

[このステップの原文](https://github.com/skills/introduction-to-github/blob/main/.github/steps/x-review.md)
