# FormFix 公開ページ

GitHub Pagesなどの静的ホスティングへ配置するための公開ページです。外部スクリプト、解析、Cookie、フォーム送信は使用しません。

`review-test.html`はApp Store審査担当者がFormFixの候補表示を確認するためのページです。架空データだけを含み、送信機能はありません。

`accessibility.html`はApp StoreのアクセシビリティURLとして利用できる公開説明ページです。申告内容は実機評価後に`AppStore/APP_ACCESSIBILITY_ANSWERS_JA.md`と同期します。

## 公開情報

- 問い合わせ先：GitHub Issues
- プライバシーポリシーの制定日・最終更新日：2026年9月27日
- 運営者名：Autenar

公開後、確定したURLと内容を`AppStore/APP_STORE_METADATA_JA.md`、`AppStore/PRIVACY_POLICY_JA.md`、`AppStore/SUPPORT_JA.md`へ反映します。

## ローカル確認

リポジトリのルートで静的HTTPサーバーを起動し、`docs/index.html`をブラウザで確認します。`file://`で直接開いても表示できます。
