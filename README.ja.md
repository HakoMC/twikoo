<a href="https://twikoo.js.org/"><img src="./docs/static/logo.png" width="300" alt="Twikoo"></a>

---

[![](https://img.shields.io/npm/v/twikoo)](https://www.npmjs.com/package/twikoo)
[![](https://img.shields.io/bundlephobia/minzip/twikoo)](https://bundlephobia.com/result?p=twikoo)
[![](https://img.shields.io/npm/dt/twikoo)](https://www.npmjs.com/package/twikoo)
[![](https://data.jsdelivr.com/v1/package/npm/twikoo/badge)](https://www.jsdelivr.com/package/npm/twikoo)
[![](https://img.shields.io/npm/l/twikoo)](./LICENSE)

**シンプル**、**安全**、**無料**の静的サイトコメントシステム。<br>
A **simple**, **safe**, **free** comment system.
[简体中文](./README.md) | [English](./README.en.md) | **日本語**

## 特徴 | Features

<details>
<summary>クリックして展開</summary>

### シンプル

- 無料で構築可能（Tencent CloudBase / Vercel / プライベートデプロイ をバックエンドとして使用）
- 簡単なデプロイ（Tencent CloudBase / Vercel のワンクリックデプロイが可能）

### 使いやすい

- 返信、いいね機能に対応
- ライトテーマ・ダークテーマに追加の設定なしで対応
- API 呼び出しに対応し、記事のコメント数や最新コメントの一括取得が可能
- 名前欄に QQID を入力すると、QQ ニックネームと QQ メールアドレスを自動補完
- QQ メールアドレスを入力すると、QQ アバターをコメントアバターとして使用
- 画像の貼り付けに対応（無効化可能）
- 画像の挿入に対応（無効化可能）
- 7bu 画像ホスティング、CloudBase 画像ホスティングに対応
- 絵文字の挿入に対応（無効化可能）
- Ctrl + Enter でクイック返信
- コメント内容をリアルタイムで下書き保存、更新時も失われません
- [Katex 数式に対応](https://twikoo.js.org/faq.html#%E5%A6%82%E4%BD%95%E5%90%AF%E7%94%A8-katex-%E6%94%AF%E6%8C%81)
- 言語別のコードハイライトに対応

### セキュリティ

- プライバシー情報の保護（メールアドレス、IP、環境設定などの機密データはクラウド関数で制御され漏洩しません）
- Akismet スパムコメント検出に対応（[akismet.com](https://akismet.com/)での登録が必要）
- テンセントクラウドコンテンツセキュリティのスパムコメント検出に対応（[テンセントクラウドコンテンツセキュリティ](https://console.cloud.tencent.com/cms/text/overview)での登録が必要）
- 手動レビューモードに対応
- XSS 攻撃対策
- 10 分間の IP 別コメント投稿数制限に対応

### 通知

- メール通知（訪問者とブロガー）
- WeChat 通知（ブロガーのみ、[Server 酱](https://sc.ftqq.com/3.version)経由、登録が必要）
- QQ 通知（ブロガーのみ、[Qmsg 酱](https://qmsg.zendee.cn/)経由、登録が必要）

### カスタマイズ

- コメント欄の背景画像をカスタマイズ可能
- 管理者を表すカスタムテキストをカスタマイズ可能
- 通知メールテンプレートをカスタマイズ可能
- コメント欄のプレースホルダーをカスタマイズ可能
- 絵文字リストをカスタマイズ可能（[OwO のデータ形式](https://cdn.jsdelivr.net/npm/owo@1.0.2/demo/OwO.json)に対応）
- 【名前】【メールアドレス】【ウェブサイト】の必須/任意を設定可能
- コードハイライトのテーマをカスタマイズ可能

### 管理機能

- 組み込み管理パネルでパスワードログインし、コメントの閲覧・非表示・削除・設定変更が可能
- 管理パネルを表示するボタンの非表示に対応し、合言葉を入力して表示できるように設定することが可能
- Valine、Artalk、Disqus からのコメントインポートに対応

### デメリット

- IE に非対応

</details>

## プレビュー | Preview

<details>
<summary>クリックして展開</summary>

### コメント

![コメント](./docs/static/readme-1.png)

### コメント管理

![コメント管理](./docs/static/readme-2.png)

### 通知

![通知](./docs/static/readme-3.jpg)

</details>

## クイックスタート | Quick Start

詳細なチュートリアルは[クイックスタート](https://twikoo.js.org/quick-start.html)をご覧ください。

<details>
<summary>更新情報の取得、提案、テストへの参加をご希望の方は、ディスカッショングループ（QQ：1080829142）にご参加ください</summary>
<img height="300" alt="1080829142" src="https://www.imaegoo.com/gallery/2020/hello-twikoo.png" />
</details>

<!-- ## 贡献者 | Contributors -->

## 謝辞 | Special Thanks

アイコンデザイン：[Maemo Lee](https://www.maemo.cc)

<!-- ## 捐赠 | Donate -->

## 開発 | Development

ローカルで二次開発を行う場合は、以下のコマンドを参考にしてください：

```sh
yarn dev # devサーバーを起動 (http://localhost:9820/demo.html)
yarn lint # コード検査
yarn build # ビルド (dist/twikoo.all.min.js)
```

あなたの改善が多くの人の役に立つ場合は、Pull Request の提出をお待ちしております！

## 国際化 | I18N

簡体字中国語、繁体字中国語、英語に対応。[翻訳 PR を歓迎します](https://github.com/twikoojs/twikoo/edit/main/src/client/utils/i18n/i18n.js)。

## ライセンス | License

<details>
<summary>MIT License</summary>

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fimaegoo%2Ftwikoo.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Fimaegoo%2Ftwikoo?ref=badge_large)

</details>
