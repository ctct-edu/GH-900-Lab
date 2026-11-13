## Step 3　サイドバーの壊れたリンクを直す

コミット画面に関連する PR が表示されていれば、リンクをたどって変更理由やレビューの経緯も確認できます。

1. `main` の `docs/_sidebar.md` を開き、4行目の `(doc-references__.md)` を `(doc-references.md)` に直します。
2. 変更を `fix-sidebar` にコミットし、**base** が `main`、**compare** が `fix-sidebar` の PR を作ります。
3. **Assignees** で自分を担当者にし、PR の説明欄に `Closes #2` を入れます。番号が Issue #2 のリンクになっていることを確認します。
4. PR を作成し、20秒ほど待ってからマージします。作業ブランチを削除し、再度20秒ほど待って案内ページを再読み込みします。

[原文](https://github.com/skills/connect-the-dots/blob/main/.github/steps/3-fix-broken-sidebar.md)
