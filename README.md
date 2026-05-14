# js2js

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

An interactive web-based tool to visualize the transformation of JavaScript code into an Abstract Syntax Tree (AST) and back into code.

JavaScript → AST → JavaScript

## Demo

**https://code4fukui.github.io/js2js/**


![A three-pane web interface showing JavaScript code on the left, its corresponding AST in JSON format in the middle, and the regenerated JavaScript code on the right.](https://github.com/user-attachments/assets/265c4c03-a187-41c7-a40a-78ade1f29be7)


## Features

-   **Interactive Three-Pane View:** Edit JavaScript on the left, see the resulting Abstract Syntax Tree (AST) in the middle, and view the regenerated code on the right.
-   **Live Updates:** The AST and regenerated code update in real-time as you type.
-   **Clear Error Reporting:** Invalid JavaScript syntax will immediately display an error message in the AST pane.
-   **Built with Standard Tools:**
    -   **Parser:** [Acorn](https://code4fukui.github.io/acorn-es/parseModule.js)
    -   **Code Generator:** [escodegen](https://code4fukui.github.io/escodegen/escodegen.js)
    -   **Editor:** [Monaco Editor](https://code4fukui.github.io/monaco-editor/monaco.js)

## How to Use

1.  Visit the [demo page](https://code4fukui.github.io/js2js/).
2.  Type or paste your JavaScript code into the left-most editor.
3.  Observe the generated AST (in JSON format) in the middle pane.
4.  View the regenerated JavaScript code in the right-most pane.

## License

MIT