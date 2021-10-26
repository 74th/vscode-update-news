# VS Code アップデート Dec 2020 ~ Oct 2021

## 自己紹介

<img src="https://74th.tech/img/me20160216.png" width="100px"/>

Atsushi Morimoto

twitter, github: 74th

### 著書

- 『VS Code 実践ガイド』技術評論社 2020
- 『VS Code デバッグ技術 2nd Edition』技術書典 11
- 『Dev Container Guidebook』技術書典 9
- 『Visual Studio Code Ninja Guide』技術書典 8
- 『Visual Studio Code Remote Dev & Cloud Code Guide』技術書典 7

## この発表はなにか

74th が気になった VS Code の最近の更新を時間のある限り紹介します！

知らない機能を知ったり、当たり前に使ってる機能が入ったの、このタイミングかと懐かしんでください。

## Explorer View でファイルを移動や削除した後に、やり直しができるよ (2020/12)

![](https://code.visualstudio.com/assets/updates/1_52/explorer-undo.gif)

## 悪さしている拡張機能を追い詰める二分探索機能がついたよ (2020/12)

![](https://code.visualstudio.com/assets/updates/1_52/ext_bisect1.png)

![](https://code.visualstudio.com/assets/updates/1_52/ext_bisect2.png)

![](https://code.visualstudio.com/assets/updates/1_52/ext_bisect3.png)

## タブが多段になるよ (2021/01)

[![画像](https://code.visualstudio.com/assets/updates/1_53/tabs-wrap.gif)](https://code.visualstudio.com/assets/updates/1_53/tabs-wrap.gif)

## マークダウンのプレビューの画像が自動再読み込みに対応したよ (2021/01)

![](https://code.visualstudio.com/assets/updates/1_53/md-preview-update.gif)

## 拡張機能のガイドラインドキュメント (2021/01)

https://code.visualstudio.com/api/references/extension-guidelines

![](https://code.visualstudio.com/assets/updates/1_53/command-palette-dos-and-donts.png)

## アクティビティーバーのアイコン変更できるようになったよ (2021/02)

VS Code 1.0 テーマ

![](https://github.com/microsoft/vscode-extension-samples/raw/main/product-icon-theme-sample/demo.png)
![](https://code.visualstudio.com/assets/updates/1_54/product-icon-themes.png)

## Apple Silicon (M1) に対応したよ (2021/02)

![](https://code.visualstudio.com/assets/updates/1_54/apple-silicon-download.png)

## Reload Window してもターミナルのセッションを保持するようになったよ (2021/02)

![](https://code.visualstudio.com/assets/updates/1_54/local-terminal-reconnection.gif)

## Timeline View から、現在との差分とかの diff を表示できるよ (2021/02)

![](https://code.visualstudio.com/assets/updates/1_54/select-for-compare.png)

## Remote 開発機能のポート転送の一覧がパネルにきたよ (2021/02)

![](https://code.visualstudio.com/assets/updates/1_54/table.png)

## ブレークポイントに変数が変わったりアクセスされたときみたいな条件が増えたよ (2021/03)

※各言語のデバッガが対応している場合のみ

![](https://code.visualstudio.com/assets/updates/1_55/break-on-value.png)

## ターミナルを実行しわける Profile 機能がついたよ (2021/02)

![](https://code.visualstudio.com/assets/updates/1_55/terminal-profiles.png)

## リモートコンテナ機能で Volume に直接 Git Clone できたり、それらを一覧する DevVolume View がついたよ (2021/04)

![](https://github.com/microsoft/vscode-docs/blob/main/remote-release-notes/images/1_56/devvolumes-view.png)

## ターミナルのタブのリストがついたよ (2021/05)

![](https://code.visualstudio.com/assets/updates/1_56/tabs.png)

![](https://code.visualstudio.com/assets/updates/1_57/tabs-joining.gif)

## ワークスペースごとに信頼するか選択できて、信頼しない場合制限モードにできる Workspace Trust がついたよ (2021/05)

![](https://code.visualstudio.com/assets/updates/1_57/workspace-trust-dialog.png)

![](https://code.visualstudio.com/assets/updates/1_57/restricted-mode-status-bar.png)

![](https://code.visualstudio.com/assets/updates/1_57/workspace-trust-editor.png)

## git clone しなくても VS Code で表示できる Remote Repository Extension が登場したよ (2021/05)

![](https://code.visualstudio.com/assets/updates/1_57/remote-repositories-remote-explorer.png)

## 定義へ移動がソースコード以外でも使えるようになったよ (2021/05)

![](https://code.visualstudio.com/assets/updates/1_57/js-go-def.gif)

## ターミナルがエディタにも表示できるようになったよ (2021/06)

![](https://code.visualstudio.com/assets/updates/1_58/terminal-editor-grid.png)

## スクロールバーのサイズがカスタマイズ可能になったよ (2021/06)

![](https://code.visualstudio.com/assets/updates/1_58/scroll-bar-width.png)

## マークダウンプレビュー中に KaTeX で数式を表示できるようになったよ (2021/06)

![](https://code.visualstudio.com/assets/updates/1_58/markdown-math.png)

## launch.json なしデバッグで、その選択をファイルごとに記憶するようになったよ (2021/06)

![](https://code.visualstudio.com/assets/updates/1_58/debug-env.gif)

## Window 間でターミナルがドラッグドロップできるようになったよ (2021/07)

![](https://code.visualstudio.com/assets/updates/1_59/terminal-dnd.gif)

## テーマを設定でちょこっといじる機能の設定がしやすくなったよ (2021/07)

```json
{
  "workbench.colorCustomizations": {
    "[Abyss][Red]": {
      "activityBar.background": "#ff0000"
    },
    "[Monokai*]": {
      "activityBar.background": "#ff0000"
    }
  }
}
```

## Jupyter Notebook の拡張機能が標準機能になったよ (2021/07)

## アセンブリにデバッグで入っていけるようにする Disassembly View ができたよ (2021/07)

![](https://code.visualstudio.com/assets/updates/1_59/disassembly-view.gif)

## リモートコンテナ機能用の CLI ツールができたよ (2021/07)

今まではリモートタブや、一度開いてからしかできなかったのが、コマンドでいきなりできて便利！

## 自動言語判定が、ML 使ってかしこくなったよ (2021/08)

![](https://code.visualstudio.com/assets/updates/1_60/language-detection-untitled.gif)

## 括弧の色付機能が標準機能になったよ (2021/08)

![](https://code.visualstudio.com/assets/updates/1_60/bracket-pair-colorization-on-off.drawio.png)

## JS/TS で引数の名前をコード中表示したり、ダックタイピングの型を表示したりできるよ (2021/08)

![](https://code.visualstudio.com/assets/updates/1_60/ts-inlay-parameters.png)

## エディターを閉じてしまわないようにタブをロックできるようになったよ (2021/08)

![](https://code.visualstudio.com/assets/updates/1_60/locked-editor-layout.png)

## github.dev で Web 版 VS Code が使えるようになったよ (2021/08)

## タブの中で分割エディタを表示できるようになったよ (2021/09)

![](https://code.visualstudio.com/assets/updates/1_61/split-in-group.gif)

## 削除したファイルや、読み取り専用ファイルが見分けやすくなったよ (2021/09)

![](https://code.visualstudio.com/assets/updates/1_61/editor-readonly-deleted.png)

## 括弧の組をラインで表示するようになったよ (2021/09)

![](https://code.visualstudio.com/assets/updates/1_61/bracket-pair-guides.png)

## ターミナルを固定幅で表示もできるようになったよ (2021/09)

![](https://code.visualstudio.com/assets/updates/1_61/terminal-dimension-dropdown.png)
