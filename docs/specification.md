# 仕様

        ## 対象レコード

        - `shoppingItem`
- `stock`
- `budgetMemo`
- `nextBuy`

        ## 必須項目

        `title`, `category`, `nextAction`

        ## 警告項目

        `priceMemo`, `reviewDate`

        ## フロー

        1. 入力レコードを受け取る。
        2. `src/core/scenarioEngine.js` が必須項目と警告項目を評価する。
        3. `src/report/reportBuilder.js` が検証結果を集計する。
        4. `dist/validation-result.json` を release evidence の前提証跡にする。

        ## 保存方針

        購入履歴は端末内保存とし、決済情報や位置情報を扱わない
