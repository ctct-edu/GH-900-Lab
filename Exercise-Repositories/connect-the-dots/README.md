# 演習07　リポジトリ内の作業を関連付ける

重複した Issue を整理し、コミット履歴から変更の経緯を調べ、サイドバーを修正します。教材の目安は15分未満です。

## 始め方

1. GitHub にサインインし、[演習をコピーする](https://github.com/new?') を開きます。**Owner** と公開範囲を確認して **Create repository** を選びます。
2. 20秒ほど待って再読み込みします。自分のコピーの **Issues** または **README** に出る案内に合わせて、この資料の同じ番号を開きます。
3. ファイル名、ブランチ名、コード、指定コメントは掲載どおりに入力します。操作後は GitHub 上で次の案内を確認します。

[GitHub Skills の原文 README](https://github.com/skills/connect-the-dots) · [教材のライセンス](LICENSE)

最初に作られる Issue #1 **Welcome** と #2 **Fix the sidebar** は、どちらも同じ現象を報告しています。想定は、`_sidebar.md` の **Documentation references** を選ぶと参照先が開くことです。実際にはファイルが見つからず、404 が表示されます。

## Step 1　重複する Issue を整理する

Issue や PR の番号を `#5` のように書くとリンクになり、リンク先にも参照元が表示されます。`#` の後にタイトルを入力して候補を探すこともできます。

1. 自分の演習コピーで Issue #1 **Welcome** を開きます。
2. `Duplicate of #2` とコメントし、Issue #1 を閉じます。コメントとクローズを同時に実行できる画面では、その操作を使います。
3. 20秒ほど待って案内ページを再読み込みします。

[このステップの原文](https://github.com/skills/connect-the-dots/blob/main/.github/steps/1-resolve-duplicate-issues.md)

## Step 2　履歴からコミットを見つける

`git blame` や GitHub の **Blame** を使うと、ファイルの各行を最後に変更したコミットや作成者が分かります。SHA はコミットを識別する値です。

1. **Code** で `docs/_sidebar.md` を開き、**Blame** を選びます。
2. `add sidebar to documentation` のコミットを開き、40桁の SHA の先頭7文字をコピーします。
3. Issue #2 **Fix the sidebar** にコピーした SHA をコメントします。20秒ほど待って案内ページを再読み込みします。

[このステップの原文](https://github.com/skills/connect-the-dots/blob/main/.github/steps/2-find-commit-in-history.md)

## Step 3　サイドバーの壊れたリンクを直す

コミット画面に関連する PR が表示されていれば、リンクをたどって変更理由やレビューの経緯も確認できます。

1. `main` の `docs/_sidebar.md` を開き、4行目の `(doc-references__.md)` を `(doc-references.md)` に直します。
2. 変更を `fix-sidebar` にコミットし、**base** が `main`、**compare** が `fix-sidebar` の PR を作ります。
3. **Assignees** で自分を担当者にし、PR の説明欄に `Closes #2` を入れます。番号が Issue #2 のリンクになっていることを確認します。
4. PR を作成し、20秒ほど待ってからマージします。作業ブランチを削除し、再度20秒ほど待って案内ページを再読み込みします。

[このステップの原文](https://github.com/skills/connect-the-dots/blob/main/.github/steps/3-fix-broken-sidebar.md)
