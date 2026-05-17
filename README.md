# vscode-custom-css

VS Code のエディタウォーターマーク（空エディタ時に表示されるロゴ）をカスタマイズする CSS です。

## 概要

[Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) 拡張機能を使用して、VS Code のデフォルトロゴを [ProgrammingVTuberLogos](https://github.com/Aikoyori/ProgrammingVTuberLogos) の VS Code ロゴに差し替えます。

## 使い方

### 1. 拡張機能のインストール

VS Code に [Custom CSS and JS Loader](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css) をインストールします。

### 2. settings.json に追加

`settings.json` に以下を追加します。

```json
"vscode_custom_css.imports": [
    "https://raw.githubusercontent.com/Naohiro-Kawamura/vscode-custom-css/main/style.css"
]
