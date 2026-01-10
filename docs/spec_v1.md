# 変換ルール仕様 v1（ドラフト・統合済み）

本ドキュメントは旧ドラフトです。内容は以下の最新ドキュメントに統合しました。

- 日本語: `docs/rules_spec_ja.md`
- English: `docs/rules_spec_en.md`

## スコープ（v1）

- CSV/JSON から JSON への変換
- YAML ルールによるマッピング
- `input/context/out` の参照
- 式（op）による変換と条件分岐

## 非対象（v1）

- `[` `]` を含むキー名のエスケープ

## 補足

- `docs/rules_spec_ja.md`/`docs/rules_spec_en.md` が実装準拠の正本です。
- 以降の更新は正本に追記してください。
