# shoocial サポートサイト

このフォルダは、GitHub PagesでHTTPS公開するための静的サイトです。HTMLとCSSだけで構成されているため、外部サーバーや有料ホスティングは必要ありません。

## 1. GitHubリポジトリを作成する

1. [GitHub](https://github.com/) にログインします。
2. 右上の「+」から「New repository」を選びます。
3. Repository nameに `shoocial-support` と入力します。
4. 「Public」を選択し、「Create repository」を押します。

## 2. ファイルをGitHubへアップロードする

1. 作成した `shoocial-support` リポジトリを開きます。
2. 「Add file」→「Upload files」を選びます。
3. このフォルダ内の以下のファイルをすべてアップロードします。
   - `index.html`
   - `privacy.html`
   - `terms.html`
   - `support.html`
   - `styles.css`
4. 画面下の「Commit changes」を押して保存します。

リポジトリの直下に `index.html` がある状態にしてください。`app-store-support` フォルダ自体をアップロードして二重のフォルダ構成にしないよう注意してください。

## 3. GitHub Pagesを有効にする

1. リポジトリの「Settings」を開きます。
2. 左側の「Pages」を選びます。
3. 「Build and deployment」の「Source」で `Deploy from a branch` を選びます。
4. Branchを `main`、フォルダを `/ (root)` にして「Save」を押します。

## 4. HTTPSの公開URLを確認する

数分待つと、Pages画面に次の形式のURLが表示されます。

```text
https://ユーザー名.github.io/shoocial-support/
```

GitHub Pagesの標準ドメインはHTTPSに対応しています。URLが `https://` で始まっていることを確認して使用してください。証明書を自分で設定する必要はありません。

## 5. App Store Connectに登録するURL

`ユーザー名` を自分のGitHubユーザー名に置き換えてください。

### Privacy Policy URL

```text
https://ユーザー名.github.io/shoocial-support/privacy.html
```

### Support URL

```text
https://ユーザー名.github.io/shoocial-support/support.html
```

### 利用規約URL

```text
https://ユーザー名.github.io/shoocial-support/terms.html
```

## 6. 公開後の確認方法

ブラウザのアドレス欄に次のURLを1つずつ貼り付けて、すべて表示できることを確認してください。

- `https://ユーザー名.github.io/shoocial-support/`
- `https://ユーザー名.github.io/shoocial-support/privacy.html`
- `https://ユーザー名.github.io/shoocial-support/terms.html`
- `https://ユーザー名.github.io/shoocial-support/support.html`

トップページから各リンクを押してページ遷移できること、アドレスがすべて `https://` で始まることも確認してください。本サイトは `http://` の外部リソースを読み込まない構成です。
