# js2js

JavaScriptコードを抽象構文木（AST）に変換し、再びコードに復元する過程を可視化する、インタラクティブなWebツールです。

JavaScript → AST → JavaScript

## デモ

**https://code4fukui.github.io/js2js/**

![左側にJavaScriptコード、中央にJSON形式の対応するAST、右側に再生成されたJavaScriptコードを表示する3ペインのWebインターフェース。](https://github.com/user-attachments/assets/265c4c03-a187-41c7-a40a-78ade1f29be7)

## 特徴

- **インタラクティブな3ペインビュー:** 左側のペインでJavaScriptを編集し、中央のペインで生成された抽象構文木（AST）を確認し、右側のペインで再生成されたコードを表示します。
- **リアルタイム更新:** 入力に合わせて、ASTと再生成されたコードがリアルタイムで更新されます。
- **明確なエラー表示:** 無効なJavaScript構文を入力すると、即座にASTペインにエラーメッセージが表示されます。
- **標準的なツールを採用:**
    - **パーサー:** [Acorn](https://code4fukui.github.io/acorn-es/parseModule.js)
    - **コードジェネレーター:** [escodegen](https://code4fukui.github.io/escodegen/escodegen.js)
    - **エディター:** [Monaco Editor](https://code4fukui.github.io/monaco-editor/monaco.js)

## 使い方

1. [デモページ](https://code4fukui.github.io/js2js/)にアクセスします。
2. 左側のエディターにJavaScriptコードを入力または貼り付けます。
3. 中央のペインで生成されたAST（JSON形式）を確認します。
4. 右側のペインで再生成されたJavaScriptコードを確認します。

## ライセンス

MIT
