# advent-calendar-2026-rails

Rails 8.1 で作る Web サービス。

## 必要なもの

- Ruby 3.3.13（`.ruby-version` を参照）
- SQLite 3

## セットアップ

```sh
bin/setup
```

依存 gem のインストールとデータベースの準備を行い、開発サーバーを起動します。

## よく使うコマンド

```sh
bin/dev          # 開発サーバーを起動 (http://localhost:3000)
bin/rails test   # テストを実行
bin/rubocop      # Lint
bin/brakeman     # セキュリティチェック
```

## 補足

- `config/master.key` はリポジトリに含まれていません。credentials を使うときは別途共有してください。
