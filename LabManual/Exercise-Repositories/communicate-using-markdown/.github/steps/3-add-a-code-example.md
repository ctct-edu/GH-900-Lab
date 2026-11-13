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

[原文](https://github.com/skills/communicate-using-markdown/blob/main/.github/steps/3-add-a-code-example.md)
