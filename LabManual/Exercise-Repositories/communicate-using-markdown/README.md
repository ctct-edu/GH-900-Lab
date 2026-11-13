# 演習04　Markdown で伝える

Issue やプルリクエストでも使える Markdown を練習します。見出し、リスト、コード、画像を含むブログの下書きを作ります。プルリクエストの基本操作が前提で、目安は1時間未満です。

## 始め方

1. 講師から案内された日本語版テンプレートの GitHub ページを開きます。**Use this template** → **Create a new repository** を選び、**Owner** と公開範囲を確認して **Create repository** を選びます。
2. 20秒ほど待って再読み込みします。自分のコピーの **Issues** または **README** に出る案内に合わせて、この資料の同じ番号を開きます。
3. ファイル名、ブランチ名、コード、指定コメントは掲載どおりに入力します。操作後は GitHub 上で次の案内を確認します。

[GitHub Skills の原文 README](https://github.com/skills/communicate-using-markdown) · [教材のライセンス](LICENSE)

## Step 1　見出しを追加する

行頭の `#` の数で見出しの階層を指定します。`#` が一番大きく、`######` が一番小さくなります。記号の後ろには空白を入れます。

1. 自分のリポジトリの **Code** から `start-blog` ブランチを作成します。
2. **Add file** → **Create new file** で `day-1.md` を作ります。
3. コード例に沿って大見出し `Daily Learning` と、小見出し `Morning Planning`、`Review` を追加します。
4. **Preview** で表示を確認し、**Commit changes** で `start-blog` に直接コミットします。

### 原文のコマンド・入力例

```md
start-blog
```

```md
day-1.md
```

```md
# Daily Learning
```

```md
## Morning Planning

## Review
```

[このステップの原文](https://github.com/skills/communicate-using-markdown/blob/main/.github/steps/1-add-headings.md)

## Step 2　タスクリストを作る

箇条書きには `-`、番号付きリストには `1.`、タスクリストには `- [ ]` を使います。完了した項目は `- [x]` と書きます。

1. `start-blog` の `day-1.md` を開き、`Morning Planning` の下に指定のタスクリストを追加します。
2. **Preview** で表示を確認し、`start-blog` に直接コミットします。

### 原文のコマンド・入力例

```md
- [ ] Check out the [github blog](https://github.blog/) for topic ideas.
- [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
- [ ] Convert my first blog post into an actual webpage.
```

[このステップの原文](https://github.com/skills/communicate-using-markdown/blob/main/.github/steps/2-make-a-task-list.md)

## Step 3　コード例を追加する

複数行のコードは3つのバッククォートで囲みます。開始側に `bash` や `js` を付けると、言語に応じて色が付きます。

1. `day-1.md` の `Review` の下に、指定の説明と ffmpeg のコード例を追加します。コマンドは記事に掲載する例です。
2. **Preview** を確認し、`start-blog` に直接コミットします。

### 原文のコマンド・入力例

````md
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
````

[このステップの原文](https://github.com/skills/communicate-using-markdown/blob/main/.github/steps/3-add-a-code-example.md)

## Step 4　画像を追加する

Markdown では `![代替テキスト](画像URL)` と書きます。サイズや位置を指定する場合は HTML の `img` 要素も使えます。

1. `day-1.md` の `Morning Planning` の下に Markdown 形式の画像を追加し、**Preview** で確認します。
2. 同じ画像を、幅と配置を指定する教材の HTML 例に置き換えます。
3. `start-blog` に直接コミットします。

### 原文のコマンド・入力例

```md
![Cloudy morning](https://octodex.github.com/images/cloud.jpg)
```

```md
<img alt="Cloudy morning" src="https://octodex.github.com/images/cloud.jpg" width="100" align="right">
```

[このステップの原文](https://github.com/skills/communicate-using-markdown/blob/main/.github/steps/4-add-an-image.md)

## Step 5　ブログ記事をマージする

1. **Pull requests** から、新しい PR を作成します。**base** は `main`、**compare** は `start-blog` にします。
2. 必要に応じて、内容が分かるタイトルと説明を付けます。
3. **Merge pull request** で取り込み、完了メッセージを確認します。

[このステップの原文](https://github.com/skills/communicate-using-markdown/blob/main/.github/steps/5-merge-your-pull-request.md)

## 振り返り

見出しで内容を整理し、チェックリストで目標を書き、コード例と画像を追加しました。Markdown を使った記事が完成しました。

[このステップの原文](https://github.com/skills/communicate-using-markdown/blob/main/.github/steps/x-review.md)
