---
lab:
  topic: GH-900
  title: "演習 – リポジトリのソフトウェアサプライチェーンを保護する"
  description: "依存関係の脆弱性を特定して修正し、Dependabot を使ったリポジトリの保護を学びます。"
  duration: 26 minutes
  level: 100
  islab: true
---

# 演習 – リポジトリのソフトウェアサプライチェーンを保護する

外部ライブラリなどの依存関係に含まれる脆弱性を見つけて修正し、リポジトリのソフトウェアサプライチェーンを保護する方法を学びます。アプリケーションが利用する外部の部品には、それぞれセキュリティ上のリスクがあります。GitHub の Dependabot などの機能で、依存関係の管理や保護を自動化できます。

この演習で学ぶこと

- サプライチェーンのセキュリティの考え方を理解する
- Dependabot アラートを有効にする
- 脆弱性の内容を確認し、修正する
- Dependabot のセキュリティ更新を設定する
- 依存関係グラフの見方を理解する
- セキュリティ上の推奨事項を実践する

所要時間の目安は **30〜45分** です。

## 始める前に

- GitHub アカウント。アカウントを持っていない方は、受講前に [新規登録](https://github.com/join) してください。手順は [GitHub アカウントの作成](https://docs.github.com/get-started/quickstart/creating-an-account-on-github) を参照してください。

- インターネットに接続できるブラウザー。

## GitHub で演習を進める

演習リポジトリを作成したあとの詳しい操作は、[演習リポジトリの日本語手順](Exercise-Repositories/secure-repository-supply-chain/README.md) で確認できます。

GitHub Skills の課題に沿って、リポジトリの依存関係を安全に保つ方法を学びます。

> **注**　Dependabot を使って、依存関係の脆弱性を確認し、修正用のプルリクエストを自動で作成する流れを体験します。

次の手順で進めます。

1. GitHub にサインインし、[日本語版テンプレートから演習を作成する](https://github.com/new?template_owner=ctct-edu&template_name=secure-repository-supply-chain&owner=%40me&name=skills-secure-repository-supply-chain&description=Exercise:+Secure+your+Repository+Supply+Chain&visibility=public) を開きます。

1. 作成画面上部の **Owner** で自分の GitHub アカウントを選びます。その横の **Repository name** に `skills-secure-repository-supply-chain` が入力されていることを確認します。公開範囲を確認し、画面下部の **Create repository** を選びます。

   > 作成後は、ページ左上の所有者名が自分のアカウントになっていることを確認します。20秒ほど待って再読み込みし、**Code** タブのファイル一覧の下にある README を確認します。**Go to Exercise** が出たらクリックします。上部の **Issues** タブから演習 Issue を開くこともできます。

   > **注**　自分のアカウントにコピーを作成したら、最初の課題が用意されるまで20秒ほど待ってページを再読み込みします。

1. 自分のコピーの README から演習 Issue を開き、日本語のステップ案内に従います。

   - ソフトウェアサプライチェーンのセキュリティとその重要性を理解する
   - リポジトリの Dependabot アラートを有効にする
   - 脆弱性のある依存関係についてセキュリティアドバイザリ（脆弱性の告知）を確認する
   - Dependabot のセキュリティ更新を有効にし、修正案の作成を自動化する
   - Dependabot が作成したプルリクエストを確認してマージする
   - 依存関係グラフの見方を理解する
   - プロジェクトの要件に合わせて Dependabot を設定する

1. 画面に表示される案内に従い、順に課題を進めます。

   > **注**　Dependabot は依存関係を自動で調べ、脆弱性のあるパッケージを修正済みバージョンに更新するためのプルリクエストを作成します。

1. すべての課題を終えると、プロジェクトの依存関係を安全に保つ方法が分かります。

## 演習の振り返り

この演習を終えると、次のことができるようになります。

- サプライチェーンのセキュリティリスクを説明できる
- Dependabot アラートを有効化し、設定できる
- 依存関係に含まれる脆弱性を確認できる
- Dependabot のセキュリティ更新を使って修正を自動化できる
- 依存関係グラフを読み取り、活用できる
- Dependabot が作ったプルリクエストを確認し、安全にマージできる
- 依存関係を安全に扱うための推奨事項を実践できる
- 依存関係を継続的に監視し、安全に保てる
- 依存関係を最新の状態に保つ重要性を説明できる

「リポジトリのソフトウェアサプライチェーンを保護する」の演習はこれで完了です。

---

原文の実習教材は [GitHub Skills](https://github.com/skills/secure-repository-supply-chain) で参照できます。

出典は [MicrosoftLearning/mslearn-github の原文](https://github.com/MicrosoftLearning/mslearn-github/blob/main/Instructions/GH-900/08-exercise-secure-repository-supply-chain.md) です。原文の著作権表示と MIT ライセンスは [LICENSE](../LICENSE) に収録しています。
