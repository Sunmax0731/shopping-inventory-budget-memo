# 要件定義

## 背景

NON PICKUP Rank 38 の `買い物・在庫・家計メモ` は、買い物メモ、在庫、予算メモを片手で更新するAndroidアプリとして閉域アルファ化します。

## ユーザー価値

- 在庫不足と予算メモから買い物リストを作る
- 入力、確認、履歴保存、次アクションを同じ作業単位で扱う。
- MVP後の磨き込みで UI/UX、責務分割、手動テスト、配布準備を同時に確認できる。

## MVP

- 代表データ4種を処理できる。
- 必須項目不足を error、補助項目不足を warning として分ける。
- リリース前 docs、QCDS、security/privacy、traceability、release evidence をそろえる。

## 非目標

- 実ユーザーデータのクラウド同期。
- 有料販売ページ、Google Play Console、BOOTH 商品ページの実公開。
- Codex 側での手動テスト代行。
