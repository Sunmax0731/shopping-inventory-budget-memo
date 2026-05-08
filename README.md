# shopping-inventory-budget-memo

買い物・在庫・家計メモ は、買い物メモ、在庫、予算メモを片手で更新するAndroidアプリです。

## Closed Alpha Scope

- Rank: 38
- Tier / Score: P2 / 59
- Domain / Idea No: AndroidApp / 1
- 主な公開先: Google Play
- GitHub: https://github.com/Sunmax0731/shopping-inventory-budget-memo
- Prerelease: https://github.com/Sunmax0731/shopping-inventory-budget-memo/releases/tag/v0.1.0-alpha.1

## 実装概要

- `src/core`: 製品プロファイルと代表シナリオ評価
- `src/validators`: 期待結果検証
- `src/report`: 検証レポート生成
- `src/review-model`: レビューゲートと責務モデル
- `src/cli`: `samples/representative-suite.json` の自動検証

## 代表データ

`samples/representative-suite.json` は `happy-path`、`missing-required`、`warning`、`mixed-batch` を含みます。

## 検証

```powershell
cd D:\AI\AndroidApp\shopping-inventory-budget-memo
cmd.exe /d /s /c npm test
```

手動テストは Codex 側では未実施です。手順は `docs/manual-test.md` と `docs/strict-manual-test-addendum.md` を参照してください。
